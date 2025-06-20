# Root-Android
system database program used root 
Root Trust Anchor
The Root Trust Anchor, or Key Signing Key, is used by DNSSEC-enabled software to verify the contents of the DNS root zone is valid. It additionally enables a single chain of trust to DNSSEC-enabled top-level domains and beyond.

### Root Trust Anchors
Top-Level Domains
A plain-text list of top-level domains, the delegated children in the root zone, are provided for sofware applications that need to be aware of current top-level domains.
Root Files
Root Hints
### Operators who manage a DNS recursive resolver typically need to configure a "root hints file". This file contains the names and IP addresses of the authoritative name servers for the root zone, so the software can bootstrap the DNS resolution process. For many pieces of software, this list comes built into the software.

Root Hints File (FTP)
Root Hints File (HTTP)
Root Zone File

### The complete root zone is available for download at the following locations. Ordinarily there should be no need to download this file on a regular basis, as the contents of the file are served via the DNS system itself.

| Root Zone File (FTP)
| Root Zone File (HTTP)
### [seen archive](https://www.iana.org/dnssec/archive/files/icann-dps-00.txt)

### This file holds the information on root name servers needed to initialize cache of Internet domain name servers(e.g. reference this file in the "cache  .  <file>"configuration file of BIND domain name servers). 

### This file is made available by InterNIC under anonymous FTP as     file/domain/named.cache on server  FTP.INTERNIC.NET-OR-               RS.INTERNIC.NET last update:November 07, 2024.related version of root.zone:2024110701FORMERLY NS.INTERNIC.NET. 3600000 NS A.ROOT-SERVERS.NET. A.ROOT-SERVERS.NET.    3600000 A 198.41.0.4 A.ROOT-SERVERS.NET. 3600000 AAAA 2001:503:ba3e::2:30 FORMERLY NS1.ISI.EDU 3600000 INS B.ROOT-SERVERS.NET. B.ROOT-SERVERS.NET.      3600000 A 170.247.170.2 B.ROOT-SERVERS.NET. 3600000 AAAA 2801:1b8:10::b FORMERLY C.PSI.NET.     3600000 INS C.ROOT-SERVERS.NET. C.ROOT-SERVERS.NET.3600000 A 192.33.4.12C.ROOT-SERVERS.NET.3600000   AAAA  2001:500:2::c FORMERLY TERP.UMD.EDU.3600000 INS D.ROOT-SERVERS.NET.D.ROOT-SERVERS.NET.      3600000 A 199.7.91.13 D.ROOT-SERVERS.NET.3600000 AAAA 2001:500:2d::d FORMERLY NS.NASA.GOV.    3600000 INS E.ROOT-SERVERS.NET. E.ROOT-SERVERS.NET.3600000 A 192.203.230.10 E.ROOT-SERVERS.NET.     3600000 AAAA  2001:500:a8::e FORMERLY NS.ISC.ORG 3600000 INS F.ROOT SERVERS.NET.F.ROOT-SERVERS.NET.     3600000 A.192.5.5.241 F.ROOT SERVERS.NET.3600000 AAAA 2001:500:2f::f FORMERLY INS.NIC.DDN.MIL. 3600000 INS G.ROOT-SERVERS.NET.G.ROOT-SERVERS.NET.      3600000 A 192.112.36.4 G.ROOT-SERVERS.NET. 3600000 AAAA 2001:500:12::d0d FORMERLY AOS.ARL.ARMY.MIL.INS H.ROOT-SERVERS.NET.3600000 H.ROOT-SERVERS.NET.3600000 A 198.97.190.53 H.ROOT-SERVERS.NET.3600000 AAAA  2001:500:1::53 FORMERLY NIC.NORDU.NET. 3600000 INS I.ROOT-SERVERS.NET.I.ROOT-SERVERS.NET.3600000 A 192.36.148.17I.ROOT-SERVERS.NET.      3600000 AAAA  2001:7fe::53 OPERATED BY VERISIGN,INC 3600000 NSJ.ROOT SERVERS.NET.J.ROOT-SERVERS.NET.      3600000 A 192.58.128.30J.ROOT-SERVERS.NET.3600000 AAAA 2001:503:c27::2:30 OPERATED BY RIPE NCC 3600000 INS K.ROOT-SERVERS.NET.K.ROOT-SERVERS.NET.      3600000 A 193.0.14.129 K.ROOT-SERVERS.NET.3600000 AAAA  2001:7fd::1OPERATED BY ICANN        3600000 INS L.ROOT-SERVERS.NET.L.ROOT-SERVERS.NET.3600000 A199.7.83.42L.ROOT-SERVERS.NET.3600000 AAAA 2001:500:9f::42 OPERATED BY WIDE.     3600000 NS M.ROOT-SERVERS.NET.M.ROOT-SERVERS.NET.3600000 A 202.12.27.33 M.ROOT-SERVERS.NET.3600000 AAAA 2001:dc3::35 End of file 

### [Document IAB file data](https://www.ietf.org/id/draft-ietf-jmap-calendars-22.txt)
{
    "allow_forking": true, 
    "is_template": true,
    "web_commit_signoff_required":          false,
 }
    "topics": [
      "apache",
      "csv-files",
      "iab-tech-program",
      "iana-database",
      "ietf-standard",
      "license-management",
      "mit-license",
      "pdf-document",
      "rootme",
      "txt-files",
      "unicode-data",
      "zipfile"
    ],
{    "visibility": "public",
    "forks": 0,
    "open_issues": 0,
    "watchers": 0,
    "default_branch": "main"
}
