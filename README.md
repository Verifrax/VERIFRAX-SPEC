# VERIFRAX-SPEC

Derived specification publication surface for the governed Verifrax system.

## Status

* Layer: derived specification publication
* Repository class: governed derived surface
* Upstream authored source: `VERIFRAX`
* npm package: `@verifrax/verifrax-spec`
* Public host ownership: none claimed as sole host surface in this README
* Package status: public npm package `@verifrax/verifrax-spec@0.1.0`
* License: Apache License Version 2.0

## One-sentence role

VERIFRAX-SPEC publishes derived specification artifacts from VERIFRAX-authored source material so that specification consumers, public verifier surfaces, and chain readers can inspect stable derived outputs without mistaking this repository for upstream protocol authority.

## What this repository is

VERIFRAX-SPEC is the derived specification repository of the stack.

It exists to provide:

* published specification artifacts derived from VERIFRAX
* structured specification surfaces suitable for downstream inspection
* stable publication boundary for derived protocol material
* explicit linkage back to the authored source repository
* verifier-consumable specification visibility for public inspection surfaces
* specification-side support for artifact-chain legibility, including artifact-0005 dependency context

This repository is a projection surface.

It is not the authored source of protocol truth.

## What this repository is not

VERIFRAX-SPEC is not:

* the upstream authored protocol repository
* the governance root
* the authority issuance repository
* the governed execution runtime
* the public verifier UI
* the proof publication repository
* the intake repository
* the evidence-root registry
* the seal archive surface

VERIFRAX-SPEC does not:

* issue authority objects
* emit CORPIFORM receipts
* register artifact truth at the evidence root
* replace VERIFRAX as authored normative source
* replace VERIFRAX-verify as the public verifier surface
* replace proof publication at `proof.verifrax.net`

A derived specification is not upstream authority just because it is easier to read.

## Normative direction

The load-bearing direction is fixed:

* VERIFRAX authors normative source material.
* VERIFRAX-SPEC publishes derived specification artifacts from VERIFRAX.
* Derived artifacts are not upstream authority.
* Governance authority is external and bound through AUCTORISEAL plus the governed repo set in `.github`.

This direction must remain explicit in this README.

If VERIFRAX-SPEC is described as canonical upstream authorship, the stack becomes internally contradictory.

## Stack position

Read the system in this order when tracing authority and interpretation:

1. `.github` — governance root and governed repo boundary
2. `AUCTORISEAL` — authority issuance and public authority object publication
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored source, evidence root, verification boundary, artifact registration
5. `VERIFRAX-SPEC` — derived publication of specification artifacts
6. `VERIFRAX-PROFILES` — deterministic profile constraints that do not change the spec
7. `VERIFRAX-verify` — public verification surface

VERIFRAX-SPEC therefore sits downstream from VERIFRAX and upstream of human readers and public inspection workflows that need derived specification visibility.

## Publication boundary

This repository publishes derived material.

That means:

* source authority remains in VERIFRAX
* projection integrity matters here
* drift from authored material is a defect here
* reader convenience does not promote this repository into upstream authority

If any derived artifact disagrees with VERIFRAX-authored material, VERIFRAX wins.

## Relationship to the public verifier

Artifact-0005 and the public verifier both make this repository load-bearing.

### Why artifact-0005 matters here

Artifact-0005 is the chain boundary that must connect:

* public canonical authority
* governed execution
* recorded receipt
* evidence registration
* verifier-visible interpretation

VERIFRAX-SPEC does not create artifact-0005.

But VERIFRAX-SPEC must remain aligned with the same vocabulary, schema direction, and interpretation boundary that artifact-0005 relies on.

This repository must therefore mention artifact-0005 as an active chain dependency without falsely claiming that artifact-0005 is complete or sealed here.

### Why the verifier matters here

`VERIFRAX-verify` is the public verifier surface at `https://verify.verifrax.net/`.

That public surface depends on stable specification interpretation.

VERIFRAX-SPEC must therefore stay connected to:

* the authored source in VERIFRAX
* the public verifier in VERIFRAX-verify
* the evidence-root semantics that artifact-0005 depends on

But it must not claim that the public verifier is owned by this repository.

## Relationship to profiles

`VERIFRAX-PROFILES` is adjacent to this repository but does not outrank it.

The correct boundary is:

* VERIFRAX authors normative source material
* VERIFRAX-SPEC publishes derived specification artifacts
* VERIFRAX-PROFILES defines deterministic profile constraints
* profiles do not change the spec

If profiles are allowed to impersonate spec authorship, specification truth fractures.

## Relationship to evidence

VERIFRAX-SPEC is not the evidence root.

It may reference artifact-chain material where necessary for interpretation, but it must not:

* register artifacts as the official chain root
* present itself as the authoritative artifact index
* claim receipt registration authority
* replace VERIFRAX evidence surfaces

