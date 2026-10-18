# Development workflow

The project was organized as a sequence of bounded research steps with explicit stopping points. The owner directed the scope and accepted or rejected the resulting readiness decisions; AI assistance supported research, coding, and checks.

## Observed workflow

1. **Bootstrap the local environment.** Use a Python virtual environment and a PowerShell setup script. Check dependency imports and fail when required operations fail.
2. **Discover sources.** Prefer original providers and author-controlled research repositories. Record access and provenance separately from reported sample counts.
3. **Audit permitted use.** Distinguish research, contest use, modification, publication of results, and redistribution. Keep unresolved candidates conditional.
4. **Acquire and preserve evidence.** Keep original bytes and download records; record checksums and failures. Do not turn a failed or incorrect file response into a successful dataset acquisition.
5. **Prepare canonical data.** Preserve original labels, unify nullable fields, mark duplicates, screen personal-data patterns, and write Parquet tables and a dataset index.
6. **Report the data gate.** A complete preparation pipeline does not imply a suitable Korean training corpus. The last recorded real-data gate is still blocked.
7. **Explore synthetic prototypes separately.** Later local scripts and artifacts cover synthetic generation, grouped splits, baseline diagnostics, temporal policies, graph propagation, and contextual explanations. Their outputs are not real-data validation.
8. **Control claims and publication.** Reconcile the evidence, identify what was actually tested, and review rights before any artifact or claim leaves the workspace.

## Experimental controls visible in the project

The local implementation contains template-family grouping, checksum-based test identification, one-time evaluation markers, development-policy selection, and frozen-policy records. These are observed mechanisms, not a certification that all experiments obeyed every control. Some reports are older than the prototype files, and the central claim registry has no populated claims.

The portfolio review did not run training, load serialized models, regenerate data, evaluate a holdout, or rerun existing audit scripts that write to the original project. It used static inspection, stored summaries, and independent package validation.

## Reproducibility boundary

This documentation-only package is readable without Python or data access. It does not offer commands for reproducing private experiments. A future code release would need file-level provenance, licensing, authorized data instructions, dependency verification, a reconciled experiment record, and separate publication approval.
