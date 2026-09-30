# CGOV.9 - Establish and Operate Internal Control {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Corporate Governance Principles Framework* (21 September 2026), `Engineering DPF Suite/CORPORATE-GOVERNANCE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Method pattern
> **Status:** Stable

## CGOV.9:1 - Problem frame {#problem-frame}

Use this pattern when a corporation's objectives depend on controls that do not operate, leave a consequential exposure untreated, impose needless burden or give governing participants an unreliable picture of what happens.

Start from the objective and the work in which failure could arise. Select controls that address the exposure, provide the means to perform them, and examine their operation and interaction. Return the controls actually established, what is known about their functioning, and the remaining limitations or correction.

Internal control spans operations, reporting and compliance. This pattern governs their connection to corporate objectives and oversight. Particular statistical, accounting, technical or administrative operations retain their own methods. An adequate existing control can continue without redesign.

## CGOV.9:2 - Problem {#problem}

A policy can require two approvals while one person controls both accounts. A reconciliation can detect a discrepancy after the recipient can no longer recover the money. A board can receive only the count of completed checks, although nobody has established that they address the exposure.

The opposite failure adds approvals to every ordinary action. Delay and diverted attention grow while the important bypass remains. The practitioner needs a control that changes what can happen or what can be detected and corrected, with a burden the corporation can sustain.

## CGOV.9:3 - Forces {#forces}

Controls should improve the prospect of achieving an objective while preserving useful work. Earlier prevention may reduce exposure but impede operations; later detection can be cheaper while allowing an irreversible loss. Separation of duties can help but may exceed a small team's available capacity.

Some controls are required by applicable rules. Others are design choices. Their present force, practical effectiveness and justification are separate questions; criticizing a requirement does not amend it.

## CGOV.9:4 - Solution {#solution}

Connect the objective, failure mechanism, control action and response. Then make that connection work in the corporation's actual arrangement.

### CGOV.9:4.1 - Identify the objective and exposure {#identify-the-objective-and-exposure}

State the objective in terms that let practitioners recognize success and failure. For example, pay the entitled counterparty once, report the corporation's commitments faithfully or prevent an unauthorized release.

Follow a representative operation through its participants, information, decisions and resulting change. Identify where an error, misuse, collusion or override could defeat the objective. Use existing knowledge and incidents where they answer the question. A complete risk inventory is unnecessary before correcting a known, consequential weakness.

Retain the conditions that matter: transaction population, authority, technology, timing and the consequence of a failure. A control appropriate for a reversible small purchase may be inadequate for an irreversible large payment.

### CGOV.9:4.2 - Choose a useful control and response {#choose-a-useful-control-and-response}

For each important exposure, determine what action would prevent it, detect it soon enough or limit and correct its consequences. Name who performs the action, what information it uses and what happens when it identifies an exception.

Compare credible alternatives, including a sufficient existing control and a narrower correction. Consider the likely reduction in exposure alongside staffing, access, delay, false alarms, displaced work and maintenance. Remove a discretionary duplicate that adds no useful protection or information.

Where duties should be separated, check the actual access and influence. Two names on a chart do not provide separation if the same person can approve both steps. When separation is impractical, identify an allowed alternative and the exposure it leaves. If an applicable rule requires separation, a cheaper alternative needs the appropriate authorized change before it can replace that requirement.

### CGOV.9:4.3 - Establish the ability to perform it {#establish-the-ability-to-perform-it}

Fit the chosen control into the work that produces the exposure. Provide the needed authority, competent participants, access, time and supporting information. Recover dependencies on software configuration or outside providers where a failure there would disable the control.

Use the actual operational method. ADM can establish entitlement, authorization and reconciliation for administrative provision; OPS.18 can manage an operating-quality or reliability problem. The corporate control question is whether those contributions address this objective together, under an accountable arrangement.

Make exception handling usable. A performer needs to know what can continue, what must be held and who may decide an unresolved case. A monitoring message without a capable recipient and response leaves the exposure untreated.

A design may be the first useful result when implementation has not been assigned. Keep it as a design. A claim that the control is established requires the necessary changes to have taken effect.

### CGOV.9:4.4 - Examine operation and interaction {#examine-operation-and-interaction}

Determine whether the control works in the circumstances for which reliance is proposed. A walkthrough can reveal a missing step or access conflict. Observed executions can show whether the action was performed. Different claims require different support; one successful demonstration does not establish sustained effectiveness.

Examine combinations as well as individual steps. Does the first operation give the next one usable information? Can a person bypass both? Does the response arrive within the interval in which it can still help? Does the incentive arrangement encourage participants to hide the exception?

Reuse adequate observations and current results. Select another test only when it can change the control or the conclusion about it and warrants its burden, or when the governing requirement calls for it. Preserve unresolved exposure instead of treating absent failures as proof that the arrangement is effective.

### CGOV.9:4.5 - Correct and return the governing result {#correct-and-return-the-governing-result}

Send a material deficiency to the participant able to correct it and to the governing recipient who needs it. Distinguish an implementation error, inadequate design, missing capability and an objective that is no longer attainable under the assumed conditions.

Apply a correction within existing authority when available. Use CGOV.11 for a corporate decision that the correction actually requires, and CGOV.14 if the governance arrangement itself must change. Routine reassignment under adequate existing powers need not become a constitutional change.

Return which controls are operating, the conditions under which they are relied on and the deficiencies that remain. Keep proposed corrections separate from completed changes. Choose follow-up by the failure and receiving decision; a permanent new report is not the default result.

## CGOV.9:7 - Conformance Checklist {#conformance-checklist}

Is the objective clear? Does the control address a specified failure mechanism? Can the assigned participants perform it and respond within the useful interval? Do the controls work together? Are design, implementation, observed operation and stronger effectiveness claims supported separately? Is the remaining burden justified?

## CGOV.9:9 - Consequences {#consequences}

The corporation can retain controls that help, correct specific weaknesses and remove unnecessary discretionary work. Some exposure remains because judgement, outside events, override or collusion can defeat an arrangement. A useful conclusion states that remaining limit rather than promising certainty.

## CGOV.9:12 - Relations {#relations}

CGOV.3 identifies relevant powers. CGOV.4 helps design the needed governing contributions, and CGOV.8 identifies the corporate information duties that a control may need to support. CGOV.10 obtains a separately scoped audit or assurance conclusion; CGOV.13 uses material control findings in continuing oversight.

OPS.18 supplies operating-quality and reliability interventions. ADM supplies the relevant administrative operations. B.1.5.EW and CGOV.16 help recover constituent and encompassing work when a control succeeds locally but fails in its combination.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-cgov/contract/CGOV-3#root for authority; spec://ai.lev/fpf-eng-ops/contract/OPS-18#root where an operating-control contribution is needed. @status:spec/done

#source spec://ai.lev/fpf-eng-cgov/source/CGOV-9
