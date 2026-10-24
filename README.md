# T3 Code Cloud runtime assets

This repository hosts compiled Linux x64 runtime archives for T3 Code Cloud. It contains no application source or credentials.

Each release is named `payload-<sha256>` and preserves the runtime archive's original version. The desktop verifies the digest from its selected runtime descriptor before caching or uploading the archive to Daytona. Published releases are immutable.

T3 Code is distributed under the MIT License, copyright (c) 2026 T3 Tools Inc. The archives retain dependency license notices.
