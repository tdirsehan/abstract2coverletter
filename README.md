# Abstract2CoverLetter

Generate and evaluate a journal-ready cover letter from your abstract, target journal, and the journal’s aims and scope.

Abstract2CoverLetter is a standalone browser-based academic publishing tool. It turns core manuscript information into a professional editor-facing cover-letter draft and evaluates that draft before submission.

## Required inputs

- Article title
- Abstract
- Target journal
- Editor-in-Chief name
- The journal’s aims and scope
- Corresponding author name
- Author number: 1 or 2 or more

## Optional inputs

- Manuscript type
- Special note
- Submission statements

## Authorship logic

The application adapts the cover-letter wording to the authorship structure:

- 1 author: first-person singular wording such as “I am pleased to submit my manuscript” and “I look forward...”
- 2 or more authors: corresponding-author wording such as “On behalf of my co-authors, I am pleased to submit our manuscript” and “We look forward...”

## Aims & Scope Fit

Aims & Scope Fit is evaluated as a separate criterion rather than being hidden inside the overall quality score.

The application compares manuscript terminology with the aims and scope text supplied by the user and reports:

- Aims & Scope Fit score /100
- Fit level: Strong, Moderate, Limited, or Weak
- Overlapping scope terms
- A journal-fit sentence used in the cover letter

This is a heuristic relevance indicator, not an acceptance probability.

## Optional submission statements

Submission statements are not required to generate the cover letter. Only statements selected by the user are included.

### Publication status
- This manuscript is original and has not been published previously.
- This manuscript is not currently under consideration by another journal.

### Authorship
- The manuscript and submission have been approved by the author(s), as applicable.

### Competing interests
- There are no known competing interests.
- There are competing interests to disclose.

If competing interests exist, the user writes the disclosure in their own words.

### Ethics approval
- Ethics approval was obtained for this study.
- Ethics approval was not required for this study.

If ethics approval was obtained, the user enters the committee / institution / approval number or other details.

### Informed consent
- Informed consent was obtained from participants.
- Informed consent was not applicable to this study.

### Funding
- This research received no external funding.
- This research received funding.

If funding was received, the user writes the funding statement.

### Data availability
- Include a data availability statement.

If selected, the user writes the data availability statement.

Mutually exclusive options cannot be selected at the same time. The application does not invent missing ethics, consent, funding, data, or competing-interest details.

## Workflow

Article title
→ Abstract
→ Aims & Scope Fit
→ Author information
→ Optional submission statements
→ Contribution extraction
→ Cover-letter drafting
→ Quality scoring
→ Strengths and weaknesses
→ Verification and risky-claim check

## Output

The application produces one journal-ready cover-letter draft and also provides:

- Cover Letter Quality Score /100
- Completeness
- Clarity
- Contribution visibility
- Aims & Scope Fit /100
- Professional tone
- Claim safety
- Fit level and overlapping scope terms
- What works
- What could be improved
- Verification and risky-claim warnings
- Copy cover letter button

## Important limitation

The application does not independently verify the Editor-in-Chief, aims and scope text, manuscript originality, exclusivity, author approval, ethics approval, informed consent, funding, data availability, competing-interest status, or any other submission statement. Any statement selected by the user remains the responsibility of the author(s) and should be checked against the target journal’s current policies before submission.

## Privacy

This version performs its drafting and evaluation locally in the browser and does not send entered manuscript text to an external AI service.

## Live app

https://tdirsehan.github.io/abstract2coverletter/
