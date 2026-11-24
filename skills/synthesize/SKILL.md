---
name: synthesize
description: Integrate research, threads, notes, transcripts, tickets, or docs into one sourced conclusion about what they mean together, when the reader needs a decision rather than a recap.
---

# Synthesize

A summary says what each source says. A synthesis says what they mean together: a claim no single source makes. If the reader only saved reading time, keep going.

## Core Principles

- **Answer a question.** Infer the question, the decision, the reader, and what is missing. Ask only when the answer would change the output.
- **Time order beats first impression.** Read the full set before you label anything. Then read it by date. A later item can answer, revise, or replace an earlier one. Reporting a stale state as current is the worst error.
- **Differences are findings.** Merge true duplicates and keep every citation. Keep apart: same topic with different conclusions, different people, a decision that changed, different periods.
- **Behavior beats statement.** What people did outranks what they said. A workaround is an unmet need. Report the gap.
- **Silence is not a decision.** Decided: the owner agreed, or it later happened. Proposed: nobody with authority agreed. Open: asked or deferred, and unanswered. Credit the person who made the point.
- **One source is a signal.** A finding needs independent support, ideally of different kinds. Put confidence next to the claim. An average can hide a split. A small difference in a small sample is not a finding.

## When to Use

- Many inputs must become one conclusion: threads, docs, notes, transcripts, tickets, surveys, research
- The reader will build, prioritize, approve, reply, or decide
- Sources disagree, overlap, or span time

## When NOT to Use

- The user asked for a summary, minutes, or a source-by-source recap
- One source, and the job is to explain it
- The job is a list (actions, quotes, owners) with no cross-source claim
- You would have to invent sources or fill a gap the inputs do not support

## Implementation Guide

Do this in the answer. Use the inputs and your judgment. Do not build a pipeline or hand the job to another skill.

### 1. Frame

Pin the question, the decision, the reader, and the set: types, count, time span, obvious gaps.

### 2. Read twice

Read everything once. Then order by date. Mark reversals, answers to earlier questions, and replaced decisions.

### 3. Atomize

One observation per note. Record what was said, done, decided, or measured, plus source, author, and date. Tag it: behavior, statement, data, or decision. Keep a verbatim line when the wording is the evidence. Flag workarounds, emotional language, repetition, and real consequences.

### 4. Deduplicate

The same fact in chat, email, and a doc is one item with many citations. Base text: most complete version. Add unique details. Prefer the most authoritative and most recent phrasing.

Same author, near-identical content, close time, the same named thing, or an explicit reference ("per the email") means one item. Disagreement does not.

### 5. Cluster

Let groups emerge. Name each with a claim ("Admins abandon setup at the SSO step"), not a topic ("Onboarding"). Split a large cluster. Leave outliers out. Record support: "7 of 10 interviews", "4 sources across chat, email, and the spec."

### 6. Weigh

- **Authority:** final docs and the owner's words over drafts, chat, and paraphrase. Observed behavior and usage over stated preference.
- **Freshness:** strict for status. Loose for stable facts. Flag anything outside the decision window.
- **Agreement:** different people, methods, or times. One source repeated is not agreement.
- **Priority:** high frequency and high impact lead. Low frequency and high impact: name the segment. High frequency and low impact: group them. The rest: one line or cut.

### 7. Status

For each decision-shaped point write: the point, who proposed it, who agreed or pushed back, and why. Joining the thread does not make someone the owner.

### 8. Cross the themes

Find a link no source states, a tension (fixing one finding worsens another), a conflict that marks a segment, a surprise against the starting assumption, or an absence (a voice, a metric, a question).

For the headline insight only: the strongest objection, a concrete test, and what would invalidate it ("this holds unless X"). Two lines. Skip co-occurrence with no real link. Never invent a citation.

### 9. Write

Keep the method internal. Do not narrate steps 1 to 8. Cut any finding that does not change the decision.

1. **Answer.** One to four sentences. It stands alone.
2. **Findings.** By idea, never by source. One to three lines each: the claim, with support and attributed evidence inline ("7 of 10 interviews; Dana, 3 Mar: 'we export to Excel first'"). Add the implication only if it is not obvious. Name a tension inside the findings it affects.
3. **So what.** Concrete actions, each tied to a finding ("Add a progress indicator to setup").
4. **Gaps.** What the inputs could not answer, how to close it, and the one missing piece that would most change the conclusion.

Cite inline. Add a source list only for 15 or more inputs.

State confidence only when it is below High, beside the claim, once. Medium: date it. Low: say what you found and what is missing. A quote is evidence. The finding is what it means. Mark your interpretation as yours only where a reader might take it for fact. Say plainly when sources disagree and you cannot resolve it.

Scale to volume. 1 to 5 items: the answer plus detail. 5 to 15: themes and key sources. 15 or more: findings, support counts, and an offer to go deeper.

## Review Checklist

- [ ] The first paragraph answers the question.
- [ ] Organized by idea. No section is "what source A said."
- [ ] At least one claim that no single source made.
- [ ] Every claim traces to a source. Numbers and quotes are specific.
- [ ] Later sources were checked for reversals.
- [ ] "Decided" was actually decided. Conflicts stay visible. Single-source items stay signals.
- [ ] The headline insight has an objection and a failure condition.
- [ ] Recommendations are concrete. Length matches what was found, not the effort.
- [ ] No sentence would fit a synthesis on any topic.
