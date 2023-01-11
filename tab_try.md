---
title: Try
layout:  null
tab: true
order: 1
tags: secure-coding-dojo
---
### Hosted by OWASP
[https://securecodingdojo.owasp.org/](https://securecodingdojo.owasp.org/ )

### Host it locally
The following steps will get you the basic configuration for the Dojo. For advanced configuration and integrations check the [wiki](https://github.com/trendmicro/SecureCodingDojo/wiki/Deploying-with-Docker)

- Install Docker latest version.
- Git clone the repository
- Change directory to the repo root directory
- Configure an environment variable DATA_DIR as a mount point for the dojo files. On *nix/mac modify .bash_profile as follows

    `export DATA_DIR="/YOUR_DATA_DIR"`

- On Mac you must allow Docker access to this directory in Docker > Preferences > File Sharing
- Restart your terminal
- Run with

    `docker-compose up`
