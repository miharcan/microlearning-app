# IP Boundary (Public Repo)

## Purpose
This document defines what can be published in the public repository and what must remain private.

## Public (Allowed)
- Product vision and UX principles.
- Sanitized screenshots and demo media.
- High-level feature descriptions.
- Public roadmap themes.
- Non-sensitive summaries of research direction.

## Private (Not Allowed)
- Production Android codebase.
- QA generation pipeline internals.
- Full question banks and raw/intermediate datasets.
- Prompt engineering templates and moderation thresholds.
- Model/quality scoring heuristics that create competitive advantage.
- Secret keys, tokens, credentials, signing assets, or private infra references.

## Publication Rule
If an artifact could let a third party replicate core product behavior, content quality layer, or intervention policy quickly, keep it private.

## Review Checklist Before Commit
1. No credentials or keys.
2. No raw or full-scale learning content dumps.
3. No proprietary policy/threshold constants.
4. No private architecture or ops details.
5. Only sanitized images and narrative docs.
