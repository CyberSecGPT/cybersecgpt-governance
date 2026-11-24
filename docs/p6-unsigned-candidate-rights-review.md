# P6 unsigned candidate rights review

Status: Proposed — authorization withheld pending evidence and owner decision.

This review implements the decision gate described in [Tokenizer PR #35](https://github.com/CyberSecGPT/cybersecgpt-tokenizer/pull/35), consistent with [ADR-0012](https://github.com/CyberSecGPT/cybersecgpt-docs/blob/8faa2f801eb87b6b8fb62e81976f33a5c6974b98/docs/decisions/ADR-0012-artifact-signing-and-promotion-trust.md). It is a review record, not a legal determination or a permission grant.

## Evidence required before approval

- Pin the admitted dataset snapshot, manifest, and source inventory by immutable revision and digest.
- For each source, attach the controlling permission or licence record and its revision, the authority behind it, and any notices, restrictions, expiry, or revocation terms. Prior training permission is evidence, not automatic authorization for this build.
- Verify separately that each source permits constructing the inert unsigned candidate and providing it to named independent evaluators under approved access, retention, and deletion controls.
- Record the proposed build and evaluation scope, authorized roles, storage and handling constraints, and an explicit owner decision linked to the reviewed evidence.

Missing, conflicting, expired, or unverifiable rights keep construction blocked. Any change to the admitted inputs or permitted use requires renewed review. Once approved, this gate still requires a separate reviewed implementation before any candidate is built. Distribution approval comes only after independent evaluation of the exact frozen unsigned bytes. This review grants no distribution, signing, publication, promotion, new training, or P7 authority.
