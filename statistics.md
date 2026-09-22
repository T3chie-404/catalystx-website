---
layout: default
title: Validator Performance
nav_title: Performance
permalink: /statistics/
description: Live CatalystX validator uptime, vote success, active stake, public performance profiles, and infrastructure status.
---

<section class="page-hero">
  <p class="eyebrow">Public, independently measurable</p>
  <h1>Validator performance.</h1>
  <p>Live values below come from StakeWiz. Longitudinal proof uses Marinade's validator API, while pool and latency data link to their current source.</p>
</section>

<section class="metric-strip metric-strip-wide" aria-label="Live validator metrics">
  <article class="metric-card"><strong data-live-metric="uptime">100%</strong><span>30-day uptime</span><small>StakeWiz methodology</small></article>
  <article class="metric-card"><strong data-live-metric="vote_success">99.8%</strong><span>Vote success</span><small>Current epoch</small></article>
  <article class="metric-card"><strong data-live-metric="activated_stake">220K SOL</strong><span>Active stake</span><small>Current delegation</small></article>
  <article class="metric-card"><strong data-live-metric="commission">5%</strong><span>Commission</span><small>Inflation rewards</small></article>
</section>
<p class="live-metric-note" data-live-updated>Reference values verified September 21, 2026; live metrics load from StakeWiz.</p>

<div class="notice">
  <strong>Why uptime values can differ.</strong>
  <p>Validator dashboards use different windows and definitions. StakeWiz measures time not delinquent over a rolling 30-day window; other platforms may calculate vote or epoch participation. Check the source and timestamp when comparing values.</p>
</div>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Ten completed epochs</p>
    <h2>99.9956% voting uptime. Zero skipped leader slots.</h2>
    <p>Across epochs 1029–1038, CatalystX produced all <strong>1,844 of 1,844 scheduled leader slots</strong>. Nine epochs recorded 100% voting uptime; one recorded 59 seconds of downtime.</p>
    <a class="text-link" href="https://validators-api.marinade.finance/validators?query_vote_accounts=ErvMUdtMC7AX55zKdYSyy4DnWNCrTsWn5GwprSG7ocnx&amp;epochs=11&amp;limit=1" target="_blank" rel="noopener noreferrer">Inspect the Marinade API source <span aria-hidden="true">→</span></a>
  </div>

  <div class="proof-panel">
    <div><span>99.9956%</span><small>voting uptime / epochs 1029–1038</small></div>
    <div><span>0 / 1,844</span><small>skipped / scheduled leader slots</small></div>
    <div><span>9 / 10</span><small>epochs at 100% voting uptime</small></div>
  </div>
</section>
<p class="section-footnote">Calculated from Marinade's validator API on September 21, 2026. This is a historical measurement, not an uptime SLA.</p>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Vote latency</p>
    <h2>Top 3.11% in the September 21 Shinobi snapshot.</h2>
    <p>CatalystX averaged <strong>1.019011 slots</strong> of vote latency and ranked <strong>#22 among 708 validators</strong>. Placement changes by epoch; the current xSHIN validator view is linked below.</p>
    <a class="text-link" href="{{ site.validator_info.profiles.shinobi }}" target="_blank" rel="noopener noreferrer">View Shinobi validators <span aria-hidden="true">→</span></a>
  </div>
  <div class="proof-panel">
    <div><span>1.019011</span><small>average latency / slots</small></div>
    <div><span>#22 / 708</span><small>September 21, 2026 xSHIN snapshot</small></div>
    <div><span data-live-metric="version">4.3.0</span><small>live client version</small></div>
  </div>
</section>

<section class="section-block">
  <div class="section-heading compact">
    <p class="eyebrow">Independent profiles</p>
    <h2>Verify CatalystX across the ecosystem.</h2>
  </div>
  <div class="source-grid">
    <a class="source-card" href="{{ site.validator_info.profiles.stakewiz }}" target="_blank" rel="noopener noreferrer"><strong>StakeWiz</strong><span>Uptime, stake, voting, APY, and score</span></a>
    <a class="source-card" href="{{ site.validator_info.profiles.jito }}" target="_blank" rel="noopener noreferrer"><strong>Jito</strong><span>Historical on-chain validator data</span></a>
    <a class="source-card" href="{{ site.validator_info.profiles.shinobi }}" target="_blank" rel="noopener noreferrer"><strong>Shinobi</strong><span>Performance Pool validators and methodology</span></a>
    <a class="source-card" href="{{ site.validator_info.profiles.validator_info }}" target="_blank" rel="noopener noreferrer"><strong>Validator.info</strong><span>Validator and delegation data</span></a>
    <a class="source-card" href="https://dashboards.validblocks.com/" target="_blank" rel="noopener noreferrer"><strong>ValidBlocks</strong><span>Location, pool stake, performance, and client</span></a>
    <a class="source-card" href="https://www.validators.app/validators/BNtHBLo1L2vAG7PBQ6mJvWz7GqVPxBnioXsY2Gjtubrg?locale=en&amp;network=mainnet" target="_blank" rel="noopener noreferrer"><strong>Validators.app</strong><span>Identity, software, stake, and network metrics</span></a>
  </div>
</section>

<section class="section-block split-section">
  <div>
    <p class="eyebrow">Infrastructure status</p>
    <h2>Three-region operating footprint.</h2>
  </div>
  <div class="location-stack">
    <div class="location-row primary-location"><span>PRIMARY</span><strong>Rotterdam</strong><small>Active validator</small></div>
    <div class="location-row"><span>BACKUP 01</span><strong>Frankfurt</strong><small>Standby</small></div>
    <div class="location-row"><span>BACKUP 02</span><strong>Madrid</strong><small>Standby</small></div>
  </div>
</section>
