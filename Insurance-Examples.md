# Insurance Industry Use Cases

Demo Link(<https://claude.site/artifacts/42b3fdd6-524a-4fd7-98ac-a5c8c6cda2da>)


- **Scenario**: AI processes claims, risk assessments, and customer support inquiries.
- **Action**: Detects attempts to manipulate AI-generated claims processing or fraudulent risk assessments.
- **Outcome**: Strengthens fraud prevention and ensures fair, unbiased AI-driven decision-making in insurance claims and underwriting.

- **Scenario**: Insurance employees use AI to review customer policies and claims.
- **Action**: Identifies when sensitive personal or health information is inadvertently exposed in AI-generated responses.
- **Outcome**: Prevents unauthorized sharing of personal data and strengthens data privacy compliance.

![Screenshot 2025-03-18 at 22.29.16.png](<https://media-hosting.imagekit.io//e47b911d38fb4c74/Screenshot%202025-03-18%20at%2022.29.16.png?Expires=1836941929&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=ZXKKBhX0262uyrHnWjkI-FGlWLd5MjmGUrzTt~8nCli-Kseib33X9NTTPBFgmgWx-82DELuUoPYAUNcXzRWp2G40-a7aca8JfzPV8yQ14YgH03He8NoaNTOUf99rhp3nHyQszlKdLRz6Ld9-mN-dVjlsEMoV9AjWuEy8RlU3DgB3e2ff3i8HdYvPDF2ChQIDlzDC~TJIa0QwhI22HlXxakkUbSidzeIdaDo4VXrFkhrZhTw9IgX5Jzf1LfOBmRQG5G4VWIBYn0i-wRKqgctX3gf~cxBqWMXQDXBLqt1e~9e6ZpWY22Pjuxxh4DHd5XBXFFZVzgIQBc9R7neTJnKAAQ__>)

## Examples:

⸻

### Example 1: Insurance Claim Investigation

Prompt (Without Anonymisation):

“I am investigating an insurance claim for our client, Michael Roberts, who is 42 years old and resides at 456 Elm Street, Los Angeles, CA. He filed a claim for property damage caused by a fire at his residence on 12/10/2023. The insurance policy covers up to $500,000, but the insurer is disputing the claim due to potential negligence. Could you provide insights on how to assess liability in this situation?”

Sensitive Information in This Prompt:

1. Full Name: “Michael Roberts”
2. Age: “42 years old”
3. Address: “456 Elm Street, Los Angeles, CA”
4. Claim Details: Specific date, claim amount, and liability dispute

Privacy Risks:

This prompt includes personally identifiable information (PII) about the client and case specifics that could compromise confidentiality.

Revised Prompt (With Anonymisation):

“I am investigating an insurance claim for a client involving property damage caused by a fire at their residence. The policy covers up to a significant amount, but the insurer is disputing the claim due to potential negligence. Could you provide insights on how to assess liability in such cases?”

⸻

### Example 2: Health Insurance Coverage Dispute

Prompt (Without Anonymisation):

“Our policyholder, Emily Carter, aged 29, living in Chicago, IL, was recently denied coverage for a medical procedure deemed medically necessary by her doctor. Her insurance plan explicitly states that the procedure is covered, but the provider claims it falls under an exclusion clause. The cost of the procedure is $15,000. What are the best approaches to appealing this decision?”

Sensitive Information in This Prompt:

	1.	Full Name: “Emily Carter”
	2.	Age: “29”
	3.	Location: “Chicago, IL”
	4.	Medical Condition & Procedure Details: Specific coverage dispute

Privacy Risks:

This prompt includes personal health details and financial information that should be anonymised.

Revised Prompt (With Anonymisation):

“A policyholder was recently denied coverage for a medical procedure deemed necessary by their doctor. Their insurance plan states the procedure is covered, but the provider claims it falls under an exclusion clause. The cost of the procedure is significant. What are the best approaches to appealing such a decision?”

⸻

### Example 3: Auto Insurance Fraud Investigation

Prompt (Without Anonymisation):

“We are reviewing a suspicious auto insurance claim from a client, John Miller, 37 years old, residing in Houston, TX. He reported a car accident on 02/15/2024, claiming $30,000 in damages. However, discrepancies in the police report suggest potential fraud. How should we proceed with the investigation?”

Sensitive Information in This Prompt:

	1.	Full Name: “John Miller”
	2.	Age: “37 years old”
	3.	Address: “Houston, TX”
	4.	Claim Details: Date, amount, and fraud suspicion

Privacy Risks:
This prompt exposes the policyholder’s identity and a potential fraud investigation, which should remain confidential.

Revised Prompt (With Anonymisation):
“We are reviewing a suspicious auto insurance claim where the reported accident details do not align with the police report. The claim amount is significant. How should we proceed with the investigation to assess potential fraud?”

⸻

### Example 4: Home Insurance Coverage Dispute

Prompt (Without Anonymisation):

“Our client, David Thompson, a homeowner in Miami, FL, is disputing a denied home insurance claim after a hurricane caused significant roof damage on 09/20/2023. The insurer argues that the damage is due to ‘wear and tear’ rather than the storm, despite a contractor’s report stating otherwise. The repair costs are estimated at $75,000. What legal or procedural options are available to contest this denial?”

Sensitive Information in This Prompt:

	1.	Full Name: “David Thompson”
	2.	Location: “Miami, FL”
	3.	Claim Details: Date of incident, dispute specifics, and financial information

Revised Prompt (With Anonymisation):

“A homeowner is disputing a denied insurance claim after a hurricane caused significant roof damage. The insurer argues the damage is due to ‘wear and tear,’ despite a contractor’s report stating otherwise. The repair costs are substantial. What legal or procedural options are available to contest this denial?”

⸻

### Example 5: Landlord Insurance Claim for Tenant Damage

Prompt (Without Anonymisation):
“A landlord, Mark Evans, who owns a rental property in Denver, CO, has filed an insurance claim after tenants caused severe interior damage, including broken fixtures and vandalised walls, before vacating the unit on 03/10/2024. The insurer is offering only partial reimbursement due to policy exclusions. What strategies can the landlord use to maximise coverage for the claim?”

Sensitive Information in This Prompt:

	1.	Full Name: “Mark Evans”
	2.	Location: “Denver, CO”
	3.	Claim Details: Date, type of damage, and insurer’s position

Revised Prompt (With Anonymisation):
“A landlord has filed an insurance claim after tenants caused severe interior damage to a rental property, including broken fixtures and vandalised walls. The insurer is offering only partial reimbursement due to policy exclusions. What strategies can the landlord use to maximise coverage for the claim?”

⸻

### Example 6: Commercial Property Insurance Dispute

Prompt (Without Anonymisation):
“A commercial property owner, Lisa Brown, who operates a retail store in San Diego, CA, is facing an insurance dispute after storm-related flooding caused structural damage on 01/15/2024. The insurer is rejecting the claim, stating that the policy does not cover flood damage, despite the client having additional disaster coverage. What are the best legal or negotiation strategies to challenge the insurer’s decision?”

Sensitive Information in This Prompt:

	1.	Full Name: “Lisa Brown”
	2.	Business Location: “San Diego, CA”
	3.	Claim Details: Incident date, cause of damage, and insurer’s rejection

Revised Prompt (With Anonymisation):
“A commercial property owner is facing an insurance dispute after storm-related flooding caused structural damage. The insurer is rejecting the claim, stating that the policy does not cover flood damage, despite the owner having additional disaster coverage. What are the best legal or negotiation strategies to challenge the insurer’s decision?”

⸻

### Example 7: Real Estate Title Insurance Dispute

Prompt (Without Anonymisation):
“Our client, Jennifer Collins, purchased a home in Seattle, WA, but is now facing a title dispute after an undisclosed lien from a previous owner surfaced. The title insurance provider is refusing to cover legal costs, arguing that the issue was not disclosed at the time of purchase. How can the homeowner challenge the insurer and seek proper coverage?”

Sensitive Information in This Prompt:

	1.	Full Name: “Jennifer Collins”
	2.	Location: “Seattle, WA”
	3.	Dispute Details: Nature of the lien and insurer’s refusal

Revised Prompt (With Anonymisation):
“A homeowner is facing a title dispute after an undisclosed lien from a previous owner surfaced. The title insurance provider is refusing to cover legal costs, arguing that the issue was not disclosed at the time of purchase. How can the homeowner challenge the insurer and seek proper coverage?”

⸻

### Example 8: Condo Association Insurance Claim

Prompt (Without Anonymisation):

“A condo association in Chicago, IL, is filing an insurance claim after a burst pipe in the common area damaged multiple units on 02/28/2024. The insurer is disputing responsibility, arguing that individual unit owners must cover repair costs. The total damage exceeds $100,000. What legal precedents or policy interpretations could support the association’s claim?”

Sensitive Information in This Prompt:

	1.	Location: “Chicago, IL”
	2.	Claim Details: Date of incident, damage amount, and dispute specifics

Revised Prompt (With Anonymisation):

“A condo association is filing an insurance claim after a burst pipe in the common area damaged multiple units. The insurer is disputing responsibility, arguing that individual unit owners must cover repair costs. The total damage is significant. What legal precedents or policy interpretations could support the association’s claim?”

⸻

## Implementation
To integrate Prompt Shields, developers can leverage its API to scan and evaluate user prompts and documents. 

For more details, visit the [Prompt Shields Documentation](#).

