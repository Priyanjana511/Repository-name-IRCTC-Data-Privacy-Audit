# Repository-name-IRCTC-Data-Privacy-Audit

## 1. Aim
To conduct a privacy-focused assessment of publicly available information about IRCTC's data collection and handling practices, identify potential privacy vulnerabilities and risks, and propose appropriate privacy controls and recommendations.
## 2. Objectives
Identify the categories of personal data collected.
Determine the stated purposes for collecting personal data.
Examine how data is used, stored, shared, and retained where publicly documented.
Identify potential privacy vulnerabilities and risks.
Examine publicly documented privacy and security controls.
Assess transparency and user privacy practices.
Recommend measures to reduce identified privacy risks.

## 3. Audit Areas
I'd use:
Data collection
Purpose of data collection
Data minimisation
Data usage
Data sharing and third parties
Data storage
Data retention
User consent and transparency
User privacy rights
Account security
Payment-related information
Cookies/tracking
Data breach/privacy incident risks
Privacy policy
Third-party/vendor risks
You don't have to find a vulnerability in every area. Some areas may simply be marked "No sufficient public evidence available".

## 4. Data Inventory

| Data Category | Example | Purpose | Source | Potential Privacy Risk |
|---|---|---|---|---|
| Identity Data | Name | Service/account identification | S01 | Identity exposure |
| Contact Data | Email, mobile number | Communication and service delivery | S01 | Phishing/contact exposure |
| Passenger Data | Passenger details | Ticket booking and reservation | S01 | Personal-data exposure |
| Transaction Data | Booking and payment-related information | Transaction processing | S01 | Financial/privacy exposure |

## 5. Privacy risks identified
For each risk, use a consistent format:

Risk ID: PR-01
Area: Data retention

Observation: Publicly available documentation does not clearly establish [whatever you actually find].

Potential risk: Personal information could be retained longer than necessary if appropriate retention controls are not established.

Impact: Increased exposure in the event of unauthorised access or disclosure.

Evidence: S01 / Screenshot-03

Recommendation: Clearly define and communicate applicable retention periods and implement appropriate deletion/archival controls.

This is much better than simply writing:

"IRCTC has poor data retention."

You're distinguishing evidence → risk → recommendation.

## 6. Privacy controls
Separate this from risks.
For example:

Control	Area	Evidence	Status
Privacy policy	Transparency	S01	Documented
Authentication	Account security	S02	Publicly observable/documented
Access controls	Internal data access	—	Not independently verifiable
Data retention controls	Retention	S01	Evidence requires further review

Use "Not independently verifiable" when you're dealing with internal controls you cannot inspect.

## 7. Key findings
For example:
Several categories of personal information are involved in railway booking/service delivery.
Personal data creates risks if exposed, misused, or retained unnecessarily.
Some controls can be identified from publicly available documentation.
Internal technical and organisational controls cannot be independently verified through a public-source assessment.
Areas requiring greater transparency or additional controls were identified.
Your actual findings should be based on your research.

## 8. Recommendations
Connect every significant recommendation to a finding.

Finding/Risk	Recommendation
Data minimisation concern	Review whether each collected data element is necessary
Retention transparency concern	Clearly communicate applicable retention periods
Third-party risk	Strengthen vendor privacy assessments and contractual controls
Transparency concern	Improve clarity of privacy notices
Account security risk	Encourage strong authentication and account-security measures

## 9. Ethical scope
State that:
The audit is educational/research-oriented.
The assessment relies primarily on publicly available information.
No unauthorised access was attempted.
No attempt was made to bypass authentication or security mechanisms.
No real customer data was intentionally collected.
No personal information belonging to other users was accessed.
Screenshots containing personal information are not published.
Findings represent the evidence available during your assessment period.

## 10. Limitations
For example:
This assessment is based primarily on publicly available information and therefore cannot independently verify IRCTC's internal databases, security architecture, access-control mechanisms, employee procedures, vendor contracts, retention systems, or incident-response processes.
Also say:
The assessment should not be interpreted as a formal legal compliance assessment, penetration test, or official IRCTC security audit.

## 11. Potential Vulnerabilities and Risks
## Potential Vulnerabilities and Risks

| Risk ID | Area | Potential Vulnerability / Risk | Potential Impact | Recommended Control |
|---|---|---|---|---|
| PR-01 | Data Collection | Collection of more personal information than necessary for a specific service | Increased privacy exposure | Apply data minimisation and regularly review data requirements |
| PR-02 | Data Storage | Personal information may remain exposed if retention and deletion controls are not appropriately implemented | Increased impact if data is compromised | Define appropriate retention and secure deletion procedures |
| PR-03 | Data Sharing | Personal information shared with third parties may create additional privacy risks | Unauthorised use or disclosure | Strengthen third-party due diligence and contractual privacy controls |
| PR-04 | Account Security | Compromised user credentials could expose account and booking information | Account takeover and personal-data exposure | Strong authentication, monitoring and user security guidance |
| PR-05 | Phishing | Personal/contact information may increase exposure to targeted phishing attempts | Credential theft or fraud | User awareness, anti-phishing controls and security notifications |
| PR-06 | Payment Data | Transaction-related information requires appropriate protection throughout processing | Financial or personal-data exposure | Apply appropriate payment-security and access controls |
| PR-07 | Transparency | Users may not always have sufficient clarity about how their information is processed | Reduced user awareness and control | Provide clear, accessible and updated privacy notices |
| PR-08 | Data Access | Inappropriate internal access to personal information could create privacy exposure | Unauthorised disclosure or misuse | Role-based access control, logging and periodic access reviews |
| PR-09 | Data Breach | A security incident could expose passenger or account information | Identity theft, fraud or other privacy harms | Incident detection, response, notification and recovery procedures |
| PR-10 | Third-Party Services | External service providers can introduce additional privacy and security dependencies | Data leakage or misuse through third parties | Vendor risk assessments and ongoing third-party monitoring |

## 12. Risk assessment table
## Risk Assessment

| Risk ID | Likelihood | Impact | Overall Risk | Rationale |
|---|---|---|---|---|
| PR-01 | Medium | High | High | Large amounts of personal information can increase exposure |
| PR-02 | Medium | High | High | Long-term retention can increase consequences of compromise |
| PR-03 | Medium | High | High | Third-party processing introduces additional dependencies |
| PR-04 | Medium | High | High | Account compromise could expose user information |
| PR-05 | High | Medium | High | Phishing is a common threat to online-service users |
