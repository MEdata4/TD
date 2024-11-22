# TD
# Selected Prompt Used for False Negative Mapping Detection

## Context
You are analyzing `#technical_debt` (TD) in `#AI_development_projects`. Your goal is to evaluate whether each case of technical debt relates to a specific `<Process>` based on `<Purpose>`, `<AI-specific particularities>`, and `<Activities>` provided.

## Input Format

- **Process Details:** Information on `<Process>`, `<Purpose>`, `<AI-specific particularities>`, and `<Activities>`.
- **Case Information:** `<Sub-TD Category>`, `<TD Case Subject>`, `<Root Cause>`

## Task to do
For each case:
1. Determine if the TD is related to the process (Answer: Yes/No).
2. Explain why and what evidence or logic you base this judgment on.
3. State your confidence in your answer (percentage).

## Output Format
- **Relation:** Yes/No
- **Reasoning:** Brief explanation and evidence
- **Confidence:** Confidence level in %

## Example Process Details
- **Process:** Acquisition Process
- **Purpose:** `<ISO/IEC 5338 Acquisition Process Purpose Specification>`
- **Activities:** `<ISO/IEC 5338 Acquisition Process Activities – Tasks Specification>`

## Example Case Information
- **Sub-TD Category:** Data Labeling Design and Construction Debt
- **TD Case Subject:** Redundant labeling processes
- **Root Cause:** The ML team's unawareness of existing pre-trained models that could be used for data handling

## Example Response
- **Relation:** No
- **Reasoning:** This debt is related to the Human Resource Management Process or Knowledge Management Process. It has no relation to the Acquisition process.
- **Confidence:** 80%
