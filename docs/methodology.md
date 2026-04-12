# Methodology

This repository does not expose the private operational system used to collect and moderate submissions.

Instead, it publishes the public methodology and sanitized outputs of that system.

## Collection model

Cases are submitted through the official campaign site.

The operational intake system may collect both public and private fields. Not every submitted field is eligible for publication.

## Publication model

A case may contribute to public reporting in different ways:

- fully public case
- private case that still contributes to aggregate totals
- case hidden from public view due to abuse review

## Public outputs

When published here, outputs are limited to:
- aggregate statistics
- curated public case snapshots
- curated public voice snapshots
- schemas describing the public data shape

## What is excluded

This repository does not publish:
- private contact details
- raw submission dumps
- private moderation notes
- anti-abuse heuristics
- operator-only metadata

## Why this boundary exists

The campaign needs to be auditable without becoming easy to game, exploit, or misuse.

That means the public can inspect the campaign's logic and outputs without receiving the operational internals that would expose people or weaken the system.
