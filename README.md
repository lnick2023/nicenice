# Awesome CVE PoC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cve.mitre.org/images/cvebanner.gif" align="right" width="70">](https://cve.mitre.org/index.html)

> ✍️ A curated list of CVE PoCs.

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 This repo is full of PoCs for CVEs.</b></p>

---

Check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456).

## Menu

- [CVE-2013-6632](#cve-2013-6632)
- [CVE-2014-1705](#cve-2014-1705)
- [CVE-2014-3176](#cve-2014-3176)
- [CVE-2014-7927](#cve-2014-7927)
- [CVE-2014-7928](#cve-2014-7928)
- [CVE-2015-0235](#cve-2015-0235)
- [CVE-2015-1233](#cve-2015-1233)
- [CVE-2015-1242](#cve-2015-1242)
- [CVE-2015-3306](#cve-2015-3306)
- [CVE-2015-6764](#cve-2015-6764)
- [CVE-2015-6771](#cve-2015-6771)
- [CVE-2015-7545](#cve-2015-7545)
- [CVE-2015-8584](#cve-2015-8584)
- [CVE-2016-0728](#cve-2016-0728)
- [CVE-2016-1646](#cve-2016-1646)
- [CVE-2016-1653](#cve-2016-1653)
- [CVE-2016-1665](#cve-2016-1665)
- [CVE-2016-1669](#cve-2016-1669)
- [CVE-2016-1677](#cve-2016-1677)
- [CVE-2016-1688](#cve-2016-1688)
- [CVE-2016-4622](#cve-2016-4622)
- [CVE-2016-3386](#cve-2016-3386)
- [CVE-2016-5129](#cve-2016-5129)
- [CVE-2016-5172](#cve-2016-5172)
- [CVE-2016-7189](#cve-2016-7189)
- [CVE-2016-7190](#cve-2016-7190)
- [CVE-2016-7194](#cve-2016-7194)
- [CVE-2016-7200](#cve-2016-7200)
- [CVE-2016-7201](#cve-2016-7201)
- [CVE-2016-7202](#cve-2016-7202)
- [CVE-2016-7203](#cve-2016-7203)
- [CVE-2016-7240](#cve-2016-7240)
- [CVE-2016-7241](#cve-2016-7241)
- [CVE-2016-7286](#cve-2016-7286)
- [CVE-2016-7287](#cve-2016-7287)
- [CVE-2017-0070](#cve-2017-0070)
- [CVE-2017-2636](#cve-2017-2636)
- [CVE-2017-5638](#cve-2017-5638)

## Resource

### [CVE-2013-6632](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2013-6632.md)

- Integer overflow in Google Chrome before 31.0.1650.57 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors, as demonstrated during a Mobile Pwn2Own competition at PacSec 2013.

### [CVE-2014-1705](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-1705.md)

- Google V8, as used in Google Chrome before 33.0.1750.152 on OS X and Linux and before 33.0.1750.154 on Windows, allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via unknown vectors.

### [CVE-2014-3176](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-3176.md)

- Google Chrome before 37.0.2062.94 does not properly handle the interaction of extensions, IPC, the sync API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2014-3177.

### [CVE-2014-7927](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7927.md)

- The SimplifiedLowering::DoLoadBuffer function in compiler/simplified-lowering.cc in Google V8, as used in Google Chrome before 40.0.2214.91, does not properly choose an integer data type, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2014-7928](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7928.md)

- hydrogen.cc in Google V8, as used Google Chrome before 40.0.2214.91, does not properly handle arrays with holes, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code that triggers an array copy.

### [CVE-2015-0235](https://github.com/geekben/cve-collections/blob/master/cve20150235poc.c)

- Heap-based buffer overflow in the __nss_hostname_digits_dots function in glibc 2.2, and other 2.x versions before 2.18, allows context-dependent attackers to execute arbitrary code via vectors related to the (1) gethostbyname or (2) gethostbyname2 function, aka "GHOST".

### [CVE-2015-1233](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1233.md)

- Google Chrome before 41.0.2272.118 does not properly handle the interaction of IPC, the Gamepad API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors.

### [CVE-2015-1242](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1242.md)

- The ReduceTransitionElementsKind function in hydrogen-check-elimination.cc in Google V8 before 4.2.77.8, as used in Google Chrome before 42.0.2311.90, allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted JavaScript code that leverages "type confusion" in the check-elimination optimization.

### [CVE-2015-3306](https://www.exploit-db.com/exploits/36803/)

- The mod_copy module in ProFTPD 1.3.5 allows remote attackers to read and write to arbitrary files via the site cpfr and site cpto commands.

### [CVE-2015-6764](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6764.md)

- The BasicJsonStringifier::SerializeJSArray function in json-stringifier.h in the JSON stringifier in Google V8, as used in Google Chrome before 47.0.2526.73, improperly loads array elements, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-6771](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6771.md)

- js/array.js in Google V8, as used in Google Chrome before 47.0.2526.73, improperly implements certain map and filter operations for arrays, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-7545](https://hackmd.io/s/SkKL68GIe#🍊-web-300-git)

- The (1) git-remote-ext and (2) unspecified other remote helper programs in Git before 2.3.10, 2.4.x before 2.4.10, 2.5.x before 2.5.4, and 2.6.x before 2.6.1 do not properly restrict the allowed protocols, which might allow remote attackers to execute arbitrary code via a URL in a (a) .gitmodules file or (b) unknown other sources in a submodule.

### [CVE-2015-8584](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-8548.md)

- JSON, OOB.

### [CVE-2016-0728](https://github.com/geekben/cve-collections/blob/master/cve20160728poc.c)

- The join_session_keyring function in security/keys/process_keys.c in the Linux kernel before 4.4.1 mishandles object references in a certain error case, which allows local users to gain privileges or cause a denial of service (integer overflow and use-after-free) via crafted keyctl commands.

### [CVE-2016-1646](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1646.md)

- The Array.prototype.concat implementation in builtins.cc in Google V8, as used in Google Chrome before 49.0.2623.108, does not properly consider element data types, which allows remote attackers to cause a denial of service (out-of-bounds read) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-1653](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1653.md)

- The LoadBuffer implementation in Google V8, as used in Google Chrome before 50.0.2661.75, mishandles data types, which allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted JavaScript code that triggers an out-of-bounds write operation, related to compiler/pipeline.cc and compiler/simplified-lowering.cc.

### [CVE-2016-1665](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1665.md)

- The JSGenericLowering class in compiler/js-generic-lowering.cc in Google V8, as used in Google Chrome before 50.0.2661.94, mishandles comparison operators, which allows remote attackers to obtain sensitive information via crafted JavaScript code.

### [CVE-2016-1669](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1669.md)

- The Zone::New function in zone.cc in Google V8 before 5.0.71.47, as used in Google Chrome before 50.0.2661.102, does not properly determine when to expand certain memory allocations, which allows remote attackers to cause a denial of service (buffer overflow) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-1677](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1677.md)

- uri.js in Google V8 before 5.1.281.26, as used in Google Chrome before 51.0.2704.63, uses an incorrect array type, which allows remote attackers to obtain sensitive information by calling the decodeURI function and leveraging "type confusion".

### [CVE-2016-1688](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-1688.md)

- The regexp (aka regular expression) implementation in Google V8 before 5.0.71.40, as used in Google Chrome before 51.0.2704.63, mishandles external string sizes, which allows remote attackers to cause a denial of service (out-of-bounds read) via crafted JavaScript code.

### [CVE-2016-4622](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4622.md)

- WebKit in Apple iOS before 9.3.3, Safari before 9.1.2, and tvOS before 9.2.2 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4589, CVE-2016-4623, and CVE-2016-4624.

### [CVE-2016-3386](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-3386.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3389, CVE-2016-7190, and CVE-2016-7194.

### [CVE-2016-5129](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5129.md)

- Google V8 before 5.2.361.32, as used in Google Chrome before 52.0.2743.82, does not properly process left-trimmed objects, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-5172](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5172.md)

- The parser in Google V8, as used in Google Chrome before 53.0.2785.113, mishandles scopes, which allows remote attackers to obtain sensitive information from arbitrary memory locations via crafted JavaScript code.

### [CVE-2016-7189](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7189.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code via a crafted web site, aka "Scripting Engine Remote Code Execution Vulnerability".

### [CVE-2016-7190](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7190.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3386, CVE-2016-3389, and CVE-2016-7194.

### [CVE-2016-7194](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7194.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3386, CVE-2016-3389, and CVE-2016-7190.

### [CVE-2016-7200](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7200.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7201, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7201](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7201.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7202](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7202.md)

- The scripting engines in Microsoft Internet Explorer 9 through 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," as demonstrated by the Chakra JavaScript engine, a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7203, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7203](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7203.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7202, CVE-2016-7208, CVE-2016-7240, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7240](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7240.md)

- The Chakra JavaScript scripting engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7200, CVE-2016-7201, CVE-2016-7202, CVE-2016-7203, CVE-2016-7208, CVE-2016-7242, and CVE-2016-7243.

### [CVE-2016-7241](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7241.md)

- Microsoft Internet Explorer 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Microsoft Browser Memory Corruption Vulnerability".

### [CVE-2016-7286](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7286.md)

- The scripting engines in Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7288, CVE-2016-7296, and CVE-2016-7297.

### [CVE-2016-7287](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7287.md)

- The scripting engines in Microsoft Internet Explorer 11 and Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability".

### [CVE-2017-0070](CVE-2017-0070.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-2636](https://a13xp0p0v.github.io/2017/03/24/CVE-2017-2636.html)

- Race condition in drivers/tty/n_hdlc.c in the Linux kernel through 4.10.1 allows local users to gain privileges or cause a denial of service (double free) by setting the HDLC line discipline.

### [CVE-2017-5638](CVE-2017-5638.md)

- The Jakarta Multipart parser in Apache Struts 2 2.3.x before 2.3.32 and 2.5.x before 2.5.10.1 mishandles file upload, which allows remote attackers to execute arbitrary commands via a #cmd= string in a crafted Content-Type HTTP header, as exploited in the wild in March 2017.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sindre Sorhus](http://sindresorhus.com) has waived all copyright and related or neighboring rights to this work.