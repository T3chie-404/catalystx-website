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
<p class="live-metric-note" data-live-updated>Reference values verified September 22, 2026; live metrics load from StakeWiz.</p>

<div class="notice">
  <strong>Why uptime values can differ.</strong>
  <p>At the September 22, 2026 check, StakeWiz reported 100% rolling 30-day uptime and no 30-day delinquency records. Marinade samples Solana's vote-account delinquent state and recorded one approximately one-minute delinquency interval in epoch 1032. A sampled vote-account delinquency does not by itself establish a hardware outage.</p>
</div>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Maximum available history</p>
    <h2>99.9995% average voting uptime. Zero skipped leader slots.</h2>
    <p>Across epochs 951–1039, CatalystX produced all <strong>17,144 of 17,144 scheduled leader slots</strong>. Marinade observed approximately one minute of vote-account delinquency in epoch 1032; the other 88 completed epochs recorded 100% uptime.</p>
    <a class="text-link" href="https://validators-api.marinade.finance/validators?query_vote_accounts=ErvMUdtMC7AX55zKdYSyy4DnWNCrTsWn5GwprSG7ocnx&amp;epochs=100&amp;limit=1" target="_blank" rel="noopener noreferrer">Inspect the Marinade API source <span aria-hidden="true">→</span></a>
  </div>

  <div class="proof-panel">
    <div><span>99.9995%</span><small>average per-epoch voting uptime</small></div>
    <div><span>0 / 17,144</span><small>skipped / scheduled leader slots</small></div>
    <div><span>89 epochs</span><small>completed history available from Marinade</small></div>
  </div>
</section>
<p class="section-footnote">99.9995% is the rounded arithmetic mean of Marinade's per-epoch uptime values for completed epochs 951–1039, retrieved September 22, 2026. Historical measurement, not an uptime SLA.</p>

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
    <h2>Rotterdam primary with Frankfurt and Madrid standby.</h2>
    <p>Operator-reported validator transition times are approximately 200 ms for planned failover and approximately 40 seconds for an unplanned emergency failover. These figures are not an SLA.</p>
  </div>
  <div class="location-stack">
    <div class="location-row primary-location"><span>PRIMARY</span><strong>Rotterdam</strong><small>Active validator</small></div>
    <div class="location-row"><span>STANDBY 01</span><strong>Frankfurt</strong><small>Planned + emergency failover</small></div>
    <div class="location-row"><span>STANDBY 02</span><strong>Madrid</strong><small>Planned + emergency failover</small></div>
  </div>
</section>
