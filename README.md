# Python Learning Coach

This portfolio project explores whether Python beginners need better support for understanding mistakes and checking whether they can apply what they learned. It is being developed by a TC Learning Analytics student with strong Python skills, as a product discovery project for US AI product management internship applications.

**Stage: user needs validation.** This is an early product hypothesis, not a working application or a validated solution. No user interviews have been conducted and no findings or product outcomes are available.


## Researcher information

- ORCID iD: 0009-0001-0085-6269
- Project DOI: Not yet assigned.

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

## Sharing & Access Information

### Public access and available files

The project is available at [Python Learning Coach on GitHub](https://github.com/xoxovoxo/python-learning-coach). Anyone can read the README and linked documents without signing in. To download the documents, select **Code → Download ZIP** on the repository page, or clone the repository with Git:

```bash
git clone https://github.com/xoxovoxo/python-learning-coach.git
```

The public files are Markdown (`.md`) documents that can be read on GitHub or opened in a text editor. They include the product hypothesis, interview guide, blank notes template, data dictionary, and validation plan listed above. No Python installation or model API access is needed to read them. **There is currently no collected interview dataset or research-results file to download.**

### Participant information and access restrictions

For the planned interviews, completed notes will be kept outside this public repository in private storage accessible to the researcher. Contact details will be stored separately from coded notes. Participant codes will be used instead of names, but codes alone do not guarantee anonymity.

Raw interview notes and contact details will not be published here. A future public research summary will contain reviewed, de-identified findings only. Any public participant quotation will require separate permission and a check for identifying details. Do not submit private participant information through GitHub issues.

### Reuse, citation, and questions

A reuse license has not yet been selected, and this repository currently has no `LICENSE` file. For reuse requests or questions about the public documentation, contact the maintainer through the repository's [GitHub issues](https://github.com/xoxovoxo/python-learning-coach/issues).

When referencing this project, identify the repository owner (`xoxovoxo`), the title (*Python Learning Coach*), the repository URL, and the access date or specific commit used. A project DOI has not been assigned as part of this work. The GitHub URL is the current sharing link, not a DOI. Git commit history records changes to the documents.

## Methodological Information

**Research status: planned, not conducted.** The following describes the proposed first round of research, not completed data collection or analysis. Collection dates and interview setting have not yet been scheduled.

### Research purpose and design

I plan to conduct a small exploratory qualitative study using semi-structured interviews. The goal is to understand how Python beginners handle learning difficulties, what help they actually use, and how they decide they understand a solution. This round will investigate the problem before testing an AI coach or measuring learning outcomes.

### Participants and recruitment

I plan to recruit **3–5 adults aged 18 or older** who are learning introductory Python and have attempted an exercise within the previous two weeks. Recruitment will start with classmates, learning groups, and personal contacts who meet these criteria. This is a convenience sample with eligibility criteria, not a random sample. Where feasible, I will include both course-based and self-directed learners, without requiring AI use or dissatisfaction with existing tools.

Participation will be voluntary. Participants may skip questions or stop the interview. I will obtain permission before taking notes and separate permission before using an anonymized quotation publicly.

### Data collection procedure

1. Practice the [interview guide](docs/interview-guide.md) in a mock session to check timing. Mock responses will not count as research data.
2. Conduct one **15–20 minute interview** per participant, focusing on a recent Python exercise and the actual sequence of actions taken when difficulty occurred.
3. Ask neutral follow-up questions about resources used, what happened afterward, and any later attempt to apply the concept. Avoid presenting the product idea before exploring the participant's experience.
4. Take notes using the [interview notes template](docs/interview-notes-template.md). No audio or video recording is planned for this round. Any optional demonstration will be distinguished from recalled behavior.
5. Review notes immediately afterward, recording uncertainties and any changes to the interview questions. Do not reconstruct missing quotes or events.

### Data organization and quality checks

Each participant will receive a code such as `P01`, and evidence entries will receive linked IDs such as `P01-E01`. These examples describe the naming scheme, not actual participants. Notes will separate accurately captured quotes, participant-reported events, direct observations, and researcher interpretations.

The [data dictionary](docs/data-dictionary.md) defines field meanings, allowed values, and missing-information markers. Unanswered descriptive fields will use markers such as `NOT_ASKED`, `NOT_RECALLED`, or `DECLINED`, rather than invented values. Consent fields will use their specified categories. Before analysis, I will check that evidence IDs are consistent, interpretations are traceable to evidence, and identifying details are excluded from public material.

### Planned analysis and decision process

I will manually compare interview notes in the evidence matrix provided in the [validation plan](docs/validation-plan.md). I will group accounts by learning context, obstacle, resources used, outcome, remaining difficulty, and any later understanding check. I will look for recurring patterns as well as cases that contradict the product hypothesis.

The output will be a short research memo with evidence IDs, limitations, and a decision to continue exploring, narrow the target group, adjust the problem, or gather more evidence. Any counts will refer to participants out of the actual sample size, rather than repeated mentions or estimates for all Python learners. The existing validation plan provides provisional decision criteria; these are research aids, not statistical tests.

### Limitations

The small convenience sample, participants' recall, and the researcher's interpretation may affect the findings. Interview accounts are not independently verified behavior, and notes without recordings may miss details. This round cannot establish how common a problem is, prove demand for the proposed product, or show that AI hints improve learning. Those questions would require separate studies. No findings or effectiveness claims will be added until relevant evidence has been collected.

## Personal notebook

I did not use a formal metadata standard like Dublin Core. Instead, I created a simple structure that fits my interview project. It includes participant IDs, learning backgrounds, evidence types, and consent. I also added a data dictionary to explain each field so I can record future interviews consistently. I used a custom Markdown template for my README. It introduces the target users, problem, proposed product flow, and current project stage. I used Codex to help draft and edit the documents, Git to track changes, and GitHub CLI to upload the project to GitHub. The hardest part was explaining my idea without making it sound like I had already proven that it would work. Since I have not conducted interviews yet, I clearly labeled the project as being in the user needs validation stage. I described the features as proposed ideas and linked my interview guide and validation plan to show what I will do next.
