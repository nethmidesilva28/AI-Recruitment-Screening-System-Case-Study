# User Acceptance Testing (UAT) Test Cases
## AI Recruitment Screening System

---

## 1. Objective

The purpose of User Acceptance Testing (UAT) is to validate that the AI Recruitment Screening System meets business requirements and supports the intended recruitment workflow for recruiters and hiring managers.

---

## 2. Scope of UAT

The UAT phase covers validation of the following key features:
- CV upload and parsing
- Job description submission and processing
- Candidate-job matching
- Candidate scoring and ranking
- Recruiter dashboard review and shortlisting flow
- Manual override of AI-generated recommendations

---

## 3. Test Cases

| Test Case ID | Test Scenario | Precondition | Test Steps | Expected Result | Status |
|-------------|---------------|--------------|------------|-----------------|--------|
| UAT-01 | Upload candidate CV | Recruiter has access to system | Upload a valid CV in PDF/DOCX format | CV is uploaded successfully and parsed into structured fields | Pending |
| UAT-02 | Submit job description | Recruiter is logged in | Enter or upload a job description | Job description is stored and required skills/criteria are extracted | Pending |
| UAT-03 | Generate candidate score | Candidate CV and job description exist | Run AI screening process | System generates a candidate score based on job relevance | Pending |
| UAT-04 | Rank candidates | Multiple candidates available for a job | Trigger ranking process | Candidates are displayed in descending order based on score | Pending |
| UAT-05 | View ranked candidates in dashboard | Ranking completed | Open recruiter dashboard | Dashboard displays candidate list, scores, and ranking details | Pending |
| UAT-06 | Filter candidates by score | Candidate ranking available | Apply score threshold filter | Dashboard displays only candidates above selected score | Pending |
| UAT-07 | Override AI recommendation | Ranked candidate list available | Recruiter manually changes shortlist status | System saves recruiter override decision successfully | Pending |
| UAT-08 | Handle invalid CV upload | Recruiter attempts unsupported file upload | Upload unsupported file type | System displays validation error message | Pending |
| UAT-09 | Verify candidate data extraction | Candidate CV uploaded | Review extracted candidate profile | Skills, education, and experience are extracted correctly | Pending |
| UAT-10 | Verify auditability of decisions | Recruiter overrides AI result | Save decision and review record | System logs AI recommendation and recruiter override action | Pending |

---

## 4. Acceptance Conditions

A UAT test case is considered successful if:
- The system performs the expected business function without critical errors
- The output aligns with defined business and functional requirements
- The workflow is usable for recruiters and hiring managers
- AI recommendations are visible, interpretable, and adjustable by human users

---

## 5. Exit Criteria

UAT will be considered complete when:
- All critical and high-priority test cases pass
- Major usability issues are resolved
- Stakeholders confirm the system supports the intended recruitment process
