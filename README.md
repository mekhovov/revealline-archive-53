# RevealLine archive 53

LOCAL PREPARATION ONLY. This proposed new bounded archive preserves the original published v0.84.0 distribution. No repository creation, GitHub push/PR/workflow/deployment or main selector change is authorized by this preparation.

Immutable source `1107f570508e0d107440236b6aeedbce8506cd7d`, tree `793ee7e682e206e0914754cf60fd93af0792c463`, annotated tag object `13c6d9632d1f2e41bc32c6b39a5db7999050c76e`, release `394095977`. The preserved source qualification is the published 14,168-byte original SHA-256 `f1c01e8d8f928572994409647e7a5be74faa8f294d00ee08b42c23982952563e`, not the later independently assembled corroboration package.

Infrastructure reuses actual Archive52 deployment `2dd7e8a598d8e37af063933733b8dc458ea9d44f`. The original ZIP extractor remains pinned to `30530b3436a1a9737be93f67f308587f89b2f8bc` / SHA-256 `38081b1791b49cb7328d18b4d4325c2876bb3bc8d7db03f4610f8d8a7c4bf91b`. The strict 3 GiB workspace guard, original ZIP CRC/member hashing, full inventory/hidden-file checks and 800,000,000-byte archive budget remain unchanged. No historical source rebuild, prior-shard modification or eviction is performed.

## Qualification compatibility

The v1 identity/passed/six-gate validation is retained; mixed v2 waiver fields in a v1 record are rejected. The new v2 path mirrors the reviewed main Pages qualification consumer: `qualified-with-test-waiver`, `releaseEligible: true`, exact source/tree/checkout, tests `{status: waived, counts: null}`, ordered five mandatory non-test gates, successful build, frozen-artifact proof flags, bounded safe unique evidence pins and exact authorized test policy. A `passed` field or test pass/count/shard claims in v2 are refused.

For v2 only, `sourceQualification.policyEvidence` in the source lock exactly matches the original qualification pin. `metadata/v0.84.0/test-policy.json` preserves the 490 original bytes from the frozen source. Before and after extraction the preparer compares them to `git show <exact source>:publishing/test-policy.json` and checks the source tree. The policy is provenance input, not a new runtime/public artifact path. The public qualification remains the untouched published original.

This bounded consumer validates the same structural evidence claims as the reviewed main consumer. It does not rerun the earlier publisher's full raw run/job/inspection archive validation; the immutable published qualification hash remains pinned to that already-reviewed package.

Automated infrastructure suites are temporarily optional (`run_tests: true` opts in), and none were run during local preparation. Metadata, inventory, schema and exact-source policy checks are mandatory. Waived tests are never relabeled passed. Hosted extraction/build, public HTTP and genuine browser admission remain pending future explicit handoff.
