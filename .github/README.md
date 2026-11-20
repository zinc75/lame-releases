# LAME release snapshots

The files of the release archives of [LAME](https://lame.sourceforge.io/), one commit per release, exactly as published. This is not a fork and not a mirror. LAME is developed and maintained by its authors at https://lame.sourceforge.io/: nothing is developed or maintained here, and this repository is not affiliated with the project. It only keeps snapshots of the releases.

LAME ("LAME Ain't an MP3 Encoder") is an MP3 encoder developed by the LAME project and its contributors, who are named in the files of the archive (`README`, `ChangeLog`). It is under the LGPL (`COPYING`, `LICENSE`). Bug reports and contributions belong to the project: https://lame.sourceforge.io/.

## Why this repository exists

[Jack Apps Collection for macOS](https://github.com/zinc75/jack-apps-collection-macos) links libmp3lame statically into its applications, and each application ships the licence and the source of what it contains. LAME is developed in Subversion on SourceForge and has no official Git repository, so there is no Git commit to reference for a release. The collection therefore needs a Git repository where the release is a commit, to reference it as a submodule. This repository keeps that copy, and it keeps the source available if a download site goes away.

## What is in it

Each tag points to a commit whose files are those of the release archive, nothing added and nothing changed. The commit message gives the address of the archive and its checksums; the project publishes an MD5 and no signature. The archive is also attached to the release of the same name. This `README` is the only addition: it is in `.github/`, on top of the tagged commits, and is not part of any release.
