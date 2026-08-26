# Security Policy

This offline verifier never reads, issues, rotates or revokes credentials. It rejects secret-shaped values and raw/body/log/prompt/content fields. Inputs are capped at 4 MiB; paths are workspace-relative and symlink-safe; content-addressed writes are exclusive and verified by read-back. A settled verdict applies only to supplied evidence and does not authenticate receipts or prove the consumer set exhaustive. Report vulnerabilities through GitHub Security Advisories without attaching credentials or production manifests.
