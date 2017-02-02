# Awesome CVE PoC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cve.mitre.org/images/cvebanner.gif" align="right" width="70">](https://cve.mitre.org/index.html)

> ✍️ A curated list of CVE PoCs.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 This repo is full of PoCs for CVEs.</b></p>

---

Check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456).

## Menu

- [PoC](#poc)
    - [CVE-2013-6632](#cve-2013-6632)
    - [CVE-2014-1705](#cve-2014-1705)
    - [CVE-2014-3176](#cve-2014-3176)
    - [CVE-2014-7927](#cve-2014-7927)
    - [CVE-2014-7928](#cve-2014-7928)
    - [CVE-2016-4622](#cve-2016-4622)

## Resource

### PoC

* [CVE-2013-6632](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2013-6632.md):

    Integer overflow in Google Chrome before 31.0.1650.57 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors, as demonstrated during a Mobile Pwn2Own competition at PacSec 2013.

* [CVE-2014-1705](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-1705.md):

    Google V8, as used in Google Chrome before 33.0.1750.152 on OS X and Linux and before 33.0.1750.154 on Windows, allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via unknown vectors.

* [CVE-2014-3176](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-3176.md):

    Google Chrome before 37.0.2062.94 does not properly handle the interaction of extensions, IPC, the sync API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2014-3177.

* [CVE-2014-7927](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7927.md):

    The SimplifiedLowering::DoLoadBuffer function in compiler/simplified-lowering.cc in Google V8, as used in Google Chrome before 40.0.2214.91, does not properly choose an integer data type, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

* [CVE-2014-7928](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7928.md):

    hydrogen.cc in Google V8, as used Google Chrome before 40.0.2214.91, does not properly handle arrays with holes, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code that triggers an array copy.

* [CVE-2016-4622](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4622.md):

    WebKit in Apple iOS before 9.3.3, Safari before 9.1.2, and tvOS before 9.2.2 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4589, CVE-2016-4623, and CVE-2016-4624.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.