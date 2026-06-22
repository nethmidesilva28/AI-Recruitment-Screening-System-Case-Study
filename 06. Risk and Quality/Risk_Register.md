# Risk Register
## AI Recruitment Screening System

---

## 1. Purpose

This risk register identifies key project, operational, technical, and ethical risks associated with the AI Recruitment Screening System.

---

## 2. Risk Register Table

| Risk ID | Risk Description | Category | Probability | Impact | Mitigation Strategy | Owner |
|--------|------------------|----------|-------------|--------|---------------------|-------|
| R-01 | AI may incorrectly rank strong candidates lower than expected | Functional / AI | Medium | High | Use recruiter review and allow manual override | Product / Recruitment Team |
| R-02 | CV parser may fail to extract data correctly from different formats | Technical | Medium | Medium | Validate parser with multiple CV formats and fallback review process | Engineering Team |
| R-03 | AI model may inherit bias from historical hiring patterns | Ethical / AI | Medium | High | Remove sensitive attributes, use fairness checks, maintain human oversight | Product / Compliance Team |
| R-04 | Recruiters may over-rely on AI recommendations without critical review | Operational | Medium | High | Position AI as decision support and include override capability | HR / Product Team |
| R-05 | Candidate personal data may be exposed or mishandled | Security / Compliance | Low | High | Apply encryption, role-based access control, and secure storage practices | Security / IT Team |
| R-06 | Job descriptions may be poorly written, reducing matching accuracy | Business / Data Quality | Medium | Medium | Encourage standardized job templates and recruiter review of extracted requirements | Recruitment Team |
| R-07 | Stakeholders may not trust AI-generated scores | Adoption / Change Management | Medium | Medium | Provide scoring transparency and explainability summary | Product Team |
| R-08 | System performance may degrade under high application volumes | Technical / Performance | Medium | Medium | Design scalable processing flow and optimize ranking pipeline | Engineering Team |
| R-09 | Legal or ethical concerns may delay adoption of AI screening | Compliance / Governance | Low | High | Include compliance review, human-in-the-loop control, and clear usage boundaries | Compliance Team |
| R-10 | Incomplete or low-quality CVs may reduce matching accuracy | Data Quality | High | Medium | Define parsing confidence thresholds and allow recruiter verification | Recruitment Team |

---

## 3. Risk Response Approach

The system should adopt a proactive risk management approach by:
- Identifying risks early during planning and design
- Assigning ownership for monitoring and mitigation
- Reviewing high-impact risks during sprint reviews and release planning
- Prioritizing ethical, compliance, and AI quality risks alongside technical risks
