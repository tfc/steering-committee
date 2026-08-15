# A Decision Process for the Steering Committee

> **Status: proposal. Not adopted. Not an SC document.**
> It is offered as a starting point for a discussion, and it can be adopted, torn
> apart, or ignored.

**The rule text is two short files:** [decision-process.md][process] and
[team-charters.md][charters], together about 2,600 words. They are independent of each other and
can be voted on separately. **This document is the reasoning behind them**, and all of it is
evidenced from the SC's own public archive.

---

## The shortest version of the problem

[Vote #11][v-0011] proposed that meeting notes become mergeable after five days, so publication
would stop being blocked. The result:

| Yes | No | Abstain |
| :---: | :--: | :-------: |
| 1 | **0** | **6** |

**Rejected.** Nobody opposed it. Four of the six abstainers wrote in [that same vote log][v-0011]
that they agreed with it. It failed anyway, because abstaining is free.

That vote was about publishing the record, and the record is still late. The cost is not
tidiness. When it takes this much work to reconstruct what was discussed, when, and by whom,
**voters cannot check whether the person they elected represented them.** Weak participation
disappears into the gaps of a bad process (or lack thereof), and so does strong participation,
which is not fair. Today a member who did the work is
[hard to distinguish](#a-record-a-voter-can-actually-check) from one who did not, and neither can
prove it.

## Three more numbers, all from this archive

- The **moderation team rebuild** appears in 14 of the 17 published minutes, from
  [November 2025][m-2025-11-05] onward. Still open.
- The **AI policy** was raised on [2026-03-25][m-2026-03-25] and appears in at least six
  meetings after that. It has never been voted on.
- The three most recent batches of minutes were published **35, 35 and 39 days** after their
  meetings.

## What is missing

[`async-voting.md`][async-voting] says how a vote *runs*. It is short, it works, and this
proposal does not change it.

Nothing says what is worth an SC decision in the first place, who prepares it, how long the SC
may take, or what happens when nobody decides. **None of the failures above is a voting problem.
Every one of them happened in that gap**, before any vote was called.

## What this proposes

> **The SC decides (only!) questions that the community could not decide itself, from a packet
> somebody else prepared, alters it in at most N sessions of S hours (three hours in total), in
> public. And if the SC does not decide, the asker decides.**

([Numbers are defined here][process-dials])

Four parts:

| | |
| --- | --- |
| **The Gate** | Four tests decide what is even an SC question. One chairperson, one week, one paragraph. If nobody answers, the question goes back to the asker. |
| **The Packet** | The asker writes the options as motion text. The SC picks, amends, or rejects. It never drafts from blank. |
| **The Clock** | Written round first. Meetings only if writing did not settle it, and never more than the ceiling. |
| **The Default** | If the deadline passes, the asker's written fallback takes effect and authority returns to them. |

### What this costs an SC member

The baseline is **one written response and no meeting at all.** The ceiling is **N × S hours per
question, ever**: three, at the values in the rule. Everything else (research, options,
trade-offs, drafting) moves to the people who asked and are already blocked.

It is a ceiling on your time, not a demand on it.

If that still sounds like regulation: every one of the four parts **removes** work from the SC.
The Gate hands questions back, the Packet moves preparation to the asker, the Clock caps the
time, the Default closes the item without another meeting. And the process the SC runs today is
not smaller. Agendas, timeboxes, tabling, deferrals: it is [merely unwritten](#objections),
which is why it cannot be relied on, and why delegating anything never quite sticks.

---

## Contents

- [Two principles](#two-principles): what everything else follows from
- [What's broken](#whats-broken): three failure modes, documented
- [Why only bodies may escalate](#why-only-bodies-may-escalate)
- [Why teams need one responsible person with real authority](#why-teams-need-one-responsible-person-with-real-authority)
- [What the SC stops doing, and what it gets back](#what-the-sc-stops-doing-and-what-it-gets-back)
- [A record a voter can actually check](#a-record-a-voter-can-actually-check)
- [What the community gives up](#what-the-community-gives-up)
- [Objections](#objections)
- [Adoption and trial terms](#adoption-and-trial-terms)
- [Summary](#summary) · [Sources](#sources)

---

## Two principles

Everything in the two rule files follows from these two. If you disagree with them, you will
disagree with the rest, and that is the conversation worth having.

### 1. Elected judgment is the scarce resource. Spend it, don't waste it.

The SC is valuable because seven elected people can make a call that the community will accept as
legitimate. That is capped time of judgment per question, not days of drafting, coordinating,
and chasing.

SC members are busy people with real jobs. We want their worldview and their judgment, and their
decisions carry weight because they were voted in by contributing members of the community. None
of that requires them to sit in many meetings and unbounded chat threads. Every minute the SC
spends on something that did not need *elected judgment* is a minute stolen from something that
did.

This is not hypothetical. From the minutes of [2026-05-13][m-2026-05-13]:

> **@philiptaron:** I haven't been able to create time to work on NixOS topics for the
> past couple months, and it's not looking good for the next two.
>
> **@cafkafk:** you are not alone in this, I see that a lot of people have reduced time.

A process that assumes abundant volunteer attention is a process that will not run.

*This is what [the Packet][process-packet] turns into a work assignment: the asker brings the
expertise, the SC brings the authority.*

### 2. A decision beats a better decision that never comes.

By the time a question reaches the SC, someone is already blocked. The SC's job at that point is
**to decide**, not to find the perfect compromise.

This deserves saying plainly, because it is easy to mishear as an insult and it is not meant as
one. SC members are not elected because they are the people most likely to find the compromise
that everybody else missed. On the merits of most questions the specialist team will understand
the problem better than the SC does. That is what specialist teams are for, and the SC should
say so more often than it does.

What the SC has that no team has is a **mandate**. It was voted in by the community, which means
its answer is one the community agreed in advance to accept. When a question is genuinely stuck,
when capable people have argued to a standstill and no additional expertise will break the tie,
what is missing is not a better answer. It is somebody with the standing to end the argument.
Supplying that is close to the entire reason the SC exists.

So "just decide" is not a lowering of the bar. It **is** the bar. A decision carrying the
community's mandate is the one thing the SC can produce that nobody else can.

Quality still matters. It just ranks second, because the community and the teams already tried
and failed. A decision that turns out wrong costs one correction. No decision costs indefinitely,
blocks people who cannot appeal it, and quietly hands the outcome to whoever is loudest and most persistent.

So the standard is **good enough and reversible**, not *right*. That is why the timebox is a hard
ceiling, why silence is not an option, and why every decision comes with an
[automatic review date][process-review].

### The numbers are dials

Every duration and count is [defined once][process-dials], at the top of the rule file, as a
named variable. The rule states them as values because a rule that hedges its own numbers cannot
be applied, but they are **starting points, not principles**. The design is: a gate, a prepared
packet, a bounded clock, an automatic outcome, a public record. Change any value and that design
still works exactly as described. Remove any of the five parts and it stops working.

| Symbol | Dial | Value | Shorter means | Longer means |
| :---: | --- | :---: | --- | --- |
| **N** | Sessions before the Default fires | 3 | Stronger pressure to decide | More tolerance for hard questions |
| **S** | Length of one session | 1 hour | Tighter focus | More room for genuinely hard wording |
| **G** | Chairperson's answer window at the Gate | 7 days | Faster answer to the asker | More slack for the chairperson |
| **W** | The written round | 7 days | Quicker decisions | More time for members and the community to weigh in |
| **D** | From admitted packet to ballot | 3 weeks | Quicker answers | More room for public comment |
| **P** | Publishing each round's outcome | 7 days | A fresher record | Less pressure on whoever writes it |
| **R** | How long a decision stands | 12 months | Easier to revisit | More stability to build on |
| **T** | Review interval for this process | 3 months | Faster verdict on the process | More evidence before judging |

So please argue about the values. That argument is cheap, and the trial period exists precisely
to find better ones. If three weeks is too fast for questions that set public policy, make it six
for that class of question. If a seven-day written round leaves the community too little time to
write to their representatives, make it fourteen. The one property worth defending is not any
particular figure: **it is that the window closes.**

---

## What's broken

Three failure modes. All of them are visible in the SC's own repository.

> **On the quotes in this document.** Every one of them links to the document it comes from, so
> that nothing here has to be taken on trust. They are not offered as blame. The same handful
> of names recurs because those are the people who showed up, did the work, and wrote
> honestly about what was going wrong. Several of the sharpest criticisms of the SC in
> this document were made by SC members about their own body. That is a credit to them.
> The argument here is that the *process* fails these people, not the other way round.

### Failure 1: there is no gate, so the SC works on whatever lands in front of it

There is no written rule about what belongs on the SC's agenda. Things arrive by whoever noticed
them, and the SC absorbs them.

- The meeting of [2026-04-15][m-2026-04-15] spent its "Correspondence" slot on Google
  Summer of Code mentor mechanics, undelivered Slack invites, and who has Discourse
  credentials.
- In that [same meeting][m-2026-04-15], the line *"@K900: doesn't know if this count, but
  we should post community updates"* appears **three times**, twice annotated
  *"@cafkafk brought this up again here."* The agenda had no way to hold it.
- Members say so themselves. @K900, [2026-04-22][m-2026-04-22]: *"the delegation problem
  remains, regardless of the people doing it. Not having a good process is an SC
  problem."* Luj, abstaining on [vote 0016][v-0016]: *"I consider that this issue is more
  of a Foundation + Organizer issue than it is a SC issue."*
- The founding question is still open. From the very first meeting,
  [2025-11-05][m-2025-11-05]: *"@tomberek: Do we do hands-on steering, or mostly big
  picture?"* Eight months later it is still being argued. The minutes of
  [2026-03-11][m-2026-03-11] record: *"Philip believes the SC's purpose is to direct and
  not to manage, and that money-allocation is managing."*

> **The rule that answers this: [§3 The Gate][process-gate].** Four tests, answered by one
> person, in public, in a paragraph. Test 3 in particular is what turns a run of sponsor votes
> into one sponsorship rule.

### Failure 2: there is no clock, so discussion has no end condition

The agenda has timeboxes. They are decorative.

- The minutes of [2026-01-07][m-2026-01-07] literally read `# Old topics (~20~ 50 min)`:
  the timebox crossed out inside the document.
- On [2026-05-20][m-2026-05-20], the five-minute "Async Updates" slot consumed the entire
  meeting. "Old topics (20 min)" and "New topics (20 min)" have no content at all.
- **The AI policy** was raised on [2026-03-25][m-2026-03-25] and appears in at least six
  meetings after that. On [2026-05-13][m-2026-05-13], @cafkafk: *"By next week, let's all
  have addressed this fully, so we can vote on roberts policy."* The
  [next week's notes][m-2026-05-20] contain nothing on it. It has still never been voted
  on.
- **The moderation team rebuild** appears in 14 of the 17 published minutes, from
  November 2025 onward, deferred again and again: *"Vote deferred"*
  ([2025-11-05][m-2025-11-05]), *"deferred from 12/31 meeting… Deferred to 2026-01-14"*
  ([2026-01-07][m-2026-01-07]). @tomberek, [2026-04-08][m-2026-04-08]: *"we're now ~6
  months into the SC cycle and from the outside it looks like nothing has happened on
  moderation."*
- One absent member stops everything: [2026-03-25][m-2026-03-25] contains three separate
  *"move to table"* motions, one of them *"because Christina is not here."*

This was diagnosed in the second meeting ever. Luj, [2025-11-13][m-2025-11-13]:
*"Meeting dysfunctional."*

> **The rule that answers this: [§5 The Clock][process-clock].** Written round first, a hard
> ceiling of committee time per question, and absence that does not stop the clock.

### Failure 3: not deciding is free, so it is what happens

This is the deepest one, and there is a single artifact that shows it perfectly.

[**Vote #11**][v-0011] proposed that meeting notes become mergeable after five days even
without review, so publication would stop being blocked. The result:

| Yes | No | Abstain |
| :---: | :--: | :-------: |
| 1 | **0** | **6** |

**Rejected.** Nobody opposed it. Four of the six abstainers wrote in
[that same vote log][v-0011] that they agreed with it: *"I am inclined to vote yes on
this"*, *"I'm in agreement with the spirit of this."* It failed anyway, because under the
current rules abstaining is free and costs nothing.

The problem it would have fixed is still with us. The three most recent batches of minutes
were published **35, 35 and 39 days** after their meetings. There is an eight-week hole in
the archive between [2026-01-07][m-2026-01-07] and [2026-03-04][m-2026-03-04]. Two commits
in the SC repository are titled [*"chore: add missing minutes"*][c-minutes] and
[*"chore: add missing votes"*][c-votes].

And the same instinct produces **case-by-case decisions instead of rules**:

- January 2026, [vote 0010][v-0010] delists a Helsing job posting. The motion itself says:
  *"We should have a unified policy towards defense contractors… it is much cleaner, and
  much less geopolitically contentious to have a blanket ban."* Both dissenters agree on
  that point. @Ericson2314: *"we have no clear rules --- we could not agree on any."*
  @tomberek: *"Be consistent… Be explicit if policy is changing."* @philiptaron:
  *"I'm explicitly abstaining. I have no coherent position."*
- **The policy was never written.** Seven months on, the public archive still contains no
  rule about who may sponsor or advertise. The only sponsorship rule the SC has adopted,
  [vote 0016][v-0016], governs whether tiers may be split between companies, not which
  companies are acceptable in the first place. So the question that vote 0010 said needed
  a policy is still answered one company at a time.
- [Vote 0013][v-0013] alone contains **four separate sponsor ballots**, one per company.
  More were approved directly in meetings. On [2026-05-13][m-2026-05-13] another sponsor
  was waved through with *"[the room was silent]: unanimous approval"*. Every one is a
  fresh judgment call where a single published prospectus rule would have done.
- The reasoning is openly about avoiding turmoil rather than about the merits. On one
  sponsor, in [vote 0013][v-0013]: *"my vibe check is that this would be contentious."*

Deferring a hard question does not make it go away. It makes it come back, at a worse
time, with less trust available.

> **The rule that answers this: [§6 The Default][process-default].** If the deadline passes,
> the asker's written default fires automatically and authority returns to them permanently.
> Not deciding stays allowed; it just stops being free.

---

## Why only bodies may escalate

[§2 of the process][process-who] restricts who can compel the SC's attention: a team, the Board,
event organisers, or a chartered working group, not an individual acting alone.

This is not gatekeeping for its own sake. An escalation channel open to everyone is a channel
owned by whoever is loudest and has the most spare time, and the SC's capped attention would be
spent on the people least affected by the outcome. Tying the right to escalate to doing the work
puts that scarce attention where the consequences land.

It also takes nothing away from anyone. Every normal avenue stays exactly as open as it is today
(issues, pull requests, Discourse, Zulip, and the teams themselves, which anyone may join). What
this governs is narrower: what can *compel* the SC to spend its limited time. Joining the work is
the way in, and it is open to everybody.

---

## Why teams need one responsible person with real authority

This is the reasoning behind [team-charters.md][charters], the second of the two rule files. It
can be adopted on its own, or alongside the decision process, or not at all. But the decision
process works considerably better with it, because [Gate test 2][process-gate] returns a question
to the team that owns it, and that works best when there is one name to return it *to*.

### The SC has already argued for this, and voted for it once

When the SC last proposed to recruit and interview team members itself (an open call plus an
interview round for the moderation team), it **rejected the idea**, and the reasons given were
the right ones. Luj, voting against in [vote 0005][v-0005]:

> in my opinion the SC should not carry the recruitment of new moderators for 3 main reasons:
>
> - We are not fit to evaluate the soft skills needed to be a good moderators, only one of us has
>   actual experience carrying moderation duty
> - This is going to turn into a evaluation of each candidate politics with everyone trying to
>   steer the composition towards their conception to a politically diverse moderation team
> - Acting one again unilaterally will not get this new team the approval of the community

The people actually doing the work asked for the same thing. @lassulus, carrying moderation at
the time, [2025-11-05][m-2025-11-05]: *"Want mods to be required to agree to new mods, don't want
SC to be able to appoint mods without mods agreeing."*

Choosing individual members is management. The SC's job is steering, and it has neither the time,
the relevant expertise, nor the standing to run recruitment for a volunteer project.

**And the principle already has a vote behind it.** [Vote 0004][v-0004] states that *"The SC is
not to intervene into day to day business of moderation, even during the interim period"*. What
this proposes is to make that the default for every team, rather than a clause that had to be
negotiated for one.

### Responsibility only works when it comes with authority

This is the part most often skipped, and skipping it is how volunteers get burned out and resign.
Someone who carries the blame for a team's outcomes but has to seek permission for its decisions
has the worst job in the project.

**None of this is a new idea in this project, and it is not an outsider's.** @tomberek, now an
SC member, set it out on Discourse in [November 2021][d-values], four years before the SC
existed, in a thread asking what values the NixOS project actually expresses:

> Responsibility and authority must be commensurate. […] Authority without responsibility leads
> to bullying and tyranny. Responsibility without authority leads to stagnation and unfairness.
> […] The right person to make overall decisions about a topic should also be the person who is
> most responsible for it.

That is the whole of [team-charters.md][charters] in three sentences, written long before there
was an SC to apply it to. What this proposes is not a new principle; it is the first time the
project would write that principle down as a rule and be held to it.

The warning is on the record too. In the rationale for [vote 0004][v-0004], @philiptaron listed
*"Steering without steering"* among the ways it could fail:

> When there's suspicion, the SC or specific SC members will be very tempted to backchannel,
> micromanage specific decisions, or fixate on specific outcomes to the detriment of the larger
> job of steering and direction setting.

And the cost of getting it wrong is on the record as well. @lassulus, carrying moderation
essentially alone, [2025-11-05][m-2025-11-05]: *"Not fun to do, no failover, am the only one…
not sustainable, wanted to offboard as a mod before."*

People do not leave because the work is hard. **They leave when the work is theirs and the power
is not.**

### One name answering is not one person deciding

The obvious objection is that this installs a dictator on every team. It does not, and the
distinction is worth stating precisely: what gets centralised is **answerability**, not
decision-making. A team can run itself by consensus, by majority vote, by rotating whoever has
time this month. That is entirely the team's business, and the SC has no view on it.

What the SC needs is one name that cannot be dissolved into a group. A body that answers
collectively answers for nothing: when everyone is responsible, the honest reply to *"why did
this not happen?"* becomes *"the team decided"*, and there is nobody left to ask the next
question. That is not a hypothetical failure mode. It is the one the current arrangement already
produces, where the SC picks the moderation team's members and then nobody at all is answerable
for whether moderation works.

So the responsible person answers for outcomes inside the remit **even when they argued the other
way and lost the vote inside their own team.** That is a real cost, and it is precisely what the
five powers are paid for. The bargain is symmetrical: authority you cannot be second-guessed on,
in exchange for answerability you cannot delegate away. Anyone unwilling to take the second half
should not be handed the first.

> **The rules that follow from this: [team-charters.md][charters].** The SC decides a remit and
> one responsible person; the team organises itself however it likes; that person is granted five
> specific powers and answers for the remit even when the team decided otherwise; and the SC keeps
> two levers only: appoint and remove.

---

## What the SC stops doing, and what it gets back

This is the part that should read as relief.

| Stops | Because |
| --- | --- |
| Approving sponsors one at a time | Gate test 3: one prospectus rule replaces every such ballot |
| Interviewing candidates for team seats † | It appoints one responsible person; they pick their own team |
| Overturning calls that were a team's to make † | Wrong call inside the remit: change the remit or the person, not the call |
| GSoC mentor mechanics, Slack invites, credentials | No named body is blocked; nobody needs elected judgment for this |
| Second-guessing decisions a team already owns | Gate test 2 hands them straight back |
| Chasing publication of its own notes | The record is written as the work happens |
| Carrying "Old topics" from month to month | Items either decide or default; nothing accumulates |
| Absorbing anything that arrives by chance | If it did not come through the Gate, it is not SC work |

† These two follow from [team-charters.md][charters], the second rule file, which can be adopted
separately.

Concretely, measured against this archive:

- The AI policy took part of at least six meetings across four months and was never
  voted on. Under this process: **a fixed ceiling of committee hours, and a decision either way.**
- Every individual sponsor decision (four in [vote 0013][v-0013] alone, more waved
  through in meetings since) becomes **one rule, decided once.**
- The defense-contractor question would have been answered in January 2026, instead of
  being fought twice and still being open.

---

## A record a voter can actually check

Every part of this proposal (the cap, the packet, the deadline, the public record) exists to
make one question answerable at election time: **did the person I voted for represent me?**

Today that question is close to unanswerable, and not because anyone is hiding anything.

- **The evidence has no edges.** One topic is spread over an unknown number of meetings,
  and nothing tells you when you have found all of it. The AI policy alone runs through at
  least six sets of minutes and still has no decision at the end of them.
- **It arrives late and uneven.** Thirty-five days and more, with an eight-week gap, in
  formats ranging from a filled-in template to a near-verbatim transcript.
- **The decision point is often invisible.** A topic can be raised, tabled, raised again,
  and settled somewhere else entirely. Some votes appear in the vote log; others exist only
  inside minutes; the CUDA approval happened in a Zulip thread and prompted @philiptaron to
  ask, on [2026-03-25][m-2026-03-25], *"Is this a vote? I think so. But it's really
  unclear."*
- **And absence explains everything.** With many meetings, several running well past their
  timebox, any individual's non-participation is always plausibly innocent. A record this
  easy to miss for good reasons is a record nobody can be held to.

So voters fall back on what is easy to find: what individual SC members say publicly about their
own work. That is the least reliable source available, and it quietly rewards whoever
communicates the most rather than whoever did the most.

A capped process produces something finite instead:

- **A countable number of items.** Every decision of a term is one file in one place. You
  can count them, and you can read all of them in an evening.
- **The same shape every time.** Question, options, who argued what, who voted how and why,
  decided or defaulted. Comparable across items and across people.
- **Participation becomes signal instead of noise.** A written position takes minutes and
  can be filed at any point in the written round. Missing that is a choice rather than a
  scheduling accident, which is what finally distinguishes the members who did the work
  from those who did not, in a way that is fair to both.
- **Failures are counted too.** Questions that hit their default sit in the same list, with
  the participation record attached.

The point is not to catch anyone out. It is that judging your representatives should not require
inferring a pattern from eight months of uneven minutes, and it should not depend on trusting
anybody's summary of their own conduct, this document's included. It should be a matter of
reading a bounded list and seeing what each person did on each item.

> **The rules that produce this: [§7 The Record][process-record] and
> [§8 Participation][process-participation].**

---

## What the community gives up

This should be said plainly rather than buried.

If you escalate a question to the SC, you are asking seven elected people to decide it for you.
When they do, **that is the answer**, and it stands for a fixed period. You do not get to
re-litigate it because you dislike the result. You wrote the options; the SC picked one.

If you think they picked badly, the remedy is the one democracies use: the record is public,
every position is attributed, and you vote for someone else next time.

In exchange, you get something the community does not have today: **an answer by a date fixed in
advance, guaranteed.** Either the SC decides, or you do.

Every decision carries an [automatic review][process-review], which is what makes it safe to
decide quickly on incomplete information. Before then, reopening requires passing the Gate again
with genuinely new facts.

---

## Objections

### "This will produce worse decisions."

Sometimes, yes. That is the trade, made deliberately. A wrong decision costs one
correction and already has a review date on it. No decision costs indefinitely and cannot
be appealed. The defense-contractor question has now been not-decided twice; nobody would
argue the community is better off for it.

### "We're volunteers. This is too much process."

It is a **ceiling on your time, not a demand on it.** The baseline is one written
response and no meeting at all. The maximum any single question may ever take from the
committee is a few hours, fixed in advance. Compare that to six meetings on an AI policy that
still does not exist.

### "This is overregulation. A volunteer project shouldn't need this much rulebook."

The objection above is about your calendar. This one is about the project, and it deserves a
separate answer.

Count what is actually here: **four moving parts** (a gate, a packet, a clock, a default), and
every one of them *removes* work from the SC rather than adding it. The Gate hands questions
back to whoever already owns them. The Packet moves preparation to the people who are blocked
and know the domain. The Clock caps what any question may consume. The Default closes an item
without another meeting. No new committee, no new role, no new reporting line, and in the
baseline case **no meeting at all.**

Then compare it with what it replaces, which is the part this objection usually skips. The SC is
not currently running without process. It has agendas, timeboxes, correspondence slots, motions
to table, and deferrals. The minutes are full of them. What it does not have is any of that
written down, which is why a timebox can be [crossed out inside the document][m-2026-01-07], why
one absent member can [table three items at once][m-2026-03-25], and why one topic can run
through fourteen sets of minutes without resolving. **The alternative to a written process is not
less process. It is the same process, unwritten, applied differently every week, and impossible
to improve.** You cannot fix a rule that was never stated.

This matters most for delegation, which is the largest single saving on offer. An unwritten norm
of "the team decides" evaporates at exactly the moment it is needed: when a team makes an
unpopular call and the pressure to intervene is highest. [Vote 0004][v-0004] had to negotiate
*"The SC is not to intervene into day to day business of moderation"* as a special clause, for
one team, in one vote, because no general rule existed to point at. Writing it down once is what
lets delegation survive a controversy, and delegation that survives is the only kind that
actually takes work off the SC. *([team-charters.md][charters] is where that rule lives.)*

### "Some questions genuinely need more time."

Then extend, by recorded vote, up to the ceiling.

And if a whole *class* of question needs more than the ceiling allows, raise the ceiling. **N**
and **S** are variables, not principles: every rule in the process reads identically at N = 5 or
S = 2 hours, and turning them up changes how much time the SC spends, not how the process works.
Nothing about its character depends on the number being three. What the design does depend on is
that a ceiling exists at all. Remove it and the failure this exists to fix comes straight back.

And if the ceiling is genuinely wrong for one particular question, the outcome is still not
chaos: it is the people who asked deciding for themselves, which is exactly what they were doing
before they asked.

### "Three weeks does not give me time to write to my representative and argue my case."

It gives you more than you have now, not less. Today the window is either unknowable or
zero: you usually learn a question was settled after the fact, and sometimes cannot tell a
decision happened at all: *"Is this a vote? I think so. But it's really unclear"*
([2026-03-25][m-2026-03-25]). Under this process the packet is public from day one,
positions are published as members file them, and the closing date is known in advance. For
the first time there is a window you can actually aim at, and you can see who is leaning
which way while it is still open.

And if three weeks really is too short, make it six. **D** and **W** are variables: every rule in
the process reads identically at either value, so lengthening them costs nothing structural. It
buys the community more time to weigh in and delays the answer by exactly that much, a trade you
can argue about on its merits, without touching the design. For questions that set public policy
a longer window is probably right, and the trial period exists precisely to find out.

**The part worth defending is not the length. It is that the window closes.**

### "Restricting who may escalate shuts out newcomers."

It restricts exactly one thing: what can compel the SC's capped attention. Every other
route stays as open as it is today, and joining a team is open to anyone. A newcomer with
a good question has the same path as a ten-year contributor: talk to the people doing the
work. If that path is blocked, the problem is the responsible person, and that has its own
remedy.

### "Requiring a reason to abstain is a penalty on abstaining."

Abstaining stays completely legitimate, and recusal is recorded as recusal. Vote #11 failed
because abstention was silent *and* free, not because abstention exists. A one-line reason
costs nothing to write and is the difference between "I have a conflict of interest here" and
a record that cannot be read at all.

### "The community will be angry about decisions it doesn't like."

It is already angry about decisions that never come. Anger at a clear answer is survivable
and fades. Resentment at eight months of silence does not.

### "This makes the SC look bad when it fails."

The SC already fails; today the failure is invisible and unattributed, which is worse,
especially for the members who *did* show up and *did* do the work. Right now they are
indistinguishable from those who did not.

### "Who decides what passes the Gate? That's a lot of power for one chairperson."

It is less power than it looks, and it is the same rotating chairperson the SC already picks at
every meeting. They answer in public, within a week, against four written tests, with a reason,
and any two SC members can overturn it. The job is closer to clerical than judicial, which is the
sense in which @philiptaron called the role *"a sacrifice role, not a power role"*
([2025-12-10][m-2025-12-10]).

The one real power a gatekeeper has is **the power to sit on something**, and that is the one
this removes. If the chairperson does not answer within the week, or if the SC never picked one,
the asker's default takes effect and authority over that question returns to them permanently.
Silence is the most expensive thing a chairperson can do, not the cheapest.

If a week seems tight for a volunteer holding the role, make it two: **G** is a variable like
every other, and the process is unchanged at any value of it. The demand is one paragraph against
four written tests, not a judgment. What must not change is that the window has an end.

Compare with today, where admission is decided by whoever happened to notice something, in a
private inbox, with no reason given and no record at all.

### "One responsible person per team creates little kingdoms."

[One name answering is not one person deciding](#one-name-answering-is-not-one-person-deciding).
The team still organises itself however it likes, including by vote; what is centralised is
answerability, not decision-making. So this creates one accountable name where today there is
frequently none. Their authority is bounded by the team's remit, the SC can remove them by public
vote, and the record shows whether questions that belonged inside the team kept landing on the SC
instead. Compare with today, where the SC picks the members and then nobody at all is answerable
for whether the team works.

---

## Adoption and trial terms

Both rule files can be adopted the same way `async-voting.md` was: **one majority vote in the
SC**, each on its own. No constitutional change is required, because neither touches the SC's
powers, only how it organises its own work.

Suggested: **adopt as a three-month trial**, with the success criteria agreed in advance and
measured against the public archive.

| Measure | Today | Target |
| --- | --- | --- |
| Longest open question | 8+ months | 3 weeks |
| Abstentions with no reason | Common | Zero |
| Individual sponsor ballots | Routine | 0, replaced by one rule |
| Days from meeting to published record | 35–39 | 7 |
| Committee time per decided question | Unbounded | ≤ 3 hours |

If after three months the numbers have not moved, throw it out. This proposal should be held to
the standard it sets for everything else: decide, measure, review.

Adopting the *shape* and arguing about the numbers afterwards is the cheaper order to do this in,
because the trial is what produces the evidence for what the numbers should be.

---

## Summary

| | Today | Proposed |
| --- | --- | --- |
| **How a question arrives** | Whoever noticed it, private inbox | A packet, through a public Gate |
| **Who may ask** | Anyone who gets the SC's attention | A body doing the work, via its responsible person |
| **Who prepares it** | The SC, from scratch | The asker, with drafted options |
| **How teams are formed** † | Case by case, no settled rule | The SC appoints one responsible person; they pick the team |
| **What that person gets** † | Responsibility, permission still needed | Responsibility *and* the authority to use it |
| **How long it may take** | Unbounded | A fixed ceiling of committee hours, within a fixed deadline |
| **If nobody decides** | It returns next month, forever | The asker decides, permanently |
| **If you don't participate** | Free and invisible | Allowed, but recorded with your name |
| **Scope** | Anything that arrives | Escalated questions plus four named duties |
| **The record** | Often 35+ days late, sometimes missing | Published on a deadline, written as work happens |
| **Judging your representative** | Infer it from months of uneven minutes | Read a bounded list of decisions and positions |
| **How a vote runs** | `async-voting.md` | `async-voting.md`, unchanged |

† From [team-charters.md][charters], the second rule file.

---

## The rule text

Everything above is reasoning. The rules themselves are two files, and they are short:

- **[decision-process.md][process]**: the Gate, the Packet, the Clock, the Default, the Record,
  Participation, and the dials.
- **[team-charters.md][charters]**: chartering a team, what the responsible person may do, and
  the grounds for removal.

Neither depends on the other, and each can be voted on separately.

## Sources

Every quote in this document links to where it came from. All of them are in the public archive
at <https://github.com/NixOS/steering-committee>, with one exception: @tomberek's 2021 post on
responsibility and authority, which is [on Discourse][d-values].

[process]: ../process/decision-process.md
[process-dials]: ../process/decision-process.md#0-dials
[process-gate]: ../process/decision-process.md#3-the-gate
[process-who]: ../process/decision-process.md#2-who-may-ask
[process-packet]: ../process/decision-process.md#4-the-packet
[process-clock]: ../process/decision-process.md#5-the-clock
[process-default]: ../process/decision-process.md#6-the-default
[process-record]: ../process/decision-process.md#7-the-record
[process-participation]: ../process/decision-process.md#8-participation
[process-review]: ../process/decision-process.md#9-standing-and-review
[charters]: ../process/team-charters.md
[async-voting]: ../process/async-voting.md
[d-values]: https://discourse.nixos.org/t/what-are-the-values-that-you-see-being-expressed-in-the-nixos-project/15959/8
[m-2025-11-05]: https://github.com/NixOS/steering-committee/blob/main/minutes/2025-11-05.md
[m-2025-11-13]: https://github.com/NixOS/steering-committee/blob/main/minutes/2025-11-13.md
[m-2025-12-10]: https://github.com/NixOS/steering-committee/blob/main/minutes/2025-12-10.md
[m-2026-01-07]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-01-07.md
[m-2026-03-04]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-03-04.md
[m-2026-03-11]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-03-11.md
[m-2026-03-25]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-03-25.md
[m-2026-04-08]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-04-08.md
[m-2026-04-15]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-04-15.md
[m-2026-04-22]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-04-22.md
[m-2026-05-13]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-05-13.md
[m-2026-05-20]: https://github.com/NixOS/steering-committee/blob/main/minutes/2026-05-20.md
[v-0004]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0004-bootstrap-community-team.md
[v-0005]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0005-full-moderation-team.md
[v-0010]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0010-delist-helsing-hiring-post.md
[v-0011]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0011-meeting-note-sla.md
[v-0013]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0013-nixcon20206-sponsorship-1.md
[v-0016]: https://github.com/NixOS/steering-committee/blob/main/vote-logs/0016-sponsorship-tier-integrity.md
[c-minutes]: https://github.com/NixOS/steering-committee/commit/a882ca6bcaea81f743920576f38d1264ea51cc5f
[c-votes]: https://github.com/NixOS/steering-committee/commit/d8ae8d54497e40885059afbe8b63d6925883377b
