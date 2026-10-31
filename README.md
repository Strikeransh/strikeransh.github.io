# Ashish Kumar — Portfolio site

This repository is structured for GitHub Pages with a simple selector homepage and two focused portfolios.

## Routes

- `/` — portfolio selector
- `/cloudops/` — CloudOps portfolio
- `/devops/` — DevOps portfolio

## Publish

1. Copy the contents of this folder into the root of `Strikeransh/strikeransh.github.io`.
2. Commit and push to the `main` branch.
3. In GitHub, confirm Pages is configured to deploy from the `main` branch and repository root.
4. Wait for the Pages deployment, then test all three URLs.

## Before publishing

- Confirm certification titles and years against the certificates (especially the OCI Foundations credential).
- Review the CloudOps and DevOps skill labels for accuracy.
- Remove customer names, account IDs, credentials, private IPs, internal hostnames, and other sensitive details from any future source-code repositories.
- Add source-code URLs only after the sanitized repositories are public.
- Confirm whether ECS/Fargate and other optional AWS services should be listed as hands-on before upgrading their skill labels.

## Project architecture

The DevOps page currently includes a high-level snapshot replication and retention workflow plus a centralized log collection/SIEM project summary. The code repositories are intentionally not linked until they are published.
