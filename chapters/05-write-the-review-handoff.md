# 5. Write the review handoff

*The reviewer needs the decision and the missing evidence, not a verdict written in advance.*

A good memo helps its reader act. “Our AI app has no IP issues” is a conclusion without a scope. “On November 26, the intended public source release includes a copied scheduling function; no permission for that use is recorded” gives the reader a version, an act and a gap they can investigate. It also leaves open whether some permission exists.

## Put the decision first

For Shelf Kite, specify whether the decision is to post code, distribute a running build or present a reduced demo. These may have separate owners. State the sequence and what can continue without exposing an unreviewed asset. Attach the parts of your evidence register the reviewer is authorized to see. Send sensitive attachments through the agreed internal route, not by pasting them into a public bug report or a prompt.

| A paragraph in the memo | What goes there |
| --- | --- |
| Decision | Proposed deliverable, version, date, market and audience |
| Evidence | Specific records and what the writer actually checked |
| Unknowns | Evidence missing or conflicting, and consequences for the release |
| Reversible next step | Isolate the asset, gather records, obtain permission or build a substitute |
| Referral | A question for the authorized owner or qualified adviser and who will track its answer |

## Worked example

**Decision:** Whether to include the copied function in the public source archive next week. **Evidence:** The team found it in a public repository and recorded a path and revision, but no terms authorizing this distribution were located. The team also has a separate original scheduling stub, which has not been checked for the same behavior. **Options:** Hold that component pending review; check whether the original stub can replace it, test its behavior, and inspect the outgoing artifact. **Referral:** Who can authorize distribution of that exact function and are there conditions on the source archive? **Boundary:** U.S. introductory analysis only. The facts do not establish what happens under another country's rules or whether any exception applies.

A polished record should make you more willing to write “not established,” not less. Suppose the team finds a license after writing the memo. Attach it to the exact version, read the scope, and update the narrow recommendation. Do not change the logo or demo rows simply because the software row improved.

## Apply the process again

Complete the [dossier exercise](../practice/release-dossier.md) unaided. Then revise from the evidence, using an optional bounded tool prompt or the printed checklist. Finally, apply your method to the separate transfer case without feedback. The [answer key](../practice/answer-key.md) evaluates evidence, scope and referral rather than predictions of legal outcomes.
