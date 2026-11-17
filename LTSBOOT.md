# ltsboot: Spring Framework 5.3 LTS fork

**Disclaimer.** ltsboot is an independent open source project. It is not affiliated with, endorsed by, or sponsored by Broadcom Inc. or VMware, Inc. Spring and Spring Boot are trademarks of Broadcom Inc. and are used here only to describe compatibility.

## Base

- Upstream: [spring-projects/spring-framework](https://github.com/spring-projects/spring-framework)
- Base tag: `v5.3.39` (2024-08-14), the last OSS release of the 5.3 line.
- This fork starts from 5.3.39, not from 5.3.31 (the version managed by Boot 2.7.18). The eight later patch releases are OSS fixes.
- License: Apache License 2.0 ([LICENSE.txt](LICENSE.txt), [NOTICE](NOTICE)).

## Versioning

Versions have four numeric parts: `<upstream version>.<ltsboot release>`, for example `5.3.39.1` and `5.3.39.2`.
Maven and Gradle are expected to rank `5.3.39.1` above the base version `5.3.39`; the ordering is verified before the first release.

First release: `5.3.39.1`.

## Coordinates

- groupId: `io.github.ltsboot` (organization name still to be defined).
- artifactIds are unchanged, for example `spring-core` and `spring-webmvc`.

## Compatibility

Java package names do not change (`org.springframework.*`). Consuming projects keep their imports and change only the version and groupId.

## Changes

Every modified file carries the line `Modifications Copyright 2026 the ltsboot contributors.` directly below the original copyright line. All changed files are listed in [CHANGES.md](CHANGES.md).
