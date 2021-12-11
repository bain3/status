---
title: TLS certificate renewal, enable IPv6
date: 2021-12-11 21:00:00 +0100
maintenance: true
resolved: true
resolvedWhen: 2021-12-11 21:45:00 +0100
affected:
 - f.bain.cz
 - s.bain.cz
 - git.bain.cz
---

I am cleaning up some not necessairly unsecure, but messy certificates that were
made when I initially set up the server. Every service will now have its proper
certificate. I am also enabling IPv6 on all affected services.
