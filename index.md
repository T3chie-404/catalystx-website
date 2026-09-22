---
layout: default
title: Validator-backed Solana infrastructure
description: SWQoS and staked QUIC forwarding, real-time shred delivery, connected RPC access, and high-performance Solana staking.
---

<section class="hero hero-home">
  <div class="hero-copy">
    <p class="eyebrow"><span class="status-dot" aria-hidden="true"></span> CatalystX / Solana mainnet</p>
    <h1>Staked QUIC in.<br><span>Real-time shreds out.</span></h1>
    <p class="hero-lede">Trusted transaction forwarding and validator-sourced Solana data for RPC operators, builders, and latency-sensitive users.</p>
    <div class="hero-actions">
      <a href="{{ '/services/' | relative_url }}" class="button button-primary">Explore connectivity</a>
      <a href="{{ '/contact/#infrastructure' | relative_url }}" class="button button-secondary">Talk to an operator</a>
    </div>
    <p class="hero-footnote">Rotterdam primary <span aria-hidden="true">·</span> Frankfurt + Madrid standby</p>
  </div>

  <div class="network-card" aria-label="CatalystX infrastructure footprint">
    <div class="network-card-header">
      <span>Validator network</span>
      <span class="network-live"><span class="status-dot" aria-hidden="true"></span> Solana mainnet</span>
    </div>
    <div class="network-diagram">
      <div class="network-node network-node-backup">
        <small>STANDBY 01</small><strong>Frankfurt</strong><span>Germany</span>
      </div>
      <div class="network-link" aria-hidden="true"></div>
      <div class="network-node network-node-primary">
        <small>PRIMARY</small><strong>Rotterdam</strong><span>Validator edge</span>
      </div>
      <div class="network-link" aria-hidden="true"></div>
      <div class="network-node network-node-backup">
        <small>STANDBY 02</small><strong>Madrid</strong><span>Spain</span>
      </div>
    </div>
    <div class="network-failover" aria-label="Operator-reported validator transition times">
      <div><small>PLANNED FAILOVER</small><strong>~200 ms</strong></div>
      <div><small>EMERGENCY FAILOVER</small><strong>~40 sec</strong></div>
    </div>
    <p class="network-disclaimer">Operator-reported transition times · not an SLA</p>
    <div class="network-output">
      <span>SWQoS</span><span>Live shreds</span><span>RPC paths</span>
    </div>
  </div>
</section>

<section class="metric-strip" aria-label="Validator performance snapshot">
  <article class="metric-card"><strong>99.9995%</strong><span>Average voting uptime</span><small>89 completed epochs · Marinade</small></article>
  <article class="metric-card"><strong>0 / 17,144</strong><span>Skipped leader slots</span><small>Epochs 951–1039</small></article>
  <article class="metric-card"><strong>Top 3.11%</strong><span>Vote latency</span><small>#22 of 708 · Sep. 21, 2026 snapshot</small></article>
  <article class="metric-card"><strong data-live-metric="activated_stake">220K SOL</strong><span>Active stake</span><small>Live via StakeWiz</small></article>
</section>
<p class="live-metric-note" data-live-updated>Live validator metrics supplied by StakeWiz.</p>

<section class="section-block">
  <div class="section-heading">
    <p class="eyebrow">Closer to the validator</p>
    <h2>Three ways to build a faster path into Solana.</h2>
    <p>Use our validator's network position directly, or let us connect you with infrastructure that already does.</p>
  </div>
  <div class="service-grid">
    <article class="service-card">
      <span class="service-index">01</span><p class="service-audience">For RPC operators</p>
      <h3>Staked QUIC forwarding</h3>
      <p>Route vetted transaction traffic through CatalystX's trusted, stake-weighted path for SWQoS-aware forwarding toward current and upcoming leaders.</p>
      <a href="{{ '/services/#swqos' | relative_url }}">Explore SWQoS <span aria-hidden="true">→</span></a>
    </article>

    <article class="service-card">
      <span class="service-index">02</span><p class="service-audience">For data infrastructure</p>
      <h3>Real-time shred delivery</h3>
      <p>Receive validator-sourced shreds over a direct delivery path designed for trading systems, indexers, and real-time data pipelines.</p>
      <a href="{{ '/services/#shreds' | relative_url }}">Explore shred delivery <span aria-hidden="true">→</span></a>
    </article>
    <article class="service-card">
      <span class="service-index">03</span><p class="service-audience">For builders and users</p>
      <h3>Connected RPC access</h3>
      <p>Tell us what you are building. We can match you with an RPC or infrastructure provider already connected to our validator path.</p>
      <a href="{{ '/services/#rpc-access' | relative_url }}">Find the right path <span aria-hidden="true">→</span></a>
    </article>
  </div>
</section>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Performance you can inspect</p>
    <h2>Top 3.11% vote latency in the September 21, 2026 Shinobi snapshot.</h2>
    <p>CatalystX ranked <strong>#22 of 708 validators</strong> at <strong>1.019011 slots</strong> of average vote latency. Pool allocation and rank change each epoch, so we link current data instead of freezing a permanent top-20 claim.</p>
    <div class="inline-links">
      <a href="{{ site.validator_info.profiles.shinobi }}" target="_blank" rel="noopener noreferrer">View Shinobi validators</a>
      <a href="{{ site.validator_info.profiles.stakewiz }}" target="_blank" rel="noopener noreferrer">Open live metrics</a>
    </div>
  </div>
  <div class="proof-panel">
    <div><span>1.019011</span><small>average vote latency / slots</small></div>
    <div><span>#22 / 708</span><small>September 21, 2026 xSHIN snapshot</small></div>
    <div><span>5%</span><small>validator commission</small></div>
  </div>
</section>

<section class="section-block">
  <div class="section-heading compact">
    <p class="eyebrow">Delegation and recognition</p>
    <h2>Selected across leading validator programs and performance pools.</h2>
  </div>
  <div class="badge-grid">
    <a class="badge-card" href="https://select.marinade.finance/" target="_blank" rel="noopener noreferrer">
      <span class="badge-mark">M</span><span><strong>Marinade Select</strong><small>Institutional validator set</small></span>
    </a>
    <a class="badge-card" href="{{ site.validator_info.profiles.shinobi }}" target="_blank" rel="noopener noreferrer">
      <span class="badge-mark">S</span><span><strong>Shinobi Performance Pool</strong><small>Performance-based delegation</small></span>
    </a>
    <a class="badge-card" href="{{ site.validator_info.profiles.jito }}" target="_blank" rel="noopener noreferrer">
      <span class="badge-mark">J</span><span><strong>JitoSOL</strong><small>Active validator set</small></span>
    </a>
  </div>
  <p class="section-footnote">Pool allocations and rankings can change by epoch.</p>
</section>

<section class="cta-band">
  <div>
    <p class="eyebrow">Need a better Solana path?</p>
    <h2>Start with the workload, not a generic plan.</h2>
    <p>Tell us your region, traffic profile, and latency target. We will map the right validator, shred, or RPC path.</p>
  </div>
  <div class="hero-actions">
    <a href="{{ '/contact/#infrastructure' | relative_url }}" class="button button-primary">Discuss infrastructure</a>
    <a href="{{ '/services/#staking' | relative_url }}" class="button button-secondary">Stake with CatalystX</a>
  </div>
</section>
