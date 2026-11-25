<img src="assets/profile_hero.svg" alt="Prince Upadhyay · Independent researcher in India" width="100%">

I build research software for questions I can check computationally. In SharkByte, that means comparing individual amplitudes across machines. In my spectral work, it means proving how many channels a particular reconstruction needs. I publish the assumptions and the evidence alongside each result.

**[Explore Reggae Shark Universe](https://github.com/reggaesharkk/Reggae-shark-universe-#the-public-work)** · [CV](https://github.com/reggaesharkk/reggaesharkk/blob/main/CV.md) · [ORCID](https://orcid.org/0009-0002-1170-4487)

## SharkByte milestones

**4,294,967,296 entries checked on two platforms.** For one connected 50-qubit GHZ-family circuit, Google Compute Engine and Colab each wrote the populated basis indices and complex amplitudes to disk and checked them against a closed-form reference. Both runs produced the same SHA-256 digest for each array. [Google Cloud receipt](https://github.com/reggaesharkk/SharkByte/blob/26dae2551b926feae8641bc4bf46c498d03dcc12/evidence/connected-ghz50-gcp/2p32/sharkbyte-ghz50-4b-gcp-receipt.json) · [Colab receipt](https://github.com/reggaesharkk/SharkByte/blob/26dae2551b926feae8641bc4bf46c498d03dcc12/evidence/connected-ghz50-colab/retry-2p32/sharkbyte-connected-ghz50-4294967296-colab.json)

- **Cross-engine agreement.** A separate connected 20-qubit circuit populated all **1,048,576 amplitudes**. Four engines agreed in the full-state comparison. [Circuit, methods and tolerances](https://github.com/reggaesharkk/SharkByte/blob/15ea5e5df3a4d0dfefafeefe528862f737e2d2c8/docs/high-support-connected-entanglement.md)
- **SharkByte Certify RC1 · private developer trials.** The public milestone report records **74 Lean modules** rebuilt on ARM64 and x86-64, and **220/220 benchmark samples** with the expected native-verifier outcome on Linux x86-64. The proofs and trial fixtures are private. The quantum contract covers X, Z, CX and H on up to eight qubits and 64 gates, with pruning disabled. Native ARM64 deployment remains blocked. [Trial report and open obligations](https://github.com/reggaesharkk/SharkByte#private-research-milestones--gates-6b156b23)

[Run the public verification notebook in Colab](https://colab.research.google.com/github/reggaesharkk/SharkByte/blob/main/notebooks/SharkByte-Colab-Integrated-Verification.ipynb)

## Research milestones

| Question | Result | Evidence |
| --- | --- | --- |
| How many spectral channels does the 99-site odd-ring benchmark need? | **Exactly 11** at relative complex L₂ error 0.001 for the specified instance. The search excluded every subset of ten or fewer channels and certified an eleven-channel reconstruction. | [LRSC certificate and assumptions](https://github.com/reggaesharkk/lrsc-odd-ring-spectral-rank/blob/main/finite-benchmark/k001-certificate/CERTIFICATE.md) |
| Which statistical model should a future AI self-reference study use? | **4,000 simulated fits** in Phase 7 retained the correlated M1 model under the prespecified calibration rule. Live confirmatory collection remains paused. | [Design Lab scientific status](https://github.com/reggaesharkk/self-referential-processing-designlab#scientific-status) |
| What can a verifier establish about a request’s lifecycle? | **16 Lean theorems** in the Reggae Shark Protocol v1.3.2 lifecycle module include a proof that a request can reach the sealed, active state only through the prescribed event sequence. | [Lean proof source](https://github.com/reggaesharkk/The-Reggae-Shark-Protocol/blob/main/lean/TypestateLifecycle.lean) |

**Open mathematical questions.** My Navier–Stokes audit establishes finite Fourier–Galerkin results. Extending them to continuum regularity remains open. My Riemann work includes finite-band certificates and conditional calculations. The strict >79% bound and the Riemann Hypothesis remain open. [Navier–Stokes evidence timeline](https://github.com/reggaesharkk/navier-stokes-bridge-audit/blob/df401d491cf243d937842eb51be1bd1f5ff8c226/notes/NAVIER_STOKES_EVIDENCE_TIMELINE_2026_11_04.md) · [Riemann frontier audit](https://github.com/reggaesharkk/riemann-bandwidth1-frontier-audit)

## Collaboration

If you replay a benchmark, find a counterexample, or see a stronger way to test a claim, I’d like to hear from you. A source revision and the smallest example that shows what you found are a great place to start. [Email me](mailto:starxshark@gmail.com)
