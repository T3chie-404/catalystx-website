---
layout: default
title: Contact CatalystX
nav_title: Contact
permalink: /contact/
description: Talk with CatalystX about SWQoS, staked QUIC forwarding, validator-sourced shreds, connected RPC access, or Solana staking.
---

<section class="page-hero" id="infrastructure">
  <p class="eyebrow">Operator to operator</p>
  <h1>Tell us what needs to move faster.</h1>
  <p>Share your workload, region, and current setup. We will help scope a validator-backed path or connect you with an RPC or infrastructure provider that is already integrated.</p>
  <div class="hero-actions">
    <a class="button button-primary" href="mailto:{{ site.email }}?subject=CatalystX%20infrastructure%20request">Email the operator</a>
    <a class="button button-secondary" href="https://x.com/{{ site.twitter_username }}" target="_blank" rel="noopener noreferrer">Message on X</a>
  </div>
</section>

<section class="contact-grid section-block" aria-label="Ways CatalystX can help">
  <article class="contact-card">
    <span class="service-index">01</span>
    <p class="service-audience">RPC operators</p>
    <h2>SWQoS and staked QUIC</h2>
    <p>Discuss trusted-source onboarding, forwarding topology, traffic volume, and regional standby options.</p>
    <a class="text-link" href="mailto:{{ site.email }}?subject=SWQoS%20and%20staked%20QUIC%20request">Start an SWQoS conversation <span aria-hidden="true">→</span></a>
  </article>

  <article class="contact-card">
    <span class="service-index">02</span>
    <p class="service-audience">Data infrastructure</p>
    <h2>Real-time shreds</h2>
    <p>Scope validator-sourced shred delivery by geography, transport, capacity, and workload.</p>
    <a class="text-link" href="mailto:{{ site.email }}?subject=Real-time%20shred%20delivery%20request">Discuss shred delivery <span aria-hidden="true">→</span></a>
  </article>

  <article class="contact-card">
    <span class="service-index">03</span>
    <p class="service-audience">Builders and users</p>
    <h2>Connected RPC access</h2>
    <p>Describe what you are building and we can introduce an integrated provider suited to the job.</p>
    <a class="text-link" href="mailto:{{ site.email }}?subject=Connected%20RPC%20access%20request">Request a provider match <span aria-hidden="true">→</span></a>
  </article>
</section>

<section class="split-section section-block">
  <div>
    <p class="eyebrow">A useful first message</p>
    <h2>Give us enough context to route the request.</h2>
    <p>Exact requirements can be worked out together. These four details make the first exchange productive.</p>
  </div>
  <div class="content-card">
    <ul class="check-list">
      <li>Your workload or use case</li>
      <li>Primary region and source IPs, if relevant</li>
      <li>Expected traffic or data volume</li>
      <li>Latency, resilience, or budget priorities</li>
    </ul>
  </div>
</section>

<section class="proof-grid section-block">
  <div class="proof-copy">
    <p class="eyebrow">Staking and partnerships</p>
    <h2>Prefer to start with the validator?</h2>
    <p>Use the vote account below for direct delegation inquiries, institutional staking discussions, and ecosystem partnerships. Public performance is available before you contact us.</p>
    <div class="inline-links">
      <a href="{{ site.validator_info.profiles.stakewiz }}" target="_blank" rel="noopener noreferrer">View live performance</a>
      <a href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener noreferrer">GitHub</a>
    </div>
  </div>
  <div class="account-box">
    <span>Vote account</span>
    <code>{{ site.validator_info.vote_account }}</code>
  </div>
</section>

<section class="cta-band compact-band">
  <div>
    <p class="eyebrow">Direct contact</p>
    <h2>{{ site.email }}</h2>
    <p>Technical, staking, and partnership inquiries all reach the operator.</p>
  </div>
  <a class="button button-primary" href="mailto:{{ site.email }}">Send an email</a>
</section>
