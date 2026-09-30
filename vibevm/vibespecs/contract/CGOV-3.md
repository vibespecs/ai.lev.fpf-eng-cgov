# CGOV.3 - Establish Authority for Corporate Appointments, Removals, and Decisions {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Corporate Governance Principles Framework* (21 September 2026), `Engineering DPF Suite/CORPORATE-GOVERNANCE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Stable

## CGOV.3:1 - Problem frame {#problem-frame}

Use this pattern when a practitioner must determine who may appoint or remove a holder, authorize a corporate matter, delegate a power, or act under an existing delegation. It helps directors, company secretaries, executives and advisers resolve authority that a title or organization chart leaves ambiguous.

Begin with the corporation, proposed act and time from CGOV.1. The first result identifies the responsible organ or holder, the applicable power and its conditions. If an existing sufficient delegation covers the act, use it; this pattern adds no requirement to seek approval again.

## CGOV.3:2 - Problem {#problem}

A shareholder can nominate a director without making the appointment. An appointed director can participate in a board decision without individually holding the board's powers. An executive can have authority to buy equipment up to a limit while lacking authority for a larger purchase. An authority account that collapses these relations can send the matter to someone unable to make it effective.

A further failure is temporal: a valid future appointment is treated as effective today, or a revoked delegation persists in a directory.

## CGOV.3:3 - Forces {#forces}

A clear allocation of authority allows action and accountability. Its use depends on the act, the holder, applicable limits and time. Reusing an adequate arrangement saves delay; resolving a genuine uncertainty prevents an ineffective or unauthorized act. Corporate powers, contractual consents and the acts that exercise them must remain distinguishable.

## CGOV.3:4 - Solution {#solution}

### CGOV.3:4.1 - Recover the source and holder of the power {#recover-the-source-and-holder-of-the-power}

Name the act and corporation. Identify the provision or qualified interpretation that allocates the power: to shareholders, a board, another organ or a person, as applicable. Use the corporation's actual model. A two-tier board, a one-tier board and a closely held company can allocate contributions differently.

For an appointment or removal, determine who can initiate, nominate, decide and make it effective. Recover eligibility, consent, term and any other condition that changes the proposed act. A nomination identifies a candidate when the rule still requires another act of appointment. Removal from an office and the consequences for an employment or other contract may require separate answers.

For an existing holder, establish whether the relied-on appointment has taken effect and remains in force. Use the existing authoritative result where sufficient. A disputed date or missing condition requires investigation of that issue, not automatic recreation of every appointment record.

### CGOV.3:4.2 - Trace a delegation and its limits {#trace-a-delegation-and-its-limits}

Where the act relies on delegation, identify the delegating power, recipient, permitted acts, conditions and effective period. Check whether the source permits the delegation and, where relied on, further delegation. A person's title can help find that basis but does not supply its terms.

Apply the limits to the whole proposed act: for example, amount, kind of transaction, territory or requirement for joint action. A reserved matter is a matter retained for a specified decision or consent. Resolve its interaction with the delegation rather than treating the two as interchangeable permission labels.

Separate the authority to decide from the authority to communicate, sign or implement the result where different rules govern them. Also retain any other party's required consent. An organ's decision power does not establish that the consent has been given.

### CGOV.3:4.3 - Determine what can happen now {#determine-what-can-happen-now}

Apply the recovered conditions to the proposed act and its participants. State who can act under the established authority and retain every condition still to be met. A matter can require both a board decision and another party's consent. Identify the responsible participant for each required act, and distinguish an unperformed act from an unresolved rule about who may perform it.

Return the authority answer to the practitioner who will perform or arrange the corporate act. For a proposed appointment or delegation, the answer identifies who can make it and what governs its effect. It does not make the appointment or delegation; the authorized participants must perform that act under the applicable procedure.

For a routine matter, a short answer can suffice: “The existing purchasing delegation covers this purchase of 80; the limit is 100 and its stated conditions are met.” A disputed major transaction may need the provisions and reasoning retained so another practitioner can examine them. The method returns an answer about applicable authority and any remaining conditions. A new matrix or legal opinion is useful only when the receiving question needs it.

## CGOV.3:7 - Conformance Checklist {#conformance-checklist}

Can the receiver identify the corporation, act, responsible organ or holder, source of power, limits and effective period? Are nomination, appointment and removal distinguished where their effects differ? Does a relied-on delegation permit this act and any relied-on further delegation? Are decision, signing and other consents separated where necessary? Does the result distinguish established authority from its later exercise?

## CGOV.3:9 - Consequences {#consequences}

Practitioners can send a matter to the right decision maker, use a valid delegation without repeated approval and identify the act needed when authority is absent. This also makes financial recommendations and organizational changes easier to use. An authority conclusion still leaves the merits of the decision and its proper exercise to the methods that answer those questions.

## CGOV.3:12 - Relations {#relations}

CGOV.1 supplies the matter and governing basis; CGOV.2 supplies the relevant shareholder and control rights. The authority account can be used in board design, conflict handling and corporate decision work. It can also answer FIN.16's question about who should receive a finance recommendation without substituting authorization for financial judgement.

OCE.6 uses a corporate appointment or authority result when establishing an organizational arrangement; it does not supply the corporate-law predicates itself. For an administrative action that depends on this authority, ADM.2 can use the established appointment or delegation to identify the relevant participants and relations. FPF A.2.1 helps distinguish an effective assignment from a proposal or record. When practitioners cannot connect a rule-relevant operation to the encompassing corporate act, B.1.5.EW helps recover that constituent/encompassing relation; an authority chart alone is not a description of how the work is performed.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-cgov/contract/CGOV-1#root/.2 where the matter or rights are unresolved; applicable corporate powers. @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-cgov/contract/CGOV-13#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-14#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-4#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-5#root, spec://ai.lev/fpf-eng-cgov/contract/CGOV-9#root @status:spec/done

#source spec://ai.lev/fpf-eng-cgov/source/CGOV-3
