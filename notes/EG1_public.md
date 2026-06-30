# EG1 Public Note (Projected Response Floor)

Mature wording: `projection / protected core`.

In-paper anchor: `paper/BUZZARD_GEE_CONJECTURE_PREPRINT.md` (`BZG_G1`).

## Goal
Make the projected response floor explicit as the protected-core gate for `proving persistence of the expected automorphic-Galois compatibility package through an admissible compatibility closure architecture`.

## Objects

- admissible class: the declared class `A` in the main preprint.
- canonical/base object package: let `u_tau = (A_tau, G_tau, D_tau, N_tau, L_tau)` denote the admissible state of automorphic packets, Galois data, defect ledgers, normalization parameters, and endpoint locks.
- projected core: the response sector controlled by `kappa_compatibility`.
- carried remainder interface: downstream defect and coherence terms remain outside the protected core rather than being hidden in it.

## Closure Criterion

`BZG_G1` closes when `kappa_compatibility` satisfies the response-floor requirement: projected response has a strict positive floor.
This is the first protected-core contribution to the strict margin `M_BZG`.

## Lemma Chain and Proof Payload

### Lemma EG1.1 (projection reduction)
On the declared admissible class, the response object may be read on the projected sector without changing the target gate.

Payload: verify that all quantities used by `kappa_compatibility` are defined on the projected sector named in the main preprint.

### Lemma EG1.2 (protected-core floor)
If the projected response floor is positive on the admissible sector, then the core cannot collapse before the later transport and remainder gates are evaluated.

Payload: check the artifact key `kappa_compatibility` and the corresponding extraction input/provenance record.

### Theorem EG1.3 (core gate closure)
If Lemmas EG1.1-EG1.2 hold and the runtime artifact accepts `kappa_compatibility`, then `BZG_G1` supplies the projected/protected-core input to `M_BZG`.

## Current Instantiation

- gate: `BZG_G1`
- artifact key: `kappa_compatibility`
- mature equivalent: `projection / protected core`
- audit surface: `artifacts/constants_registry.json`, `artifacts/constants_extracted.json`, and `repro/certificate_runtime.json`
