# IMPORTANT UPDATE
Please note that our Responsible Disclosure Program has now moved to HackerOne. You will find our program [here](https://hackerone.com/strongdm). We are mirroring our new Responsible Disclosure Program's policy in this repository for public view. 

# Background
Responsible Disclosure Policies and Vulnerability Disclosure Programs encourage security researchers, customers, and other members of the public to safely and securely report potential vulnerabilities to strongDM without fear of prosecution or legal action, and allows strongDM a chance to be informed of potential vulnerabilities prior to them being publicly announced.

These programs also signal to current and potential customers that a company is practicing a mature vulnerability management program, and is interested in advancing the security of their product.

strongDM looks forward to working with the security community to find security vulnerabilities in order to keep our businesses and customers safe.

# Table of Contents
- [Safe Harbor][safe-harbor]
- [Response & Remediation Targets][response--remediation-targets]
- [Program Rules][program-rules]
  - [Prohibited Methods][prohibited-methods]
  - [What Should Not be Submitted][what-should-not-be-submitted]
- [Out-of-Scope vulnerabilities][out-of-scope-vulnerabilities]

# Safe Harbor
Any activities conducted in a manner consistent with this policy will be considered authorized conduct and we will not initiate legal action against you. If legal action is initiated by a third party against you in connection with activities conducted under this policy, we will take steps to make it known that your actions were conducted in compliance with this policy.

As long as you follow the rules defined in this policy, strongDM makes the following commitments:

- We will not pursue civil or criminal legal action against a vulnerability reporter in response to vulnerability research and disclosure to us;
- We will work with the vulnerability reporter to understand and reproduce the vulnerability that has disclosed to us;
- We will keep the vulnerability reporter informed of our timeline for fixing the submitted vulnerability once we have verified it;
- We will recognize the vulnerability reporter on our website for their contributions toward making our product more secure;
- We may allow the vulnerability reporter to publicly disclose the vulnerability and their research methods _after_ the vulnerability has been fixed, subject to strongDM’s explicit written consent;

Thank you for helping keep strongDM and our customers safe!

# Response & Remediation Targets
strongDM will make a best effort to meet the following SLAs for hackers participating in our program:

| Type of Response | SLA in business days |
| ------------- | ------------- |
| First Response | 2 days |
| Time to Triage | 2 days |
| Time to Resolution | depends on severity and complexity |

Once a vulnerability has been verified, we will make a best effort to remediate within the following timelines:

| Severity Rating | Resolution Target |
|:-:|:-:|
| Critical | 14 days |
| High | 30 days |
| Medium | 60 days |
| Low | 90 days or accepted risk |

Please note that the severity rating for a reported vulnerability may be adjusted by strongDM in line with our Vulnerability Management Program. We’ll try to keep you informed about our progress throughout the process.

# Program Rules
1. Research only that which is "in-scope" or "allowed", without using any of the [Prohibited Methods][prohibited-methods] listed below
1. Follow HackerOne's [disclosure guidelines](https://www.hackerone.com/disclosure-guidelines)
1. Communicate with us only by the methods provided by HackerOne
1. Please provide detailed reports with reproducible steps. If the report is not detailed enough to reproduce the issue, the issue may not be marked as triaged.
    1. Submit one vulnerability per report, unless you need to chain vulnerabilities to provide impact
    1. Multiple vulnerabilities caused by one underlying issue will be treated as one valid report.
    1. When duplicates occur, we only triage the first report that was received (provided that it can be fully reproduced).
1. Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service. Only interact with accounts you own or with explicit permission of the account holder.
1. Ensure any data exposed is kept to a minimum, not stored, and treated as confidential at all times;
1. Do not destroy or alter data discovered during your research
1. Do not publicly or privately disclose any vulnerabilities [existing or remediated] discovered during your research to anyone other than strongDM and HackerOne

# VDP Scope

## In-Scope Assets
### Domains
Any strongDM-owned domains _not_ listed below are not in scope and _not_ covered by our legal safe harbor
- `app.strongdm.com`
- `api.strongdm.com`
- `*.sdm.network`

### Software Development Kits
strongDM provides software development kits to its customers to speed integrations. Our four SDKs are available in public GitHub repositories linked below:
- [Go](https://github.com/strongdm/strongdm-sdk-go)
- [Ruby](https://github.com/strongdm/strongdm-sdk-ruby)
- [Python](https://github.com/strongdm/strongdm-sdk-python)
- [Java](https://github.com/strongdm/strongdm-sdk-java)

### Installed Applications (Executables)
Part of the strongDM Platform includes local client and gateway server applications. These are

- Client Applications
  - [macOS](https://www.strongdm.com/docs/user-guide/client-installation/mac-installation)
    - x86/x64 (Intel)
    - ARM (Apple M1)
  - [Windows](https://www.strongdm.com/docs/user-guide/client-installation/windows-installation)
    - x86/x64 (Intel)
    - ARM
  - [Linux CLI](https://www.strongdm.com/docs/user-guide/client-installation/linux-installation)
- Gateway Applications
  - [Linux](https://www.strongdm.com/docs/installation/install-your-gateway/linux-gateway)
  - [Docker/Kubernetes/Fargate Container](https://www.strongdm.com/docs/installation/install-your-gateway/docker-gateway)

### Out-of-Scope Assets
- Any domain owned by strongDM not specifically listed above, including:
  - `www.strongdm.com`
- Any SaaS applications used by strongDM for business operations, such as Slack, Google Workspace, Zoom, etc.

### Out-of-Scope vulnerabilities
**When reporting vulnerabilities, please consider (1) attack scenario/exploitability, and (2) security impact of the bug. The following issues are considered out of scope:**

* Any activity that could lead to the disruption of our service (DoS)
* Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.)
* Tabnabbing
* Clickjacking on pages with no sensitive actions
* Cross-Site Request Forgery (CSRF) on unauthenticated forms or forms with no sensitive actions
* Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS
* Open redirect unless an additional security impact can be demonstrated
* Issues that require unlikely user interaction
* Attacks requiring MITM or physical access to a user's device
* Vulnerabilities only affecting users of outdated or unpatched browsers [Less than 2 stable versions behind the latest released stable version]
* Previously known vulnerable libraries without a working Proof of Concept
* Comma Separated Values (CSV) injection without demonstrating a vulnerability
* Misconfigurations on third-party applications/widgets on any domain, unless there is immediate and verifiable confidential data disclosure (e.g. you can actually see the confidential information, not just theoretically gain access)

## Prohibited Methods
The following methods are prohibited and considered out-of-scope:  

1. Posting, uploading, linking to, or storing any malicious software or programs
1. Physical security testing of office and/or data center access (e.g. open doors, tailgating)
1. Social engineering of our employees or customers (e.g. phishing, vishing, smishing)
1. Knowingly executing or attempting to execute any destructive or Denial of Service attacks
1. Targeting out of scope applications
1. Targeting our customers users, administrators, or infrastructure in any way

## What Should Not be Submitted
Please do not send any of the following information to us:

- Personally Identifiable Information for persons other than yourself;
- Private Health Information;
- Credit Card Information of any type (PAN, CCV/CVN, etc.);

[disclosure-policy]: #user-content-disclosure-policy
[safe-harbor]: #user-content-safe-harbor
[response--remediation-targets]: #user-content-response--remediation-targets
[program-rules]: #user-content-program-rules
[prohibited-methods]: #user-content-prohibited-methods
[what-should-not-be-submitted]: #user-content-what-should-not-be-submitted
[out-of-scope-vulnerabilities]: #user-content-out-of-scope-vulnerabilities
