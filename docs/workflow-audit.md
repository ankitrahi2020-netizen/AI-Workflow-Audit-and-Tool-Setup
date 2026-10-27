# Workflow Audit — FL-01

**Framework:** Ethan Mollick, *"On-boarding Your AI Intern"*  
**Buckets:** Just me · Delegate with review · Collaborate with AI · Fully automate  
**Student:** TODO(me) | **Date:** October 2026

---

## Audit Table

| # | Task | How often | Classification | One-line rationale |
|---|------|-----------|----------------|--------------------|
| 1 | Deciding what to study from GRIT syllabus PDFs and in what order | Weekly | **Collaborate with AI** | AI maps syllabus to topics; I set priority based on my exam dates and weak areas. |
| 2 | Generating exam-style MCQ practice sets from a syllabus | 2–3× per week | **Delegate with review** | AI drafts questions fast; I verify answer keys against official sources before using them. |
| 3 | Writing GenAI exam notes in exam-question style | Weekly | **Delegate with review** | AI condenses lecture content; I cross-check every point against my original notes. |
| 4 | Solving C++ coding problems for Computational Thinking | Daily | **Just me** | The exam tests *my* problem-solving speed; AI is only consulted *after* I attempt, to check logic. |
| 5 | Aptitude / quant problem solving (time-work, percentages, P&C, etc.) | Daily | **Just me** | Speed and mental-math fluency are the skills being tested; outsourcing the solving defeats the purpose. |
| 6 | HTML/CSS/JS practice and debugging | 3–4× per week | **Collaborate with AI** | I write the code; AI explains error messages and suggests targeted fixes so I still learn. |
| 7 | Drafting sections of the TDP research paper | Weekly | **Collaborate with AI** | AI structures and drafts paragraphs; I verify every factual claim before it stays in the paper. |
| 8 | Verifying IEEE references for the TDP paper | Per writing session | **Just me** (AI only for formatting) | AI can fabricate citations; I must confirm each DOI/URL exists — this is non-negotiable for academic integrity. |
| 9 | Building and modifying the AirIndex prototype code | Weekly | **Collaborate with AI** | AI generates and refactors boilerplate; I own the architecture decisions and run every test. |
| 10 | Explaining each prototype change and its reason | Per code change | **Delegate with review** | AI drafts the change-log text; I confirm it accurately reflects what the code actually does before committing. |
| 11 | Making SIH idea PPT content | Per milestone | **Collaborate with AI** | AI helps with slide structure and wording; I own the project story, all numbers, and the narrative arc. |
| 12 | Answering evaluator / judge questions live | Per presentation | **Just me** | I must understand and defend my own project in the room; AI helps me *prepare*, but the answers are mine. |
| 13 | Writing Conventional Commit messages and enforcing the format | Every commit | **Fully automate** | The format is rule-based (type/scope/subject); a commitlint-style lint check can enforce it without human thought. |

---

## What I learned

Going through this exercise made me realise that the "Just me" tasks are not where AI is bad — they are where *the human doing the work* is the entire point. Solving a C++ problem or defending a project in front of judges cannot be delegated because the examiner is measuring *me*, not the output. The "Collaborate" bucket was the most interesting: it forces a clear split between what AI does well (structure, speed, pattern) and what I must still own (judgment, verification, context). The "Fully automate" row (commit linting) was a useful reminder that many tedious format-checks are pure rule-following and do not need any human attention at all. The exercise has made me deliberately slow down before starting any new task and ask: *who should own this?*
