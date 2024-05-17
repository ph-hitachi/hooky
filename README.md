# hooky

This repository is a submodule for https://github.com/markuta/CVE-2024-32002, which contains a simple hook located in [y/hooks/post-checkout](y/hooks/post-checkout) to open calculator on macOS systems:
```
open -a Calculator.app
```
More info about the vulnerability can be found [here](https://github.blog/2024-05-14-securing-git-addressing-5-new-vulnerabilities/) and [here](https://github.com/git/git/security/advisories/GHSA-8h77-4q3w-gfgv).
