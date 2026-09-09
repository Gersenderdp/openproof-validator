Gersenderdp/openproof-validator

# OpenProof Validator — project status and verification entry point

**Status: this repository is a scaffold, not a complete validation package.**

The current public verification example is maintained in [openproof-net/rpo-spec-v0.1](https://github.com/openproof-net/rpo-spec-v0.1). Start there rather than relying on the placeholder files here.

## Available checks

The [local demonstration checker](https://github.com/openproof-net/rpo-spec-v0.1/blob/main/tools/verify-demo.cjs) inspects basic fields and compares a SHA-256 fingerprint with a supplied, retained reference. Its tests cover content changes, ordering, malformed structures and the documented command.

[Run the quick start](https://github.com/openproof-net/rpo-spec-v0.1#verify-the-public-example-locally) · [Try browser verification](https://rpo.openproof.net/tests.html)

## Explicit limits

The demonstration does not perform full JSON Schema validation or verify source files, PDFs, signatures or external registry entries. A matching fingerprint does not establish the truth of an assertion or the legal validity of a record. The reference must itself be preserved or authenticated independently where authenticity matters.

The complete OpenProof application and TruthX Engine remain private. The first product pilot is OpenProof Legal.

[Contribute to the maintained example](https://github.com/openproof-net/rpo-spec-v0.1/blob/main/CONTRIBUTING.md) · [Qualify a pilot case](https://openproof.net/qualify?intent=case) · [Contact Gersende](https://www.linkedin.com/in/gryard/)

Existing licensing terms in this repository are unchanged.

