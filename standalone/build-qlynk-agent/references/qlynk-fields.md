# Qlynk field map

Use the live product when it differs and report the difference.

## Agent type

Choose exactly one:

- `personal`: a person's work, experience, projects, and expertise.
- `business`: a company, service, offering, process, and next steps.
- `property`: a property, venue, facility, or destination.
- `operations`: onboarding, responsibilities, checklists, equipment, and SOPs.
- `product`: features, setup, usage, limitations, and support.
- `support`: approved FAQs and troubleshooting with escalation.
- `custom`: another focused purpose that follows Qlynk safeguards.

## Role and rules

Produce:

- `purpose`: one primary job, maximum 500 characters.
- `audience`: intended users, maximum 300 characters.
- `allowed_topics`: up to 20 items, 160 characters each.
- `blocked_topics`: up to 20 items, 160 characters each.
- `behavior_rules`: up to 20 “do” rules, 160 characters each.
- `forbidden_behaviors`: up to 20 “don't” rules, 160 characters each.
- `uncertainty_message`: maximum 500 characters.
- `escalation_message`: maximum 500 characters with an approved route.
- `custom_instructions`: lower-priority details only, maximum 2,000 characters.
- `response_length`: `concise`, `balanced`, or `detailed`.
- `scope_mode`: `standard` or `strict`.
- `daily_message_limit`: blank, or an integer from 10 to 10,000.

Do not repeat the knowledge base in custom instructions or attempt to replace Qlynk policy.

## Identity and profile

Produce:

- agent name, role/display title, bio, welcome message, avatar source, primary color, and Qlynk tone;
- capabilities as `{name, level}`, leaving `level` blank when unsuitable;
- examples as `{name, description, url}`;
- contact email, phone, location, website, and booking link;
- social links as `{platform, url}`;
- concise custom knowledge only when it does not belong in a fact or FAQ.

Keep profile and knowledge sources consistent and avoid duplication.

## Knowledge base

Produce:

1. Facts with a clear `title` and self-contained `content`.
2. FAQs with `question`, approved `answer`, category, and priority 1–5. Categories: `general`, `pricing`, `services`, `contact`, or `technical`.
3. Direct approved public-page URLs for indexing.
4. Approved `.pdf`, `.docx`, or `.txt` documents no larger than 3 MB.

Remove obsolete pages, hidden comments, credentials, private records, and irrelevant content. Use facts or high-priority FAQs for pricing, policies, eligibility, contacts, and other answers that must be explicit. Re-index or review URLs after source pages change.

## Access, visual style, and widget

Choose `public`, `email`, or `password`. Never place the actual access password in the Build Pack.

Optionally provide font and colors for page background, CTA button and text, bio/pre-chat text, welcome-page text, user bubble, and AI bubble.

For a widget, provide:

- internal installation name and enabled status;
- exact website origins, one per line, or an explicit allow-any decision;
- `bottom-left` or `bottom-right`;
- six-digit hex launcher color;
- pre-chat enabled status and introduction of at most 240 characters;
- email shown and required status.
