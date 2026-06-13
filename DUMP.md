# Decision Dump Instructions

Reference this file whenever Patrick or Melissa sends unstructured bathroom-project thoughts, research, prices, ideas, or decisions.

## Processing Rules

When processing a dump:

1. Preserve the useful intent, but rewrite it into concise project language.
2. Sort each item into the appropriate file under `decisions/`.
3. Classify every item as one of:
   - **Confirmed decision:** explicitly approved and ready to guide the project
   - **Current direction:** preferred approach that still requires a final product, measurement, or implementation choice
   - **Option under consideration:** possible approach that has not been selected
   - **Reference estimate:** preliminary pricing or technical guidance that must be verified
   - **Open question:** missing information needed before a decision can be finalized
4. Do not silently overwrite or merge conflicting decisions. Record the conflict and move the subject back to an open decision.
5. Add provided product prices to the relevant tracking area. Include source, quantity, and date when available.
6. Do not treat rough price ranges as committed budget amounts.
7. Update MVP exit criteria only when the documented answer fully satisfies the criterion.
8. Update `README.md` when a dump changes a high-level project goal or known decision.
9. After processing, summarize what changed and continue the clarification process with no more than three questions at a time.

## Conflict Handling

When new information conflicts with an existing decision:

- Preserve both options and the reason for each.
- Mark the decision as open.
- Identify what information will resolve the conflict.
- Ask about it in the next relevant clarification round.
- Follow the repository-wide conflict requirements in [AGENTS.md](AGENTS.md).

## Budget Handling

- Record actual or quoted material prices when Patrick or Melissa provides them.
- Maintain a material subtotal.
- Add the agreed 10% buffer to calculate the current planned total.
- Keep labor estimates and rough market-price research separate from the committed material budget.
- Recalculate after every price or quantity change.

## Expected Output

Every processed dump should leave the project files with:

- Confirmed decisions in the appropriate decision tables
- Current directions and options clearly labeled
- Conflicts and open questions visible
- Relevant technical notes preserved
- Price information categorized correctly
