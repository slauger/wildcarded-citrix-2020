# Exposed wildcard certificates
Through four volunteers, the GDI Foundation scanned the internet for vulnerable Citrix devices and validated the results to remove false positives, sinkholes, and honeypots.

More than 98,000 vulnerable Citrix endpoints were found and reported through the Dutch Institute for Vulnerability Disclosure [DIVD.nl](https://divd.nl) to companies and Internet Service Providers when the owner could not be determined.

Gevers told BleepingComputer that about 11,800 wildcard TLS certificates to validate multiple sub-domains were exposed at some point, and some of them still are.

If an attacker steals a wildcard certificate, they can build phishing sites that impersonate a reputable entity such as governments, hospitals, universities, or companies.

“So after patching these organizations need to have this certificates revoked and get new ones “ - Victor Gevers

DIVD issued an [alert on Wednesday](https://www.securitymeldpunt.nl/cases/202002-Wildcard-Certificaten-Citrix-ADC/) about the poor combination of wildcard certificates with the Citrix vulnerability. 

This is the [full article](https://www.bleepingcomputer.com/news/security/patching-the-citrix-adc-bug-doesnt-mean-you-werent-hacked/) on Bleepingcomputer.

## Status
We are still retrieving and analyzing data of (previous) vulnerable Citrix servers and verifying if they have issued new cerificates.

This is the list of exposed wildcard certificates. At this moment, we can't share the full data set because not all vulnerable servers are successfully patched and secured yet.

* [Exposed (13,869) wildcard certificates: Short list](https://github.com/cookiemonster/wildcarded-citrix-2020/blob/master/exposed_wildcards.txt) - ***not complete***
