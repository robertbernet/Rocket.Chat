# Reporting Security Issues

My scanning tool keeps identifying CWE-416 and CWE-918 as vulnerabilities. Anyone having similiar issues?

When sending a payload with an arbitrary domain name I'm able to have RocketChat perfom server-side DNS lookup. Is this a known issue and has there been any mediation or upgrades with versions?

Likewise, I have concerns that if the DNS name lookup results in the server being open it could be flooded with DNS response traffic. Just some concerns. In short, worried that that the DNS name lookup request to the open DNS server with the source address spoofed to be the target's address.
So when the DNS server send DNS recored response it's to the target.
