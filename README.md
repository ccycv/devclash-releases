# DevClash Desktop Releases

This repository hosts public installers, signed update artifacts, release notes, and the update manifest for **DevClash**.

Visit [devclash.ai/download](https://devclash.ai/download) for available installers. The first approved version is **0.1.0-beta.1**. Signed installers are being prepared; no production installers are currently published.

`latest.json` is updated only after a release passes the build, signature, and distribution checks. Its initial `null` version means that no update is available. Apps use the public updater key embedded in DevClash to verify downloaded updates before installation.

Application source and private service configuration live in the separate DevClash source repository. No credentials or source code are stored here.
