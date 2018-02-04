# Awesome CVE PoC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://cve.mitre.org/images/cvebanner.gif" align="right" width="70">](https://cve.mitre.org/index.html)

> ✍️ A curated list of CVE PoCs.

Here is a collection about Proof of Concepts of Common Vulnerabilities and Exposures, and you might also want to check out [awesome-web-security](https://github.com/qazbnm456/awesome-web-security).

*Please read the [contribution guidelines](CONTRIBUTING.md) before contributing.*

---

<p align="center"><b>🌈 This repo is full of PoCs for CVEs.</b></p>

---

If you like this and would like to support it. Check out my [patreon page](https://www.patreon.com/boik) :)
And don't forget to check out my [repos](https://github.com/qazbnm456) 🐾 or say *hi* on my [Twitter](https://twitter.com/qazbnm456) as well!

## Contents

- [CVE-2013-6632](#cve-2013-6632)
- [CVE-2014-1705](#cve-2014-1705)
- [CVE-2014-3176](#cve-2014-3176)
- [CVE-2014-6332](#cve-2014-6332)
- [CVE-2014-7927](#cve-2014-7927)
- [CVE-2014-7928](#cve-2014-7928)
- [CVE-2015-0235](#cve-2015-0235)
- [CVE-2015-0240](#cve-2015-0240)
- [CVE-2015-1233](#cve-2015-1233)
- [CVE-2015-1242](#cve-2015-1242)
- [CVE-2015-1635](#cve-2015-1635)
- [CVE-2015-1830](#cve-2015-1830)
- [CVE-2015-3306](#cve-2015-3306)
- [CVE-2015-5531](#cve-2015-5531)
- [CVE-2015-6086](#cve-2015-6086)
- [CVE-2015-6764](#cve-2015-6764)
- [CVE-2015-6771](#cve-2015-6771)
- [CVE-2015-7450](#cve-2015-7450)
- [CVE-2015-7501](#cve-2015-7501)
- [CVE-2015-7545](#cve-2015-7545)
- [CVE-2015-8584](#cve-2015-8584)
- [CVE-2016-0040](#cve-2016-0040)
- [CVE-2016-0450](#cve-2016-0450)
- [CVE-2016-0451](#cve-2016-0451)
- [CVE-2016-0728](#cve-2016-0728)
- [CVE-2016-0792](#cve-2016-0792)
- [CVE-2016-1646](#cve-2016-1646)
- [CVE-2016-1653](#cve-2016-1653)
- [CVE-2016-1665](#cve-2016-1665)
- [CVE-2016-1669](#cve-2016-1669)
- [CVE-2016-1677](#cve-2016-1677)
- [CVE-2016-1688](#cve-2016-1688)
- [CVE-2016-1857](#cve-2016-1857)
- [CVE-2016-1910](#cve-2016-1910)
- [CVE-2016-2384](#cve-2016-2384)
- [CVE-2016-2386](#cve-2016-2386)
- [CVE-2016-2388](#cve-2016-2388)
- [CVE-2016-3087](#cve-2016-3087)
- [CVE-2016-3088](#cve-2016-3088)
- [CVE-2016-3309](#cve-2016-3309)
- [CVE-2016-3371](#cve-2016-3371)
- [CVE-2016-3386](#cve-2016-3386)
- [CVE-2016-4338](#cve-2016-4338)
- [CVE-2016-4622](#cve-2016-4622)
- [CVE-2016-4734](#cve-2016-4734)
- [CVE-2016-4971](#cve-2016-4971)
- [CVE-2016-5129](#cve-2016-5129)
- [CVE-2016-5172](#cve-2016-5172)
- [CVE-2016-5195](#cve-2016-5195)
- [CVE-2016-5198](#cve-2016-5198)
- [CVE-2016-5200](#cve-2016-5200)
- [CVE-2016-5346](#cve-2016-5346)
- [CVE-2016-5734](#cve-2016-5734)
- [CVE-2016-6210](#cve-2016-6210)
- [CVE-2016-6277](#cve-2016-6277)
- [CVE-2016-6415](#cve-2016-6415)
- [CVE-2016-6662](#cve-2016-6662)
- [CVE-2016-6700](#cve-2016-6700)
- [CVE-2016-6702](#cve-2016-6702)
- [CVE-2016-6762](#cve-2016-6762)
- [CVE-2016-6787](#cve-2016-6787)
- [CVE-2016-7124](#cve-2016-7124)
- [CVE-2016-7189](#cve-2016-7189)
- [CVE-2016-7190](#cve-2016-7190)
- [CVE-2016-7194](#cve-2016-7194)
- [CVE-2016-7200](#cve-2016-7200)
- [CVE-2016-7201](#cve-2016-7201)
- [CVE-2016-7202](#cve-2016-7202)
- [CVE-2016-7203](#cve-2016-7203)
- [CVE-2016-7240](#cve-2016-7240)
- [CVE-2016-7241](#cve-2016-7241)
- [CVE-2016-7255](#cve-2016-7255)
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
- [CVE-2016-9793](#cve-2016-9793)
- [CVE-2016-10033](#cve-2016-10033)
- [CVE-2016-10191](#cve-2016-10191)
- [CVE-2016-10277](#cve-2016-10277)
- [CVE-2016-10370](#cve-2016-10370)
- [CVE-2017-0015](#cve-2017-0015)
- [CVE-2017-0037](#cve-2017-0037)
- [CVE-2017-0059](#cve-2017-0059)
- [CVE-2017-0070](#cve-2017-0070)
- [CVE-2017-0071](#cve-2017-0071)
- [CVE-2017-0134](#cve-2017-0134)
- [CVE-2017-0141](#cve-2017-0141)
- [CVE-2017-0143](#cve-2017-0143)
- [CVE-2017-0144](#cve-2017-0144)
- [CVE-2017-0145](#cve-2017-0145)
- [CVE-2017-0146](#cve-2017-0146)
- [CVE-2017-0147](#cve-2017-0147)
- [CVE-2017-0148](#cve-2017-0148)
- [CVE-2017-0199](#cve-2017-0199)
- [CVE-2017-0213](#cve-2017-0213)
- [CVE-2017-0283](#cve-2017-0283)
- [CVE-2017-0290](#cve-2017-0290)
- [CVE-2017-0392](#cve-2017-0392)
- [CVE-2017-0475](#cve-2017-0475)
- [CVE-2017-0497](#cve-2017-0497)
- [CVE-2017-0521](#cve-2017-0521)
- [CVE-2017-0531](#cve-2017-0531)
- [CVE-2017-0541](#cve-2017-0541)
- [CVE-2017-0548](#cve-2017-0548)
- [CVE-2017-0576](#cve-2017-0576)
- [CVE-2017-0678](#cve-2017-0678)
- [CVE-2017-0714](#cve-2017-0714)
- [CVE-2017-0718](#cve-2017-0718)
- [CVE-2017-0719](#cve-2017-0719)
- [CVE-2017-0720](#cve-2017-0720)
- [CVE-2017-0722](#cve-2017-0722)
- [CVE-2017-0745](#cve-2017-0745)
- [CVE-2017-0758](#cve-2017-0758)
- [CVE-2017-0760](#cve-2017-0760)
- [CVE-2017-0761](#cve-2017-0761)
- [CVE-2017-0764](#cve-2017-0764)
- [CVE-2017-0776](#cve-2017-0776)
- [CVE-2017-0777](#cve-2017-0777)
- [CVE-2017-0778](#cve-2017-0778)
- [CVE-2017-0781](#cve-2017-0781)
- [CVE-2017-0785](#cve-2017-0785)
- [CVE-2017-0813](#cve-2017-0813)
- [CVE-2017-0814](#cve-2017-0814)
- [CVE-2017-0820](#cve-2017-0820)
- [CVE-2017-1082](#cve-2017-1082)
- [CVE-2017-1083](#cve-2017-1083)
- [CVE-2017-1084](#cve-2017-1084)
- [CVE-2017-1085](#cve-2017-1085)
- [CVE-2017-2416](#cve-2017-2416)
- [CVE-2017-2419](#cve-2017-2419)
- [CVE-2017-2446](#cve-2017-2446)
- [CVE-2017-2447](#cve-2017-2447)
- [CVE-2017-2464](#cve-2017-2464)
- [CVE-2017-2491](#cve-2017-2491)
- [CVE-2017-2521](#cve-2017-2521)
- [CVE-2017-2531](#cve-2017-2531)
- [CVE-2017-2536](#cve-2017-2536)
- [CVE-2017-2547](#cve-2017-2547)
- [CVE-2017-2636](#cve-2017-2636)
- [CVE-2017-2641](#cve-2017-2641)
- [CVE-2017-3506](#cve-2017-3506)
- [CVE-2017-3599](#cve-2017-3599)
- [CVE-2017-3629](#cve-2017-3629)
- [CVE-2017-3630](#cve-2017-3630)
- [CVE-2017-3631](#cve-2017-3631)
- [CVE-2017-3881](#cve-2017-3881)
- [CVE-2017-4901](#CVE-2017-4901)
- [CVE-2017-4914](#cve-2017-4914)
- [CVE-2017-4915](#cve-2017-4915)
- [CVE-2017-4918](#cve-2017-4918)
- [CVE-2017-4933](#cve-2017-4933)
- [CVE-2017-4946](#cve-2017-4946)
- [CVE-2017-4971](#cve-2017-4971)
- [CVE-2017-5030](#cve-2017-5030)
- [CVE-2017-5033](#cve-2017-5033)
- [CVE-2017-5040](#cve-2017-5040)
- [CVE-2017-5053](#cve-2017-5053)
- [CVE-2017-5070](#cve-2017-5070)
- [CVE-2017-5071](#cve-2017-5071)
- [CVE-2017-5088](#cve-2017-5088)
- [CVE-2017-5098](#cve-2017-5098)
- [CVE-2017-5115](#cve-2017-5115)
- [CVE-2017-5116](#cve-2017-5116)
- [CVE-2017-5121](#cve-2017-5121)
- [CVE-2017-5122](#cve-2017-5122)
- [CVE-2017-5123](#cve-2017-5123)
- [CVE-2017-5124](#cve-2017-5124)
- [CVE-2017-5126](#cve-2017-5126)
- [CVE-2017-5127](#cve-2017-5127)
- [CVE-2017-5128](#cve-2017-5128)
- [CVE-2017-5129](#cve-2017-5129)
- [CVE-2017-5133](#cve-2017-5133)
- [CVE-2017-5135](#cve-2017-5135)
- [CVE-2017-5622](#cve-2017-5622)
- [CVE-2017-5624](#cve-2017-5624)
- [CVE-2017-5626](#cve-2017-5626)
- [CVE-2017-5638](#cve-2017-5638)
- [CVE-2017-5689](#cve-2017-5689)
- [CVE-2017-5715](#cve-2017-5715)
- [CVE-2017-5753](#cve-2017-5753)
- [CVE-2017-5754](#cve-2017-5754)
- [CVE-2017-5891](#cve-2017-5891)
- [CVE-2017-5892](#cve-2017-5892)
- [CVE-2017-5948](#cve-2017-5948)
- [CVE-2017-6008](#cve-2017-6008)
- [CVE-2017-6074](#cve-2017-6074)
- [CVE-2017-6178](#cve-2017-6178)
- [CVE-2017-6326](#cve-2017-6326)
- [CVE-2017-6736](#cve-2017-6736)
- [CVE-2017-6980](#cve-2017-6980)
- [CVE-2017-6984](#cve-2017-6984)
- [CVE-2017-7056](#cve-2017-7056)
- [CVE-2017-7061](#cve-2017-7061)
- [CVE-2017-7089](#cve-2017-7089)
- [CVE-2017-7092](#cve-2017-7092)
- [CVE-2017-7115](#cve-2017-7115)
- [CVE-2017-7117](#cve-2017-7117)
- [CVE-2017-7219](#cve-2017-7219)
- [CVE-2017-7269](#cve-2017-7269)
- [CVE-2017-7279](#cve-2017-7279)
- [CVE-2017-7280](#cve-2017-7280)
- [CVE-2017-7281](#cve-2017-7281)
- [CVE-2017-7281](#cve-2017-7282)
- [CVE-2017-7281](#cve-2017-7283)
- [CVE-2017-7293](#cve-2017-7293)
- [CVE-2017-7308](#cve-2017-7308)
- [CVE-2017-7344](#cve-2017-7344)
- [CVE-2017-7442](#cve-2017-7442)
- [CVE-2017-7494](#cve-2017-7494)
- [CVE-2017-7504](#cve-2017-7504)
- [CVE-2017-7525](#cve-2017-7525)
- [CVE-2017-7529](#cve-2017-7529)
- [CVE-2017-7533](#cve-2017-7533)
- [CVE-2017-8046](#cve-2017-8046)
- [CVE-2017-8295](#cve-2017-8295)
- [CVE-2017-8386](#cve-2017-8386)
- [CVE-2017-8464](#cve-2017-8464)
- [CVE-2017-8514](#cve-2017-8514)
- [CVE-2017-8543](#cve-2017-8543)
- [CVE-2017-8548](#cve-2017-8548)
- [CVE-2017-8570](#cve-2017-8570)
- [CVE-2017-8601](#cve-2017-8601)
- [CVE-2017-8625](#cve-2017-8625)
- [CVE-2017-8634](#cve-2017-8634)
- [CVE-2017-8636](#cve-2017-8636)
- [CVE-2017-8640](#cve-2017-8640)
- [CVE-2017-8645](#cve-2017-8645)
- [CVE-2017-8646](#cve-2017-8646)
- [CVE-2017-8656](#cve-2017-8656)
- [CVE-2017-8670](#cve-2017-8670)
- [CVE-2017-8671](#cve-2017-8671)
- [CVE-2017-8729](#cve-2017-8729)
- [CVE-2017-8740](#cve-2017-8740)
- [CVE-2017-8751](#cve-2017-8751)
- [CVE-2017-8755](#cve-2017-8755)
- [CVE-2017-8759](#cve-2017-8759)
- [CVE-2017-8850](#cve-2017-8850)
- [CVE-2017-8851](#cve-2017-8851)
- [CVE-2017-8877](#cve-2017-8877)
- [CVE-2017-8878](#cve-2017-8878)
- [CVE-2017-8890](#cve-2017-8890)
- [CVE-2017-8917](#cve-2017-8917)
- [CVE-2017-9417](#cve-2017-9417)
- [CVE-2017-9791](#cve-2017-9791)
- [CVE-2017-9798](#cve-2017-9798)
- [CVE-2017-9805](#cve-2017-9805)
- [CVE-2017-9822](#cve-2017-9822)
- [CVE-2017-9948](#cve-2017-9948)
- [CVE-2017-9993](#cve-2017-9993)
- [CVE-2017-10271](#cve-2017-10271)
- [CVE-2017-10661](#cve-2017-10661)
- [CVE-2017-11105](#cve-2017-11105)
- [CVE-2017-11120](#cve-2017-11120)
- [CVE-2017-11421](#cve-2017-11421)
- [CVE-2017-11444](#cve-2017-11444)
- [CVE-2017-11610](#cve-2017-11610)
- [CVE-2017-11764](#cve-2017-11764)
- [CVE-2017-11774](#cve-2017-11774)
- [CVE-2017-11779](#cve-2017-11779)
- [CVE-2017-11793](#cve-2017-11793)
- [CVE-2017-11799](#cve-2017-11799)
- [CVE-2017-11802](#cve-2017-11802)
- [CVE-2017-11809](#cve-2017-11809)
- [CVE-2017-11811](#cve-2017-11811)
- [CVE-2017-11812](#CVE-2017-11812)
- [CVE-2017-11839](#cve-2017-11839)
- [CVE-2017-11840](#cve-2017-11840)
- [CVE-2017-11841](#cve-2017-11841)
- [CVE-2017-11855](#cve-2017-11855)
- [CVE-2017-11861](#cve-2017-11861)
- [CVE-2017-11870](#cve-2017-11870)
- [CVE-2017-11873](#cve-2017-11873)
- [CVE-2017-11882](#cve-2017-11882)
- [CVE-2017-11890](#cve-2017-11890)
- [CVE-2017-11893](#cve-2017-11893)
- [CVE-2017-11903](#cve-2017-11903)
- [CVE-2017-11906](#cve-2017-11906)
- [CVE-2017-11907](#cve-2017-11907)
- [CVE-2017-11909](#cve-2017-11909)
- [CVE-2017-11911](#cve-2017-11911)
- [CVE-2017-11914](#cve-2017-11914)
- [CVE-2017-11918](#cve-2017-11918)
- [CVE-2017-12097](#cve-2017-12097)
- [CVE-2017-12098](#cve-2017-12098)
- [CVE-2017-12149](#cve-2017-12149)
- [CVE-2017-12581](#cve-2017-12581)
- [CVE-2017-12611](#cve-2017-12611)
- [CVE-2017-12615](#cve-2017-12615)
- [CVE-2017-12617](#cve-2017-12617)
- [CVE-2017-13089](#cve-2017-13089)
- [CVE-2017-14335](#cve-2017-14335)
- [CVE-2017-14491](#cve-2017-14491)
- [CVE-2017-14492](#cve-2017-14492)
- [CVE-2017-14493](#cve-2017-14493)
- [CVE-2017-14494](#cve-2017-14494)
- [CVE-2017-14495](#cve-2017-14495)
- [CVE-2017-14496](#cve-2017-14496)
- [CVE-2017-14904](#cve-2017-14904)
- [CVE-2017-15361](#cve-2017-15361)
- [CVE-2017-15388](#cve-2017-15388)
- [CVE-2017-15396](#cve-2017-15396)
- [CVE-2017-15399](#cve-2017-15399)
- [CVE-2017-15401](#cve-2017-15401)
- [CVE-2017-15411](#cve-2017-15411)
- [CVE-2017-15412](#cve-2017-15412)
- [CVE-2017-15415](#cve-2017-15415)
- [CVE-2017-15428](#cve-2017-15428)
- [CVE-2017-15613](#cve-2017-15613)
- [CVE-2017-15614](#cve-2017-15614)
- [CVE-2017-15615](#cve-2017-15615)
- [CVE-2017-15616](#cve-2017-15616)
- [CVE-2017-15617](#cve-2017-15617)
- [CVE-2017-15618](#cve-2017-15618)
- [CVE-2017-15619](#cve-2017-15619)
- [CVE-2017-15620](#cve-2017-15620)
- [CVE-2017-15621](#cve-2017-15621)
- [CVE-2017-15622](#cve-2017-15622)
- [CVE-2017-15623](#cve-2017-15623)
- [CVE-2017-15624](#cve-2017-15624)
- [CVE-2017-15625](#cve-2017-15625)
- [CVE-2017-15626](#cve-2017-15626)
- [CVE-2017-15627](#cve-2017-15627)
- [CVE-2017-15628](#cve-2017-15628)
- [CVE-2017-15629](#cve-2017-15629)
- [CVE-2017-15630](#cve-2017-15630)
- [CVE-2017-15631](#cve-2017-15631)
- [CVE-2017-15632](#cve-2017-15632)
- [CVE-2017-15633](#cve-2017-15633)
- [CVE-2017-15634](#cve-2017-15634)
- [CVE-2017-15635](#cve-2017-15635)
- [CVE-2017-15636](#cve-2017-15636)
- [CVE-2017-15637](#cve-2017-15637)
- [CVE-2017-16544](#cve-2017-16544)
- [CVE-2017-16584](#cve-2017-16584)
- [CVE-2017-16716](#cve-2017-16716)
- [CVE-2017-16943](#cve-2017-16943)
- [CVE-2017-16944](#cve-2017-16944)
- [CVE-2017-17033](#cve-2017-17033)
- [CVE-2017-17107](#cve-2017-17107)
- [CVE-2017-17215](#cve-2017-17215)
- [CVE-2017-17405](#cve-2017-17405)
- [CVE-2017-17562](#cve-2017-17562)
- [CVE-2017-17692](#cve-2017-17692)
- [CVE-2017-17867](#cve-2017-17867)
- [CVE-2017-1000112](#cve-2017-1000112)
- [CVE-2017-1000117](#cve-2017-1000117)
- [CVE-2017-1000251](#cve-2017-1000251)
- [CVE-2017-1000353](#cve-2017-1000353)
- [CVE-2017-1000364](#cve-2017-1000364)
- [CVE-2017-1000365](#cve-2017-1000365)
- [CVE-2017-1000366](#cve-2017-1000366)
- [CVE-2017-1000367](#cve-2017-1000367)
- [CVE-2017-1000369](#cve-2017-1000369)
- [CVE-2017-1000370](#cve-2017-1000370)
- [CVE-2017-1000371](#cve-2017-1000371)
- [CVE-2017-1000372](#cve-2017-1000372)
- [CVE-2017-1000373](#cve-2017-1000373)
- [CVE-2017-1000374](#cve-2017-1000374)
- [CVE-2017-1000375](#cve-2017-1000375)
- [CVE-2017-1000376](#cve-2017-1000376)
- [CVE-2017-1000377](#cve-2017-1000377)
- [CVE-2017-1000378](#cve-2017-1000378)
- [CVE-2017-1000379](#cve-2017-1000379)
- [CVE-2017-1000405](#cve-2017-1000405)
- [CVE-2018-0101](#cve-2018-0101)
- [CVE-2018-0743](#cve-2018-0743)
- [CVE-2018-0744](#cve-2018-0744)
- [CVE-2018-0758](#cve-2018-0758)
- [CVE-2018-0767](#cve-2018-0767)
- [CVE-2018-0769](#cve-2018-0769)
- [CVE-2018-0774](#cve-2018-0774)
- [CVE-2018-0775](#cve-2018-0775)
- [CVE-2018-0776](#cve-2018-0776)
- [CVE-2018-0777](#cve-2018-0777)
- [CVE-2018-0780](#cve-2018-0780)
- [CVE-2018-0802](#cve-2018-0802)
- [CVE-2018-2694](#cve-2018-2694)
- [CVE-2018-2698](#cve-2018-2698)
- [CVE-2018-5189](#cve-2018-5189)
- [CVE-2018-5318](#cve-2018-5318)
- [CVE-2018-5711](#cve-2018-5711)
- [CVE-2018-6055](#cve-2018-6055)
- [CVE-2018-6317](#cve-2018-6317)
- [CVE-2018-6460](#cve-2018-6460)
- [CVE-2018-1000006](#cve-2018-1000006)

## Resource

### [CVE-2013-6632](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2013-6632.md)

- Integer overflow in Google Chrome before 31.0.1650.57 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via unspecified vectors, as demonstrated during a Mobile Pwn2Own competition at PacSec 2013.

### [CVE-2014-1705](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-1705.md)

- Google V8, as used in Google Chrome before 33.0.1750.152 on OS X and Linux and before 33.0.1750.154 on Windows, allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via unknown vectors.

### [CVE-2014-3176](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-3176.md)

- Google Chrome before 37.0.2062.94 does not properly handle the interaction of extensions, IPC, the sync API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2014-3177.

### [CVE-2014-6332](https://gist.github.com/worawit/84ab41358b8465966224)

- OleAut32.dll in OLE in Microsoft Windows Server 2003 SP2, Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, and Windows RT Gold and 8.1 allows remote attackers to execute arbitrary code via a crafted web site, as demonstrated by an array-redimensioning attempt that triggers improper handling of a size value in the SafeArrayDimen function, aka "Windows OLE Automation Array Remote Code Execution Vulnerability."

### [CVE-2014-7927](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7927.md)

- The SimplifiedLowering::DoLoadBuffer function in compiler/simplified-lowering.cc in Google V8, as used in Google Chrome before 40.0.2214.91, does not properly choose an integer data type, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2014-7928](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2014-7928.md)

- hydrogen.cc in Google V8, as used Google Chrome before 40.0.2214.91, does not properly handle arrays with holes, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code that triggers an array copy.

### [CVE-2015-0235](https://github.com/geekben/cve-collections/blob/master/cve20150235poc.c)

- Heap-based buffer overflow in the __nss_hostname_digits_dots function in glibc 2.2, and other 2.x versions before 2.18, allows context-dependent attackers to execute arbitrary code via vectors related to the (1) gethostbyname or (2) gethostbyname2 function, aka "GHOST".

### [CVE-2015-0240](https://gist.github.com/worawit/051e881fc94fe4a49295)

- The Netlogon server implementation in smbd in Samba 3.5.x and 3.6.x before 3.6.25, 4.0.x before 4.0.25, 4.1.x before 4.1.17, and 4.2.x before 4.2.0rc5 performs a free operation on an uninitialized stack pointer, which allows remote attackers to execute arbitrary code via crafted Netlogon packets that use the ServerPasswordSet RPC API, as demonstrated by packets reaching the _netr_ServerPasswordSet function in rpc_server/netlogon/srv_netlog_nt.c.

### [CVE-2015-1233](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1233.md)

- Google Chrome before 41.0.2272.118 does not properly handle the interaction of IPC, the Gamepad API, and Google V8, which allows remote attackers to execute arbitrary code via unspecified vectors.

### [CVE-2015-1242](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-1242.md)

- The ReduceTransitionElementsKind function in hydrogen-check-elimination.cc in Google V8 before 4.2.77.8, as used in Google Chrome before 42.0.2311.90, allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted JavaScript code that leverages "type confusion" in the check-elimination optimization.

### [CVE-2015-1635](https://gist.github.com/worawit/54f2e5a7a1a028191f76)

- HTTP.sys in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8, Windows 8.1, and Windows Server 2012 Gold and R2 allows remote attackers to execute arbitrary code via crafted HTTP requests, aka "HTTP.sys Remote Code Execution Vulnerability."

### [CVE-2015-1830](https://github.com/ysrc/xunfeng/blob/master/vulscan/vuldb/activemq_upload.py)

- Directory traversal vulnerability in the fileserver upload/download functionality for blob messages in Apache ActiveMQ 5.x before 5.11.2 for Windows allows remote attackers to create JSP files in arbitrary directories via unspecified vectors.

### [CVE-2015-3306](https://www.exploit-db.com/exploits/36803/)

- The mod_copy module in ProFTPD 1.3.5 allows remote attackers to read and write to arbitrary files via the site cpfr and site cpto commands.

### [CVE-2015-5531](https://github.com/nixawk/labs/tree/master/CVE-2015-5531)

- Directory traversal vulnerability in Elasticsearch before 1.6.1 allows remote attackers to read arbitrary files via unspecified vectors related to snapshot API calls.

### [CVE-2015-6086](http://payatu.com/from-crash-to-exploit/)

- Microsoft Internet Explorer 9 through 11 allows remote attackers to obtain sensitive information from process memory via a crafted web site, aka "Internet Explorer Information Disclosure Vulnerability."

### [CVE-2015-6764](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6764.md)

- The BasicJsonStringifier::SerializeJSArray function in json-stringifier.h in the JSON stringifier in Google V8, as used in Google Chrome before 47.0.2526.73, improperly loads array elements, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-6771](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-6771.md)

- js/array.js in Google V8, as used in Google Chrome before 47.0.2526.73, improperly implements certain map and filter operations for arrays, which allows remote attackers to cause a denial of service (out-of-bounds memory access) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2015-7450](https://cxsecurity.com/issue/WLB-2017030142)

- Serialized-object interfaces in certain IBM analytics, business solutions, cognitive, IT infrastructure, and mobile and social products allow remote attackers to execute arbitrary commands via a crafted serialized Java object, related to the InvokerTransformer class in the Apache Commons Collections library.

### [CVE-2015-7501](https://github.com/joaomatosf/JavaDeserH2HC)

- Red Hat JBoss A-MQ 6.x; BPM Suite (BPMS) 6.x; BRMS 6.x and 5.x; Data Grid (JDG) 6.x; Data Virtualization (JDV) 6.x and 5.x; Enterprise Application Platform 6.x, 5.x, and 4.3.x; Fuse 6.x; Fuse Service Works (FSW) 6.x; Operations Network (JBoss ON) 3.x; Portal 6.x; SOA Platform (SOA-P) 5.x; Web Server (JWS) 3.x; Red Hat OpenShift/xPAAS 3.x; and Red Hat Subscription Asset Manager 1.3 allow remote attackers to execute arbitrary commands via a crafted serialized Java object, related to the Apache Commons Collections (ACC) library.

### [CVE-2015-7545](https://hackmd.io/s/SkKL68GIe#🍊-web-300-git)

- The (1) git-remote-ext and (2) unspecified other remote helper programs in Git before 2.3.10, 2.4.x before 2.4.10, 2.5.x before 2.5.4, and 2.6.x before 2.6.1 do not properly restrict the allowed protocols, which might allow remote attackers to execute arbitrary code via a URL in a (a) .gitmodules file or (b) unknown other sources in a submodule.

### [CVE-2015-8584](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2015-8548.md)

- JSON, OOB.

### [CVE-2016-0040](https://github.com/de7ec7ed/CVE-2016-0040)

- The kernel in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, and Windows 7 SP1 allows local users to gain privileges via a crafted application, aka "Windows Elevation of Privilege Vulnerability."

### [CVE-2016-0450](https://redr2e.com/cve-to-poc-cve-2016-0450/)

- Unspecified vulnerability in the Oracle GoldenGate component in Oracle GoldenGate 11.2 and 12.1.2 allows remote attackers to affect availability via unknown vectors.

### [CVE-2016-0451](https://redr2e.com/cve-to-poc-cve-2016-0451/)

- Unspecified vulnerability in the Oracle GoldenGate component in Oracle GoldenGate 11.2 and 12.1.2 allows remote attackers to affect confidentiality, integrity, and availability via unknown vectors, a different vulnerability than CVE-2016-0452.

### [CVE-2016-0728](https://github.com/geekben/cve-collections/blob/master/cve20160728poc.c)

- The join_session_keyring function in security/keys/process_keys.c in the Linux kernel before 4.4.1 mishandles object references in a certain error case, which allows local users to gain privileges or cause a denial of service (integer overflow and use-after-free) via crafted keyctl commands.

### [CVE-2016-0792](https://github.com/jpiechowka/jenkins-cve-2016-0792)

- Multiple unspecified API endpoints in Jenkins before 1.650 and LTS before 1.642.2 allow remote authenticated users to execute arbitrary code via serialized data in an XML file, related to XStream and groovy.util.Expando.

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

### [CVE-2016-1910](https://github.com/vah13/SAP_exploit)

- The User Management Engine (UME) in SAP NetWeaver 7.4 allows attackers to decrypt unspecified data via unknown vectors, aka SAP Security Note 2191290.

### [CVE-2016-2384](https://github.com/xairy/kernel-exploits/tree/master/CVE-2016-2384)

- Double free vulnerability in the snd_usbmidi_create function in sound/usb/midi.c in the Linux kernel before 4.5 allows physically proximate attackers to cause a denial of service (panic) or possibly have unspecified other impact via vectors involving an invalid USB descriptor.

### [CVE-2016-2386](https://github.com/vah13/SAP_exploit)

- SQL injection vulnerability in the UDDI server in SAP NetWeaver J2EE Engine 7.40 allows remote attackers to execute arbitrary SQL commands via unspecified vectors, aka SAP Security Note 2101079.

### [CVE-2016-2388](https://github.com/vah13/SAP_exploit)

- The Universal Worklist Configuration in SAP NetWeaver 7.4 allows remote attackers to obtain sensitive user information via a crafted HTTP request, aka SAP Security Note 2256846.

### [CVE-2016-3087](https://github.com/nixawk/labs/tree/master/CVE-2016-3087)

- Apache Struts 2.3.20.x before 2.3.20.3, 2.3.24.x before 2.3.24.3, and 2.3.28.x before 2.3.28.1, when Dynamic Method Invocation is enabled, allow remote attackers to execute arbitrary code via vectors related to an ! (exclamation mark) operator to the REST Plugin.

### [CVE-2016-3088](https://github.com/coffeehb/Some-PoC-oR-ExP/tree/master/ActiveMQExP)

- The Fileserver web application in Apache ActiveMQ 5.x before 5.14.0 allows remote attackers to upload and execute arbitrary files via an HTTP PUT followed by an HTTP MOVE request.

### [CVE-2016-3309](https://siberas.de/blog/2017/10/05/exploitation_case_study_wild_pool_overflow_CVE-2016-3309_reloaded.html)

- The kernel-mode drivers in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability," a different vulnerability than CVE-2016-3308, CVE-2016-3310, and CVE-2016-3311.

### [CVE-2016-3371](https://github.com/WindowsExploits/Exploits/tree/master/CVE-2016-3371)

- The kernel API in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, and Windows 10 Gold, 1511, and 1607 does not properly enforce permissions, which allows local users to obtain sensitive information via a crafted application, aka "Windows Kernel Elevation of Privilege Vulnerability."

### [CVE-2016-3386](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2016-3386.md)

- The Chakra JavaScript engine in Microsoft Edge allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, aka "Scripting Engine Memory Corruption Vulnerability," a different vulnerability than CVE-2016-3389, CVE-2016-7190, and CVE-2016-7194.

### [CVE-2016-4338](https://github.com/nixawk/labs/tree/master/CVE-2016-4338)

- The mysql user parameter configuration script (userparameter_mysql.conf) in the agent in Zabbix before 2.0.18, 2.2.x before 2.2.13, and 3.0.x before 3.0.3, when used with a shell other than bash, allows context-dependent attackers to execute arbitrary code or SQL commands via the mysql.size parameter.

### [CVE-2016-4622](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4622.md)

- WebKit in Apple iOS before 9.3.3, Safari before 9.1.2, and tvOS before 9.2.2 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4589, CVE-2016-4623, and CVE-2016-4624.

### [CVE-2016-4734](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2016-4734.md)

- WebKit in Apple iOS before 10, Safari before 10, and tvOS before 10 allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted web site, a different vulnerability than CVE-2016-4611, CVE-2016-4730, CVE-2016-4733, and CVE-2016-4735.

### [CVE-2016-4971](https://github.com/KINGSABRI/CVE-in-Ruby/tree/master/CVE-2016-4971)

- GNU wget before 1.18 allows remote servers to write to arbitrary files by redirecting a request from HTTP to a crafted FTP resource.

### [CVE-2016-5129](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5129.md)

- Google V8 before 5.2.361.32, as used in Google Chrome before 52.0.2743.82, does not properly process left-trimmed objects, which allows remote attackers to cause a denial of service (memory corruption) or possibly have unspecified other impact via crafted JavaScript code.

### [CVE-2016-5172](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5172.md)

- The parser in Google V8, as used in Google Chrome before 53.0.2785.113, mishandles scopes, which allows remote attackers to obtain sensitive information from arbitrary memory locations via crafted JavaScript code.

### [CVE-2016-5195](https://github.com/nixawk/labs/tree/master/CVE-2016-5195)

- Race condition in mm/gup.c in the Linux kernel 2.x through 4.x before 4.8.3 allows local users to gain privileges by leveraging incorrect handling of a copy-on-write (COW) feature to write to a read-only memory mapping, as exploited in the wild in October 2016, aka "Dirty COW."

### [CVE-2016-5198](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5198.md)

- V8 in Google Chrome prior to 54.0.2840.90 for Linux, and 54.0.2840.85 for Android, and 54.0.2840.87 for Windows and Mac included incorrect optimisation assumptions, which allowed a remote attacker to perform arbitrary read/write operations, leading to code execution, via a crafted HTML page.

### [CVE-2016-5200](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2016-5200.md)

- V8 in Google Chrome prior to 54.0.2840.98 for Mac, and 54.0.2840.99 for Windows, and 54.0.2840.100 for Linux, and 55.0.2883.84 for Android incorrectly applied type rules, which allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page.

### [CVE-2016-5346](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-5346)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2016-5734](https://github.com/coffeehb/Some-PoC-oR-ExP/blob/master/PhpMyAdmin/phpmyadmin4.6.2_RCE.py)

- phpMyAdmin 4.0.x before 4.0.10.16, 4.4.x before 4.4.15.7, and 4.6.x before 4.6.3 does not properly choose delimiters to prevent use of the preg_replace e (aka eval) modifier, which might allow remote attackers to execute arbitrary PHP code via a crafted string, as demonstrated by the table search-and-replace implementation.

### [CVE-2016-6210](https://github.com/KINGSABRI/CVE-in-Ruby/tree/master/CVE-2016-6210)

- sshd in OpenSSH before 7.3, when SHA256 or SHA512 are used for user password hashing, uses BLOWFISH hashing on a static password when the username does not exist, which allows remote attackers to enumerate users by leveraging the timing difference between responses when a large password is provided.

### [CVE-2016-6277](https://github.com/nixawk/labs/tree/master/CVE-2016-6277)

- NETGEAR R6250 before 1.0.4.6.Beta, R6400 before 1.0.1.18.Beta, R6700 before 1.0.1.14.Beta, R6900, R7000 before 1.0.7.6.Beta, R7100LG before 1.0.0.28.Beta, R7300DST before 1.0.0.46.Beta, R7900 before 1.0.1.8.Beta, R8000 before 1.0.3.26.Beta, D6220, D6400, D7000, and possibly other routers allow remote attackers to execute arbitrary commands via shell metacharacters in the path info to cgi-bin/.

### [CVE-2016-6415](https://github.com/nixawk/labs/tree/master/CVE-2016-6415)

- The server IKEv1 implementation in Cisco IOS 12.2 through 12.4 and 15.0 through 15.6, IOS XE through 3.18S, IOS XR 4.3.x and 5.0.x through 5.2.x, and PIX before 7.0 allows remote attackers to obtain sensitive information from device memory via a Security Association (SA) negotiation request, aka Bug IDs CSCvb29204 and CSCvb36055 or BENIGNCERTAIN.

### [CVE-2016-6662](https://github.com/MaYaSeVeN/CVE-2016-6662)

- Oracle MySQL through 5.5.52, 5.6.x through 5.6.33, and 5.7.x through 5.7.15; MariaDB before 5.5.51, 10.0.x before 10.0.27, and 10.1.x before 10.1.17; and Percona Server before 5.5.51-38.1, 5.6.x before 5.6.32-78.0, and 5.7.x before 5.7.14-7 allow local users to create arbitrary configurations and bypass certain protection mechanisms by setting general_log_file to a my.cnf configuration. NOTE: this can be leveraged to execute arbitrary code with root privileges by setting malloc_lib. NOTE: the affected MySQL version information is from Oracle's October 2016 CPU. Oracle has not commented on third-party claims that the issue was silently patched in MySQL 5.5.52, 5.6.33, and 5.7.15.

### [CVE-2016-6700](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6700)

- An elevation of privilege vulnerability in libzipfile in Android 4.x before 4.4.4, 5.0.x before 5.0.2, and 5.1.x before 5.1.1 could enable a local malicious application to execute arbitrary code within the context of a privileged process. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Android ID: A-30916186.

### [CVE-2016-6702](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6702)

- A remote code execution vulnerability in libjpeg in Android 4.x before 4.4.4, 5.0.x before 5.0.2, and 5.1.x before 5.1.1 could enable an attacker using a specially crafted file to execute arbitrary code in the context of an unprivileged process. This issue is rated as High due to the possibility of remote code execution in an application that uses libjpeg. Android ID: A-30259087.

### [CVE-2016-6762](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2016-6762)

- An elevation of privilege vulnerability in the libziparchive library could enable a local malicious application to execute arbitrary code within the context of a privileged process. This issue is rated as High because it could be used to gain local access to elevated capabilities, which are not normally accessible to a third-party application. Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0. Android ID: A-31251826.

### [CVE-2016-6787](https://hardenedlinux.github.io/system-security/2017/10/16/Exploiting-on-CVE-2016-6787.html)

- kernel/events/core.c in the performance subsystem in the Linux kernel before 4.0 mismanages locks during certain migrations, which allows local users to gain privileges via a crafted application, aka Android internal bug 31095224.

### [CVE-2016-7124](http://0x48.pw/2016/09/13/0x22/)

- ext/standard/var_unserializer.c in PHP before 5.6.25 and 7.x before 7.0.10 mishandles certain invalid objects, which allows remote attackers to cause a denial of service or possibly have unspecified other impact via crafted serialized data that leads to a (1) __destruct call or (2) magic method call.

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

### [CVE-2016-7255](https://github.com/mwrlabs/CVE-2016-7255)

- The kernel-mode drivers in Microsoft Windows Vista SP2, Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, and 1607, and Windows Server 2016 allow local users to gain privileges via a crafted application, aka "Win32k Elevation of Privilege Vulnerability."

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

### [CVE-2016-9651](https://github.com/secmob/pwnfest2016/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2016-9793](https://github.com/xairy/kernel-exploits/tree/master/CVE-2016-9793)

- The sock_setsockopt function in net/core/sock.c in the Linux kernel before 4.8.14 mishandles negative values of sk_sndbuf and sk_rcvbuf, which allows local users to cause a denial of service (memory corruption and system crash) or possibly have unspecified other impact by leveraging the CAP_NET_ADMIN capability for a crafted setsockopt system call with the (1) SO_SNDBUFFORCE or (2) SO_RCVBUFFORCE option.

### [CVE-2016-10033](https://exploitbox.io/vuln/WordPress-Exploit-4-6-RCE-CODE-EXEC-CVE-2016-10033.html)

- The mailSend function in the isMail transport in PHPMailer before 5.2.18 might allow remote attackers to pass extra parameters to the mail command and consequently execute arbitrary code via a \" (backslash double quote) in a crafted Sender property.

### [CVE-2016-10191](https://www.secfree.com/article-396.html)

- Heap-based buffer overflow in libavformat/rtmppkt.c in FFmpeg before 2.8.10, 3.0.x before 3.0.5, 3.1.x before 3.1.6, and 3.2.x before 3.2.2 allows remote attackers to execute arbitrary code by leveraging failure to check for RTMP packet size mismatches.

### [CVE-2016-10277](https://alephsecurity.com/2017/05/23/nexus6-initroot/)

- An elevation of privilege vulnerability in the Motorola bootloader could enable a local malicious application to execute arbitrary code within the context of the bootloader. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-33840490.

### [CVE-2016-10370](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus devices such as the 3T. The OnePlus OTA Updater pushes the signed-OTA image over HTTP without TLS. While it does not allow for installation of arbitrary OTAs (due to the digital signature), it unnecessarily increases the attack surface, and allows for remote exploitation of other vulnerabilities such as CVE-2017-5948, CVE-2017-8850, and CVE-2017-8851.

### [CVE-2017-0015](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0015.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0037](https://redr2e.com/cve-to-poc-cve-2017-0037/)

- Microsoft Internet Explorer 10 and 11 and Microsoft Edge have a type confusion issue in the Layout::MultiColumnBoxBuilder::HandleColumnBreakOnColumnSpanningElement function in mshtml.dll, which allows remote attackers to execute arbitrary code via vectors involving a crafted Cascading Style Sheets (CSS) token sequence and crafted JavaScript code that operates on a TH element.

### [CVE-2017-0059](https://redr2e.com/cve-to-poc-cve-2017-0059/)

- Microsoft Internet Explorer 9 through 11 allow remote attackers to obtain sensitive information from process memory via a crafted web site, aka "Internet Explorer Information Disclosure Vulnerability." This vulnerability is different from those described in CVE-2017-0008 and CVE-2017-0009.

### [CVE-2017-0070](CVE-2017-0070.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0071](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0071.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0134](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0134.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0141, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0141](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-0141.md)

- A remote code execution vulnerability exists in the way affected Microsoft scripting engines render when handling objects in memory in Microsoft browsers. These vulnerabilities could corrupt memory in such a way that an attacker could execute arbitrary code in the context of the current user. An attacker who successfully exploited the vulnerability could gain the same user rights as the current user. If the current user is logged on with administrative user rights, an attacker who successfully exploited the vulnerability could take control of an affected system. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights. This vulnerability is different from those described in CVE-2017-0010, CVE-2017-0015, CVE-2017-0032, CVE-2017-0035, CVE-2017-0067, CVE-2017-0070, CVE-2017-0071, CVE-2017-0094, CVE-2017-0131, CVE-2017-0132, CVE-2017-0133, CVE-2017-0134, CVE-2017-0136, CVE-2017-0137, CVE-2017-0138, CVE-2017-0150, and CVE-2017-0151.

### [CVE-2017-0143](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0144, CVE-2017-0145, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0144](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0145, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0145](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0146, and CVE-2017-0148.

### [CVE-2017-0146](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0145, and CVE-2017-0148.

### [CVE-2017-0147](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to obtain sensitive information from process memory via a crafted packets, aka "Windows SMB Information Disclosure Vulnerability."

### [CVE-2017-0148](MS17-010.md)

- The SMBv1 server in Microsoft Windows Vista SP2; Windows Server 2008 SP2 and R2 SP1; Windows 7 SP1; Windows 8.1; Windows Server 2012 Gold and R2; Windows RT 8.1; and Windows 10 Gold, 1511, and 1607; and Windows Server 2016 allows remote attackers to execute arbitrary code via crafted packets, aka "Windows SMB Remote Code Execution Vulnerability." This vulnerability is different from those described in CVE-2017-0143, CVE-2017-0144, CVE-2017-0145, and CVE-2017-0146.

### [CVE-2017-0199](CVE-2017-0199.md)

- Microsoft Office 2007 SP3, Microsoft Office 2010 SP2, Microsoft Office 2013 SP1, Microsoft Office 2016, Microsoft Windows Vista SP2, Windows Server 2008 SP2, Windows 7 SP1, Windows 8.1 allow remote attackers to execute arbitrary code via a crafted document, aka "Microsoft Office/WordPad Remote Code Execution Vulnerability w/Windows API."

### [CVE-2017-0213](https://github.com/WindowsExploits/Exploits/tree/master/CVE-2017-0213)

- Windows COM Aggregate Marshaler in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an elevation privilege vulnerability when an attacker runs a specially crafted application, aka "Windows COM Elevation of Privilege Vulnerability". This CVE ID is unique from CVE-2017-0214.

### [CVE-2017-0283](https://0patch.blogspot.tw/2017/07/0patching-quick-brown-fox-of-cve-2017.html)

- Uniscribe in Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, Windows Server 2016, Microsoft Office 2007 SP3, Microsoft Office 2010 SP2, Microsoft Office Word Viewer, Microsoft Lync 2013 SP1, Skype for Business 2016, Microsoft Silverlight 5 Developer Runtime when installed on Microsoft Windows, and Microsoft Silverlight 5 when installed on Microsoft Windows allows a remote code execution vulnerability due to the way it handles objects in memory, aka "Windows Uniscribe Remote Code Execution Vulnerability". This CVE ID is unique from CVE-2017-8528.

### [CVE-2017-0290](CVE-2017-0290.md)

- NScript in mpengine in Microsoft Malware Protection Engine with Engine Version before 1.1.13704.0, as used in Windows Defender and other products, allows remote attackers to execute arbitrary code or cause a denial of service (type confusion and application crash) via crafted JavaScript code within any file scanned by this engine.

### [CVE-2017-0392](https://github.com/derrekr/android_security/blob/master/CVE-2017-0392)

- A denial of service vulnerability in VBRISeeker.cpp in libstagefright in Mediaserver could enable a remote attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High due to the possibility of remote denial of service. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1. Android ID: A-32577290.

### [CVE-2017-0475](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0475)

- An elevation of privilege vulnerability in the recovery verifier could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as Critical due to the possibility of a local permanent device compromise, which may require reflashing the operating system to repair the device. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1. Android ID: A-31914369.

### [CVE-2017-0497](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0497)

- A denial of service vulnerability in Mediaserver could enable an attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as Moderate because it requires an uncommon device configuration. Product: Android. Versions: 7.0, 7.1.1. Android ID: A-33300701.

### [CVE-2017-0521](https://github.com/derrekr/android_security/tree/master/CVE-2017-0521)

- An elevation of privilege vulnerability in the Qualcomm camera driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32919951. References: QC-CR#1097709.

### [CVE-2017-0531](https://github.com/derrekr/android_security/blob/master/CVE-2017-0531/msm_lsm_client_lab_main.c)

- An information disclosure vulnerability in the Qualcomm Wi-Fi driver could enable a local malicious application to access data outside of its permission levels. This issue is rated as Moderate because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-32877245. References: QC-CR#1087469.

### [CVE-2017-0541](https://github.com/JiounDai/CVE-2017-0541)

- A remote code execution vulnerability in sonivox in Mediaserver could enable an attacker using a specially crafted file to cause memory corruption during media file and data processing. This issue is rated as Critical due to the possibility of remote code execution within the context of the Mediaserver process. Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1. Android ID: A-34031018.

### [CVE-2017-0548](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0548)

- A remote denial of service vulnerability in libskia could enable an attacker to use a specially crafted file to cause a device hang or reboot. This issue is rated as High severity due to the possibility of remote denial of service. Product: Android. Versions: 7.0, 7.1.1. Android ID: A-33251605.

### [CVE-2017-0576](https://github.com/derrekr/android_security/blob/master/CVE-2017-0576/qcom_qcedev_byteoffset_overflow.c)

- An elevation of privilege vulnerability in the Qualcomm crypto engine driver could enable a local malicious application to execute arbitrary code within the context of the kernel. This issue is rated as High because it first requires compromising a privileged process. Product: Android. Versions: Kernel-3.10, Kernel-3.18. Android ID: A-33544431. References: QC-CR#1103089.

### [CVE-2017-0678](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0678)

- A remote code execution vulnerability in the Android media framework. Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-36576151.

### [CVE-2017-0714](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0714)

- A remote code execution vulnerability in the Android media framework (h263 decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-36492637.

### [CVE-2017-0718](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0718)

- A remote code execution vulnerability in the Android media framework (mpeg2 decoder). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37273547.

### [CVE-2017-0719](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0719)

- A remote code execution vulnerability in the Android media framework (mpeg2 decoder). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37273673.

### [CVE-2017-0720](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0720)

- A remote code execution vulnerability in the Android media framework (libhevc). Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37430213.

### [CVE-2017-0722](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0722)

- A remote code execution vulnerability in the Android media framework (h263 decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37660827.

### [CVE-2017-0745](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0745)

- A remote code execution vulnerability in the Android media framework (avc decoder). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37079296.

### [CVE-2017-0758](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0758)

- A remote code execution vulnerability in the Android media framework (libhevc). Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-36492741.

### [CVE-2017-0760](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0760)

- A remote code execution vulnerability in the Android media framework (libstagefright). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-37237396.

### [CVE-2017-0761](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0761)

- A remote code execution vulnerability in the Android media framework (libavc). Product: Android. Versions: 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-38448381.

### [CVE-2017-0764](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0764)

- A remote code execution vulnerability in the Android media framework (libvorbis). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62872015.

### [CVE-2017-0776](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0776)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-38496660.

### [CVE-2017-0777](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0777)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-38342499.

### [CVE-2017-0778](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0778)

- A information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-62133227.

### [CVE-2017-0781](CVE-2017-0781.md)

- A remote code execution vulnerability in the Android system (bluetooth). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-63146105.

### [CVE-2017-0785](https://github.com/ojasookert/CVE-2017-0785)

- A information disclosure vulnerability in the Android system (bluetooth). Product: Android. Versions: 4.4.4, 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-63146698.

### [CVE-2017-0813](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0813)

- A denial of service vulnerability in the Android media framework (libstagefright). Product: Android. Versions: 7.0, 7.1.1, 7.1.2. Android ID: A-36531046.

### [CVE-2017-0814](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0814)

- An information disclosure vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62800140.

### [CVE-2017-0820](https://github.com/ele7enxxh/poc-exp/tree/master/CVE-2017-0820)

- A vulnerability in the Android media framework (n/a). Product: Android. Versions: 7.0, 7.1.1, 7.1.2, 8.0. Android ID: A-62187433.

### [CVE-2017-1082](Stack-Clash.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-1083](Stack-Clash.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-1084](Stack-Clash.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-1085](Stack-Clash.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-2416](https://blog.flanker017.me/cve-2017-2416-gif-remote-exec/)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. macOS before 10.12.4 is affected. tvOS before 10.2 is affected. watchOS before 3.2 is affected. The issue involves the "ImageIO" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted image file.

### [CVE-2017-2419](http://blog.talosintelligence.com/2017/09/vulnerability-spotlight-content.html)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to bypass a Content Security Policy protection mechanism via unspecified vectors.

### [CVE-2017-2446](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2446.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code via a crafted web site that leverages the mishandling of strict mode functions.

### [CVE-2017-2447](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2447.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to obtain sensitive information or cause a denial of service (memory corruption) via a crafted web site.

### [CVE-2017-2464](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2464.md)

- An issue was discovered in certain Apple products. iOS before 10.3 is affected. Safari before 10.1 is affected. tvOS before 10.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2491](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2491.md)

- Use after free vulnerability in the String.replace method JavaScriptCore in Apple Safari in iOS before 10.3 allows remote attackers to execute arbitrary code via a crafted web page, or a crafted file.

### [CVE-2017-2521](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2521.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. watchOS before 3.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2531](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2531.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2536](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2536.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2547](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-2547.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-2636](https://a13xp0p0v.github.io/2017/03/24/CVE-2017-2636.html)

- Race condition in drivers/tty/n_hdlc.c in the Linux kernel through 4.10.1 allows local users to gain privileges or cause a denial of service (double free) by setting the HDLC line discipline.

### [CVE-2017-2641](http://netanelrub.in/2017/03/20/moodle-remote-code-execution/)

- In Moodle 2.x and 3.x, SQL injection can occur via user preferences.

### [CVE-2017-3506](https://www.anquanke.com/post/id/92003)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: Web Services). Supported versions that are affected are 10.3.6.0, 12.1.3.0, 12.2.1.0, 12.2.1.1 and 12.2.1.2. Difficult to exploit vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in unauthorized creation, deletion or modification access to critical data or all Oracle WebLogic Server accessible data as well as unauthorized access to critical data or complete access to all Oracle WebLogic Server accessible data. CVSS 3.0 Base Score 7.4 (Confidentiality and Integrity impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:N).

### [CVE-2017-3599](https://github.com/SECFORCE/CVE-2017-3599/blob/master/cve-2017-3599_poc.py)

- Vulnerability in the MySQL Server component of Oracle MySQL (subcomponent: Server: Pluggable Auth). Supported versions that are affected are 5.6.35 and earlier and 5.7.17 and earlier. Easily "exploitable" vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise MySQL Server. Successful attacks of this vulnerability can result in unauthorized ability to cause a hang or frequently repeatable crash (complete DOS) of MySQL Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H). NOTE: the previous information is from the April 2017 CPU. Oracle has not commented on third-party claims that this issue is an integer overflow in sql/auth/sql_authentication.cc which allows remote attackers to cause a denial of service via a crafted authentication packet.

### [CVE-2017-3629](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). Supported versions that are affected are 10 and 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in takeover of Solaris. CVSS 3.0 Base Score 7.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H).

### [CVE-2017-3630](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). Supported versions that are affected are 10 and 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in unauthorized update, insert or delete access to some of Solaris accessible data as well as unauthorized read access to a subset of Solaris accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of Solaris. CVSS 3.0 Base Score 5.3 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L).

### [CVE-2017-3631](Stack-Clash.md)

- Vulnerability in the Solaris component of Oracle Sun Systems Products Suite (subcomponent: Kernel). The supported version that is affected is 11. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Solaris executes to compromise Solaris. Successful attacks of this vulnerability can result in unauthorized update, insert or delete access to some of Solaris accessible data as well as unauthorized read access to a subset of Solaris accessible data and unauthorized ability to cause a partial denial of service (partial DOS) of Solaris. CVSS 3.0 Base Score 5.3 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:U/C:L/I:L/A:L).

### [CVE-2017-3881](https://github.com/artkond/cisco-rce)

- A vulnerability in the Cisco Cluster Management Protocol (CMP) processing code in Cisco IOS and Cisco IOS XE Software could allow an unauthenticated, remote attacker to cause a reload of an affected device or remotely execute code with elevated privileges. The Cluster Management Protocol utilizes Telnet internally as a signaling and command protocol between cluster members. The vulnerability is due to the combination of two factors: (1) the failure to restrict the use of CMP-specific Telnet options only to internal, local communications between cluster members and instead accept and process such options over any Telnet connection to an affected device; and (2) the incorrect processing of malformed CMP-specific Telnet options. An attacker could exploit this vulnerability by sending malformed CMP-specific Telnet options while establishing a Telnet session with an affected Cisco device configured to accept Telnet connections. An exploit could allow an attacker to execute arbitrary code and obtain full control of the device or cause a reload of the affected device. This affects Catalyst switches, Embedded Service 2020 switches, Enhanced Layer 2 EtherSwitch Service Module, Enhanced Layer 2/3 EtherSwitch Service Module, Gigabit Ethernet Switch Module (CGESM) for HP, IE Industrial Ethernet switches, ME 4924-10GE switch, RF Gateway 10, and SM-X Layer 2/3 EtherSwitch Service Module. Cisco Bug IDs: CSCvd48893.

### [CVE-2017-4901](https://github.com/unamer/vmware_escape)

- The drag-and-drop (DnD) function in VMware Workstation 12.x before version 12.5.4 and Fusion 8.x before version 8.5.5 has an out-of-bounds memory access vulnerability. This may allow a guest to execute code on the operating system that runs Workstation or Fusion.

### [CVE-2017-4914](https://www.exploit-db.com/exploits/42152/)

- VMware vSphere Data Protection (VDP) 6.1.x, 6.0.x, 5.8.x, and 5.5.x contains a deserialization issue. Exploitation of this issue may allow a remote attacker to execute commands on the appliance.

### [CVE-2017-4915](https://www.exploit-db.com/exploits/43449/)

- VMware Workstation Pro/Player contains an insecure library loading vulnerability via ALSA sound driver configuration files. Successful exploitation of this issue may allow unprivileged host users to escalate their privileges to root in a Linux host machine.

### [CVE-2017-4918](https://bogner.sh/2017/07/cve-2017-4918-code-injection-in-vmware-horizons-macos-client/)

- VMware Horizon View Client (2.x, 3.x and 4.x prior to 4.5.0) contains a command injection vulnerability in the service startup script. Successful exploitation of this issue may allow unprivileged users to escalate their privileges to root on the Mac OSX system where the client is installed.

### [CVE-2017-4933](https://www.talosintelligence.com/reports/TALOS-2017-0368)

- VMware ESXi (6.5 before ESXi650-201710401-BG), Workstation (12.x before 12.5.8), and Fusion (8.x before 8.5.9) contain a vulnerability that could allow an authenticated VNC session to cause a heap overflow via a specific set of VNC packets resulting in heap corruption. Successful exploitation of this issue could result in remote code execution in a virtual machine via the authenticated VNC session. Note: In order for exploitation to be possible in ESXi, VNC must be manually enabled in a virtual machine's .vmx configuration file. In addition, ESXi must be configured to allow VNC traffic through the built-in firewall.

### [CVE-2017-4946](https://gosecure.net/2018/01/10/vmware-horizon-v4h-v4pa-desktop-agent-privilege-escalation-vulnerability-cve-2017-4946/)

- The VMware V4H and V4PA desktop agents (6.x before 6.5.1) contain a privilege escalation vulnerability. Successful exploitation of this issue could result in a low privileged windows user escalating their privileges to SYSTEM.

### [CVE-2017-4971](http://bobao.360.cn/learning/detail/3963.html)

- An issue was discovered in Pivotal Spring Web Flow through 2.4.4. Applications that do not change the value of the MvcViewFactoryCreator useSpringBinding property which is disabled by default (i.e., set to 'false') can be vulnerable to malicious EL expressions in view states that process form submissions but do not have a sub-element to declare explicit data binding property mappings.

### [CVE-2017-5030](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5030.md)

- Incorrect handling of complex species in V8 in Google Chrome prior to 57.0.2987.98 for Linux, Windows, and Mac and 57.0.2987.108 for Android allowed a remote attacker to execute arbitrary code via a crafted HTML page.

### [CVE-2017-5033](http://blog.talosintelligence.com/2017/09/vulnerability-spotlight-content.html)

- Blink in Google Chrome prior to 57.0.2987.98 for Mac, Windows, and Linux and 57.0.2987.108 for Android failed to correctly propagate CSP restrictions to local scheme pages, which allowed a remote attacker to bypass content security policy via a crafted HTML page.

### [CVE-2017-5040](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5040.md)

- V8 in Google Chrome prior to 57.0.2987.98 for Mac, Windows, and Linux and 57.0.2987.108 for Android was missing a neutering check, which allowed a remote attacker to read values in memory via a crafted HTML page.

### [CVE-2017-5053](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5053.md)

- An out-of-bounds read in V8 in Google Chrome prior to 57.0.2987.133 for Linux, Windows, and Mac, and 57.0.2987.132 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page, related to Array.prototype.indexOf.

### [CVE-2017-5070](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5070.md)

- Type confusion in V8 in Google Chrome prior to 59.0.3071.86 for Linux, Windows, and Mac, and 59.0.3071.92 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-5071](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5071.md)

- Insufficient validation of untrusted input in V8 in Google Chrome prior to 59.0.3071.86 for Linux, Windows and Mac, and 59.0.3071.92 for Android allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-5088](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5088.md)

- Insufficient validation of untrusted input in V8 in Google Chrome prior to 59.0.3071.104 for Mac, Windows, and Linux, and 59.0.3071.117 for Android, allowed a remote attacker to perform out of bounds memory access via a crafted HTML page.

### [CVE-2017-5098](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5098.md)

- A use after free in V8 in Google Chrome prior to 60.0.3112.78 for Mac, Windows, Linux, and Android allowed a remote attacker to perform an out of bounds memory read via a crafted HTML page.

### [CVE-2017-5115](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5115.md)

- Type confusion in V8 in Google Chrome prior to 61.0.3163.79 for Windows allowed a remote attacker to potentially exploit object corruption via a crafted HTML page.

### [CVE-2017-5116](CVE-2017-5116.md)

- Type confusion in V8 in Google Chrome prior to 61.0.3163.79 for Mac, Windows, and Linux, and 61.0.3163.81 for Android, allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page.

### [CVE-2017-5121](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5121.md)

- Inappropriate use of JIT optimisation in V8 in Google Chrome prior to 61.0.3163.100 for Linux, Windows, and Mac allowed a remote attacker to execute arbitrary code inside a sandbox via a crafted HTML page, related to the escape analysis phase.

### [CVE-2017-5122](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-5122.md)

- Inappropriate use of table size handling in V8 in Google Chrome prior to 61.0.3163.100 for Windows allowed a remote attacker to trigger out-of-bounds access via a crafted HTML page.

### [CVE-2017-5123](CVE-2017-5123.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5124](https://github.com/Bo0oM/CVE-2017-5124/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5126](https://bugs.chromium.org/p/chromium/issues/detail?id=760455)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5127](https://bugs.chromium.org/p/chromium/issues/detail?id=765384)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5128](https://bugs.chromium.org/p/chromium/issues/detail?id=765469)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5129](https://bugs.chromium.org/p/chromium/issues/detail?id=765495)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5133](https://bugs.chromium.org/p/chromium/issues/detail?id=762106)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-5135](https://stringbleed.github.io/)

- Certain Technicolor devices have an SNMP access-control bypass, possibly involving an ISP customization in some cases. The Technicolor (formerly Cisco) DPC3928SL with firmware D3928SL-P15-13-A386-c3420r55105-160127a could be reached by any SNMP community string from the Internet; also, you can write in the MIB because it provides write properties, aka Stringbleed. NOTE: the string-bleed/StringBleed-CVE-2017-5135 GitHub repository is not a valid reference as of 2017-04-27; it contains Trojan horse code purported to exploit this vulnerability.

### [CVE-2017-5622](https://alephsecurity.com/2017/03/26/oneplus3t-adb-charger/)

- With OxygenOS before 4.0.3, when a charger is connected to a powered-off OnePlus 3 or 3T device, the platform starts with adbd enabled. Therefore, a malicious charger or a physical attacker can open up, without authorization, an ADB session with the device, in order to further exploit other vulnerabilities and/or exfiltrate sensitive information.

### [CVE-2017-5624](https://alephsecurity.com/2017/02/08/oneplus3-bootloader-vulns/)

- An issue was discovered in OxygenOS before 4.0.3 for OnePlus 3 and 3T. The attacker can persistently make the (locked) bootloader start the platform with dm-verity disabled, by issuing the 'fastboot oem disable_dm_verity' command. Having dm-verity disabled, the kernel will not verify the system partition (and any other dm-verity protected partition), which may allow for persistent code execution and privilege escalation.

### [CVE-2017-5626](https://alephsecurity.com/2017/02/08/oneplus3-bootloader-vulns/)

- OxygenOS before version 4.0.2, on OnePlus 3 and 3T, has two hidden fastboot oem commands (4F500301 and 4F500302) that allow the attacker to lock/unlock the bootloader, disregarding the 'OEM Unlocking' checkbox, without user confirmation and without a factory reset. This allows for persistent code execution with high privileges (kernel/root) with complete access to user data.

### [CVE-2017-5638](CVE-2017-5638.md)

- The Jakarta Multipart parser in Apache Struts 2 2.3.x before 2.3.32 and 2.5.x before 2.5.10.1 mishandles file upload, which allows remote attackers to execute arbitrary commands via a #cmd= string in a crafted Content-Type HTTP header, as exploited in the wild in March 2017.

### [CVE-2017-5689](CVE-2017-5689.md)

- An unprivileged network attacker could gain system privileges to provisioned Intel manageability SKUs: Intel Active Management Technology (AMT) and Intel Standard Manageability (ISM). An unprivileged local attacker could provision manageability features gaining unprivileged network or local system privileges on Intel manageability SKUs: Intel Active Management Technology (AMT), Intel Standard Manageability (ISM), and Intel Small Business Technology (SBT).

### [CVE-2017-5715](CVE-2017-5715.md)

- Systems with microprocessors utilizing speculative execution and indirect branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis.

### [CVE-2017-5753](CVE-2017-5753.md)

- Systems with microprocessors utilizing speculative execution and branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis.

### [CVE-2017-5754](CVE-2017-5754.md)

- Systems with microprocessors utilizing speculative execution and indirect branch prediction may allow unauthorized disclosure of information to an attacker with local user access via a side-channel analysis of the data cache.

### [CVE-2017-5891](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 have Login Page CSRF and Save Settings CSRF.

### [CVE-2017-5892](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 allow JSONP Information Disclosure such as a network map.

### [CVE-2017-5948](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One, X, 2, 3, and 3T devices. OxygenOS and HydrogenOS are vulnerable to downgrade attacks. This is due to a lenient 'updater-script' in OTAs that does not check that the current version is lower than or equal to the given image's. Downgrades can occur even on locked bootloaders and without triggering a factory reset, allowing for exploitation of now-patched vulnerabilities with access to user data. This vulnerability can be exploited by a Man-in-the-Middle (MiTM) attacker targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, a physical attacker can reboot the phone into recovery, and then use 'adb sideload' to push the OTA (on OnePlus 3/3T 'Secure Start-up' must be off).

### [CVE-2017-6008](https://github.com/cbayet/Exploit-CVE-2017-6008)

- A kernel pool overflow in the driver hitmanpro37.sys in Sophos SurfRight HitmanPro before 3.7.20 Build 286 (included in the HitmanPro.Alert solution and Sophos Clean) allows local users to escalate privileges via a malformed IOCTL call.

### [CVE-2017-6074](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-6074)

- The dccp_rcv_state_process function in net/dccp/input.c in the Linux kernel through 4.9.11 mishandles DCCP_PKT_REQUEST packet data structures in the LISTEN state, which allows local users to obtain root privileges or cause a denial of service (double free) via an application that makes an IPV6_RECVPKTINFO setsockopt system call.

### [CVE-2017-6178](http://bobao.360.cn/learning/detail/3935.html)

- The IofCallDriver function in USBPcap 1.1.0.0 allows local users to gain privileges via a crafted 0x00090028 IOCTL call, which triggers a NULL pointer dereference.

### [CVE-2017-6326](https://pentest.blog/unexpected-journey-5-from-weak-password-to-rce-on-symantec-messaging-gateway/)

- The Symantec Messaging Gateway can encounter an issue of remote code execution, which describes a situation whereby an individual may obtain the ability to execute commands remotely on a target machine or in a target process.

### [CVE-2017-6736](https://github.com/artkond/cisco-snmp-rce)

- The Simple Network Management Protocol (SNMP) subsystem of Cisco IOS 12.0 through 12.4 and 15.0 through 15.6 and IOS XE 2.2 through 3.17 contains multiple vulnerabilities that could allow an authenticated, remote attacker to remotely execute code on an affected system or cause an affected system to reload. An attacker could exploit these vulnerabilities by sending a crafted SNMP packet to an affected system via IPv4 or IPv6. Only traffic directed to an affected system can be used to exploit these vulnerabilities. The vulnerabilities are due to a buffer overflow condition in the SNMP subsystem of the affected software. The vulnerabilities affect all versions of SNMP: Versions 1, 2c, and 3. To exploit these vulnerabilities via SNMP Version 2c or earlier, the attacker must know the SNMP read-only community string for the affected system. To exploit these vulnerabilities via SNMP Version 3, the attacker must have user credentials for the affected system. All devices that have enabled SNMP and have not explicitly excluded the affected MIBs or OIDs should be considered vulnerable. Cisco Bug IDs: CSCve57697.

### [CVE-2017-6980](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-6980.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-6984](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-6984.md)

- An issue was discovered in certain Apple products. iOS before 10.3.2 is affected. Safari before 10.1.1 is affected. iTunes before 12.6.1 on Windows is affected. tvOS before 10.2.1 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7056](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7056.md)

- An issue was discovered in certain Apple products. iOS before 10.3.3 is affected. Safari before 10.1.2 is affected. iCloud before 6.2.2 on Windows is affected. iTunes before 12.6.2 on Windows is affected. tvOS before 10.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7061](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7061.md)

- An issue was discovered in certain Apple products. iOS before 10.3.3 is affected. Safari before 10.1.2 is affected. iCloud before 6.2.2 on Windows is affected. iTunes before 12.6.2 on Windows is affected. tvOS before 10.2.2 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7089](https://github.com/Bo0oM/CVE-2017-7089)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. The issue involves the "WebKit" component. It allows remote attackers to conduct Universal XSS (UXSS) attacks via a crafted web site that is mishandled during parent-tab processing.

### [CVE-2017-7092](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7092.md)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. iTunes before 12.7 on Windows is affected. tvOS before 11 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7115](https://www.exploit-db.com/exploits/42996/)

- An issue was discovered in certain Apple products. iOS before 11 is affected. tvOS before 11 is affected. The issue involves the "Wi-Fi" component. It might allow remote attackers to execute arbitrary code in a privileged context or cause a denial of service (memory corruption) via crafted Wi-Fi traffic that leverages a race condition.

### [CVE-2017-7117](https://github.com/tunz/js-vuln-db/blob/master/jsc/CVE-2017-7117.md)

- An issue was discovered in certain Apple products. iOS before 11 is affected. Safari before 11 is affected. iCloud before 7.0 on Windows is affected. iTunes before 12.7 on Windows is affected. tvOS before 11 is affected. The issue involves the "WebKit" component. It allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption and application crash) via a crafted web site.

### [CVE-2017-7219](https://blog.scrt.ch/2017/04/26/heap-overflow-vulnerability-in-citrix-netscaler-gateway-cve-2017-7219/)

- A heap overflow vulnerability in Citrix NetScaler Gateway versions 10.1 before 135.8/135.12, 10.5 before 65.11, 11.0 before 70.12, and 11.1 before 52.13 allows a remote authenticated attacker to run arbitrary commands via unspecified vectors.

### [CVE-2017-7269](https://github.com/zcgonvh/cve-2017-7269-tool)

- Buffer overflow in the ScStoragePathFromUrl function in the WebDAV service in Internet Information Services (IIS) 6.0 in Microsoft Windows Server 2003 R2 allows remote attackers to execute arbitrary code via a long header beginning with "If: <http://" in a PROPFIND request, as exploited in the wild in July or August 2016.

### [CVE-2017-7279](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An unprivileged user of the Unitrends Enterprise Backup before 9.0.0 web server can escalate to root privileges by modifying the "token" cookie issued at login.

### [CVE-2017-7280](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An issue was discovered in api/includes/systems.php in Unitrends Enterprise Backup before 9.0.0. User input is not properly filtered before being sent to a popen function. This allows for remote code execution by sending a specially crafted user variable.

### [CVE-2017-7281](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-1/)

- An issue was discovered in Unitrends Enterprise Backup before 9.1.2. A lack of sanitization of user input in the createReportName and saveReport functions in recoveryconsole/bpl/reports.php allows for an authenticated user to create a randomly named file on disk with a user-controlled extension, contents, and path, leading to remote code execution, aka Unrestricted File Upload.

### [CVE-2017-7282](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-2/)

- An issue was discovered in Unitrends Enterprise Backup before 9.1.1. The function downloadFile in api/includes/restore.php blindly accepts any filename passed to /api/restore/download as valid. This allows an authenticated attacker to read any file in the filesystem that the web server has access to, aka Local File Inclusion (LFI).

### [CVE-2017-7283](https://rhinosecuritylabs.com/research/remote-code-execution-bug-hunting-chapter-2/)

- An authenticated user of Unitrends Enterprise Backup before 9.1.2 can execute arbitrary OS commands by sending a specially crafted filename to the /api/restore/download-files endpoint, related to the downloadFiles function in api/includes/restore.php.

### [CVE-2017-7293](CVE-2017-7293.md)

- The DAX2API service installed as part of the Realtek Audio Driver on Windows 10 is vulnerable to a privilege escalation vulnerability which allows a normal user to get arbitrary system privileges.

### [CVE-2017-7308](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-7308)

- The packet_set_ring function in net/packet/af_packet.c in the Linux kernel through 4.10.6 does not properly validate certain block-size data, which allows local users to cause a denial of service (integer signedness error and out-of-bounds write), or gain privileges (if the CAP_NET_RAW capability is held), via crafted system calls.

### [CVE-2017-7344](https://securite.intrinsec.com/2017/12/22/cve-2017-7344-fortinet-forticlient-windows-privilege-escalation-at-logon/)

- A privilege escalation in Fortinet FortiClient Windows 5.4.3 and earlier as well as 5.6.0 allows attacker to gain privilege via exploiting the Windows "security alert" dialog thereby popping up when the "VPN before logon" feature is enabled and an untrusted certificate chain.

### [CVE-2017-7442](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/windows/fileformat/nitro_reader_jsapi.rb)

- Nitro Pro 11.0.3.173 allows remote attackers to execute arbitrary code via saveAs and launchURL calls with directory traversal sequences.

### [CVE-2017-7494](CVE-2017-7494.md)

- Samba since version 3.5.0 is vulnerable to remote code execution vulnerability, allowing a malicious client to upload a shared library to a writable share, and then cause the server to load and execute it.

### [CVE-2017-7504](https://github.com/joaomatosf/JavaDeserH2HC)

- HTTPServerILServlet.java in JMS over HTTP Invocation Layer of the JbossMQ implementation, which is enabled by default in Red Hat Jboss Application Server <= Jboss 4.X does not restrict the classes for which it performs deserialization, which allows remote attackers to execute arbitrary code via crafted serialized data.

### [CVE-2017-7525](https://www.secfree.com/article-617.html)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-7529](https://cert.360.cn/detailnews.html?id=b879782fbad4a7f773b6c18490d67ac7)

- Nginx versions since 0.5.6 up to and including 1.13.2 are vulnerable to integer overflow vulnerability in nginx range filter module resulting into leak of potentially sensitive information triggered by specially crafted request.

### [CVE-2017-7533](https://github.com/hardenedlinux/offensive_poc/tree/master/CVE-2017-7533)

- Race condition in the fsnotify implementation in the Linux kernel through 4.12.4 allows local users to gain privileges or cause a denial of service (memory corruption) via a crafted application that leverages simultaneous execution of the inotify_handle_event and vfs_rename functions.

### [CVE-2017-8046](https://tech.meituan.com/Spring_Data_REST_远程代码执行漏洞(CVE-2017-8046)_分析与复现.html)

- Malicious PATCH requests submitted to spring-data-rest servers in Pivotal Spring Data REST versions prior to 2.5.12, 2.6.7, 3.0 RC3, Spring Boot versions prior to 2.0.0M4, and Spring Data release trains prior to Kay-RC3 can use specially crafted JSON data to run arbitrary Java code.

### [CVE-2017-8295](https://github.com/cyberheartmi9/CVE-2017-8295)

- WordPress through 4.7.4 relies on the Host HTTP header for a password-reset e-mail message, which makes it easier for remote attackers to reset arbitrary passwords by making a crafted wp-login.php?action=lostpassword request and then arranging for this message to bounce or be resent, leading to transmission of the reset key to a mailbox on an attacker-controlled SMTP server. This is related to problematic use of the SERVER_NAME variable in wp-includes/pluggable.php in conjunction with the PHP mail function. Exploitation is not achievable in all cases because it requires at least one of the following: (1) the attacker can prevent the victim from receiving any e-mail messages for an extended period of time (such as 5 days), (2) the victim's e-mail system sends an autoresponse containing the original message, or (3) the victim manually composes a reply containing the original message.

### [CVE-2017-8386](https://insinuator.net/2017/05/git-shell-bypass-by-abusing-less-cve-2017-8386/)

- git-shell in git before 2.4.12, 2.5.x before 2.5.6, 2.6.x before 2.6.7, 2.7.x before 2.7.5, 2.8.x before 2.8.5, 2.9.x before 2.9.4, 2.10.x before 2.10.3, 2.11.x before 2.11.2, and 2.12.x before 2.12.3 might allow remote authenticated users to gain privileges via a repository name that starts with a - (dash) character.

### [CVE-2017-8464](CVE-2017-8464.md)

- Windows Shell in Microsoft Windows Server 2008 SP2 and R2 SP1, Windows 7 SP1, Windows 8, Windows 8.1, Windows Server 2012 Gold and R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows local users or remote attackers to execute arbitrary code via a crafted .LNK file, which is not properly handled during icon display in Windows Explorer or any other application that parses the icon of the shortcut. aka "LNK Remote Code Execution Vulnerability."

### [CVE-2017-8514](http://respectxss.blogspot.tw/2017/06/a-look-at-cve-2017-8514-sharepoints.html)

- An information disclosure vulnerability exists when Microsoft SharePoint software fails to properly sanitize a specially crafted requests, aka "Microsoft SharePoint Reflective XSS Vulnerability".

### [CVE-2017-8543](http://adlab.venustech.com.cn/article.html?type=vuln_analysis&date=20170718)

- Microsoft Windows XP SP3, Windows XP x64 XP2, Windows Server 2003 SP2, Windows Vista, Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to take control of the affected system when Windows Search fails to handle objects in memory, aka "Windows Search Remote Code Execution Vulnerability".

### [CVE-2017-8548](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8548.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system when Microsoft Edge improperly handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8499, CVE-2017-8520, CVE-2017-8521, and CVE-2017-8549.

### [CVE-2017-8570](https://mp.weixin.qq.com/s/dMqovzZ70SJgdnfAZtcZMg)

- Microsoft Office allows a remote code execution vulnerability due to the way that it handles objects in memory, aka "Microsoft Office Remote Code Execution Vulnerability". This CVE ID is unique from CVE-2017-0243.

### [CVE-2017-8601](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8601.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user when the JavaScript engine fails to render when handling objects in memory in Microsoft Edge, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8596, CVE-2017-8610, CVE-2017-8618, CVE-2017-8619, CVE-2017-8603, CVE-2017-8604, CVE-2017-8605, CVE-2017-8606, CVE-2017-8607, CVE-2017-8608, CVE-2017-8598 and CVE-2017-8609.

### [CVE-2017-8625](https://msitpros.com/?p=3909)

- Internet Explorer in Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to bypass Device Guard User Mode Code Integrity (UMCI) policies due to Internet Explorer failing to validate UMCI policies, aka "Internet Explorer Security Feature Bypass Vulnerability".

### [CVE-2017-8634](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8634.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8636](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8636.md)

- Microsoft browsers in Microsoft Windows 7 SP1, Windows Server 2008 R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8640](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8640.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8645](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8645.md)

- Microsoft Edge in Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8646](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8646.md)

- Microsoft Edge in Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8656](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8656.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8657, CVE-2017-8670, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8670](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8670.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8671, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8671](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8671.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user due to the way that Microsoft browser JavaScript engines render content when handling objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8634, CVE-2017-8635, CVE-2017-8636, CVE-2017-8638, CVE-2017-8639, CVE-2017-8640, CVE-2017-8641, CVE-2017-8645, CVE-2017-8646, CVE-2017-8647, CVE-2017-8655, CVE-2017-8656, CVE-2017-8657, CVE-2017-8670, CVE-2017-8672, and CVE-2017-8674.

### [CVE-2017-8729](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8729.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8740](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8740.md)

- Microsoft Edge in Microsoft Windows 10 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8751](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8751.md)

- Microsoft Edge in Microsoft Windows 1703 allows an attacker to execute arbitrary code in the context of the current user, due to the way that Microsoft Edge accesses objects in memory, aka "Microsoft Edge Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8731, CVE-2017-8734, and CVE-2017-11766.

### [CVE-2017-8755](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-8755.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the scripting engine handles objects in memory in Microsoft Edge, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8756, and CVE-2017-11764.

### [CVE-2017-8759](https://github.com/Voulnet/CVE-2017-8759-Exploit-sample)

- Microsoft .NET Framework 2.0, 3.5, 3.5.1, 4.5.2, 4.6, 4.6.1, 4.6.2 and 4.7 allow an attacker to execute code remotely via a malicious document or application, aka ".NET Framework Remote Code Execution Vulnerability."

### [CVE-2017-8850](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One, X, 2, 3, and 3T devices. Due to a lenient updater-script in the OnePlus OTA images, and the fact that both ROMs use the same OTA verification keys, attackers can install HydrogenOS over OxygenOS and vice versa, even on locked bootloaders, which allows for exploitation of vulnerabilities patched on one image but not on the other, in addition to expansion of the attack surface. This vulnerability can be exploited by Man-in-the-Middle (MiTM) attackers targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, physical attackers can reboot the phone into recovery, and then use 'adb sideload' to push the OTA (on OnePlus 3/3T 'Secure Start-up' must be off).

### [CVE-2017-8851](https://alephsecurity.com/2017/05/11/oneplus-ota/)

- An issue was discovered on OnePlus One and X devices. Due to a lenient updater-script on the OnePlus One and X OTA images, the fact that both products use the same OTA verification keys, and the fact that both products share the same 'ro.build.product' system property, attackers can install OTAs of one product over the other, even on locked bootloaders. That could theoretically allow for exploitation of vulnerabilities patched on one image but not on the other, in addition to expansion of the attack surface. Moreover, the vulnerability may result in having the device unusable until a Factory Reset is performed. This vulnerability can be exploited by Man-in-the-Middle (MiTM) attackers targeting the update process. This is possible because the update transaction does not occur over TLS (CVE-2016-10370). In addition, physical attackers can reboot the phone into recovery, and then use 'adb sideload' to push the OTA.

### [CVE-2017-8877](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware through 3.0.0.4.380.7378 allow JSONP Information Disclosure such as the SSID.

### [CVE-2017-8878](https://wwws.nightwatchcybersecurity.com/2017/05/09/multiple-vulnerabilities-in-asus-routers/)

- ASUS RT-AC* and RT-N* devices with firmware before 3.0.0.4.380.7378 allow remote authenticated users to discover the Wi-Fi password via WPS_info.xml.

### [CVE-2017-8890](https://github.com/hardenedlinux/offensive_poc/tree/master/CVE-2017-8890)

- The inet_csk_clone_lock function in net/ipv4/inet_connection_sock.c in the Linux kernel through 4.10.15 allows attackers to cause a denial of service (double free) or possibly have unspecified other impact by leveraging use of the accept system call.

### [CVE-2017-8917](https://blog.sucuri.net/2017/05/sql-injection-vulnerability-joomla-3-7.html)

- SQL injection vulnerability in Joomla! 3.7.x before 3.7.1 allows attackers to execute arbitrary SQL commands via unspecified vectors.

### [CVE-2017-9417](http://boosterok.com/blog/broadpwn2/)

- Broadcom BCM43xx Wi-Fi chips allow remote attackers to execute arbitrary code via unspecified vectors, aka the "Broadpwn" issue.

### [CVE-2017-9791](CVE-2017-9791.md)

- The Struts 1 plugin in Apache Struts 2.3.x might allow remote code execution via a malicious field value passed in a raw message to the ActionMessage.

### [CVE-2017-9798](https://blog.fuzzing-project.org/60-Optionsbleed-HTTP-OPTIONS-method-can-leak-Apaches-server-memory.html)

- Apache httpd allows remote attackers to read secret data from process memory if the Limit directive can be set in a user's .htaccess file, or if httpd.conf has certain misconfigurations, aka Optionsbleed. This affects the Apache HTTP Server through 2.2.34 and 2.4.x through 2.4.27. The attacker sends an unauthenticated OPTIONS HTTP request when attempting to read secret data. This is a use-after-free issue and thus secret data is not always sent, and the specific data depends on many factors including configuration. Exploitation with .htaccess can be blocked with a patch to the ap_limit_section function in server/core.c.

### [CVE-2017-9805](CVE-2017-9805.md)

- The REST Plugin in Apache Struts 2.1.2 through 2.3.x before 2.3.34 and 2.5.x before 2.5.13 uses an XStreamHandler with an instance of XStream for deserialization without any type filtering, which can lead to Remote Code Execution when deserializing XML payloads.

### [CVE-2017-9822](https://cert.360.cn/warning/detail?id=e689288863456481733e01b093c986b6)

- DNN (aka DotNetNuke) before 9.1.1 has Remote Code Execution via a cookie, aka "2017-08 (Critical) Possible remote code execution on DNN sites."

### [CVE-2017-9948](https://www.vulnerability-lab.com/get_content.php?id=2071)

- A stack buffer overflow vulnerability has been discovered in Microsoft Skype 7.2, 7.35, and 7.36 before 7.37, involving MSFTEDIT.DLL mishandling of remote RDP clipboard content within the message box.

### [CVE-2017-9993](CVE-2017-9993.md)

- FFmpeg before 2.8.12, 3.0.x and 3.1.x before 3.1.9, 3.2.x before 3.2.6, and 3.3.x before 3.3.2 does not properly restrict HTTP Live Streaming filename extensions and demuxer names, which allows attackers to read arbitrary files via crafted playlist data.

### [CVE-2017-10271](CVE-2017-10271.md)

- Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Security). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 and 12.2.1.2.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H).

### [CVE-2017-10661](http://bbs.pediy.com/thread-220490.htm)

- Race condition in fs/timerfd.c in the Linux kernel before 4.10.15 allows local users to gain privileges or cause a denial of service (list corruption or use-after-free) via simultaneous file-descriptor operations that leverage improper might_cancel queueing.

### [CVE-2017-11105](https://alephsecurity.com/vulns/aleph-2017026)

- The OnePlus 2 Primary Bootloader (PBL) does not validate the SBL1 partition before executing it, although it contains a certificate. This allows attackers with write access to that partition to disable signature validation.

### [CVE-2017-11120](https://bugs.chromium.org/p/project-zero/issues/detail?id=1289)

- On Broadcom BCM4355C0 Wi-Fi chips 9.44.78.27.0.1.56 and other chips, an attacker can craft a malformed RRM neighbor report frame to trigger an internal buffer overflow in the Wi-Fi firmware, aka B-V2017061204.

### [CVE-2017-11421](http://news.dieweltistgarnichtso.net/posts/gnome-thumbnailer-msi-fail.html)

- gnome-exe-thumbnailer before 0.9.5 is prone to a VBScript Injection when generating thumbnails for MSI files, aka the "Bad Taste" issue. There is a local attack if the victim uses the GNOME Files file manager, and navigates to a directory containing a .msi file with VBScript code in its filename.

### [CVE-2017-11444](http://mp.weixin.qq.com/s/89mCnjUCvmptLsKaeVlC9Q)

- Subrion CMS before 4.1.5.10 has a SQL injection vulnerability in /front/search.php via the $_GET array.

### [CVE-2017-11610](https://github.com/ysrc/xunfeng/blob/master/vulscan/vuldb/crack_supervisor_web.py)

- The XML-RPC server in supervisor before 3.0.1, 3.1.x before 3.1.4, 3.2.x before 3.2.4, and 3.3.x before 3.3.3 allows remote authenticated users to execute arbitrary commands via a crafted XML-RPC request, related to nested supervisord namespace lookups.

### [CVE-2017-11764](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11764.md)

- Microsoft Edge in Microsoft Windows 10 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to the way that the Microsoft Edge scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-8649, CVE-2017-8660, CVE-2017-8729, CVE-2017-8738, CVE-2017-8740, CVE-2017-8741, CVE-2017-8748, CVE-2017-8752, CVE-2017-8753, CVE-2017-8755, and CVE-2017-8756.

### [CVE-2017-11774](https://sensepost.com/blog/2017/outlook-home-page-another-ruler-vector/)

- Microsoft Outlook 2010 SP2, Outlook 2013 SP1 and RT SP1, and Outlook 2016 allow an attacker to execute arbitrary commands, due to how Microsoft Office handles objects in memory, aka "Microsoft Outlook Security Feature Bypass Vulnerability."

### [CVE-2017-11779](https://www.bishopfox.com/blog/2017/10/a-bug-has-no-name-multiple-heap-buffer-overflows-in-the-windows-dns-client/)

- The Microsoft Windows Domain Name System (DNS) DNSAPI.dll on Microsoft Windows 8.1, Windows Server 2012 R2, Windows RT 8.1, Windows 10 Gold, 1511, 1607, and 1703, and Windows Server 2016 allows a remote code execution vulnerability when it fails to properly handle DNS responses, aka "Windows DNSAPI Remote Code Execution Vulnerability".

### [CVE-2017-11793](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11793.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11796, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11799](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11799.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11802](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11802.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11809](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11809.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11810, CVE-2017-11811, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11811](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11811.md)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11812](https://www.zerodayinitiative.com/blog/2017/12/22/a-matching-pair-of-use-after-free-bugs-in-chakra-asmjs)

- ChakraCore and Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11792, CVE-2017-11793, CVE-2017-11796, CVE-2017-11797, CVE-2017-11798, CVE-2017-11799, CVE-2017-11800, CVE-2017-11801, CVE-2017-11802, CVE-2017-11804, CVE-2017-11805, CVE-2017-11806, CVE-2017-11807, CVE-2017-11808, CVE-2017-11809, CVE-2017-11810, CVE-2017-11812, and CVE-2017-11821.

### [CVE-2017-11839](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11839.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to take control of an affected system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11840](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11840.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11841](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11841.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11855](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11855.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 SP2 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Internet Explorer Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11856.

### [CVE-2017-11861](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11861.md)

- Microsoft Edge in Windows 10 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11870](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11870.md)

- ChakraCore and Microsoft Edge in Windows 10 1703, 1709, and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11871, and CVE-2017-11873.

### [CVE-2017-11873](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11873.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, Windows Server 2016 and Windows Server, version 1709 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11836, CVE-2017-11837, CVE-2017-11838, CVE-2017-11839, CVE-2017-11840, CVE-2017-11841, CVE-2017-11843, CVE-2017-11846, CVE-2017-11858, CVE-2017-11859, CVE-2017-11861, CVE-2017-11862, CVE-2017-11866, CVE-2017-11869, CVE-2017-11870, and CVE-2017-11871.

### [CVE-2017-11882](https://github.com/Ridter/CVE-2017-11882)

- Microsoft Office 2007 Service Pack 3, Microsoft Office 2010 Service Pack 2, Microsoft Office 2013 Service Pack 1, and Microsoft Office 2016 allow an attacker to run arbitrary code in the context of the current user by failing to properly handle objects in memory, aka "Microsoft Office Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11884.

### [CVE-2017-11890](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11890.md)

- Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allow an attacker to execute arbitrary code in the context of the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11893](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11893.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11903](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11903.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11906](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11906.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, and Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2017-11887 and CVE-2017-11919.

### [CVE-2017-11907](https://github.com/tunz/js-vuln-db/blob/master/jscript/CVE-2017-11907.md)

- Internet Explorer in Microsoft Windows 7 SP1, Windows Server 2008 and R2 SP1, Windows 8.1 and Windows RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how Internet Explorer handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11909](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11909.md)

- ChakraCore and Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11911](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11911.md)

- ChakraCore and Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11914](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11914.md)

- ChakraCore and Microsoft Edge in Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11916, CVE-2017-11918, and CVE-2017-11930.

### [CVE-2017-11918](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2017-11918.md)

- ChakraCore and Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to gain the same user rights as the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2017-11886, CVE-2017-11889, CVE-2017-11890, CVE-2017-11893, CVE-2017-11894, CVE-2017-11895, CVE-2017-11901, CVE-2017-11903, CVE-2017-11905, CVE-2017-11905, CVE-2017-11907, CVE-2017-11908, CVE-2017-11909, CVE-2017-11910, CVE-2017-11911, CVE-2017-11912, CVE-2017-11913, CVE-2017-11914, CVE-2017-11916, and CVE-2017-11930.

### [CVE-2017-12097](https://www.talosintelligence.com/reports/TALOS-2017-0449)

- An exploitable cross site scripting (XSS) vulnerability exists in the filter functionality of the delayed_job_web rails gem version 1.4. A specially crafted URL can cause an XSS flaw resulting in an attacker being able to execute arbitrary javascript on the victim's browser. An attacker can phish an authenticated user to trigger this vulnerability.

### [CVE-2017-12098](https://www.talosintelligence.com/reports/TALOS-2017-0450)

- An exploitable cross site scripting (XSS) vulnerability exists in the add filter functionality of the rails_admin rails gem version 1.2.0. A specially crafted URL can cause an XSS flaw resulting in an attacker being able to execute arbitrary javascript on the victim's browser. An attacker can phish an authenticated user to trigger this vulnerability.

### [CVE-2017-12149](https://github.com/joaomatosf/JavaDeserH2HC)

- In Jboss Application Server as shipped with Red Hat Enterprise Application Platform 5.2, it was found that the doFilter method in the ReadOnlyAccessFilter of the HTTP Invoker does not restrict classes for which it performs deserialization and thus allowing an attacker to execute arbitrary code via crafted serialized data.

### [CVE-2017-12581](https://blog.doyensec.com/2017/08/03/electron-framework-security.html)

- GitHub Electron before 1.6.8 allows remote command execution because of a nodeIntegration bypass vulnerability. This also affects all applications that bundle Electron code equivalent to 1.6.8 or earlier. Bypassing the Same Origin Policy (SOP) is a precondition; however, recent Electron versions do not have strict SOP enforcement. Combining an SOP bypass with a privileged URL internally used by Electron, it was possible to execute native Node.js primitives in order to run OS commands on the user's host. Specifically, a chrome-devtools://devtools/bundled/inspector.html window could be used to eval a Node.js child_process.execFile API call.

### [CVE-2017-12611](CVE-2017-12611.md)

- In Apache Struts 2.0.1 through 2.3.33 and 2.5 through 2.5.10, using an unintentional expression in a Freemarker tag instead of string literals can lead to a RCE attack.

### [CVE-2017-12615](https://www.secfree.com/article-399.html)

- When running Apache Tomcat 7.0.0 to 7.0.79 on Windows with HTTP PUTs enabled (e.g. via setting the readonly initialisation parameter of the Default to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server.

### [CVE-2017-12617](http://www.freebuf.com/vuls/150203.html)

- When running Apache Tomcat versions 9.0.0.M1 to 9.0.0, 8.5.0 to 8.5.22, 8.0.0.RC1 to 8.0.46 and 7.0.0 to 7.0.81 with HTTP PUTs enabled (e.g. via setting the readonly initialisation parameter of the Default servlet to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server.

### [CVE-2017-13089](https://paper.seebug.org/525/)

- The http.c:skip_short_body() function is called in some circumstances, such as when processing redirects. When the response is sent chunked in wget before 1.19.2, the chunk parser uses strtol() to read each chunk's length, but doesn't check that the chunk length is a non-negative number. The code then tries to skip the chunk in pieces of 512 bytes by using the MIN() macro, but ends up passing the negative chunk length to connect.c:fd_read(). As fd_read() takes an int argument, the high 32 bits of the chunk length are discarded, leaving fd_read() with a completely attacker controlled length argument.

### [CVE-2017-14335](https://blogs.securiteam.com/index.php/archives/3420)

- On Beijing Hanbang Hanbanggaoke devices, because user-controlled input is not sufficiently sanitized, sending a PUT request to /ISAPI/Security/users/1 allows an admin password change.

### [CVE-2017-14491](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14491.py)

- Heap-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted DNS response.

### [CVE-2017-14492](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14492.py)

- Heap-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted IPv6 router advertisement request.

### [CVE-2017-14493](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14493.py)

- Stack-based buffer overflow in dnsmasq before 2.78 allows remote attackers to cause a denial of service (crash) or execute arbitrary code via a crafted DHCPv6 request.

### [CVE-2017-14494](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14494.py)

- dnsmasq before 2.78, when configured as a relay, allows remote attackers to obtain sensitive memory information via vectors involving handling DHCPv6 forwarded requests.

### [CVE-2017-14495](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14495.py)

- Memory leak in dnsmasq before 2.78, when the --add-mac, --add-cpe-id or --add-subnet option is specified, allows remote attackers to cause a denial of service (memory consumption) via vectors involving DNS response creation.

### [CVE-2017-14496](https://github.com/google/security-research-pocs/blob/master/vulnerabilities/dnsmasq/CVE-2017-14496.py)

- Integer underflow in the add_pseudoheader function in dnsmasq before 2.78 , when the --add-mac, --add-cpe-id or --add-subnet option is specified, allows remote attackers to cause a denial of service via a crafted DNS request.

### [CVE-2017-14904](https://android-developers.googleblog.com/2018/01/android-security-ecosystem-investments.html)

- In Android for MSM, Firefox OS for MSM, QRD Android, with all Android releases from CAF using the Linux kernel, a crafted binder request can cause an arbitrary unmap in MediaServer.

### [CVE-2017-15361](https://crocs.fi.muni.cz/public/papers/rsa_ccs17)

- The Infineon RSA library 1.02.013 in Infineon Trusted Platform Module (TPM) firmware, such as versions before 0000000000000422 - 4.34, before 000000000000062b - 6.43, and before 0000000000008521 - 133.33, mishandles RSA key generation, which makes it easier for attackers to defeat various cryptographic protection mechanisms via targeted attacks, aka ROCA. Examples of affected technologies include BitLocker with TPM 1.2, YubiKey 4 (before 4.3.5) PGP key generation, and the Cached User Data encryption feature in Chrome OS.

### [CVE-2017-15388](https://bugs.chromium.org/p/chromium/issues/detail?id=756563)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15396](https://bugs.chromium.org/p/chromium/issues/detail?id=770452)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15399](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-15399.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15401](https://github.com/tunz/js-vuln-db/blob/master/v8/CVE-2017-15401.md)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15411](https://bugs.chromium.org/p/chromium/issues/detail?id=770148)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15412](https://bugs.chromium.org/p/chromium/issues/detail?id=727039)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15415](https://bugs.chromium.org/p/chromium/issues/detail?id=765512)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15428](https://github.com/xuechiyaobai/V8_November_2017/tree/master/CVE-2017-15428)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-15613](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-interface variable in the cmxddns.lua file.

### [CVE-2017-15614](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-outif variable in the pptp_client.lua file.

### [CVE-2017-15615](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the lcpechointerval variable in the pptp_client.lua file.

### [CVE-2017-15616](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-interface variable in the phddns.lua file.

### [CVE-2017-15617](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the iface variable in the interface_wan.lua file.

### [CVE-2017-15618](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-enable variable in the pptp_client.lua file.

### [CVE-2017-15619](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the pptphellointerval variable in the pptp_client.lua file.

### [CVE-2017-15620](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-zone variable in the ipmac_import.lua file.

### [CVE-2017-15621](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the olmode variable in the interface_wan.lua file.

### [CVE-2017-15622](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-mppeencryption variable in the pptp_client.lua file.

### [CVE-2017-15623](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-enable variable in the pptp_server.lua file.

### [CVE-2017-15624](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-authtype variable in the pptp_server.lua file.

### [CVE-2017-15625](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-olmode variable in the pptp_client.lua file.

### [CVE-2017-15626](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-bindif variable in the pptp_server.lua file.

### [CVE-2017-15627](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-pns variable in the pptp_client.lua file.

### [CVE-2017-15628](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the lcpechointerval variable in the pptp_server.lua file.

### [CVE-2017-15629](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-tunnelname variable in the pptp_client.lua file.

### [CVE-2017-15630](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-remotesubnet variable in the pptp_client.lua file.

### [CVE-2017-15631](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-workmode variable in the pptp_client.lua file.

### [CVE-2017-15632](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-mppeencryption variable in the pptp_server.lua file.

### [CVE-2017-15633](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-ipgroup variable in the session_limits.lua file.

### [CVE-2017-15634](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the name variable in the wportal.lua file.

### [CVE-2017-15635](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the max_conn variable in the session_limits.lua file.

### [CVE-2017-15636](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the new-time variable in the webfilter.lua file.

### [CVE-2017-15637](https://github.com/chunibalon/Vulnerability/blob/master/CVE-2017-15613_to_CVE-2017-15637.txt)

- TP-Link WVR, WAR and ER devices allow remote authenticated administrators to execute arbitrary commands via command injection in the pptphellointerval variable in the pptp_server.lua file.

### [CVE-2017-16544](https://www.twistlock.com/2017/11/20/cve-2017-16544-busybox-autocompletion-vulnerability/)

- In the add_match function in libbb/lineedit.c in BusyBox through 1.27.2, the tab autocomplete feature of the shell, used to get a list of filenames in a directory, does not sanitize filenames and results in executing any escape sequence in the terminal. This could potentially result in code execution, arbitrary file writes, or other attacks.

### [CVE-2017-16584](https://twitter.com/steventseeley/status/930555302013005827)

- This vulnerability allows remote attackers to disclose sensitive information on vulnerable installations of Foxit Reader 8.3.2.25013. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file. The specific flaw exists within util.printf. The issue results from the lack of proper validation of user-supplied data, which can result in a read past the end of an allocated object. An attacker can leverage this in conjunction with other vulnerabilities to execute code in the context of the current process. Was ZDI-CAN-5290.

### [CVE-2017-16716](https://www.exploit-db.com/exploits/43928/)

- A SQL Injection issue was discovered in WebAccess versions prior to 8.3. WebAccess does not properly sanitize its inputs for SQL commands.

### [CVE-2017-16943](https://devco.re/blog/2017/12/11/Exim-RCE-advisory-CVE-2017-16943-en/)

- The receive_msg function in receive.c in the SMTP daemon in Exim 4.88 and 4.89 allows remote attackers to execute arbitrary code or cause a denial of service (use-after-free) via vectors involving BDAT commands.

### [CVE-2017-16944](https://devco.re/blog/2017/12/11/Exim-RCE-advisory-CVE-2017-16943-en/)

- The receive_msg function in receive.c in the SMTP daemon in Exim 4.88 and 4.89 allows remote attackers to cause a denial of service (infinite loop and stack exhaustion) via vectors involving BDAT commands and an improper check for a '.' character signifying the end of the content, related to the bdat_getc function.

### [CVE-2017-17033](https://pastebin.com/XAKn6q5Y)

- A buffer overflow vulnerability in password function in QNAP QTS version 4.2.6 build 20171026, 4.3.3.0378 build 20171117, 4.3.4.0387 (Beta 2) build 20171116 and earlier could allow remote attackers to execute arbitrary code on NAS devices.

### [CVE-2017-17107](https://twitter.com/ankit_anubhav/status/950485367215525888)

- Zivif PR115-204-P-RS V2.3.4.2103 web cameras contain a hard-coded cat1029 password for the root user. The SONIX operating system's setup renders this password unchangeable and it can be used to access the device via a TELNET session.

### [CVE-2017-17215](http://xlab.tencent.com/cn/2018/01/05/a-new-way-to-exploit-cve-2017-17215/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2017-17405](https://shugo.net/jit/20171215.html)

- Ruby before 2.4.3 allows Net::FTP command injection. Net::FTP#get, getbinaryfile, gettextfile, put, putbinaryfile, and puttextfile use Kernel#open to open a local file. If the localfile argument starts with the "|" pipe character, the command following the pipe character is executed. The default value of localfile is File.basename(remotefile), so malicious FTP servers could cause arbitrary command execution.

### [CVE-2017-17562](https://www.elttam.com.au/blog/goahead/)

- Embedthis GoAhead before 3.6.5 allows remote code execution if CGI is enabled and a CGI program is dynamically linked. This is a result of initializing the environment of forked CGI scripts using untrusted HTTP request parameters in the cgiHandler function in cgi.c. When combined with the glibc dynamic linker, this behaviour can be abused for remote code execution using special parameter names such as LD_PRELOAD. An attacker can POST their shared object payload in the body of the request, and reference it using /proc/self/fd/0.

### [CVE-2017-17692](https://datarift.blogspot.tw/p/samsung-interent-browser-sop-bypass-cve.html)

- Samsung Internet Browser 5.4.02.3 allows remote attackers to bypass the Same Origin Policy and obtain sensitive information via crafted JavaScript code that redirects to a child tab and rewrites the innerHTML property.

### [CVE-2017-17867](https://neonsea.uk/blog/2017/12/23/rce-inteno-iopsys.html)

- Inteno iopsys 2.0-3.14 and 4.0 devices allow remote authenticated users to execute arbitrary OS commands by modifying the leasetrigger field in the odhcpd configuration to specify an arbitrary program, as demonstrated by a program located on an SMB share. This issue existed because the /etc/uci-defaults directory was not being used to secure the OpenWrt configuration.

### [CVE-2017-1000112](https://github.com/xairy/kernel-exploits/tree/master/CVE-2017-1000112)

- Exploitable memory corruption due to UFO to non-UFO path switch.

### [CVE-2017-1000117](http://bobao.360.cn/learning/detail/4244.html)

- A malicious third-party can give a crafted "ssh://..." URL to an unsuspecting victim, and an attempt to visit the URL can result in any program that exists on the victim's machine being executed. Such a URL could be placed in the .gitmodules file of a malicious project, and an unsuspecting victim could be tricked into running "git clone --recurse-submodules" to trigger the vulnerability.

### [CVE-2017-1000251](https://gitlab.com/marcinguy/blueborne-CVE-2017-1000251)

- The native Bluetooth stack in the Linux Kernel (BlueZ), starting at the Linux kernel version 3.3-rc1 and up to and including 4.13.1, are vulnerable to a stack overflow vulnerability in the processing of L2CAP configuration responses resulting in Remote code execution in kernel space.

### [CVE-2017-1000353](CVE-2017-1000353.md)

- Jenkins Java Deserialization CVE-2017-1000353 Remote Code Execution Vulnerability.

### [CVE-2017-1000364](Stack-Clash.md)

- An issue was discovered in the size of the stack guard page on Linux, specifically a 4k stack guard page is not sufficiently large and can be "jumped" over (the stack guard page is bypassed), this affects Linux Kernel versions 4.11.5 and earlier (the stackguard page was introduced in 2010).

### [CVE-2017-1000365](Stack-Clash.md)

- The Linux Kernel imposes a size restriction on the arguments and environmental strings passed through RLIMIT_STACK/RLIM_INFINITY (1/4 of the size), but does not take the argument and environment pointers into account, which allows attackers to bypass this limitation. This affects Linux Kernel versions 4.11.5 and earlier. It appears that this feature was introduced in the Linux Kernel version 2.6.23.

### [CVE-2017-1000366](Stack-Clash.md)

- glibc contains a vulnerability that allows specially crafted LD_LIBRARY_PATH values to manipulate the heap/stack, causing them to alias, potentially resulting in arbitrary code execution. Please note that additional hardening changes have been made to glibc to prevent manipulation of stack and heap memory but these issues are not directly exploitable, as such they have not been given a CVE. This affects glibc 2.25 and earlier.

### [CVE-2017-1000367](Stack-Clash.md)

- A vulnerability in Sudo's get_process_ttyname() for Linux: this function opens "/proc/[pid]/stat" (man proc) and reads the device number of the tty from field 7 (tty_nr). Unfortunately, these fields are space-separated and field 2 (comm, the filename of the command) can contain spaces (CVE-2017-1000367).

### [CVE-2017-1000369](Stack-Clash.md)

- Exim supports the use of multiple "-p" command line arguments which are malloc()'ed and never free()'ed, used in conjunction with other issues allows attackers to cause arbitrary code execution. This affects exim version 4.89 and earlier. Please note that at this time upstream has released a patch (commit 65e061b76867a9ea7aeeb535341b790b90ae6c21), but it is not known if a new point release is available that addresses this issue at this time.

### [CVE-2017-1000370](Stack-Clash.md)

- The offset2lib patch as used in the Linux Kernel contains a vulnerability that allows a PIE binary to be execve()'ed with 1GB of arguments or environmental strings then the stack occupies the address 0x80000000 and the PIE binary is mapped above 0x40000000 nullifying the protection of the offset2lib patch. This affects Linux Kernel version 4.11.5 and earlier. This is a different issue than CVE-2017-1000371. This issue appears to be limited to i386 based systems.

### [CVE-2017-1000371](Stack-Clash.md)

- The offset2lib patch as used by the Linux Kernel contains a vulnerability, if RLIMIT_STACK is set to RLIM_INFINITY and 1 Gigabyte of memory is allocated (the maximum under the 1/4 restriction) then the stack will be grown down to 0x80000000, and as the PIE binary is mapped above 0x80000000 the minimum distance between the end of the PIE binary's read-write segment and the start of the stack becomes small enough that the stack guard page can be jumped over by an attacker. This affects Linux Kernel version 4.11.5. This is a different issue than CVE-2017-1000370 and CVE-2017-1000365. This issue appears to be limited to i386 based systems.

### [CVE-2017-1000372](Stack-Clash.md)

- A flaw exists in OpenBSD's implementation of the stack guard page that allows attackers to bypass it resulting in arbitrary code execution using setuid binaries such as /usr/bin/at. This affects OpenBSD 6.1 and possibly earlier versions.

### [CVE-2017-1000373](Stack-Clash.md)

- The OpenBSD qsort() function is recursive, and not randomized, an attacker can construct a pathological input array of N elements that causes qsort() to deterministically recurse N/4 times. This allows attackers to consume arbitrary amounts of stack memory and manipulate stack memory to assist in arbitrary code execution attacks. This affects OpenBSD 6.1 and possibly earlier versions.

### [CVE-2017-1000374](Stack-Clash.md)

- A flaw exists in NetBSD's implementation of the stack guard page that allows attackers to bypass it resulting in arbitrary code execution using certain setuid binaries. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000375](Stack-Clash.md)

- NetBSD maps the run-time link-editor ld.so directly below the stack region, even if ASLR is enabled, this allows attackers to more easily manipulate memory leading to arbitrary code execution. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000376](Stack-Clash.md)

- libffi requests an executable stack allowing attackers to more easily trigger arbitrary code execution by overwriting the stack. Please note that libffi is used by a number of other libraries. It was previously stated that this affects libffi version 3.2.1 but this appears to be incorrect. libffi prior to version 3.1 on 32 bit x86 systems was vulnerable, and upstream is believed to have fixed this issue in version 3.1.

### [CVE-2017-1000377](Stack-Clash.md)

- An issue was discovered in the size of the default stack guard page on PAX Linux (originally from GRSecurity but shipped by other Linux vendors), specifically the default stack guard page is not sufficiently large and can be "jumped" over (the stack guard page is bypassed), this affects PAX Linux Kernel versions as of June 19, 2017 (specific version information is not available at this time).

### [CVE-2017-1000378](Stack-Clash.md)

- The NetBSD qsort() function is recursive, and not randomized, an attacker can construct a pathological input array of N elements that causes qsort() to deterministically recurse N/4 times. This allows attackers to consume arbitrary amounts of stack memory and manipulate stack memory to assist in arbitrary code execution attacks. This affects NetBSD 7.1 and possibly earlier versions.

### [CVE-2017-1000379](Stack-Clash.md)

- The Linux Kernel running on AMD64 systems will sometimes map the contents of PIE executable, the heap or ld.so to where the stack is mapped allowing attackers to more easily manipulate the stack. Linux Kernel version 4.11.5 is affected.

### [CVE-2017-1000405](https://medium.com/bindecy/huge-dirty-cow-cve-2017-1000405-110eca132de0)

- The Linux Kernel versions 2.6.38 through 4.14 have a problematic use of pmd_mkdirty() in the touch_pmd() function inside the THP implementation. touch_pmd() can be reached by get_user_pages(). In such case, the pmd will become dirty. This scenario breaks the new can_follow_write_pmd()'s logic - pmd can become dirty without going through a COW cycle. This bug is not as severe as the original "Dirty cow" because an ext4 file (or any other regular file) cannot be mapped using THP. Nevertheless, it does allow us to overwrite read-only huge pages. For example, the zero huge page and sealed shmem files can be overwritten (since their mapping can be populated using THP). Note that after the first write page-fault to the zero page, it will be replaced with a new fresh (and zeroed) thp.

### [CVE-2018-0101](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20180129-asa1)

- A vulnerability in the Secure Sockets Layer (SSL) VPN functionality of the Cisco Adaptive Security Appliance (ASA) Software could allow an unauthenticated, remote attacker to cause a reload of the affected system or to remotely execute code. The vulnerability is due to an attempt to double free a region of memory when the webvpn feature is enabled on the Cisco ASA device. An attacker could exploit this vulnerability by sending multiple, crafted XML packets to a webvpn-configured interface on the affected system. An exploit could allow the attacker to execute arbitrary code and obtain full control of the system, or cause a reload of the affected device. This vulnerability affects Cisco ASA Software that is running on the following Cisco products: 3000 Series Industrial Security Appliance (ISA), ASA 5500 Series Adaptive Security Appliances, ASA 5500-X Series Next-Generation Firewalls, ASA Services Module for Cisco Catalyst 6500 Series Switches and Cisco 7600 Series Routers, ASA 1000V Cloud Firewall, Adaptive Security Virtual Appliance (ASAv), Firepower 2100 Series Security Appliance, Firepower 4110 Security Appliance, Firepower 9300 ASA Security Module, Firepower Threat Defense Software (FTD). Cisco Bug IDs: CSCvg35618.

### [CVE-2018-0743](https://github.com/saaramar/execve_exploit)

- Windows Subsystem for Linux in Windows 10 version 1703, Windows 10 version 1709, and Windows Server, version 1709 allows an elevation of privilege vulnerability due to the way objects are handled in memory, aka "Windows Subsystem for Linux Elevation of Privilege Vulnerability".

### [CVE-2018-0744](https://www.exploit-db.com/exploits/43446/)

- The Windows kernel in Windows 8.1 and RT 8.1, Windows Server 2012 and R2, Windows 10 Gold, 1511, 1607, 1703 and 1709, Windows Server 2016 and Windows Server, version 1709 allows an elevation of privilege vulnerability due to the way objects are handled in memory, aka "Windows Elevation of Privilege Vulnerability".

### [CVE-2018-0758](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0758.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0767](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0767.md)

- Microsoft Edge in Microsoft Windows 10 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0780 and CVE-2018-0800.

### [CVE-2018-0769](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0769.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0774](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0774.md)

- Microsoft Edge in Windows 10 1709 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0775, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0775](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0775.md)

- Microsoft Edge in Windows 10 1709 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0776, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0776](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0776.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0777, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0777](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0777.md)

- Microsoft Edge in Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to execute arbitrary code in the context of the current user, due to how the scripting engine handles objects in memory, aka "Scripting Engine Memory Corruption Vulnerability". This CVE ID is unique from CVE-2018-0758, CVE-2018-0762, CVE-2018-0768, CVE-2018-0769, CVE-2018-0770, CVE-2018-0772, CVE-2018-0773, CVE-2018-0774, CVE-2018-0775, CVE-2018-0776, CVE-2018-0778, and CVE-2018-0781.

### [CVE-2018-0780](https://github.com/tunz/js-vuln-db/blob/master/chakra/CVE-2018-0780.md)

- Microsoft Edge in Microsoft Windows 10 Gold, 1511, 1607, 1703, 1709, and Windows Server 2016 allows an attacker to obtain information to further compromise the user's system, due to how the scripting engine handles objects in memory, aka "Scripting Engine Information Disclosure Vulnerability". This CVE ID is unique from CVE-2018-0767 and CVE-2018-0800.

### [CVE-2018-0802](https://github.com/zldww2011/CVE-2018-0802_POC)

- Equation Editor in Microsoft Office 2007, Microsoft Office 2010, Microsoft Office 2013, and Microsoft Office 2016 allow a remote code execution vulnerability due to the way objects are handled in memory, aka "Microsoft Office Memory Corruption Vulnerability". This CVE is unique from CVE-2018-0797 and CVE-2018-0812.

### [CVE-2018-2694](https://twitter.com/_niklasb/status/953602210088341505)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.32 and Prior to 5.2.6. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-2698](https://blogs.securiteam.com/index.php/archives/3649)

- Vulnerability in the Oracle VM VirtualBox component of Oracle Virtualization (subcomponent: Core). Supported versions that are affected are Prior to 5.1.32 and Prior to 5.2.6. Easily exploitable vulnerability allows low privileged attacker with logon to the infrastructure where Oracle VM VirtualBox executes to compromise Oracle VM VirtualBox. While the vulnerability is in Oracle VM VirtualBox, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle VM VirtualBox. CVSS 3.0 Base Score 8.8 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.0/AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:H).

### [CVE-2018-5189](https://www.fidusinfosec.com/jungo-windriver-code-execution-cve-2018-5189)

- Race condition in Jungo Windriver 12.5.1 allows local users to cause a denial of service (buffer overflow) or gain system privileges by flipping pool buffer size, aka a "double fetch" vulnerability.

### [CVE-2018-5318](https://paper.seebug.org/504/)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-5711](http://blog.orange.tw/2018/01/php-cve-2018-5711-hanging-websites-by.html)

- gd_gif_in.c in the GD Graphics Library (aka libgd), as used in PHP before 5.6.33, 7.0.x before 7.0.27, 7.1.x before 7.1.13, and 7.2.x before 7.2.1, has an integer signedness error that leads to an infinite loop via a crafted GIF file, as demonstrated by a call to the imagecreatefromgif or imagecreatefromstring PHP function. This is related to GetCode_ and gdImageCreateFromGifCtx.

### [CVE-2018-6055](https://bugs.chromium.org/p/project-zero/issues/detail?id=1450)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-6317](https://medium.com/secjuice/claymore-dual-gpu-miner-10-5-format-strings-vulnerability-916ab3d2db30)

- ** RESERVED ** This candidate has been reserved by an organization or individual that will use it when announcing a new security problem. When the candidate has been publicized, the details for this candidate will be provided.

### [CVE-2018-6460](http://www.paulosyibelo.com/2018/02/hotspot-shield-cve-2018-6460-sensitive.html)

- Hotspot Shield runs a webserver with a static IP address 127.0.0.1 and port 895. The web server uses JSONP and hosts sensitive information including configuration. User controlled input is not sufficiently filtered: an unauthenticated attacker can send a POST request to /status.js with the parameter func=$_APPLOG.Rfunc and extract sensitive information about the machine, including whether the user is connected to a VPN, to which VPN he/she is connected, and what is their real IP address.

### [CVE-2018-1000006](https://xianzhi.aliyun.com/forum/topic/1994?from=timeline&isappinstalled=0)

- GitHub Electron versions 1.8.2-beta.3 and earlier, 1.7.10 and earlier, 1.6.15 and earlier has a vulnerability in the protocol handler, specifically Electron apps running on Windows 10, 7 or 2008 that register custom protocol handlers can be tricked in arbitrary command execution if the user clicks on a specially crafted URL. This has been fixed in versions 1.8.2-beta.4, 1.7.11, and 1.6.16.

## Code of Conduct

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@qazbnm456](https://qazbnm456.github.io/) has waived all copyright and related or neighboring rights to this work.
