# CGOV.2 - Distinguish Shareholding, Voting Power, and Control {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Corporate Governance Principles Framework* (21 September 2026), `Engineering DPF Suite/CORPORATE-GOVERNANCE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Stable

## CGOV.2:1 - Problem frame {#problem-frame}

Use this pattern when a proposed vote, financing, appointment or change of ownership depends on who can receive returns, cast votes, give consent or influence the outcome. It helps a governance practitioner explain those relations for a particular corporation and matter.

Begin with the relevant holders and the rights attached to their interests. A current, sufficient ownership account can be used directly. The first useful result is an answer such as “the founder receives 40% of this distribution but has 400 of the 460 votes on this resolution; this borrowing also requires a separate class consent.”

## CGOV.2:2 - Problem {#problem}

A capitalization table shows holdings but may hide different voting rights, nominee arrangements, class consent, voting agreements or indirect influence. Multiplying ownership percentages through a group can describe one economic interest while misdescribing the ability to determine a decision.

“Control” is particularly easy to overstate. The ability to block a reserved transaction, elect some directors, determine a shareholder resolution and direct another person's conduct are different claims. A finding under an accounting, takeover or beneficial-ownership rule may answer only that rule's question.

## CGOV.2:3 - Forces {#forces}

Keep the account small enough to use while retaining differences that change the matter. Separate exercisable rights from observed influence, and current rights from conditional or future ones. A simple percentage is convenient; the relevant outcome can also depend on coalitions, eligibility, separate consent and the allocation of powers between organs.

## CGOV.2:4 - Solution {#solution}

### CGOV.2:4.1 - Ask which outcome depends on the holdings {#ask-which-outcome-depends-on-the-holdings}

Name the corporation, matter and time. State whether the receiving work needs an economic allocation, the votes available for a resolution, an appointment power, a required consent, or a specified control assessment. More than one can matter, but each needs its own answer.

For a legally defined control question, use that rule's criteria. For a practical influence question, state the decision and the mechanism by which a participant could affect it. Avoid an unqualified label such as “ultimate controller” when the grounds establish only one narrower ability.

### CGOV.2:4.2 - Recover rights before calculating percentages {#recover-rights-before-calculating-percentages}

Identify the relevant interests, their holders and the terms that affect this matter. Separate the registered holder from a person entitled to economic benefits or able to instruct the holder when that distinction changes exercise of the right.

For each material interest, recover the needed rights from its terms: participation in a specified distribution, votes for this resolution, class approval, appointment or removal, transfer, or conversion. These are possible rights, not a claim that every share carries each one. Record dates, expiry, default or conversion can change the answer. An unexercised option can matter to a future scenario without supplying present votes.

Keep the source and uncertainty with a contested right. Reuse sufficient established terms. Investigate an additional holding, agreement or intermediary only when its resolution can change the receiving result.

### CGOV.2:4.3 - Calculate the relevant entitlement and possible outcome {#calculate-the-relevant-entitlement-and-possible-outcome}

For the chosen matter, apply its voting or allocation rule to eligible rights. Use the rule's denominator: all eligible votes, votes cast, a class, persons, or another defined basis. Include thresholds, quorum and exclusions when they affect the question. Do not infer an actual passing vote from a count of possible votes; attendance, casting and any additional conditions may remain to be established.

Follow indirect relations one link at a time. Identify what each link transmits. Proportional economic participation, voting instruction, nomination and a veto are not interchangeable operations. When a coalition matters, distinguish an enforceable or otherwise established agreement from an assumed willingness to cooperate.

State the resulting abilities separately. For example: the holder can block this amendment; the two holders together could pass this resolution under the supplied conditions; the board still has the power to decide the operating transaction. A right to influence who sits on the board does not by itself give the holder the board's powers.

### CGOV.2:4.4 - Return the decision-relevant account {#return-the-decision-relevant-account}

Give the receiver the holdings or relations needed to understand the result, the applicable conditions and the consequence for the matter. A table or graph is useful when several relations must be held together; a short calculation can suffice for a simple class vote.

Use CGOV.3 to establish the relevant appointment or decision authority. Return an unresolved rule, agreement or holder identity only with the particular conclusion it prevents. A supported economic calculation remains usable even if a separate voting claim is unresolved.

## CGOV.2:7 - Conformance Checklist {#conformance-checklist}

Does each percentage name what is allocated and its denominator? Are class rights, eligibility and material separate consents included? Does each control statement identify the outcome and mechanism it concerns? Are assumed cooperation and future rights distinguished from presently supported ones? Can the receiver see what the result permits them to conclude and what remains unresolved?

## CGOV.2:9 - Consequences {#consequences}

Financing, conflict, disclosure and minority-rights work can use a common account without erasing their different questions. A new instrument or agreement can require recalculation of only the affected rights. The method can reveal that an apparently dominant holder needs another participant's consent, or that an economic majority has little voting influence.

## CGOV.2:12 - Relations {#relations}

CGOV.1 bounds the corporation and matter; CGOV.3 uses the resulting rights to establish authority. Conflict analysis, disclosure and minority protection can consume the same account.

FIN.11 compares financing mixes and can use the consequences of a proposed rights change. Its financial comparison does not establish the rights this pattern recovers. FPF A.6.REL supports distinguishing the participants and conditions of a relation; the corporate rules provide the domain predicates.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-cgov/contract/CGOV-1#root for the matter; FPF spec://ai.lev/fpf-spec/contract/A-6-REL#root for the distinct relations. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-cgov/contract/CGOV-1#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-12#root @status:spec/done

#source spec://ai.lev/fpf-eng-cgov/source/CGOV-2
