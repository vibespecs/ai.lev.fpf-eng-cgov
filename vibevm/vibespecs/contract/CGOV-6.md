# CGOV.6 - Expose Conflicts and Related-Party Interests {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Corporate Governance Principles Framework* (21 September 2026), `Engineering DPF Suite/CORPORATE-GOVERNANCE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Stable

## CGOV.6:1 - Problem frame {#problem-frame}

Use this pattern when a corporate matter may be influenced by a participant's other interests or duties, when a transaction involves a connected party, or when a proposed exclusion needs a reason beyond disagreement with that participant.

Begin with the matter, the participant's contribution and the duty or rule that governs it. Identify the potentially competing interest and how it could affect the contribution. Return a supported conflict account, the applicable participation or disclosure conditions and any unresolved question that changes handling of the matter.

## CGOV.6:2 - Problem {#problem}

A director may influence a purchase from a business in which they have an interest. A controlling shareholder may benefit from terms that disadvantage other holders. A specialist's payment may depend on the transaction they are asked to assess. Without recovering these relations, an apparently ordinary recommendation can conceal a conflicted contribution.

Yet differences in preferences are common in legitimate corporate work. One director may prefer growth and another distributions; an engineer and a salesperson may favor different product characteristics. Declaring a conflict merely because their preferences differ can suppress useful deliberation and obscure the actual duty at risk.

## CGOV.6:3 - Forces {#forces}

The corporation needs relevant knowledge, including knowledge held by interested participants. It also needs judgement and participation under the applicable duties and safeguards. Early disclosure can permit appropriate handling without an accusation of misconduct. Excessive investigation can delay a usable decision; inadequate inquiry can leave an important interest hidden.

## CGOV.6:4 - Solution {#solution}

Recover the conflict as a relation in a particular matter. Identify its consequences under the applicable corporate rules before selecting how to handle it.

### CGOV.6:4.1 - Connect the matter, participant, duty and interest {#connect-the-matter-participant-duty-and-interest}

Name the proposed act or decision and the participant's actual contribution: preparing information, negotiating, advising, deliberating, voting or implementing. Recover the duty or participation condition relevant to that contribution. A shareholder, a director and an external adviser need not have the same duties even when they support the same outcome.

Identify the interest or other duty that could affect the contribution. It may involve an economic benefit, a family or business relationship, another appointment, dependence on a participant, or an incentive tied to the outcome. Explain the influence that matters here. Do not infer it solely from a broad label such as “management” or “investor.”

A conflict can concern the risk of affected judgement before any improper act is shown. Conversely, an allegation of misconduct needs its own basis; identifying a conflict does not prove that allegation.

### CGOV.6:4.2 - Apply the relevant related-party and participation rules {#apply-the-relevant-related-party-and-participation-rules}

Establish which definition governs the present use. A reporting definition of a related party and a rule requiring transaction approval may cover different relations or thresholds. Apply each to its own question.

Use existing qualified ownership, appointment and relationship information where sufficient. Determine the consequences of the established relation: disclosure, restricted participation, another decision body, a required review or an applicable exception. Several conditions may apply together.

Keep an exemption within its stated scope. An exception from one approval procedure does not by itself remove a different disclosure or substantive duty. Equally, a related-party label does not by itself establish a prohibition: the applicable rule and transaction conditions decide what is required.

### CGOV.6:4.3 - Resolve the uncertainty that changes handling {#resolve-the-uncertainty-that-changes-handling}

Separate an established relation, a plausible concern and an unresolved factual or legal question. Ask what answer would change participation, the permitted act or reliance on the contribution.

Use a sufficient current declaration or other qualified result without rebuilding a complete interests register. Seek additional information where its attainable contribution justifies the acquisition, interpretation, delay and displaced work, or where a binding condition requires it. A required condition that cannot be established can prevent the dependent act even when further investigation is not worthwhile.

Where a legal rule itself is uncertain, obtain the relevant qualified interpretation or limit the conclusion. Do not make the uncertainty disappear by assuming either that the participant is harmless or that every participation must stop.

### CGOV.6:4.4 - Return the conflict and its consequences {#return-the-conflict-and-its-consequences}

Give the practitioner handling the matter the relevant duty, interest, affected contribution, applicable rule and resulting conditions. Identify any required declaration and its recipient, exclusions or other safeguards, while distinguishing a required action from one already performed.

A sufficient answer may be short: the disclosed connection triggers a particular participation restriction; the stated exception applies; no relevant conflict is supported on the present basis; or one named fact prevents deciding. Retain enough reasoning for the receiving use, without requiring a new form when an existing working communication suffices.

Use CGOV.7 when the matter needs an independent review or an arrangement for eligible participants to decide. Reopen only the affected conclusion if the interests, terms, participants or applicable rule change.

## CGOV.6:7 - Conformance Checklist {#conformance-checklist}

Can the receiver identify the matter, participant, contribution, duty and relevant interest? Does the rule used answer this participation or reporting question? Are established facts, uncertain concerns and allegations distinguished? Are the necessary safeguards and their actual performance kept separate? Does additional inquiry have a defined contribution and an attainable scope?

## CGOV.6:9 - Consequences {#consequences}

The corporation can handle a concern before it becomes concealed influence or an unsupported accusation. Valuable knowledge can remain available under appropriate participation conditions. A bounded no-conflict answer also allows work to proceed. Some cases retain unresolved facts or legal interpretations that limit only the conclusions depending on them.

## CGOV.6:12 - Relations {#relations}

CGOV.2 supplies relevant ownership and control relations; CGOV.3 identifies the participant's authority. CGOV.7 uses the conflict account to arrange review and eligible decision participation. CGOV.8 handles the required information and disclosure questions; CGOV.11 performs the corporate decision.

PSD.9 can represent legitimate value disagreements without resolving corporate eligibility. FPF A.6.REL helps recover the participants and conditions of the relation. C.11.DUA helps evaluate discretionary further inquiry; questioning a requirement's justification does not itself change its present legal force.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-cgov/contract/CGOV-1#root/.3 for the matter and duties; FPF spec://ai.lev/fpf-spec/contract/A-6-REL#root for participants and conditions. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-cgov/contract/CGOV-11#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-7#root @status:spec/done

#source spec://ai.lev/fpf-eng-cgov/source/CGOV-6
