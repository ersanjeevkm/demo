Initializing Sales Analysis Agent...
Your question: get summary of last call  

Processing your query...
SELECT filename FROM calls ORDER BY created_at DESC LIMIT 1
3_objection_call.txt

============================================================
Tool Used: SUMMARIZE
============================================================

Summary of 2 call(s):

1. 3_objection_call.txt:
### Sales Call Summary

**1. Call Purpose and Agenda:**
- **Purpose:** To address security, privacy, and legal concerns to facilitate moving forward with the pilot.
- **Agenda:**
  1. Data residency & encryption
  2. Retention & deletion
  3. Sub-processors & compliance
  4. Roadmap clarifications
  5. Next steps

**2. Key Discussion Points:**
- **Data Residency:** Customer data is stored in AWS ap-south-1 (Mumbai) by default, with an option for EU residency in eu-central-1 (Frankfurt).
- **Encryption:** Data is encrypted using AES-256 at rest and TLS 1.3 in transit. Support for customer-managed keys is available.
- **Retention Policies:** Default retention is 90 days, with options for immediate deletion and API access for specific call IDs.
- **Sub-processors:** The company uses AWS, OpenAI, and Sentry, with strict data handling protocols.
- **Compliance:** The company is SOC 2 Type II compliant, with an independent pen-test completed.
- **PII Redaction:** Automatic redaction of sensitive information before storing transcripts.
- **Roadmap:** Hindi diarization is expected to be in GA by Q3, with Slack push notifications already in GA.
- **Logging and Privacy:** IP addresses are recorded in audit logs, with options for truncation upon request.

**3. Customer Concerns or Objections Raised:**
- **Data Residency and Backup:** Clarification on disaster recovery options and cross-region replication.
- **Retention Extensions:** Ability to extend retention for specific workspaces for legal discovery.
- **Sub-processor Data Handling:** Concerns about data sent to OpenAI and fallback options for local processing.
- **Performance Guarantees:** Questions about accuracy and potential clawbacks if performance metrics are not met.
- **Privacy Compliance:** Need for additional documentation regarding compliance with India’s DPDPA.

**4. Next Steps or Commitments Made:**
- **Elena** to share the SOC 2 report and pen-test summary.
- **Elena** to provide the DPA with India addendum.
- **Jordan** to draft a contractual service level agreement (SLR) for Slack and Hindi diarization with a 10% credit clause.
- **Priya** to schedule an IT review of SSO for the following Tuesday.
- **Elena** to provide sample deletion logs for DSR proof and resend the CSA STAR Level 1 questionnaire.

**5. Overall Call Sentiment and Outcome:**
The call was productive and collaborative, with all parties engaged and addressing concerns effectively. The prospects expressed satisfaction with the solutions offered and the flexibility of the product. The call concluded with a clear path forward, aiming for a green light on the 25-seat pilot by June 30.

2. 3_objection_call.txt:
Error summarizing 3_objection_call.txt: unsupported operand type(s) for +=: 'float' and 'NoneType'

Files Processed: 2

Sources:
   1. Source: 3_objection_call.txt (Full transcript)

------------------------------------------------------------

Your question: get summary of last two calls

Processing your query...
SELECT filename FROM calls ORDER BY created_at DESC LIMIT 2
3_objection_call.txt
2_pricing_call.txt

============================================================
Tool Used: SUMMARIZE
============================================================

Summary of 4 call(s):

1. 3_objection_call.txt:
### Sales Call Summary

**1. Call Purpose and Agenda:**
- **Purpose:** To address security, privacy, and legal concerns in order to move the pilot forward.
- **Agenda:**
  1. Data residency & encryption
  2. Retention & deletion
  3. Sub-processors & compliance
  4. Roadmap clarifications
  5. Next steps

**2. Key Discussion Points:**
- **Data Residency:** Customer data is stored in AWS ap-south-1 (Mumbai) by default, with an option for EU residency in eu-central-1 (Frankfurt).
- **Encryption:** Data is encrypted at rest using AES-256 and in transit with TLS 1.3. Support for customer-managed keys (CMK) is available, with a roadmap for Bring Your Own Key (BYOK) in Q4.
- **Retention & Deletion:** Default retention is 90 days, with options for 30, 60 days, or immediate deletion after processing. An API is available to override retention for specific call IDs.
- **Sub-processors:** Three sub-processors are used: AWS, OpenAI, and Sentry, with strict data handling policies.
- **Compliance:** The company is SOC 2 Type II compliant, with a recent pen-test completed by NCC Group.
- **PII Redaction:** Automatic redaction of sensitive information before storing transcripts.
- **Roadmap Items:** Hindi diarization expected by Q3 and Slack push notifications for call summaries available from July 15.
- **Sandbox Environment:** A free sandbox with 10 seats is offered for testing.