Its evidence role is descriptive and derived, not primary.

## Inputs and outputs

### Inputs consumed by this repository

This repository consumes:

* authored normative material from VERIFRAX
* agreed terminology used across authority, execution, and verification boundaries
* profile-adjacent constraints where relevant but non-authoritative for spec authorship
* verifier-facing interpretation requirements that must remain aligned with authored source

### Outputs produced by this repository

This repository produces:

* published derived specification artifacts
* structured publication views over authored source material
* stable derived references for readers and verifier-adjacent consumers

It does not produce authority, execution, proof publication, or artifact registration.

## Public-surface relationship

This README should avoid false host claims.

It is correct to link adjacent public surfaces such as:

* `https://verify.verifrax.net/` — public verifier
* `https://proof.verifrax.net/` — proof publication
* `https://api.verifrax.net/` — execution surface
* `https://auctoriseal.verifrax.net/` — authority surface
* `https://corpiform.verifrax.net/` — runtime reference surface

It is not correct to claim that VERIFRAX-SPEC solely owns those surfaces.

If a rendered specification view exists elsewhere, this repository still remains the derived publication repository, not the universal owner of every spec-facing URL.

## Drift rule

A derived publication surface fails when any of these happen:

* it contradicts VERIFRAX-authored source
* it implies upstream authority
* it omits the verifier relationship
* it omits artifact-0005 chain dependency language
* it presents profile material as if profiles rewrite the spec
* it claims evidence-root authority it does not hold

## Reader rule

Read this repository after VERIFRAX and before using derived specification artifacts as support material for:

* public verification interpretation
* documentation surfaces
* downstream implementation reading
* profile alignment review

If a reader starts here, this README must still direct them back to VERIFRAX as upstream authored source.

## Canonical related repositories

* [`.github`](https://github.com/Verifrax/.github) — governance root
* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored normative source and evidence root
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance/reference
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution and receipts
* [`VERIFRAX-PROFILES`](https://github.com/Verifrax/VERIFRAX-PROFILES) — deterministic profiles that do not change the spec
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verifier UI
* [`VERIFRAX-DOCS`](https://github.com/Verifrax/VERIFRAX-DOCS) — explanatory documentation surface

## CI and governance expectations

Any workflow, badge, or status language here must prove publication integrity rather than decorate it.

This repository should only claim checks that are real for:

* identity alignment with repository truth
* derived/publication consistency
* authored-source drift detection
* determinism where declared
* reference integrity to adjacent repositories and surfaces

README prose must not substitute for source-to-derived verification.


## Verifrax system path labels

The governed Verifrax path that this README must stay compatible with is:

1. `.github` — organization governance and governed repository boundary
2. `AUCTORISEAL` — authority issuance and public authority reference
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored protocol, evidence root, and artifact-chain registration boundary
5. `VERIFRAX-SPEC` — derived specification publication surface
6. `VERIFRAX-PROFILES` — deterministic profile-constraint surface
7. `VERIFRAX-SAMPLES` — pinned sample and reproducibility surface
8. `VERIFRAX-verify` — public verification repository and UI boundary
9. `VERIFRAX-DOCS` — explanatory documentation surface
10. `cicullis` — enforcement boundary
11. `proof` — proof publication surface
12. `SIGILLARIUM` — seal and archive reference surface
13. `apply` — intake surface

The live host-label map that must remain explicit and non-contradictory is:

* `https://api.verifrax.net/` — execution surface
* `https://proof.verifrax.net/` — proof publication surface
* `https://auctoriseal.verifrax.net/` — authority issuance and authority reference surface
* `https://corpiform.verifrax.net/` — runtime and receipt reference surface
* `https://cicullis.verifrax.net/` — enforcement reference surface
* `https://verify.verifrax.net/` — public verification surface
* `https://sigillarium.verifrax.net/` — seal and archive reference surface
* `https://apply.verifrax.net/` — intake surface
* `https://docs.verifrax.net/` — documentation surface

This README must remain compatible with `artifact-0005` as the load-bearing authority → execution → verification → evidence boundary without claiming that this repository alone authors, proves, seals, or registers `artifact-0005` unless that role is actually true for this repository.


## Security

A specification publication failure can contaminate downstream interpretation even when code is unchanged.

Security issues here include:

* silent divergence from VERIFRAX-authored source
* incorrect derived publication of verification-relevant fields
* misleading artifact-0005 interpretation text
* incorrect public-verifier boundary statements

## Contributing

A change is wrong if it:

* makes VERIFRAX-SPEC appear upstream from VERIFRAX
* removes the derived/publication distinction
* weakens verifier linkage
* weakens artifact-0005 chain relevance
* introduces host claims not mechanically proved
* adds package/publication claims not backed by metadata reality
* replaces current truth with placeholder prose

## License

Apache License Version 2.0. See `LICENSE`.
