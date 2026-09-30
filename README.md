# Python Learning Coach

This portfolio project explores whether Python beginners need better support for understanding mistakes and checking whether they can apply what they learned. It is being developed by a TC Learning Analytics student with strong Python skills, as a product discovery project for US AI product management internship applications.

## Researcher information

- ORCID iD: https://orcid.org/0009-0001-0085-6269
- Project DOI: Not yet assigned.
**Stage: user needs validation.** This is an early product hypothesis, not a working application or a validated solution. No user interviews have been conducted and no findings or product outcomes are available.

## Proposed target users

Adult Python beginners learning through introductory courses or independent study who have recently struggled with an exercise. The first research round will explore this group; the final user segment has not been selected.

## Problem hypothesis

Some learners may get their code to run by copying a solution or following instructions without understanding the underlying concept. They may then struggle with a different problem involving the same idea. We do not yet know how common, important, or underserved this problem is.

## Preliminary product flow

The following is a proposed flow to investigate, not an implemented feature set:

1. A learner shares an exercise, an attempt, and their reasoning.
2. The coach asks a clarifying question and proposes a possible misunderstanding, acknowledging uncertainty.
3. The learner receives progressive hints: a conceptual cue, a more specific prompt, and then a worked explanation if needed.
4. The learner tries a new problem that uses the same concept in a different context.
5. The coach asks for an explanation and uses the attempt to suggest what to review next. One correct answer would not establish mastery.

AI is one possible implementation, not a requirement. Interviews may point toward better course materials, fixed hints, worked examples, or human support instead.

## Current work

The first milestone is 3–5 exploratory interviews about recent learning difficulties and actual help-seeking behavior. This small sample can refine the problem definition; it cannot demonstrate product effectiveness, demand across a population, or learning gains.

| Document | Purpose |
| --- | --- |
| [Product hypothesis](docs/product-hypothesis.md) | Separate known context from assumptions and identify what could disconfirm them. |
| [Interview guide](docs/interview-guide.md) | Run a neutral 15–20 minute conversation about a real experience. |
| [Interview notes template](docs/interview-notes-template.md) | Keep quotes, observations, and interpretations separate. |
| [Interview data dictionary](docs/data-dictionary.md) | Define research fields, allowed values, missing information, and evidence types. |
| [Validation plan](docs/validation-plan.md) | Recruit participants, synthesize evidence, and decide the next research step. |

There is no application, model API integration, or setup process at this stage. This repository contains the project's product discovery documents. Future portfolio updates should report actual evidence and limitations, with participant information removed.

## Personal notebook

I did not use a formal metadata standard like Dublin Core. Instead, I created a simple structure that fits my interview project. It includes participant IDs, learning backgrounds, evidence types, and consent. I also added a data dictionary to explain each field so I can record future interviews consistently. I used a custom Markdown template for my README. It introduces the target users, problem, proposed product flow, and current project stage. I used Codex to help draft and edit the documents, Git to track changes, and GitHub CLI to upload the project to GitHub. The hardest part was explaining my idea without making it sound like I had already proven that it would work. Since I have not conducted interviews yet, I clearly labeled the project as being in the user needs validation stage. I described the features as proposed ideas and linked my interview guide and validation plan to show what I will do next.
