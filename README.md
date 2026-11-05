# Stopper — public resources

Public resources for the independent **Stopper** Safari content-blocking app.

## Privacy policy

- [Политика конфиденциальности — Русский](privacy/)
- [Privacy Policy — English](privacy/en/)

## Support and privacy contact

- **App support and bug reports:** [GitHub Issues](https://github.com/veronikakudlai/stopper-public/issues)
- **Private privacy inquiries:** [privacy_policy.ios@proton.me](mailto:privacy_policy.ios@proton.me)

Issues are public. Do not disclose browsing history, webpage content, cookie values or personally identifying information in an issue.

## Signed filter dataset

This repository separately distributes an **adapted EasyList Cookie** declarative Safari filter dataset. The licensing and attribution conditions are specified in [LICENSE](LICENSE), including CC BY-SA 3.0 and attribution to the EasyList authors.

The `stable.json` manifest and detached `stable.sig` are signed release metadata. Immutable release snapshots and optional deltas are located under `releases/`. Only rule datasets — not executable source code or private signing material — are distributed here. Privacy documents are independent of the signed rule manifest.

Stopper processes page content locally in Safari; downloading filter updates may expose ordinary connection metadata to the file-hosting service. See the public policy for details.

## Legal

The public privacy policy describes the app's information practices. Dataset licensing is separate from the private source code license for the Stopper application.
