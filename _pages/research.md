---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /wordpress/research/
---


Privacy-Preserving Computation
===============================
While my research utilizes many primitives in the realm of privacy-preserving computation, I highlight the two primitives that I have worked with the most:

Zero Knowledge Proofs
------
Zero Knowledge Proofs (ZKPs) allow a Prove to prove to a Verifier that they know a secret without leaking any information about the secret. My current research has been focused on the application of ZKPs in emerging learning paradigms. Our most recent work, zPROBE, utilizes ZKPs to verify computation and ensure robustness for federated learning. In this work, we protect against data poisoning attacks in the malicious client security setting. We do this by employing the ZKPs for verifiable computation during secure aggregation and range checks after aggregation. Some of our future works in this domain are focused on verifiable computation for machine learning. In collaboration with Intel Labs, I am currently working on a hardware accelerator for ring-based zero knowledge Succinct Non-Interactive Arguments of Knowledge (zkSNARKs).

Fully Homomorphic Encryption
------

Fully Homomorphic Encryption (FHE) allows any arbitrary computation to be done on encrypted data. I was introduced to FHE during an internship with Intel Labs, in which I was working on the DARPA DPRIVE project. DARPA proposed the DPRIVE effort to realize a hardware accelerator that can perform FHE workloads in a comparable order of magnitude to plaintext computation. A key operation in FHE is polynomial multiplication, which can be done efficiently using the Number Theoretic Transform (NTT). The NTT is a generalization of the DFT. During my time at Intel Labs, I focused on developing a hardware-aware implementation of the NTT for the DARPA DPRIVE accelerator. By the end of the internship, I was able to develop a heavily optimized NTT, resulting in two invention disclosures pertaining to my design, and built a model for the full compute engine of the accelerator.