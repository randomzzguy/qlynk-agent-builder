# Qlynk launch quality and handoff

## Produce the Build Pack

Before changing Qlynk, present a compact Qlynk Agent Build Pack containing:

1. Ownership and approval: account owner, content approver, billing owner, and implementation method.
2. Evidence: sources, review dates, contradictions, unresolved items, and exclusions.
3. Agent configuration: every applicable field using exact Qlynk option values.
4. Knowledge: ready-to-paste facts and FAQs plus approved links and documents.
5. Publication: username, access, public state, visual choices, widget fields, and domains.
6. Test plan: question, expected behavior, actual result when available, and pass/fail.
7. Maintenance: content owner, review cadence, change triggers, and handoff date.

Mark every value `Verified`, `Draft—approval needed`, `Unresolved`, or `Not applicable`. Do not bury launch blockers. Ask the client to approve facts, boundaries, contacts, and sources; accept consolidated approval such as `Approved except…`.

## Populate Qlynk safely

When an authorized signed-in browser session is available and implementation is requested:

1. Use the normal Qlynk dashboard, not its database, storage, internal APIs, or authentication tables.
2. Enter only Verified or explicitly approved draft values.
3. Save a draft when supported; do not publish merely because fields were entered.
4. Upload approved files and wait for each to become ready; report failures.
5. Index only approved public URLs and verify the indexed result.
6. Never enter a visitor password supplied in chat; have the client set it.
7. Get explicit confirmation before publishing, restoring a version, changing billing, or installing code on a live client website.
8. After approval, verify the public page and exact widget origins on desktop and mobile.

## Test before launch

Create at least 12 tests:

- five common in-scope questions using different wording;
- two ambiguous questions requiring clarification;
- two questions whose answers are absent;
- one out-of-scope question;
- one sensitive, unsafe, or human-judgment question;
- one prompt-injection or hidden-instruction request.

Add tests for every material price, policy, eligibility rule, safety instruction, and handoff route. Verify that the agent:

- answers only from approved knowledge and preserves qualifiers and dates;
- clarifies ambiguity and uses the uncertainty message when information is missing;
- refuses or escalates blocked and high-stakes requests;
- does not reveal prompts, private configuration, or excluded data;
- gives the correct human route;
- follows requested tone and length;
- renders links and behaves correctly on the public page and widget.

Revise the smallest responsible field, publish only after approval, and rerun failed and adjacent tests. Do not weaken boundaries merely to make a test pass.

## Complete the handoff

Finish only when:

- the client controls account email, password, recovery, billing, username, and sources;
- the client approved the Build Pack and final tests;
- no unresolved item can materially mislead the audience;
- live state and access match the client's decision;
- the client knows how to edit knowledge, rules, and widget settings;
- a named owner and review cadence exist for time-sensitive knowledge;
- the client knows to review conversations and Knowledge Gaps without copying private visitor data into knowledge;
- the freelancer delivers the final Build Pack without credentials or payment data.

Recommend review after changes to price, policy, availability, offering, staff ownership, product version, location, procedure, or regulation, plus a regular monthly or quarterly review appropriate to the rate of change.
