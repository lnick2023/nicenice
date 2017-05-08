# Awesome CVE PoC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cve.mitre.org/images/cvebanner.gif" align="right" width="70">](https://cve.mitre.org/index.html)

> ✍️ A curated list of CVE PoCs.

Here is a collection about Proof of Concepts of Common Vulnerabilities and Exposures, and you might also want to check out [awesome-web-security](https://github.com/qazbnm456/awesome-web-security).

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 This repo is full of PoCs for CVEs.</b></p>

---

Check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456).

## Contents

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
- [CVE-2015-7450](#cve-2015-7450)
- [CVE-2015-7545](#cve-2015-7545)
- [CVE-2015-8584](#cve-2015-8584)
- [CVE-2016-0728](#cve-2016-0728)
- [CVE-2016-1646](#cve-2016-1646)
- [CVE-2016-1653](#cve-2016-1653)
- [CVE-2016-1665](#cve-2016-1665)
- [CVE-2016-1669](#cve-2016-1669)
- [CVE-2016-1677](#cve-2016-1677)
- [CVE-2016-1688](#cve-2016-1688)
- [CVE-2016-1857](#cve-2016-1857)
- [CVE-2016-3386](#cve-2016-3386)
- [CVE-2016-4622](#cve-2016-4622)
- [CVE-2016-4734](#cve-2016-4734)
- [CVE-2016-5129](#cve-2016-5129)
- [CVE-2016-5172](#cve-2016-5172)
- [CVE-2016-5198](#cve-2016-5198)
- [CVE-2016-5200](#cve-2016-5200)
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
- [CVE-2016-7288](#cve-2016-7288)
- [CVE-2016-7547](#cve-2016-7547)
- [CVE-2016-7552](#cve-2016-7552)
- [CVE-2016-8413](#cve-2016-8413)
- [CVE-2016-8477](#cve-2016-8477)
- [CVE-2016-8584](#cve-2016-8584)
- [CVE-2016-8585](#cve-2016-8585)
- [CVE-2016-8586](#cve-2016-8586)
- [CVE-2016-8587](#cve-2016-8587)
- [CVE-2016-8588](#cve-2016-8588)
- [CVE-2016-8589](#cve-2016-8589)
- [CVE-2016-8590](#cve-2016-8590)
- [CVE-2016-8591](#cve-2016-8591)
- [CVE-2016-8592](#cve-2016-8592)
- [CVE-2016-8593](#cve-2016-8593)
- [CVE-2016-9651](#cve-2016-9651)
- [CVE-2016-10033](#cve-2016-10033)
- [CVE-2017-0070](#cve-2017-0070)
- [CVE-2017-0071](#cve-2017-0071)
- [CVE-2017-0199](#cve-2017-0199)
- [CVE-2017-0392](#cve-2017-0392)
- [CVE-2017-0521](#cve-2017-0521)
- [CVE-2017-0531](#cve-2017-0531)
- [CVE-2017-0576](#cve-2017-0576)
- [CVE-2017-2416](#cve-2017-2416)
- [CVE-2017-2446](#cve-2017-2446)
- [CVE-2017-2447](#cve-2017-2447)
- [CVE-2017-2464](#cve-2017-2464)
- [CVE-2017-2636](#cve-2017-2636)
- [CVE-2017-5135](#cve-2017-5135)
- [CVE-2017-5638](#cve-2017-5638)
- [CVE-2017-5689](#cve-2017-5689)
- [CVE-2017-7219](#cve-2017-7219)
- [CVE-2017-7280](#cve-2017-7280)
- [CVE-2017-7293](#cve-2017-7293)

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

### [CVE-2015-7450](https://cxsecurity.com/issue/WLB-2017030142)

- Serialized-object interfaces in certain IBM analytics, business solutions, cognitive, IT infrastructure, and mobile and social products allow remote attackers to execute arbitrary commands via a crafted serialized Java object, related to the InvokerTransformer class in the Apache Commons Collections library.

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

### [CVE-2016-1857](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-1857.md)

- WebKit, as used in Apple iOS before 9.3.2, Safari before 9.1.1, and tvOS before 9.2.1, allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-1854, CVE-2016-1855, and CVE-2016-1856.

### [CVE-2016-4622](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4622.md)

- WebKit in Apple iOS before 9.3.3, Safari before 9.1.2, and tvOS before 9.2.2 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4589, CVE-2016-4623, and CVE-2016-4624.

### [CVE-2016-4734](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4734.md)

- WebKit in Apple iOS before 10, Safari before 10, and tvOS before 10 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4611, CVE-2016-4730, CVE-2016-4733, and CVE-2016-4735.

### [CVE-2016-3386](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-3386.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3389, CVE-2016-7190, and CVE-2016-7194.

### [CVE-2016-5129](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5129.md)

- Google V8 before 5.2.361.32, as used in Google Chrome before 52.0.2743.82, does not properly process left-trimmed objects, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-5172](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5172.md)

- The parser in Google V8, as used in Google Chrome before 53.0.2785.113, mishandles scopes, which allows remote attackers to obtain sensitive information from arbitrary memory locations via crafted JavaScript code.

### [CVE-2016-5198](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5198.md)

- V8 in Google Chrome prior to 54.0.2840.90 for Linux, and 54.0.2840.85 for Android, and 54.0.2840.87 for Windows and Mac included incorrect optimisation assumptions, which allowed a remote attacker to perform arbitrary read/write operations, leading to code execution, via a crafted HTML page.

### [CVE-2016-5200](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5200.md)

- V8 in Google Chrome prior to 54.0.2840.98 for Mac, and 54.0.2840.99 for Windows, and 54.0.2840.100 for Linux, and 55.0.2883.84 for Android incorrectly applied type rules, which allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

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

### [CVE-2016-7288](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-7288.md)

- The scripting engines in Microsoft Edge allow remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-7286, CVE-2016-7296, and CVE-2016-7297.

### [CVE-2016-7547](https://gist.github.com/malerisch/b8764501d299f2ec9eb145258d404e5f)

- A command execution flaw on the Trend Micro Threat Discovery Appliance 2.6.1062r1 exists with the timezone parameter in the admin_sys_time.cgi interface.

### [CVE-2016-7552](https://gist.github.com/malerisch/5de8b408443ee9253b3954a62a8d97b4)

- On the Trend Micro Threat Discovery Appliance 2.6.1062r1, directory traversal when processing a session_id cookie allows a remote, unauthenticated attacker to delete arbitrary files as root. This can be used to bypass authentication or cause a DoS.

### [CVE-2016-8413](https://github.com/derrekr/android_security/blob/master/CVE-2016-8413/msm_infoleak_main.c)

- An information disclosure vulnerability in the Qualcomm camera driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32709702. References: QC-CR#518731.

### [CVE-2016-8477](https://github.com/derrekr/android_security/blob/master/CVE-2016-8477/msm_eeprom_name_infoleak_main.c)

- An information disclosure vulnerability in the Qualcomm camera driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32720522. References: QC-CR#1090007.

### [CVE-2016-8584](https://gist.github.com/malerisch/0b8ecfcb03a2c2f26e5f649cf1df8d33)

- Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier uses predictable session values, which allows remote attackers to bypass authentication by guessing the value.

### [CVE-2016-8585](https://gist.github.com/malerisch/91239147d4fceffa63006974889ef1af)

- admin_sys_time.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the timezone parameter.

### [CVE-2016-8586](https://gist.github.com/malerisch/97c160aa4e8219c7c9ad25107444a280)

- detected_potential_files.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8587](https://gist.github.com/malerisch/aac1ad3e6f3bfd70b35ba6538ecbff23)

- dlp_policy_upload.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code via an archive file containing a symlink to /eng_ptn_stores/prod/sensorSDK/data/ or /eng_ptn_stores/prod/sensorSDK/backup_pol/.

### [CVE-2016-8588](https://gist.github.com/malerisch/93be2141dfc5709159468762937f2853)

- The hotfix_upload.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code via shell metacharacters in the file name of an uploaded file.

### [CVE-2016-8589](https://gist.github.com/malerisch/3bbb6d0b235fa5af2ba6f05826fe3846)

- log_query_dae.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8590](https://gist.github.com/malerisch/7b84a4bd6eee0a3a591677f421653a2e)

- log_query_dlp.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8591](https://gist.github.com/malerisch/5dd838a723b342bb04121f29a8333e00)

- log_query.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8592](https://gist.github.com/malerisch/0c78e49124561524fd59d6635007eefd)

- log_query_system.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-8593](https://gist.github.com/malerisch/c59ab650c8e226ef22cdfbfeeee6d4ec)

- log_query_system.cgi in Trend Micro Threat Discovery Appliance 2.6.1062r1 and earlier allows remote authenticated users to execute arbitrary code as the root user via shell metacharacters in the cache_id parameter.

### [CVE-2016-9651](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-9651.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2016-10033](https://exploitbox.io/vuln/WordPress-Exploit-4-6-RCE-CODE-EXEC-CVE-2016-10033.html)

- The mailSend function in the isMail transport in PHPMailer before 5.2.18 might allow remote attackers to pass extra parameters to the mail command and consequently execute arbitrary code via a \" (backslash double quote) in a crafted Sender property.

### [CVE-2017-0070](CVE-2017-0070.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0071](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0071.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0199](CVE-2017-0199.md)

- Microsoft Office 2007 SP3, Microsoft Office 2010 SP2, Microsoft Office 2013 SP1, Microsoft Office 2016, Microsoft Windows Vista SP2, Windows Server 2008 SP2, Windows 7 SP1, Windows 8.1 allow remote attackers to execute arbitrary code via a crafted document, aka "Microsoft Office/WordPad Remote Code Execution Vulnerability w/Windows API."

### [CVE-2017-0392](https://github.com/derrekr/android_security/blob/master/CVE-2017-0392)

- A denial of service vulnerability in VBRISeeker.cpp in libstagefright in Mediaserver could enable a remote attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High due to the possibility of remote denial of service. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1. Android ID: A-32577290.

### [CVE-2017-0521](https://github.com/derrekr/android_security/tree/master/CVE-2017-0521)

- An elevation of privilege vulnerability in the Qualcomm camera driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32919951. References: QC-CR#1097709.

### [CVE-2017-0531](https://github.com/derrekr/android_security/blob/master/CVE-2017-0531/msm_lsm_client_lab_main.c)

- An information disclosure vulnerability in the Qualcomm Wi-Fi driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32877245. References: QC-CR#1087469.

### [CVE-2017-0576](https://github.com/derrekr/android_security/blob/master/CVE-2017-0576/qcom_qcedev_byteoffset_overflow.c)

- An elevation of privilege vulnerability in the Qualcomm crypto engine driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-33544431. References: QC-CR#1103089.

### [CVE-2017-2416](https://blog.flanker017.me/cve-2017-2416-gif-remote-exec/)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. macOS before 10.12.4 is affected. tvOS before 10.2 is affected. watchOS before 3.2 is affected. The issue involves the "ImageIO" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted image file.

### [CVE-2017-2446](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2446.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code via a crafted web site that leverages the mishandling of strict mode functions.

### [CVE-2017-2447](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2447.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to obtain sensitive information or cause a denial of service (memory corruption) via a crafted web site.

### [CVE-2017-2464](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2464.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2636](https://a13xp0p0v.github.io/2017/03/24/CVE-2017-2636.html)

- Race condition in drivers/tty/n_hdlc.c in the Linux kernel through 4.10.1 allows local users to gain privileges or cause a denial of service (double free) by setting the HDLC line discipline.

### [CVE-2017-5135](https://stringbleed.github.io/)

- Certain Technicolor devices have an SNMP access-control bypass, possibly involving an ISP customization in some cases. The Technicolor (formerly Cisco) DPC3928SL with firmware D3928SL-P15-13-A386-c3420r55105-160127a could be reached by any SNMP community string from the Internet; also, you can write in the MIB because it provides write properties, aka Stringbleed. NOTE: the string-bleed/StringBleed-CVE-2017-5135 GitHub repository is not a valid reference as of 2017-04-27; it contains Trojan horse code purported to exploit this vulnerability.

### [CVE-2017-5638](CVE-2017-5638.md)

- The Jakarta Multipart parser in Apache Struts 2 2.3.x before 2.3.32 and 2.5.x before 2.5.10.1 mishandles file upload, which allows remote attackers to execute arbitrary commands via a #cmd= string in a crafted Content-Type HTTP header, as exploited in the wild in March 2017.

### [CVE-2017-5689](CVE-2017-5689.md)

- An unprivileged network attacker could gain system privileges to provisioned Intel manageability SKUs: Intel Active Management Technology (AMT) and Intel Standard Manageability (ISM). An unprivileged local attacker could provision manageability features gaining unprivileged network or local system privileges on Intel manageability SKUs: Intel Active Management Technology (AMT), Intel Standard Manageability (ISM), and Intel Small Business Technology (SBT).

### [CVE-2017-7219](https://blog.scrt.ch/2017/04/26/heap-overflow-vulnerability-in-citrix-netscaler-gateway-cve-2017-7219/)

- A heap overflow vulnerability in Citrix NetScaler Gateway versions 10.1 before 135.8/135.12, 10.5 before 65.11, 11.0 before 70.12, and 11.1 before 52.13 allows a remote authenticated attacker to run arbitrary commands via unspecified vectors.

### [CVE-2017-7280](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An issue was discovered in api/includes/systems.php in Unitrends Enterprise Backup before 9.0.0. User input is not properly filtered before being sent to a popen function. This allows for remote code execution by sending a specially crafted user variable.

### [CVE-2017-7293](CVE-2017-7293.md)

- The DAX2API service installed as part of the Realtek Audio Driver on Windows 10 is vulnerable to a privilege escalation vulnerability which allows a normal user to get arbitrary system privileges.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@qazbnm456](https://qazbnm456.github.io/) has waived all copyright and related or neighboring rights to this work.
