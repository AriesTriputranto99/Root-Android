# Root-Android-
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
The complete root zone is available for download at the following locations. Ordinarily there should be no need to download this file on a regular basis, as the contents of the file are served via the DNS system itself.

Root Zone File (FTP)
Root Zone File (HTTP)
[seen archive](https://www.iana.org/dnssec/archive/files/icann-dps-00.txt)
