
## Security

Rhosys protects data with encryption in transit and at rest, providing organization-wide protection by delegation to trusted authentication providers.

## Privacy

Data privacy is a human right:
* [Authress Privacy Policy](https://authress.io/app/#privacy)
* [Teaminator Privacy Policy](https://app.teaminator.io/#privacy)
* [Standup and Prosper Privacy Policy](https://standup.teaminator.io/app/#/privacy)

### Data Protection Officers

Oversight of Data Security is handled by Rhosys respective Data Protection Officers. Should you wish to make modifications, deletions or additions to any personal data you believe to be captured by Rhosys, or if you have any general security concern, please contact our **Data Protection Officer (DPO)** at the following email address: [security@rhosys.ch](mailto:security@rhosys.ch)

## Compliance

We strive to maintain consistent and auditable security practices. These are always best-in-class practices. While we do not maintain an independently certified security controls certification, we do operate within an information security control framework, to insure that relevant security practices are followed in all aspects without individual certifications. We do this by collecting the requirements from SOC 2 and adding in additional requirements from other frameworks. Together these influence this document as well as establish our [security practices](./Security-Practices.md).

## Common Security Related Questions for Enterprises

### Governance

1. Do you maintain a quality management system (QMS) approved by management?
In lieu of a formal and static QMS, Rhosys has a dynamic and responsive approach to quality management.
Does your quality management system (QMS) include coverage for software application security principles?
   - YES

1. Is quality management system (QMS) content published and communicated to all relevant employees?
   - YES.

1. Is quality management system (QMS) content reviewed and updated (if appropriate) at least once per year?
   - As all documents and materials it is considered a constant Work In Progress, and is updated as soon as necessary.

1. Is there defined management oversight who is responsible for application quality and security reporting & signoff?
   - YES. Our teams under go our Code Review Process via our collaboration tools. These procedures are followed and provide necessary reporting and signoff. Quality is a responsibility of every employee.

1. Is access to and maintenance of applications, systems, network components (including routers, databases, firewalls, voice communications servers, voice recording servers, etc), operating systems, virtualization components, hypervisors, or other information objects restricted to authorized personnel only?
   - YES

1. Is access to and maintenance of applications, systems, network components (including routers, firewalls, voice communications servers, voice recording servers, voice response units (VRU) etc), operating systems, virtualization components, hypervisors, or other information objects granted based upon need-to-know job function?
   - YES

1. For all IT systems including but not limited to servers, routers, switches, firewalls, databases, and external social spaces, is management approval required prior to creating all user and privileged accounts (e.g., system or security administrator)?
   - YES

1. For all IT systems including but not limited to servers, routers, switches, firewalls, databases are privileged accounts (e.g., system or security administrator) logged at all times and reviewed on at least a quarterly basis?
   - YES

1. Are all user accounts (including, but not limited to, standard user, system administrator, security administrator, internal social spaces, etc) assigned to an individual employee and not shared?
   - YES

1. Are all user accounts disabled after no more than ten unsuccessful logon attempts?
   - YES. All user accounts are controlled through delegation of Google G Suite and other authentication providers, which have rigorous fraudulent protection mechanisms in place. We do not directly control these as they are configurable by the responsible organization.

1. For all IT systems (including but not limited to servers, routers, database, switches, firewalls, external social spaces), are inactive user and privileged accounts (e.g., system administrator or security administrator) disabled after 90 days or more?
   - YES

1. Is a user's identity verified before communicating an initial/temporary password or initiating a password reset by an automated or manual process?
   - YES

1. Do application, system, and device passwords (including routers, firewalls, databases, and external social spaces) require passwords to have the following characteristics: 1. minimum length of 8 characters, 2. chosen from any acceptable character sets available on the target system, 3. includes at least one alphabetic and one numeric character.)
   - YES

1. Are passwords prevented from being displayed in clear text during user authentication or in electronic/printed reports?
   - YES

1. Are passwords/PINs sent to users utilizing a secure method (e.g. secure e-mail) and sent separately from other authentication information such as the user account?
   - YES

1. For all IT systems (including but not limited to servers, routers, databases, switches, firewalls), are user and privileged account (e.g., system or security administrator) passwords changed at least every 90 days?
   - YES

1. Are users required to authenticate prior to changing their password?
   - YES

1. Are all system, application and device password files encrypted using an industry standard encryption algorithm where technically feasible?
   - YES

1. In instances where a software token is used to access an application or system, is a password or PIN required?
   - YES

1. In instances where a software token is used to access an application or system, are stored keys and software token files encrypted using an industry standard algorithm and smartcards compliant to FIPS level 2 or above?
   - YES

1. For externally hosted environment, is there separation of administrative access between the hosting infrastructure/platform and the hosted platform and data?
   - YES

1. If user accounts are assigned to non-permanent personnel (e.g., contractors, consultants)  for troubleshooting purposes, are the accounts disabled or removed after each use?
   - YES

1. Is the retirement or replacement of encryption keys included in key management procedures when the integrity of the key has been weakened (such as departure of an employee with key knowledge) or keys are suspected of being compromised?
   - YES

1. If you use cloud services, do you ensure that confidential data or an aggregation of proprietary information that can reveal confidential information is encrypted to ensure confidentiality at rest and in transit?
   - YES

1. If you use cloud services, do you have key management procedures to manage and maintain encryption keys?
   - YES

### Software Development Life Cycle (SDLC)

1. Are there documented processes, procedures, standards and templates used in your SDLC process?
   - YES.

1. Do the materials above include references to application security best-practices and principles being followed?
   - YES.

1. Are design and code reviews performed as part of your SDLC processes?
   - YES.

1. Are security considerations (checklists, standards and policies) referenced in the design and code review?
   - YES.

1. Is app security threat modeling performed when deemed appropriate (i.e. new or changed architectures and approaches)?
   - NO.

1. Is application code managed in a secure configuration management system with access controls?
   - YES.

1. Is there a configuration management plan and are release artifacts maintained in a configuration management system?
   - YES.

1. Are test plans and records kept that reflects the tests performed and results observed for each release?
   - YES.

1. Is security testing defined and included in the test plan for each release?
   - YES. As with all testing, security is tested via our SDLC via detailed and documented test cases.

1. Is a release criteria defined, measured and reported on to confirm targeted release quality is achieved?
   - YES. We do automated and manual QA for each new deployment for all versions deployed.

1. Are specific application security characteristics and measures part of the defined release criteria?
   - NO.

1. Do you work with third parties that may have access to your IP and sensitive data?
   - NO. Except where contractors are concerned and in those cases they have access only to the data which they need to operate and have verified to follow the guidelines here.

1. If so, is access to data controlled by terms of Non-Disclosure Agreements?
   - YES

### Training

1. Is Internal company training available & performed commensurate with personnel roles and responsibilities?
   - YES; peer-to-peer training is commonplace.

1. Does training include security awareness?
   - YES; as applicable for the role.

1. Does training include education on policies, standards, procedures and updates when needed?
   - YES; as applicable.

1. Are personnel training plans and records kept for internal company compliance purposes?
   - YES.

### Enterprise Protection

1. Is antivirus protection enabled on endpoints?
   - NO. Any Antivirus solution suggests that there are non-vulnerable devices able to access secure data. Instead Rhosys exists using a Zero-Trust framework, where all external devices are considered vulnerable by default. All sensitive information is protected from external devices. Elevated access is given progressively to authenticated connected devices, and are verified by the device management strategy.

### Validation

1. Are results from the execution of test plans reported and used to track and justify release readiness?
   - YES. We require all automated and manual tests to pass before any deployment of code.

1. Does the quality assurance organization have authority to delay shipment of releases due to non-conformance reasons?
   - YES.

1. Is some form of static code scanning performed as part of the release acceptance? What tools are used?
   - YES. For example, [ESLint](https://eslint.org/), [Snyk](https://app.snyk.io/account), and [GitLab](https://docs.gitlab.com/ee/user/application_security/dependency_scanning/) which are part of our test suite and alert us to any security issues in our libraries.

1. Is some form of dynamic code scanning performed as part of the release acceptance? What tools are used?
   - YES. We use GitLab CI for this purpose.

### Security Response

1. Do you have a documented company security incident response process?
   - NO

1. Do your maintenance releases include fixes for both quality and security related issues?
   - YES.

1. Do you provide dedicated security patches for software versions that are released and supported in the field? How?
   - YES. via standard deployment mechanisms. We create updated versions for used libraries and deploy them to the release repositories.

1. Is there proactive notification provided to customers and software partners (PTC)?  How?
   - YES. Notifications in form of--blog posts, tweets, a mailing list, and Slack user support workspace. Depending on the issue we may use any or all of these.

1. Do you have a formal risk severity classification assessment approach?
   - NO.

1. Is there a specified response policy that includes the timeframe issues are to be addressed?
   - NO.
