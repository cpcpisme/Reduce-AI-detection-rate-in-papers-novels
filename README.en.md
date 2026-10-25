# Revision Assistant for Papers, WeChat Articles & Novels

> A structured writing-revision assistant for Chinese papers, WeChat Official Account articles, novels, and other long-form text.

[简体中文](README.zh-CN.md) · [Bilingual index](README.md)

## Online Service

**Try the tool:** <https://fuckaigc.cc.cd/>

This project focuses on natural expression, logical coherence, paragraph rhythm, and stylistic consistency. Instead of relying on mechanical synonym replacement or superficial word-order changes, it encourages revision at the sentence, paragraph, and document levels.

> **Positioning:** The output should be treated as an editing draft or revision suggestion, not as an unchecked final manuscript. Results vary by platform, detector version, text type, document length, and the amount of human revision applied afterward.

## Background

As academic, publishing, and content platforms adopt more text-quality and AIGC evaluation systems, authors commonly face several challenges:

- Sentences and paragraphs may look overly uniform or formulaic;
- Connectives, summary phrases, and stock expressions may be repeated too often;
- The underlying argument may be sound while the wording remains unnatural;
- Long-form revisions may introduce terminology drift, inconsistent character voices, or broken context;
- Word-by-word rewriting can damage meaning, grammar, and readability.

The project approaches these issues through structured editing, including sentence-length rhythm, lexical variety, paragraph transitions, information density, and narrative style. Its practical goal is to help authors improve wording and structure while preserving authentic content.

## Core Capabilities

### 1. Academic and Report-Oriented Revision

- Refine rigid or highly templated academic wording;
- Vary sentence rhythm and paragraph structure where appropriate;
- Improve transitions between claims, evidence, explanations, and conclusions;
- Offer more natural wording without casually changing technical meaning;
- Support theses, course papers, research reports, and early journal drafts.

### 2. Expression Restructuring and Repetition Reduction

- Identify repeated phrases, parallel sentence patterns, and stock wording;
- Improve flow through splitting, merging, reordering, and adding necessary context;
- Preserve the original argument, terminology, and direction whenever possible;
- Avoid large-scale mechanical replacement that creates awkward or ambiguous prose.

### 3. WeChat Article Revision and Publishing Preparation

- Adapt titles, introductions, section headings, and closing calls to action for WeChat articles;
- Improve opening impact, paragraph rhythm, and mobile readability without changing facts or core claims;
- Add a moderate amount of emoji when appropriate, such as 📌, ✨, or 👉, to improve visual hierarchy and interaction;
- Record pre-revision and post-revision platform distribution metrics in one comparison table.

### 4. Novel and Narrative Text Support

- Preserve character relationships, plot clues, and narrative direction;
- Maintain voice, point of view, atmosphere, and dialogue style;
- Reduce repetitive, overly regular, or list-like narration;
- Support chapter polishing, passage rewriting, and style consistency checks.

## Typical Workflow

```text
Prepare the original manuscript
          ↓
Choose a text type: paper / WeChat article / novel
          ↓
Submit one paragraph, section, or scene at a time (do not submit the full manuscript at once)
          ↓
Generate revision and restructuring suggestions for the current segment
          ↓
Confirm terminology, voice, character settings, or article style before moving to the next segment
          ↓
Combine the segments and read through the complete text once
```

## Example Results

The original project materials include one recorded example in a VIP-style detection scenario: the reported score moved from approximately **69.9%** before revision to approximately **3.9%** afterward. This is a sample observation from a specific text, time, and test environment—not a universal or reproducible guarantee for every document or platform.

Example screenshots:

### Before revision

<img width="1005" height="506" alt="Detection example before revision" src="https://github.com/user-attachments/assets/87eeec73-1f35-4912-9e37-cfbc5ccbc950" />

### After revision

<img width="965" height="480" alt="Detection example after revision" src="https://github.com/user-attachments/assets/112bf186-545f-4313-8dd4-c98d5b764e12" />

### Tool interface example

<img width="769" height="567" alt="Tool interface example" src="https://github.com/user-attachments/assets/e77be441-010e-4d05-b6ca-6ae659aba3d1" />

## WeChat Case Example

The user-provided case screenshots show a clear difference between the two versions: **12 reads, 1 share, and 0 comments** before revision versus **569 reads, 134 shares, and 78 comments** after revision. A separate backend screenshot shows **452 readers**, **352 shares**, and **99 new followers** for the day.

<img src="assets/wechat-before-after.png" alt="WeChat distribution comparison before and after revision" width="900" />

<img src="assets/wechat-backend-metrics.png" alt="WeChat backend metrics after revision" width="900" />

> These screenshots are a user-provided case record, not a universal guarantee. WeChat distribution also depends on topic, title, publishing time, account history, cover image, and interactions.

## WeChat Distribution Comparison

For WeChat use cases, record real publishing data under comparable conditions: the same account, similar publishing time, and similar topic. The table below is a display template for backend metrics; this repository does not contain verifiable WeChat backend data, so it does not invent numbers.

