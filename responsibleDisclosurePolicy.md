# Responsible Disclosure Policy
## Requirements to Follow
1. strongDM requires that those submitting vulnerabilities through this Responsible Disclosure Policy:

    - Research only that which is "in-scope" or "allowed", as defined below;
    - Communicate to us only by the methods described in the “How to Send Us a Report” section below;
    - Keep any information about vulnerabilities you’ve discovered confidential between yourself and strongDM for at least 90 days;
    - Ensure any data exposed is kept to a minimum, not stored, and treated as confidential at all times;

## Requests for Compensation
1. This Responsible Disclosure Program is _not_ a bug bounty program, and strongDM does not provide monetary compensation for reported vulnerabilities.

1. Vulnerability Reporters who request monetary compensation, either before or after submission, will be considered non-compliant with the requirements of this policy, and will not be afforded the protections defined in [strongDM's Commitments](#strongdms-commitments).

## strongDM's Commitments
1. As long as a vulnerability reporter follows the requirements defined in this policy, strongDM makes the following commitments:

    - We will not pursue civil or criminal legal action against a vulnerability reporter in response to vulnerability research and disclosure to us;
    - We will work with the vulnerability reporter to understand and reproduce the vulnerability that has disclosed to us;
    - We will keep the vulnerability reporter informed of our timeline for fixing the submitted vulnerability once we have verified it;
    - We will recognize the vulnerability reporter on our website for their contributions toward making our product more secure;
    - We may allow the vulnerability reporter to publicly disclose the vulnerability and their research methods _after_ the vulnerability has been fixed, subject to strongDM’s explicit written consent;
    - We will send the vulnerability reporter a custom strongDM Vulnerability Reporter t-shirt;

## Defining the Scope
### Allowed Targets
1. The following targets are considered to be "in-scope" or allowable under the provisions of this Responsible Disclosure Policy:

    - The strongDM Marketing website located at `https://www.strongdm.com`
    - The strongDM Web Application located at `https://app.strongdm.com`
    - The strongDM client applications
        - macOS
        - Windows
        - Linux
    - The strongDM gateway/relay application

### Prohibited Methods
1. The following methods are prohibited and considered out-of-scope:  

    - Posting, uploading, linking to, or storing any malicious software or programs;
    - Physical security testing of office and/or data center access (e.g. open doors, tailgating);
    - Social engineering of our employees or customers (e.g. phishing, vishing);
    - Knowingly executing or attempting to execute any destructive or Denial of Service attacks;
    - Targeting applications or systems not specifically listed in the __[Allowed Targets](#allowed-targets)__ section of this policy;

## Submitting Vulnerabilities
### What Should be Submitted
1. Please forward as much of the following to our Security Team as you have available:

    - The asset or target that is subject to the vulnerability you are disclosing;
    - A brief summary of the vulnerability you are disclosing;
    - Detailed steps so that we can assess and reproduce the vulnerability on our own to verify it, or enough information to demonstrate the potential vulnerability (in the event it might be destructive or a denial of service type of vulnerability);
    - Any scripts or environment information that would be helpful in reproducing the vulnerability;
    - If the vulnerability results in sensitive information disclosure, please describe the type (but not content) of the sensitive information disclosed;

### What Should Not be Submitted
1. Please do not send any of the following information to us:

    - Personally Identifiable Information for persons other than yourself;
    - Private Health Information;
    - Credit Card Information of any type (PAN, CCV/CVN, etc.);

### How to Send Us a Report
1. strongDM's Security Team keeps a public GitHub repository with instructions and templates for creating vulnerability reports located at `https://www.github.com/strongdm/security`

1. Vulnerability Reporters should refer to the GitHub repository for the most up to date methods for securely submitting reports to strongDM

## What Comes Next
1. The strongDM Security Team will respond with an acknowledgement of receipt of submitted vulnerabilities within 3 business day

1. The strongDM Security Team will work with internal stakeholders, and the Vulnerability Reporter as needed, to reproduce and verify the submitted vulnerability

1. The strongDM Security Team will work with internal stakeholders to develop a timeline for remediation, accounting for the severity of the vulnerability, availability of exploit code, and internal workloads. The timeline for remediation will be communicated to the Vulnerability Reporter

1. After a reported issue has been remediated, strongDM will follow up with the Vulnerability Reporter to ensure they are aware of the fix, discuss public disclosure of the vulnerability, and discuss details for public recognition on strongDM's website

### Remediation Timelines
1. Consistent with strongDM's internal policies on vulnerability remediation, strongDM will strive to resolve all reported vulnerabilities within the following timelines, subject to verification and reproduction of the vulnerability, and strongDM making an independent assessment of the criticality:

| Rating | Deadline |
|:-|:-|
| Critical | 14 days |
| High | 30 days |
| Medium | 60 days |
| Low | 90 days |

# Definitions
Within this document, the following definitions apply:

i. *Availability*: Ensuring timely and reliable access to and use of information

i. *Auditability*: Ability to independently review or examine the records and activities of a system to assess the adequacy of system controls, and ensure compliance with established policies, and attribute all actions on a system to a unique account or process.

i. *Confidentiality*: Preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information

i. *Integrity*: Guarding against improper information modification or destruction, and includes ensuring information non-repudiation and authenticity

i. *Reporters*: Any person who, through this Policy, submits a report of a potential vulnerability to strongDM

i. *Security Team*: The employees of strongDM who are responsible for ensuring the confidentiality, integrity, availability, and auditability of all information systems that process, store, or handle strongDM data

i. *System Owners*: The person or role that is responsible for implementing and maintaining an information system

i. *Vulnerability*: Weakness in an information system, system security procedures, internal controls, or implementation that could be exploited or triggered by a threat source
