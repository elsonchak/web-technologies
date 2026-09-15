# Elson Chakonza — student profile

A semantic HTML5 student profile and mini-portfolio page for the Web Technologies (CIS2103) Practical Assignment 1.

## Files

- [aboutme.html](./aboutme.html) — the responsive profile, learning map, selected work, and contact form.
- [PROMPT_LOG.md](./PROMPT_LOG.md) — the exact About-section prompt, raw AI draft, edited copy, and reflection.

## Accessibility implementation

- Uses a visible-on-focus **Skip to main content** link.
- Uses semantic landmarks: `header`, `nav`, `main`, `section`, `article`, `aside`, `form`, and `footer`.
- Uses one clear `h1`, then correctly nested `h2` and `h3` headings.
- Every form control has a persistent, associated `label` and an `id`/`for` pair.
- The form uses native HTML validation attributes including `required`, `type="email"`, `type="tel"`, `pattern`, `minlength`, and `maxlength`.
- JavaScript enhancement adds inline errors, `aria-invalid`, an error summary with links, focus management, and an `aria-live` submission status. Native validation remains available when JavaScript is disabled.
- The page uses high-contrast paper, ink, chalkboard, and solar-yellow tokens, plus visible keyboard focus styles.
- The page contains no images, so there are no image alternative-text requirements to miss.

## Peer-review evidence

The supplied starter files did not include the Thursday peer reviewer’s name or exact feedback, so that evidence is not fabricated here. Before submitting, replace the bracketed fields below with the real record from the practical session.

- **Peer reviewer:** `[add the reviewer’s name]`
- **Issue found:** `[paste the peer reviewer’s exact accessibility feedback]`
- **Fix applied:** The finished page provides persistent labels for every form control, native validation, linked inline error messages, an error summary that receives focus, a skip link, and visible keyboard focus styles. Select the specific fix that corresponds to the reviewer’s actual note and describe it in their wording.

A directly observable gap in the supplied starter draft was that its form was empty, so there were no labelled controls or validation rules to test. This implementation closes that gap; the exact peer-review note still needs to be added by the student before submission.

## Public contact details

- Email: [elsonchak@gmail.com](mailto:elsonchak@gmail.com)
- Phone: [+263 784 490 014](tel:+263784490014)
- Instagram: [@sheloves_.hoops](https://www.instagram.com/sheloves_.hoops/)

## Contact form note

The form demonstrates native and progressively enhanced validation locally because the assignment repository does not provide a server endpoint. The direct email, phone, and Instagram links above are the student’s supplied public contact details. Connect the form action to a real endpoint if one is available before publishing.

## Submission checklist

- [x] Add the supplied public email, phone number, and Instagram handle.
- [ ] Fill in the real Thursday peer-review evidence above.
- [ ] Make at least three meaningful incremental commits, for example `Create semantic profile scaffold`, `Add accessible contact form`, and `Polish responsive profile styles`.
- [ ] Push the repository publicly (or grant the lecturer access) and submit its link through Google Classroom.
