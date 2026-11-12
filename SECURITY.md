# Security policy

## Reporting a vulnerability

Email **security@fingerly.io**. Please do not open a public issue, pull request or discussion for a suspected vulnerability.

This policy covers every Fingerly repository in this organisation and the SDKs they publish. It is also published at [fingerly.io/.well-known/security.txt](https://fingerly.io/.well-known/security.txt). How Fingerly protects keys, webhooks and visitor data is described at [docs.fingerly.io/docs/security](https://docs.fingerly.io/docs/security).

## What to include

The more of this you can give us, the faster we can reproduce and fix the problem.

- Where the issue is: the repository, package, file or endpoint.
- The type of issue, for example an authentication bypass, a signature check that can be skipped, or data exposure.
- The affected SDK and version, plus the platform or runtime you tested on.
- Step-by-step instructions to reproduce it.
- Proof of concept or exploit code, if you have any.
- Any special configuration needed to reproduce it.
- What an attacker could do with it.

Never include real secret keys, webhook secrets or personal data in a report. Redact them.

## Sample code

Example and sample code in these repositories is illustrative. It may not be hardened for production, so review it before you use it in a live system.

## Scope

Please test only with accounts and data you own, and do not disrupt other customers or access their data. There is no bug bounty programme.
