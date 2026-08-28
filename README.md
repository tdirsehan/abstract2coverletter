# Abstract2CoverLetter

Generate and evaluate a journal-ready cover letter from your abstract, target journal, and the journal’s aims and scope.

Abstract2CoverLetter is a standalone browser-based academic publishing tool. It turns core manuscript information into a professional editor-facing cover-letter draft and evaluates that draft before submission.

## Inputs

- Article title
- Abstract
- Target journal
- Editor-in-Chief name
- The journal’s aims and scope
- Corresponding author name
- Author number: 1 or 2 or more
- Manuscript type (optional)
- Special note (optional)

## Authorship logic

The application adapts the cover-letter wording to the authorship structure:

- 1 author: first-person singular wording such as “I am pleased to submit my manuscript” and “I confirm...”
- 2 or more authors: corresponding-author wording such as “On behalf of my co-authors, I am pleased to submit our manuscript” and “We confirm...”

## Workflow

Article title
→ Abstract
→ Aims & scope
→ Author information
→ Contribution extraction
→ Journal-fit analysis
→ Cover-letter drafting
→ Quality scoring
→ Strengths and weaknesses
→ Risky-claim and verification check

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

The application uses the aims and scope text supplied by the user but does not independently verify that it is current or complete. It also does not independently verify the current Editor-in-Chief, manuscript originality, exclusivity, authorship approval, or other submission declarations. These items must be checked by the author(s) before submission.

## Privacy

This version performs its drafting and evaluation locally in the browser and does not send entered manuscript text to an external AI service.

## Live app

https://tdirsehan.github.io/abstract2coverletter/