| Metric | Before revision | After revision |
| --- | --- | --- |
| Initial distribution / first exposure | Actual backend value | Actual backend value |
| Reads / opens | Actual backend value | Actual backend value |
| Likes | Actual backend value | Actual backend value |
| “In-view” reactions / shares | Actual backend value | Actual backend value |
| Completion rate / dwell time | Actual backend value | Actual backend value |

> 📊 Replace “Actual backend value” with the real publishing data after release to show the distribution difference before and after revision. Distribution is also affected by topic, title, publishing time, account history, and cover image; it should not be attributed to wording alone.

## How This Differs from Simple Synonym Replacement

| Approach | Typical problems | Project approach |
| --- | --- | --- |
| Word-by-word replacement | Meaning drift, collocation errors, and damaged technical terminology | Preserve meaning and terminology first, then refine syntax and context |
| Word-order changes only | Surface variation while paragraph structure remains repetitive | Revise sentences, paragraphs, and document structure together |
| Optimizing a score alone | Facts, logic, citations, and readability may be ignored | Put text quality and human verification first |
| Using generated text without review | Hallucinated information or a voice that does not belong to the author | Review, revise, and confirm responsibility paragraph by paragraph |

## Best Practices

### General Processing

- **Process text in segments instead of submitting the full manuscript at once.** A single large submission can dilute the important context and produce generic, repetitive, or stylistically inconsistent rewrites. Use one paragraph, section, or scene per pass.
- Include the necessary context for each segment, such as the paper section goal, target WeChat audience, or a novel character relationship and point of view.
- Confirm the direction of the current segment before moving on; after all segments are done, read the complete text once for terminology, voice, and continuity.
- Use emoji according to context: 📌✨👉 can fit WeChat articles, academic papers normally should not use them, and novels should follow the character and narrative style.

### Papers and Research Reports

- Lock down the research question, method, data, and conclusions before language revision;
- Do not let an automatic edit change technical terms, variable names, formulas, units, or citations without checking;
- Process the abstract, conclusion, limitations, and contributions separately instead of submitting the entire paper;
- Re-check facts, citations, terminology, and formatting requirements after revision.

### WeChat Articles

- Define the title, target audience, core value, and desired reader action first;
- Process the title, introduction, body sections, and closing interaction as separate segments;
- Add emoji, short sentences, and subheadings when useful, without sacrificing information density;
- After publishing, record distribution, reads, interactions, and completion metrics before and after revision for the next iteration.

### Novels and Narrative Text

- Establish character profiles, point of view, and the intended voice first;
- Work chapter by chapter, scene by scene, or paragraph by paragraph to reduce continuity drift;
- Check pronouns, tense, names, forms of address, action order, and dialogue tone;
- Add emoji only when it fits the character and the work's style; do not insert it mechanically.

## Limitations

- Detection platforms and their rules may change over time;
- Results depend on discipline, genre, length, and the quality of the original text;
- Automatic revision may introduce factual errors, citation problems, or semantic drift;
- Complex layouts, tables, formulas, footnotes, and citations still require separate inspection;
- The tool cannot prove that data are authentic or replace an advisor, editor, reviewer, or publisher.

## Privacy and Data Handling

When processing unpublished research, personal information, company material, or submission-sensitive content:

1. Remove names, contact details, identification numbers, experiment IDs, and other unnecessary identifiers;
2. De-identify unpublished data, charts, and attachments;
3. Submit only the content required for the current editing task;
4. Delete temporary files and intermediate exports when the task is complete;
5. Follow the data-handling requirements of your institution, organization, journal, or platform.

## Responsibility

This project is intended for learning, technical research, language improvement, and editorial workflow exploration. Users remain responsible for the truthfulness, originality, citation integrity, data accuracy, and submission of the final text. Do not use the tool to fabricate experimental data, alter references, invent facts, or conceal unauthorized ghostwriting or improper attribution.

## FAQ

### Can the project guarantee a specific platform's detection result?
No. Results depend on the platform version, document content, detection strategy, human revision, and submission environment. The examples in this repository are not guarantees.

### Is it limited to academic papers?
No. It can also support research reports, WeChat Official Account articles, novel chapters, and other Chinese long-form text. Each use case needs its own segmentation, tone, and checking priorities.

### Why not rely only on synonyms?
Synonym replacement changes surface vocabulary but does not solve paragraph logic, repeated syntax, terminology consistency, or context. It can also damage the original meaning.

### How should a long text be split into segments?
Split papers by section or paragraph, WeChat articles by title, introduction, and body section, and novels by scene or paragraph. Do not submit the entire long text in one pass.

## Feedback and Contributions

Useful feedback includes:

- representative issues from different genres;
- segmentation, long-context handling, and revision-quality problems;
- improvements to terminology consistency, paragraph transitions, and long-context handling;
- reproducible bug reports with input conditions and expected behavior.

Please remove personal information, unpublished data, and other sensitive material before sharing examples.
