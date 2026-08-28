# Abstract2CoverLetter

Generate and evaluate a journal-ready cover letter from your abstract, target journal, and the journal’s aims and scope.

Abstract2CoverLetter is a standalone browser-based academic publishing tool. It turns core manuscript information and verified submission declarations into a professional editor-facing cover-letter draft and evaluates that draft before submission.

## Required inputs

- Article title
- Abstract
- Target journal
- Editor-in-Chief name
- The journal’s aims and scope
- Corresponding author name
- Author number: 1 or 2 or more
- Originality / prior-publication confirmation
- Confirmation that the manuscript is not currently under consideration by another journal
- Author-approval confirmation
- Competing-interest declaration

## Optional inputs

- Manuscript type
- Special note

## Authorship logic

The application adapts the cover-letter wording to the authorship structure:

- 1 author: first-person singular wording such as “I am pleased to submit my manuscript” and “I confirm...”
- 2 or more authors: corresponding-author wording such as “On behalf of my co-authors, I am pleased to submit our manuscript” and “We confirm...”

## Submission declarations

The cover letter cannot be generated until the user confirms the required submission declarations.

The user must confirm that:

- the manuscript is original and has not been published previously;
- the manuscript is not currently under consideration by another journal;
- the manuscript and submission have been approved by the author(s), as applicable.

For competing interests, the user must select one of two options:

- No known competing interests
- Competing interests exist and will be disclosed

The generated letter adapts its wording to the selected competing-interest status instead of assuming that no conflict exists.

## Workflow

Article title
→ Abstract
→ Aims & scope
→ Author information
→ Submission declarations
→ Contribution extraction
→ Journal-fit analysis
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
- Journal relevance based partly on overlap with the supplied aims and scope
- Professional tone
- Claim safety
- What works
- What could be improved
- Verification and risky-claim warnings
- Copy cover letter button

## Important limitation

The application does not independently verify the Editor-in-Chief, aims and scope text, manuscript originality, exclusivity, author approval, competing-interest status, or any other submission declaration. All declarations remain the responsibility of the author(s) and should be checked against the target journal’s current policies before submission.

## Privacy

This version performs its drafting and evaluation locally in the browser and does not send entered manuscript text to an external AI service.

## Live app

https://tdirsehan.github.io/abstract2coverletter/
