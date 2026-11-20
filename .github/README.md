# LAME release snapshots

The files of the release archives of [LAME](https://lame.sourceforge.io/), one commit per release, exactly as published. This is not a fork and not a mirror. LAME is developed and maintained by the LAME project and its contributors at https://lame.sourceforge.io/: nothing is developed or maintained here, and this repository is not affiliated with the project. It only keeps snapshots of the releases.

LAME ("LAME Ain't an MP3 Encoder") is an MP3 encoder. The people who wrote it are named in the files of the archive (`README`, `ChangeLog`). It is under the LGPL (`COPYING`, `LICENSE`). Bug reports and contributions belong to the project: https://lame.sourceforge.io/.

## Why this repository exists

[Jack Apps Collection for macOS](https://github.com/zinc75/jack-apps-collection-macos) builds libmp3lame and links it statically into its applications. Each application ships the licence and the source of the libraries it contains, so the collection needs to point to the exact source of the release that it uses. It does so with a Git submodule, which needs a commit of a Git repository.

LAME is developed in Subversion on SourceForge, and the LAME project has no official Git repository. There is no Git commit that gives the source of a release. This repository fills that gap: each release is one commit, and the collection references the commit of the release it uses. The snapshots also keep the source available if the download site goes away.

## What is in it

Each tag points to a commit whose files are those of the release archive, nothing added and nothing changed. The commit message gives the address of the archive and its MD5 and its SHA-256 (the project publishes an MD5 and no signature). The archive is also attached to the release of the same name.

The only addition is this `README`, in `.github/`, on top of the tagged commits: it is not part of any release.
