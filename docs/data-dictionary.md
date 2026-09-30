# Interview data dictionary

**Version 0.1 · Stage: user needs validation · Schema only; no interview data or findings.**

Use this dictionary with the [interview notes template](interview-notes-template.md) to record the first 3–5 interviews consistently. Field names are suggested labels for future structured analysis; the Markdown template can continue using its readable headings. This is an interview research dictionary, not an application database specification.

## Record structure and missing information

- Create one session record per interview and multiple evidence entries per session. Round 1 plans one session per participant; if repeat interviews are introduced, add a session ID before collecting them.
- `participant_id` connects evidence and synthesis to a session. Each `evidence_id` must be unique and refer to that participant. Codes such as `P01` and `P01-E01` below illustrate formats only, not actual participants.
- For unanswered descriptive fields, use `NOT_ASKED`, `NOT_RECALLED`, `DECLINED`, `NOT_APPLICABLE`, or `UNCLEAR`, as appropriate. Do not use zero or “No” for missing information. A blank in the unused template is a placeholder; resolve blanks before synthesis.
- For consent fields, use the listed values. “Not asked” or unclear permission does not authorize the activity. Notes permission must be obtained before creating a participant record; if declined, do not retain a completed record.
- Record “None reported” only when the participant explicitly reports no resource, consequence, or action. An absent account does not establish that nothing happened.
- Preserve self-reported approximations. Do not infer experience, elapsed time, motivation, or understanding from performance.

## Session fields

| Field | Template heading | Definition and type | Values / recording rule |
| --- | --- | --- | --- |
| `participant_id` | Participant code | Text; anonymous working identifier | `P` plus two digits; unique within this round. Never a name or username. |
| `session_date` | Session date | Date; date of interview | `YYYY-MM-DD`; keep in private notes only. |
| `duration_minutes` | Duration | Number; actual session length in minutes | Positive number; label an estimate as approximate in notes. |
| `interviewer_id` | Interviewer | Text; researcher code | Use a stable code, not participant information. |
| `learning_context` | Broad learning context | Category and optional short explanation | Course-based / Self-directed / Both / Other; use Other rather than forcing a category. Omit exact course identifiers. |
| `python_experience` | Approximate Python experience | Text; participant's description of duration and exposure | Preserve approximate wording; do not assign proficiency scores. |
| `notes_permission` | Permission for anonymized notes | Category; explicit permission to take notes | Yes / No. Retain a completed record only for Yes. |
| `quote_permission` | Separate permission for an anonymized public quote | Category; permission for public quotation | Yes / No / Not asked. Record any limits; only Yes permits review for publication. |
| `follow_up_permission` | Follow-up permission | Category; permission for later contact | Yes / No / Not asked. Store contact details separately. |
| `recording` | Recording | Category; recording method | None for this round. |

## Recent learning episode fields

These describe the participant's account unless an evidence entry explicitly records direct observation. Use concise text or ordered lists, retaining evidence IDs wherever available.

| Field | Template heading | Definition / recording rule |
| --- | --- | --- |
| `goal_and_task` | Goal and task | What the learner was trying to accomplish and the exercise context. |
| `expected_and_actual` | Expected behavior and actual outcome | What they expected versus what happened; separate the two explicitly. |
| `steps_taken` | Steps taken, in order | Ordered actions after the difficulty occurred; distinguish recollection from observed actions. |
| `resources_used` | Resources or people actually consulted | List of resources actually used, in order when known; omit personal names. Do not include merely suggested alternatives. |
| `reported_consequence` | Reported time, effort, or other consequence | Participant-reported impact; keep time units and mark approximations. Not the same as interview duration. |
| `session_outcome` | How the session ended | Outcome of the learning session, not the research interview. Working code does not by itself establish understanding. |
| `stopping_reason` | How the participant decided to move on | Their stated stopping criterion, not the interviewer's explanation. |
| `later_use` | Later use of the concept, if any | Account of a subsequent attempt and outcome; distinguish no later opportunity from failed transfer. |
| `information_gaps` | What remains unknown or was not asked | Missing details with the reason they are missing. |

## Evidence entries

| Field | Template heading | Definition and allowed format |
| --- | --- | --- |
| `evidence_id` | Evidence ID | Unique text code: participant ID plus `-E` and two digits. |
| `participant_quote` | Exact participant quote | Accurately captured words only. If wording is uncertain, put a labeled paraphrase in the reported-event column instead. |
| `evidence_type` | Label inside Observation / reported event | Directly observed / Participant-reported. Split mixed entries into separate rows. |
| `event_description` | Observation / reported event | What happened, with its evidence-type label. Recollection of past actions is participant-reported. |
| `interpretation` | Interviewer interpretation | Provisional researcher explanation linked to this evidence ID; never present it as the participant's words or a measured result. |
| `uncertainty` | Uncertainty or alternative explanation | Competing explanations, recall limitations, or ambiguity. |

An entry can contain a quote, an event description, or both. Mark a quote as `NOT_APPLICABLE` for an observation without speech. Do not invent a quotation to complete a row. A participant statement is evidence of what they reported, not independent confirmation of the event.

## Provisional synthesis and sharing fields

All synthesis fields are researcher analysis, not additional observations. Use text with supporting evidence IDs. Keep contradictory cases rather than forcing agreement.

| Field | Template heading | Definition / recording rule |
| --- | --- | --- |
| `possible_need` | Possible need, linked to evidence IDs | Tentative need inferred from evidence, not a validated requirement. |
| `existing_successes` | What already works well | Effective existing support or successful learner strategies. |
| `supporting_evidence` | Evidence supporting an assumption | Evidence IDs plus the specific assumption they support. |
| `contradicting_evidence` | Evidence contradicting an assumption | Evidence IDs plus the assumption they challenge. |
| `alternative_explanation` | Other plausible explanation | Another interpretation of the same account. |
| `follow_up_question` | Potential follow-up question | Question to resolve an evidence gap; does not imply permission to contact. |
| `interviewer_influence` | Interviewer influence or leading questions | Prompts or assistance that may have shaped the response. |
| `concept_exposure` | Concept introduced? When? | Yes / No, with timing if Yes. Label post-pitch reactions separately from accounts collected before the pitch. |
| `deidentification_actions` | Identifying details removed or generalized | Details changed or excluded before sharing; do not reproduce the identifiers here. |
| `public_quote_review` | Public quote permission verified, if applicable | Verified / Not permitted / Pending / Not applicable. Verified requires explicit permission and review of any limits. |
| `excluded_material` | Material excluded from any public write-up | Broad description of what must remain private, without repeating sensitive content. |

## Storage and interpretation boundaries

Keep completed records and contact information outside this public repository, in separate private locations. Participant codes alone do not guarantee anonymity. Only share a reviewed, de-identified synthesis and permitted quotations; do not publish raw notes.

Public forum posts and published studies belong in a separate secondary-research log with source links. Do not assign them participant IDs or count them among your interviews. These fields support exploratory comparison, not learning scores, causal claims, or proof that the proposed product works.
