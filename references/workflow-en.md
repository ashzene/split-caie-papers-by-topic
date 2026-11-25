# Cambridge topical past papers

## Define the scope

Use the request and available material to identify the subject, syllabus code, topics, exam years and any specified papers. Classify questions by what they assess. When the user gives a textbook unit or a current syllabus heading, match older questions to that scope and check for changes in titles, numbering and content.

Before selecting questions, use the applicable syllabus and actual questions to identify the assessment formats that cover the topic. If the same topic is genuinely assessed in different formats such as written theory and practical programming, and the user has not selected a format, paper, or both, ask once. Name the applicable paper numbers and formats. Inventory the files while waiting if useful, and wait for the answer before selecting questions and exporting. Proceed when the paper or format is already clear.

For example, when 9618 Topic 19 spans Paper 3 (theory) and Paper 4 (practical programming), ask which paper to cover or whether to include both. Proceed when the syllabus clearly places a mathematics topic in a paper. Regional variants of the same paper, such as 31, 32 and 33, are one assessment format. Ask about other scope decisions only when they materially affect selection and the user can resolve them.

## Find and pair papers

Read [Coverage and missing papers](source-coverage-en.md). Use the user's computer date and time zone as the default cutoff. Build an inventory of the exam series and variants Cambridge offered for the subject and year, then compare it with the local files. Use any cutoff or series the user specifies.

| Available material | Action |
|---|---|
| Complete local coverage | Check the Desktop and its subfolders recursively. Use original question papers (QP) and official mark schemes (MS) that match the expected inventory. Check supplied folders or attachments first. |
| Missing local QP, MS or whole series | Search public sources for missing material that has reached its release date. Reuse complete local pairs. If the local files stop at the previous year, use the cutoff to check for released series from the current year. |
| No usable original papers on the Desktop | Find publicly available Cambridge QP and official MS in scope. Prefer Cambridge sources. A public mirror is suitable when the files can be verified as original Cambridge documents. |
| User specifies local material only | Apply this requirement first. Use the available pairs within scope and identify missing variants in the delivery message. |

- Match each QP and MS by syllabus code, exam year, series, component and variant. Verify their identity from the cover or page headers. File aliases and existing topic compilations can help find the original papers. Use an excerpt from a compilation only if the source, completeness and official MS can all be verified.
- Deliver QP and MS as a pair unless the user explicitly asks for one type. If gaps remain, deliver the verified pairs and report the actual coverage, series awaiting release, and specific QP or MS that have been released but could not be obtained. Explain when a topic has no questions available for delivery and omit empty PDFs. Include specimen papers only on explicit request.

## Select, crop and deduplicate

Read [Scope and PDF checks](review-checks-en.md) before selecting new material or cropping source pages. When only reordering or splitting an audited pack, repeat the checks affected by the change.

1. Classify each subquestion using the QP and official MS as described in [Scope decisions](review-checks-en.md#scope-decisions). Review exclusions and cross-topic questions before cropping.
2. If a necessary definition or diagram appears in an out-of-scope subquestion, extract only the relevant original material as context. When a retained question requires an answer calculated or derived in an earlier part, keep that prerequisite and its matching MS. Preserve original subquestion labels and check every cross-page reference. Embed the necessary content from an official insert or data file in the QP where possible. Report the question as a coverage gap if the dependency is missing or cannot be supplied in the requested format.
3. If a question spans topics, assign independently answerable, marked subquestions to their respective topics and include the stem or prerequisites each topic needs. Place an indivisible subquestion once, under the best-matching requested topic it directly assesses. Shared context or a prerequisite may appear in more than one topic where it is needed for independent use.
4. Compare the wording, subquestions, figures, data and code within the same exam year. Keep one copy of an exact match and use the official MS for the source variant retained. Ignore differences in original numbering and layout. Retain questions that differ in substantive details such as values or circuits, and retain questions from different years. Verify proposed duplicates with figures or formulas against the original pages.
5. Use one internal manifest for both PDF types. Record retained parts, dependencies, context-only excerpts, excluded parts and pending reviews by source paper and subquestion. Record marking rows and final numbers for assessed parts. Keep the manifest and temporary files in the workspace.

## Assemble and deliver

- **One topic in a single assessment format.** Export two PDFs, one QP and one MS. Treat the listed subsections of a unit as its scope unless the user explicitly asks for separate outputs for each subsection.
- **Multiple topics.** Export a separate QP/MS pair for each topic by default. Follow the user's requested layout if they explicitly ask for a combined edition.
- **Different assessment formats for one topic.** Export one separate QP/MS pair per format by default. Including both theory and practical programming produces four PDFs. Put the paper number or assessment format in each filename and cover. Combine formats only on explicit request. Give the theory and practical sections matching, prominent paper and format headings in both PDFs, with descending exam years within each section.
- **Newest year first.** Start each PDF after its cover with the newest exam year and work backwards. Within a year, order series newest first. Within a series, follow the source paper variant and question order. In a combined edition explicitly divided by topic or assessment format, apply the same descending year order within each section.
- Finalise the order, then number questions consecutively from 001. Use the same number for each question in the QP and MS. When exporting separate topics, continue numbering in the user's topic order or in syllabus order if none was given. When separating formats for the same topic, start each QP/MS pair independently at 001. When splitting an existing compilation with topic sections, verify the order and pairing before preserving its numbering.
- Deliver the requested PDFs only. Use compact question numbers and paper identifiers, and preserve original questions and official marking content. Each PDF has one cover page by default. Add a table of contents, revision notes, extra solutions or an inventory only on request.
- Put new PDFs on the Desktop by default and name them with the syllabus code, topic and QP or MS. Use the location the user specifies. Preserve the original source files. When the user requests removal of earlier files from the Desktop, move only the identified, verified outputs to the workspace so they can be recovered. Split a verified, accurate combined edition directly when possible to avoid cutting it again.
- Reopen every final PDF. Apply the separate checks for visible content, text layers and crop bounds in [PDF acceptance checks](review-checks-en.md#pdf-acceptance-checks). Render the covers and check the fonts and QP/MS suffix. Verify year order, paired numbers, paper identifiers, subquestion order and marks by topic, then confirm each delivered file’s location.

## Cover pages

Use a simple A4 portrait first page for each PDF. Set both lines in a serif font, preferably Baskerville or Georgia, with a Times family font as the fallback. Centre the text within generous margins. Set the topic title larger than the first line, and wrap long titles where needed.

Put the English subject name and topic number on the first line. Put the English topic name and the lowercase suffix `qp` or `ms` on the second line. When separating formats for the same topic, add the paper number or format before the suffix on the second line. Use the numbering the user adopted. If there is no topic number, use the subject name alone on the first line. For a combined edition, use its topic range on the first line and the title the user adopted with the appropriate suffix on the second.

```text
Physics Topic 1
Circular motion qp
```

Use the same layout for both PDFs in a pair, with `ms` on the mark scheme cover. Keep the cover outside question numbering and include only the subject, topic, any required paper label and document type. Omit the cover if explicitly requested.
