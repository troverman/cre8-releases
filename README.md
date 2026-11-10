# cre8-releases

Release bundles for the CRE8 runtime peer, `cre8runtime`.

Each release holds one archive per platform, named
`cre8-runtime-peer-<version>-<platform>` (`.zip` on Windows, `.tar.gz`
elsewhere), and a `SHA256SUMS` file covering every archive in it.

The installers at `https://www.cre8.xyz/install.sh` and
`https://www.cre8.xyz/install.ps1` download from here. They read `SHA256SUMS`
first, stop if the release has no bundle for your platform, and check the
archive against its checksum before unpacking.

This repository holds bundles and checksums only; it has no source code.
