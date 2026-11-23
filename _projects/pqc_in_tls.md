---
layout: page
title: Post-Quantum Cryptography in TLS
description: Merkle Tree Certificates & Certificate Transparency
img: assets/img/pqc_project.png
importance: 1
category: research
---

## Overview

A research investigating the implications of post-quantum cryptography for TLS certificate infrastructure and the Web Public Key Infrastructure (Web PKI).

## Research Focus

- Examined the implications of post-quantum cryptographic algorithms for digital certificates.
- Investigated certificate sizes and TLS handshake overhead.
- Studied Merkle Tree Certificates (MTCs).
- Explored the relationship between MTCs and Certificate Transparency.
- Considered approaches to improving the efficiency and scalability of Web PKI.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/tls.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <a href="https://assets.bytebytego.com/diagrams/0220-how-does-https-work.png" target="_blank" rel="noopener noreferrer">
    TLS Handshake
  </a>
</div>

## Topics Covered

- Post-Quantum Cryptography
- TLS
- X.509 Certificates
- Web PKI
- Merkle Trees
- Certificate Transparency

<div class="caption">
    Certificate Transparency
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ct.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pqc_ciphers.png" title="PQC Cipher Candidates" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/merkle_trees.png" title="Merkle Trees" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the recommended PQC ciphers by <a href="https://www.enisa.europa.eu/publications/post-quantum-cryptography-current-state-and-quantum-mitigation" target="_blank" rel="noopener noreferrer">ENISA</a> and on the right, an introduction on how Merkle Trees work.
</div>

## Research Outcome

The project explored how certificate infrastructure may evolve to accommodate post-quantum cryptography while managing performance and scalability challenges.
