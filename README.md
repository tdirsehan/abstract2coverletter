# Abstract2CoverLetter

Generate and evaluate a journal-ready cover letter from your abstract, target journal, and the journal’s aims and scope.

Abstract2CoverLetter is a standalone browser-based academic publishing tool. It turns core manuscript information into a professional cover-letter draft and evaluates that draft before submission.

## Inputs

- Article title
- Abstract
- Target journal
- Editor-in-Chief name
- The journal’s aims and scope
- Corresponding author name
- Author number: 1 to 10
- Manuscript type (optional)
- Special note (optional)

## Authorship logic

The generated letter adapts automatically to the selected author number:

- 1 author: singular language such as “my manuscript” and “I confirm”
- 2–10 authors: plural language such as “our manuscript” and “We confirm”
- For multi-author manuscripts, the declaration refers to the selected total number of authors.

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

The application uses information supplied by the user but does not independently verify the current Editor-in-Chief, journal aims and scope, author count, manuscript originality, exclusivity, or author approval. These items must be checked before submission.

## Privacy

This version performs its drafting and evaluation locally in the browser and does not send entered manuscript text to an external AI service.

## Live app

https://tdirsehan.github.io/abstract2coverletter/
