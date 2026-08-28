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
- Submission declarations

## Authorship logic

The application adapts the cover-letter wording to the authorship structure:

- 1 author: first-person singular wording such as “I am pleased to submit my manuscript” and “I look forward...”
- 2 or more authors: corresponding-author wording such as “On behalf of my co-authors, I am pleased to submit our manuscript” and “We look forward...”

## Optional submission declarations

Submission declarations are not required to generate the cover letter. The user is asked whether each statement applies and can tick only the statements they want included.

Available declaration options are:

- This manuscript is original and has not been published previously.
- This manuscript is not currently under consideration by another journal.
- The manuscript and submission have been approved by the author(s), as applicable.
- There are no known competing interests.
- There are competing interests to disclose.

Only selected declarations are included in the generated cover letter. Unselected declarations are omitted rather than assumed.

If “There are competing interests to disclose” is selected, a text box appears and the user writes the competing-interest statement in their own words. The application does not invent or infer the disclosure.

The “No known competing interests” and “There are competing interests to disclose” options are mutually exclusive.

## Workflow

Article title
→ Abstract
→ Aims & scope
→ Author information
→ Optional submission declarations
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

The application does not independently verify the Editor-in-Chief, aims and scope text, manuscript originality, exclusivity, author approval, competing-interest status, or any other submission declaration. Any declaration selected by the user remains the responsibility of the author(s) and should be checked against the target journal’s current policies before submission.

## Privacy

This version performs its drafting and evaluation locally in the browser and does not send entered manuscript text to an external AI service.

## Live app

https://tdirsehan.github.io/abstract2coverletter/
