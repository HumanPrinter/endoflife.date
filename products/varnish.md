---
title: Varnish
permalink: /varnish
category: server-app
sortReleasesBy: "releaseCycle"
releasePolicyLink: https://varnish-cache.org/releases/
changelogTemplate: https://varnish-cache.org/releases/rel__LATEST__.html
iconSlug: NA
versionCommand: varnishd -V
auto:
-   git: https://github.com/varnishcache/varnish-cache.git
    regex: ^varnish-(?<major>0|[1-9]\d*)\.(?<minor>0|[1-9]\d*)\.(?<patch>0|[1-9]\d*)$
releases:
-   releaseCycle: "7.1"
    eol: 2023-03-15
    latestReleaseDate: 2022-03-15
    latest: 7.1.0
    releaseDate: 2022-03-15
-   releaseCycle: "7.0"
    eol: 2022-09-15
    latestReleaseDate: 2022-01-12
    latest: 7.0.2
    releaseDate: 2021-09-15
-   releaseCycle: "6.0"
    eol: false
    latestReleaseDate: 2022-01-12
    latest: 6.0.10
    lts: true
    releaseDate: 2018-03-15

---

> [Varnish](https://varnish-cache.org/) is a caching HTTP reverse proxy.

A new minor version is released every 6 months.

A list of security vulnerabilities is [available here](https://varnish-cache.org/security/index.html). You can also subscribe to the [varnish-announce](https://varnish-cache.org/lists/mailman/listinfo/varnish-announce) mailing list.
