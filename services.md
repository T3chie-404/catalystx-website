---
layout: default
title: Connectivity Services
nav_title: Services
permalink: /services/
description: Validator-backed SWQoS, staked QUIC forwarding, real-time shred delivery, connected RPC access, and Solana staking.
---

<section class="page-hero">
  <p class="eyebrow">Connectivity services</p>
  <h1>Move transactions and data closer to the validator.</h1>
  <p>Infrastructure is scoped around your workload—whether you operate an RPC, consume real-time Solana data, or need a provider already connected to a validator-backed path.</p>
</section>

<section class="service-detail" id="swqos">
  <div class="service-detail-number">01</div>
  <div class="service-detail-copy">
    <p class="service-audience">RPC and infrastructure operators</p>
    <h2>SWQoS / staked QUIC forwarding</h2>
    <p>CatalystX can provide an eligible staked forwarding path for RPC operators that want to improve transaction delivery to current and upcoming leaders. SWQoS prioritizes trusted traffic; it does not guarantee transaction inclusion.</p>
    <div class="content-grid two-column">
      <div class="content-card">
        <h3>What we provide</h3>
        <ul class="check-list">
          <li>Validator-backed staked QUIC forwarding</li>
          <li>Regional path and standby planning</li>
          <li>Traffic-policy and source onboarding</li>
          <li>Operational monitoring and coordination</li>
        </ul>
      </div>

      <div class="content-card">
        <h3>What we need</h3>
        <ul class="check-list">
          <li>RPC identity public key(s)</li>
          <li>Trusted source IPs and primary region</li>
          <li>Expected transaction volume</li>
          <li>Current TPU peering and forwarding configuration</li>
        </ul>
      </div>
    </div>
    <a class="text-link" href="mailto:contact@s3rdv.com?subject=SWQoS%20and%20staked%20QUIC%20request">Request staked forwarding <span aria-hidden="true">→</span></a>
  </div>
</section>

<section class="service-detail" id="shreds">
  <div class="service-detail-number">02</div>
  <div class="service-detail-copy">
    <p class="service-audience">Trading systems, indexers, and real-time infrastructure</p>
    <h2>Validator-sourced real-time shreds</h2>
    <p>Consume shreds from infrastructure tied directly to CatalystX validator operations. This path is intended for workloads where earlier data and a direct delivery path matter: trading, search, indexing, and low-latency event pipelines.</p>
    <div class="pill-row" aria-label="Common shred delivery use cases">
      <span>Trading systems</span><span>Indexers</span><span>Block intelligence</span><span>Real-time analytics</span>
    </div>
    <p class="service-note">Delivery method, geography, capacity, and commercial terms are scoped per integration.</p>
    <a class="text-link" href="mailto:contact@s3rdv.com?subject=Real-time%20shred%20delivery%20request">Request shred delivery <span aria-hidden="true">→</span></a>
  </div>
</section>

<section class="service-detail" id="rpc-access">
  <div class="service-detail-number">03</div>
  <div class="service-detail-copy">
    <p class="service-audience">Individual builders, teams, and latency-sensitive users</p>
    <h2>Connected RPC and infrastructure access</h2>
    <p>You may not need to operate an RPC or integrate a forwarding layer yourself. We can help match you with an RPC or infrastructure provider already connected to CatalystX and suited to your location, workload, and budget.</p>
    <div class="notice">
      <strong>A matched service, not an anonymous public endpoint.</strong>
      <p>CatalystX does not publish an open retail RPC URL on this site. We learn what you need and connect you with an appropriate integrated provider.</p>
    </div>
    <a class="text-link" href="mailto:contact@s3rdv.com?subject=Connected%20RPC%20access%20request">Find a connected provider <span aria-hidden="true">→</span></a>
  </div>
</section>

<section class="service-detail" id="staking">
  <div class="service-detail-number">04</div>
  <div class="service-detail-copy">
    <p class="service-audience">Individual and institutional delegators</p>
    <h2>High-performance Solana staking</h2>
    <p>Delegate directly to CatalystX or access us through supported performance-focused pools. We operate at 5% validator commission with public performance data and a redundant European footprint.</p>
    <div class="account-box">
      <span>Vote account</span>
      <code>{{ site.validator_info.vote_account }}</code>
    </div>
    <div class="inline-links">
      <a href="{{ site.validator_info.profiles.stakewiz }}" target="_blank" rel="noopener noreferrer">StakeWiz profile</a>
      <a href="{{ site.validator_info.profiles.jito }}" target="_blank" rel="noopener noreferrer">Jito profile</a>
      <a href="https://select.marinade.finance/" target="_blank" rel="noopener noreferrer">Marinade Select</a>
      <a href="{{ site.validator_info.profiles.shinobi }}" target="_blank" rel="noopener noreferrer">Shinobi Pool</a>
    </div>
  </div>
</section>

<section class="cta-band compact-band">
  <div>
    <p class="eyebrow">Start a technical conversation</p>
    <h2>Tell us where you are and what needs to move.</h2>
  </div>
  <a href="{{ '/contact/#infrastructure' | relative_url }}" class="button button-primary">Send your requirements</a>
</section>
