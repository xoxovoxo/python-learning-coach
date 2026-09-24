# Product hypothesis

**Status: user needs validation · Version 0.1 · No interviews or results yet**

## Known context

- The project owner studies TC Learning Analytics and is proficient in Python.
- The intended deliverable is a portfolio project for US AI product management internship applications.
- Python Learning Coach is a proposed concept. The target segment, problem severity, and solution value have not been validated.

## Proposed user and scenario — unvalidated

An adult beginner is working on a Python exercise for a class or personal learning goal. Their code fails or produces an unexpected result. They find an explanation or correction, finish the exercise, and later encounter a related task. They may be unsure whether they understand the concept or only reproduced the previous solution.

This scenario is a research prompt, not an observed user story. We need to learn whether it happens, to whom, and whether it has consequences that matter to the learner.

## Problem and value hypothesis — unvalidated

For beginners who repeatedly struggle to explain or reuse a corrected solution, support that responds to their reasoning, offers progressive hints, and provides a fresh practice problem might help them identify what they still need to learn. We hypothesize that this is valuable beyond simply obtaining working code. Learners may instead prioritize completing the assignment quickly, or already have adequate support.

## Possible current alternatives — usage not yet established

Course notes, documentation, search results, tutorials, worked examples, automated exercise feedback, classmates, tutors or teaching assistants, and general-purpose AI chat tools are candidate alternatives. Interviews should establish which were actually used, in what order, what they cost in time or effort, and what remained unresolved. Do not assume these alternatives are inadequate.

## Why AI might be useful — conditional

Learners can express the same misunderstanding through different code and explanations. AI might help interpret these varied inputs, adapt a hint, or draft a related exercise. However, incorrect diagnoses, misleading explanations, and accidental answer disclosure could undermine learning. A fixed hint sequence, clearer examples, or human feedback may be sufficient. AI should only be explored if evidence suggests a need for adaptation that simpler approaches do not meet; its accuracy and educational value would require separate evaluation.

## Critical assumptions to investigate

| Assumption | Evidence to seek | Evidence against it |
| --- | --- | --- |
| A meaningful gap remains after getting working code. | A recent, detailed account of being unable to explain or reuse a solution, with a consequence. | Learners can explain and reuse solutions, or the main obstacle is setup or unclear instructions. |
| Current support leaves this gap unresolved. | Actual attempts with available resources and a specific unresolved difficulty. | Existing help resolves the issue adequately. |
| Understanding is important enough to motivate extra practice. | Past voluntary checking, retrying, or seeking explanations. | Learners consistently stop when code runs and describe no meaningful downside. |
| The problem has a coherent initial segment. | Similar episodes among learners with a shared context or concept. | Difficulties are unrelated and call for different interventions. |

**Next decision:** use 3–5 interviews to continue investigating, narrow the segment, or revise the problem. Positive reactions to the concept would not validate these assumptions. Product usefulness, AI reliability, and learning gains remain questions for later studies.
