# Qlynk client discovery

## Start the interview

Begin with:

> I can do a Quick setup with five high-yield questions, or an Advanced setup for deeper rules, edge cases, and testing. Which would you prefer? If you have a website or documents, send those too and I will avoid asking for information they already contain.

Ask the five Quick prompts sequentially. Adapt wording to the client's language and omit parts already answered by approved sources.

## Quick interview

### 1. Job and audience

> Who should use this agent, what should it help them do, and what are the five questions they ask you most often?

Extract agent type, purpose, audience, allowed topics, common intents, and starter tests.

### 2. Business truth

> In one rough message, tell me what you offer and the facts people need before taking the next step—such as services or products, prices, inclusions, process, timing, hours, locations, policies, proof, and current limitations. Skip anything that does not apply.

Extract facts, FAQs, capabilities, examples, projects, and gaps. Prefer explicit values and conditions over promotional language.

### 3. Limits and handoff

> What must the agent never answer, promise, reveal, or decide; what should it say when information is missing; and exactly where should it send someone who needs a human?

Extract blocked topics, don't rules, uncertainty wording, escalation wording, private-data exclusions, and human contacts.

### 4. Identity and voice

> What should the agent be called and sound like? Share a display title, a one- or two-sentence description, preferred tone, welcome message, logo or avatar, and brand color—or say “choose for me.”

Map tone only to Qlynk's current choices: `professional`, `friendly`, `funny`, or `creative`. Draft alternatives for approval when needed.

### 5. Public experience

> Which website, booking, contact, and social links may be public, and should the agent use a public link, email capture, password access, a website widget, or a combination?

Extract contact information, social links, access level, public username preference, indexed URLs, widget domains and side, and pre-chat preferences.

After question five, show only:

- a concise summary;
- contradictions, risky content, and missing facts that could materially change answers;
- at most three targeted follow-up questions;
- the option to continue to Advanced discovery.

Do not force Advanced discovery when Quick provides enough verified material.

## Advanced discovery

Ask only relevant modules and remaining gaps. Ask no more than three related questions per turn.

### Goals and audiences

- Identify primary and secondary audiences, vocabulary, and top intents.
- Identify the single conversion or next step.
- Define observable success measures without inventing integrations or outcomes.

### Offers, fit, and comparisons

- Capture each offer's name, intended customer, inclusions, exclusions, price rule, timeline, availability, prerequisites, and next step.
- Capture approved fit criteria, comparisons, objections, and alternatives.
- Escalate decisions requiring human judgment, negotiation, licensing, identity verification, or account access.

### Process and policies

- Capture sequence, owner, inputs, timing, exceptions, stop conditions, and escalation route.
- Capture returns, cancellations, warranties, deposits, delivery, booking, support, and availability only from current approved sources.
- Ask for effective dates and relevant jurisdiction or location.

### Knowledge and terminology

- Capture official names, acronyms, deprecated terms, synonyms, and wording that must remain exact.
- Identify source owners, review dates, conflicting documents, and change triggers.
- Prefer small direct facts and reviewed FAQs for critical answers.

### Safety, privacy, and authority

- Identify confidential, personal, financial, medical, security, employee, customer, or account-specific information that must stay out.
- Identify emergencies, regulated advice, diagnoses, approvals, transactions, guarantees, and decisions that require escalation.
- Confirm rights to use every document, image, testimonial, logo, and source.

### Brand and visitor experience

- Capture spelling, capitalization, tone examples, banned phrases, reading level, response length, greeting, public contacts, colors, font, and avatar.
- Choose `standard` scope for reasonably related questions or `strict` when uncertain and loosely related requests should be blocked.
- Explain that a daily message cap supplements rather than replaces the plan limit.

### Publishing and website embed

- Confirm public username, access mode, live/offline state, and approval owner.
- For widgets, capture installation name, exact origins, side, launcher color, and optional pre-chat name/email capture.
- Treat email capture as collection, not ownership verification. Use password access for restricted access.