**3. Customer Concerns or Objections Raised:**
- Questions regarding data residency and disaster recovery options.
- Clarifications on encryption methods and key management.
- Concerns about retention policies and the ability to extend retention for legal discovery.
- Inquiry about the accuracy of local models compared to OpenAI.
- Request for additional compliance documentation, including DPA addendums and deletion logs for proof of GDPR compliance.

**4. Next Steps or Commitments Made:**
- Elena will share the SOC 2 report and pen-test summary.
- Elena will provide the DPA with the India addendum.
- Jordan will draft a contractual Service Level Requirement (SLR) for Slack and Hindi diarization with a 10% credit clause.
- Priya will schedule an IT review of Single Sign-On (SSO) for the following Tuesday.
- Additional requests include sample deletion logs and a CSA STAR Level 1 questionnaire.

**5. Overall Call Sentiment and Outcome:**
- The call was constructive and collaborative, with all participants actively engaging in discussions. 
- The outcome was positive, with a clear path forward established for the pilot, contingent on the completion of the IT review and document sign-off by June 30.

2. 3_objection_call.txt:
Error summarizing 3_objection_call.txt: unsupported operand type(s) for +=: 'float' and 'NoneType'

3. 2_pricing_call.txt:
### Sales Call Summary

**1. Call Purpose and Agenda:**
The purpose of the call was to discuss pricing structures, discount options, and competitive positioning against Competitor X and Competitor Y. Participants included members from the sales, RevOps, finance, and pricing strategy teams. The call was structured to last 90 minutes but aimed to conclude sooner if discussions remained focused.

**2. Key Discussion Points:**
- **Pricing Overview:** Maya presented the pricing tiers: Growth at ₹1,800/user/mo, Pro at ₹2,400/user/mo, and Enterprise at ₹2,950/user/mo, with specific features and limitations outlined for each.
- **Competitive Comparison:** Dan raised concerns regarding Competitor X's pricing and features, specifically their flat rate and unlimited minutes. AE explained the differences in service offerings, including additional features provided by their product.
- **Total Cost of Ownership (TCO):** Maya shared a detailed TCO analysis comparing their offering with Competitor X, highlighting cost spikes and flat pricing over three years.
- **Discount Structure:** Maya outlined potential discounts, including logo discounts, volume discounts, and term discounts, with a maximum stacking cap of 18%.
- **Customer Concerns:** Dan expressed concerns about budget recognition and the need for a competitive headline number. He also mentioned the CFO's preference for clean rates without ramp discounts.

**3. Customer Concerns or Objections Raised:**
- Competitor X's pricing and features were perceived as more attractive due to a lower rate and unlimited minutes.
- The need for a competitive discount structure to match or exceed offers from Competitor Y.
- Concerns about budget recognition and the implications of ramp discounts on financial reporting.
- The necessity for dedicated customer success management (CSM) to be included at no extra cost.

**4. Next Steps or Commitments Made:**
- Maya will draft an order form reflecting 120 seats (96 Growth, 24 Pro) with a 20% net discount, a 4% renewal cap, and additional commitments for early-access Slack and Hindi diarization.
- The inclusion of dedicated CSM at no charge for the pilot and first renewal cycle was agreed upon.
- Legal will be looped in for Master Service Agreement (MSA) redlines, and the TCO sheet will be sent to the customer for CFO review.
- A DocuSign will be prepared and sent within two hours to finalize the agreement.

**5. Overall Call Sentiment and Outcome:**
The call had a positive and collaborative sentiment, with both parties actively engaging in discussions to address concerns. The outcome was a commitment to draft a formal agreement that aligns closely with the customer's needs while addressing competitive pricing pressures. The session concluded with mutual appreciation for the partnership and a clear path forward.

4. 2_pricing_call.txt:
Error summarizing 2_pricing_call.txt: unsupported operand type(s) for +=: 'float' and 'NoneType'

Files Processed: 4

Sources:
   1. Source: 2_pricing_call.txt (Full transcript)
   2. Source: 3_objection_call.txt (Full transcript)

------------------------------------------------------------
