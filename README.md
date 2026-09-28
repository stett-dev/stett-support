# Stett support

The public tracker for [Stett](https://www.stett.dev), the review-first client for GitHub. Bugs, ideas and questions all land here, and we answer them here.

## How to reach us

- **In the app:** click the **?** icon in the top bar ("Help and feedback"). It files an issue in this repo for you, with the page you were on attached.
- **On GitHub:** [open an issue](https://github.com/stett-dev/stett-support/issues/new) in this repo.
- **By email:** [team@stett.dev](mailto:team@stett.dev), for anything you'd rather not post in public, such as billing, your account or your data.

## Before you post

Issues here are public. Don't paste tokens, private code, customer data or screenshots of private repositories. Email us instead and we'll take it from there.

**Found a security problem?** Email [team@stett.dev](mailto:team@stett.dev). Please don't open an issue for it.

## What an in-app report includes

Your message, then a short footer with your GitHub login, your plan, the page you were on, the app version and your browser's user agent. That's all; nothing else from your account is attached.

## Labels

| Label | Meaning |
| --- | --- |
| `type:bug`, `type:idea`, `type:question` | What kind of report it is |
| `source:in-app` | Filed from the Help button in the app |
| `needs-triage` | Not looked at yet |
| `p0`, `p1`, `p2` | How urgent it is once triaged, `p0` highest |
| `area:pr`, `area:issues`, `area:notifications`, `area:discussions`, `area:billing` | The part of the app it's about |

## What happens next

We read every report, usually within one working day. We label it, reply on the issue and keep it updated. When we close it, the last comment says whether it was fixed, answered or not planned.

## About the code in this repo

The small Next.js app here is a sandbox we use to test Stett against a real repository, for things like stacked pull requests. It isn't part of Stett, and you don't need it to report anything.
