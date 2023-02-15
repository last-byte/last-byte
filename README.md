My name is Federico a.k.a. [last](https://twitter.com/last0x00), I'm an Italian security researcher and member of the [Advanced Persistent Tortellini collective](https://aptw.tf/about/). I study and develop offensive software, hold a bunch of certs, enjoy lockpicking and [acrobatic quadcopter ~~crashing~~ flying](https://www.youtube.com/watch?v=DpP_eaYOmxg). I also play CTFs with my mates @ [JBZ Team](https://jbz.team/about/) and I'm a huge fan of [XKCD](https://xkcd.com/1243/). If you want to have a look at the ~~shitty~~ code I write head to my [GitHub profile](https://github.com/last-byte). Other than that I don't have much to showcase to be honest... `¯\_(ツ)_/¯`  

Certifications:
- [Offensive Security Certified Professional (OSCP) - 2017](https://www.credential.net/497f4a4f-2f17-4d39-9bed-02da76f6b399)
- [Offensive Security Certified Expert (OSCE) - 2018](https://www.credential.net/085513c1-932c-4c00-a2af-bd0fe36b41be)
- [Certified Red Team Professional (CRTP) - 2019](https://www.credential.net/26836014-f36f-4c2d-8d2d-f807f160e309)
- [Offensive Security Web Expert (OSWE) - 2020](https://www.credential.net/bab90b9c-b9ab-4b9c-bced-ebde83996ff2)
- [eLearnSecurity Certified Penetration Tester eXtreme (eCPTX) - 2020](https://verified.elearnsecurity.com/certificates/347d8a32-7a71-41c6-9cfa-788bfd4f4d19)
- [Certified Red Team Operator (CRTO) - 2020](https://badgr.com/public/assertions/JMGMVoJ8QmqEkA9g0dbohw?identity__email=fed.lag@protonmail.ch)
- [Certified Red Team Expert (CRTE) - 2022](https://www.credential.net/3349518b-6395-4891-bd11-6c51fb69a17a)
- [Certified Azure Red Team Professional (CARTP) - 2022](https://www.credential.net/ee2939e1-29d7-4bb0-a47b-d64426f49886)

External blog posts:
- [Taking a detour inside LSASS](https://aptw.tf/2020/11/16/extracting-hashes-hooking.html) - extracting local hashes by hooking the MsvpPasswordValidate function inside LSASS memory
- [The dying knight in the shiny armour](https://aptw.tf/2021/08/21/killing-defender.html) - killing Defender through NT symbolic links redirection while keeping it unbothered
- [Stealing weapons from the Armoury](https://aptw.tf/2021/09/24/armoury-crate-privesc.html) - root cause analysis of a privilege escalation vulnerability in ASUS ROG Armoury Crate Lite Service v4.2.8 (CVE-2021-40981)
- [The ace(r) up your sleeve!](https://aptw.tf/2022/01/20/acer-care-center-privesc.html) - privilege escalation vulnerability in Acer Care Center (CVE-2021-45975)
- [Gaining the upper hand(le)](https://aptw.tf/2022/02/10/leaked-handle-hunting.html) - hunting for privilege escalations and UAC bypasses by looking for leaked handles in unprivileged processes

CVEs:
- [CVE-2021-40981](https://cve.report/CVE-2021-40981): privilege escalation I found in Asus ROG Armoury Crate. Blogpost [here](https://aptw.tf/2021/09/24/armoury-crate-privesc.html).
- [CVE-2021-45975](https://cve.report/CVE-2021-45975): privilege escalation I found in Acer Care Center for Windows. Blogpost [here](https://aptw.tf/2022/01/20/acer-care-center-privesc.html).

Projects:
- [PersistenceSniper](https://github.com/last-byte/PersistenceSniper/): Powershell script that can be used by Blue Teams, Incident Responders and System Administrators to hunt persistences implanted in Windows machines. The script is also available on Powershell Gallery.
- [RIPPL](https://github.com/last-byte/RIPPL/): C++ tool, forked from [PPLDump](https://github.com/itm4n/PPLdump) which abuses a flaw in the way Windows manages PPL processes, allowing the operator to tamper, disrupt or, more generally, interact with PPL processes like EDRs, antimalware etc. The flaw has been patched with Windows 10 v21H2 Build 19044.1826.
- [unDefender](https://github.com/last-byte/unDefender): C++ tool which abuses a flaw in the way Windows loads Defender's WDFilter.sys driver by redirecting a NT symbolic link in order to make Defender load an arbitrary driver. The full explanation of the technique is available [here](https://aptw.tf/2021/08/21/killing-defender.html).
- [DefenderSwitch](https://github.com/last-byte/DefenderSwitch): C++ tool to disable Windows Defender by abusing MsMpEng.exe's misconfigured ACL. The misconfiguration is now patched.
- [HppDLL](https://github.com/last-byte/HppDLL): C++ DLL that can be injected into LSASS in order to dump local password hashes without touching the registry. The full explanation of the technique is available [here](https://aptw.tf/2020/11/16/extracting-hashes-hooking.html).
- [Hybris](https://github.com/last-byte/hybris): C++ tool to spawn arbitrary processes running as NT AUTHORITY\SYSTEM by abusing Winlogon's token impersonation.
- [UpperHandler](https://github.com/last-byte/UpperHandler): C++ tool to automatically look for privileged handle leaks which may lead to privilege escalation vulnerabilities. The full explanation of the technique is available [here](https://aptw.tf/2022/02/10/leaked-handle-hunting.html). Not yet released.
- [GRIP](https://github.com/last-byte/GRIP): Go RIP Injection Program is a tool written in Go that can be used to inject fake routes in a RIPv2 network. The full explanation of the technique is available [here](https://blog.notso.pro/2019-01-27-grip-0.1/).

Public talks:
- [🇮🇹 Windows gold mining](https://www.youtube.com/watch?v=erg3aMPN7G4) - a somewhat deep dive into Windows credentials extraction for fun and (hopefully) profit
- [🇮🇹 Survival of the evilest](https://www.youtube.com/watch?v=30x7s3_I-B0) - persistence techniques in an enterprise environment to ensure the survival of your operation 
- [🇮🇹 Anonymity Fails, good shoes won't save you this time!](https://www.radioradicale.it/scheda/490952/e-privacy-xx-2016-privacy-ed-antiterrorismo-un-equilibrio-reale-tra-obbiettivi?i=3629963) - how bad guys got busted and what you can learn from an OPSEC perspective

You can find me at [last AT notso DOT pro](mailto:last@notso.pro) or on [Twitter](https://twitter.com/last0x00).
