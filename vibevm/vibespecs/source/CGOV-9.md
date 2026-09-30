# CGOV.9 - Establish and Operate Internal Control: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Corporate Governance Principles Framework* (21 September 2026), `Engineering DPF Suite/CORPORATE-GOVERNANCE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## CGOV.9:5 - Archetypal Grounding {#archetypal-grounding}

### CGOV.9:5.1 - Two approvals that use one unverified instruction {#two-approvals-that-use-one-unverified-instruction}

In a constructed payment operation, a clerk can change a supplier's bank details. A second employee approves the payment but checks only the invoice amount. Both rely on the same incoming message for the new account. The identified exposure is payment to an account that the supplier did not designate.

Adding a third amount approval leaves that exposure. The selected control instead confirms a bank-detail change through a previously established supplier contact and separates that confirmation from release of the payment. The confirmer needs the established contact information and authority to hold the change; the releaser needs the confirmed result.

A walkthrough reveals that confirmation uses the new contact number entered from the same change request. The confirmer could therefore reach a destination supplied by the unverified instruction. The team restores use of the previously established supplier contact and protects its update route before relying on the control. After implementation, observed operation can support the bounded claim that this route is used; it does not prove immunity to every fraud or collusion.

### CGOV.9:5.2 - Detection after the useful response window {#detection-after-the-useful-response-window}

A small organization reviews payment discrepancies monthly. A new service makes payments irreversible within hours. The existing review can still explain a past discrepancy, but its timing cannot provide the intended early containment.

The practitioner separates those uses. Retain the review where it remains useful, and compare a permitted pre-release control or timely alert and response for the irreversible exposure. Staffing a separate department is only one possible arrangement. If no feasible permitted response meets the needed protection, report that limitation before treating the new service as adequately controlled.

## CGOV.9:6 - Bias-Annotation {#bias-annotation}

Visible paperwork can make a weak control look reliable. Recent absence of loss can make it seem unnecessary. Examine how the control changes the exposure and what the observation actually supports. Include the cost imposed on ordinary work and the possibility that several controls share the same failure.

## CGOV.9:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

- **Completed checks stand in for controlled exposure.** Follow the control's action and consequence.
- **Several approvals repeat one unverified input.** Repair the shared source or dependence.
- **Detection is called prevention.** Compare the response time with the consequence being prevented.
- **The auditor becomes the operator of the control.** Keep management's operation and independent assessment appropriately separated.

## CGOV.9:10 - Architectural Rationale {#architectural-rationale}

A control is valuable through its effect in the work and its connection to a corporate objective. Its description and the observation of its operation play different roles. The arrangement must therefore connect control design, enabling conditions, actual execution and the governing response without using any one of them as proof of the others.

## CGOV.9:11 - SoTA-Echoing {#sota-echoing}

[COSO's Internal Control—Integrated Framework, Executive Summary](https://www.coso.org/_files/ugd/3059fc_1df7d5dd38074006bce8fdf621a942cf.pdf) distinguishes design, operation and interacting components, recognizes limits on assurance and allows elimination of ineffective controls.

This method concentrates those concerns on a selected exposure and its operating response. It does not claim that the examples implement the entire COSO framework. A policy catalogue can aid discovery, while a matter-specific walkthrough exposes how the chosen control is supposed to work. Changed operations, objectives, access or failure mechanisms reopen the affected control.


## CGOV.9:End {#end}
