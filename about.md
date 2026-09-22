---
layout: default
title: About CatalystX
nav_title: About
permalink: /about/
description: Meet CatalystX, a performance-focused Solana validator and validator-backed infrastructure operator.
---

<section class="page-hero">
  <p class="eyebrow">Independent infrastructure, public performance</p>
  <h1>We run the validator behind the path.</h1>
  <p>CatalystX is operated by S3RDV LLC. We combine high-performance Solana validation with practical connectivity for RPC operators, infrastructure providers, builders, and delegators.</p>
</section>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Our operating model</p>
    <h2>Geographic standby with planned and emergency failover.</h2>
    <p>Rotterdam is the active validator, with geographically separate standby sites in Frankfurt and Madrid. Operator-reported transition times are approximately 200 ms for planned failover and approximately 40 seconds for an unplanned emergency failover. These figures are not an SLA.</p>
  </div>
  <div class="location-stack">
    <div class="location-row primary-location"><span>PRIMARY</span><strong>Rotterdam, NL</strong><small>Validator edge</small></div>
    <div class="location-row"><span>STANDBY 01</span><strong>Frankfurt, DE</strong><small>Planned + emergency failover</small></div>
    <div class="location-row"><span>STANDBY 02</span><strong>Madrid, ES</strong><small>Planned + emergency failover</small></div>
  </div>
</section>

<section class="section-block">
  <div class="section-heading compact">
    <p class="eyebrow">How we operate</p>
    <h2>Built around measurable network outcomes.</h2>
  </div>
  <div class="content-grid three-column">
    <article class="content-card">
      <span class="card-kicker">Latency</span><h3>Fast voting</h3>
      <p>We tune infrastructure and network paths for near-one-slot voting, then rely on public dashboards to show the result.</p>
    </article>
    <article class="content-card">
      <span class="card-kicker">Resilience</span><h3>Geographic standby</h3>
      <p>Three European locations are designed to reduce dependence on one facility or metro.</p>
    </article>
    <article class="content-card">
      <span class="card-kicker">Operations</span><h3>Measured and observable</h3>
      <p>Validator health, voting, connectivity, and infrastructure telemetry inform operator response.</p>
    </article>
  </div>
</section>

<section class="section-block split-section">
  <div>
    <p class="eyebrow">Network standing</p>
    <h2>Trusted across different delegation models.</h2>
    <p>CatalystX participates in validator programs serving different audiences—from institutional allocators to performance-driven liquid staking users.</p>
  </div>
  <ul class="recognition-list">
    <li><strong>Marinade Select</strong><span>Institutional validator set</span></li>
    <li><strong>Shinobi Performance Pool</strong><span>Data-driven performance selection</span></li>
    <li><strong>JitoSOL</strong><span>Active validator set</span></li>
  </ul>
</section>

<section class="section-block">
  <div class="section-heading compact">
    <p class="eyebrow">Operator</p>
    <h2>S3RDV LLC</h2>
    <p>Our background spans distributed systems, network engineering, security operations, and blockchain infrastructure. CatalystX is where that experience meets production Solana operations.</p>
  </div>
  <div class="account-box"><span>Validator identity</span><code>{{ site.validator_info.identity_account }}</code></div>
  <div class="account-box"><span>Vote account</span><code>{{ site.validator_info.vote_account }}</code></div>
</section>
