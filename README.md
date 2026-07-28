# OpenProof Validator

> **OpenProof is the probative infrastructure. TruthX Engine is the deterministic structuring engine powering it. RPO is the Registered Probative Object it produces.**

This repository provides public validation tools for **Registered Probative Objects (RPOs)**.

It checks whether an RPO conforms to the public specification and whether its protected content has retained its structural integrity.

## Role in the architecture

| Component | Role |
|---|---|
| **TruthX Engine** | Structures heterogeneous evidence through a controlled, deterministic pipeline. |
| **RPO** | Preserves the resulting record, its sources, transformations, reservations and integrity data. |
| **OpenProof Validator** | Checks the RPO’s structural conformity and integrity. |
| **OpenProof** | Provides the surrounding probative infrastructure and verification layer. |

**Processing chain:**

`Evidence → TruthX Engine → RPO → OpenProof validation`

## What the validator checks

The validator can check:

- canonical JSON structure;
- presence of required fields;
- schema compliance;
- integrity-hash format;
- correspondence between protected content and its integrity hash;
- detectable modification of sealed content.

A successful result means that the submitted object passes the implemented structural and integrity checks.

## What successful validation does not mean

Validation does **not** establish:

- that an allegation is true;
- that a source is authentic or reliable;
- that the evidence is complete;
- that a causal interpretation is correct;
- that the record has a particular legal weight;
- that a judicial, institutional or governance decision should be taken.

The validator controls the object. It does not decide the merits of the underlying matter.

**Structural validity is not factual truth. Integrity is not judgment.**

## Official specification

The canonical public RPO specification is maintained here:

[openproof-net/rpo-spec-v0.1](https://github.com/openproof-net/rpo-spec-v0.1)

This validator implements checks derived from that specification. The specification remains the authoritative reference.

## Status

Early public reference implementation.

The current validator demonstrates the verification principles and will evolve alongside the public RPO specification.

## Related repositories

- [RPO Specification](https://github.com/openproof-net/rpo-spec-v0.1) — canonical public specification.
- [RPO Reference](https://github.com/Gersenderdp/rpo-reference) — reference implementation of the specification.
- [RPO Examples](https://github.com/Gersenderdp/rpo-examples) — example probative objects and use cases.

## Maintainer

Maintained by [Gersende de Parcey](https://github.com/Gersenderdp), founder of TruthX and builder of OpenProof.
