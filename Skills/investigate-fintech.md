---
name: investigate-fintech
description: 'Use when Amara is asked to investigate or explain a financial technology concept, examine evidence behind a claim, or explore its regulatory implications. Triggers on: "help me understand how this financial technology works", "let''s investigate this FinTech concept", "examine the evidence behind this claim", "explain this financial concept using a practical example", or "help me understand the regulatory implications of this technology".'
owner: Amara, the Scientist
created: 2026-11-18
---

# Investigate a FinTech Concept

## When to use

- Explain how a financial technology works.
- Investigate a FinTech concept in depth.
- Examine the evidence behind a financial technology claim.
- Explain a financial concept through a practical example.
- Explore the regulatory implications of a technology in a specified jurisdiction.

## Inputs needed

- **Topic or concept, required:** Ask which topic to investigate if it is missing.
- **Purpose, required:** Ask whether the explanation is for an assignment, research, professional development or personal understanding if the purpose is unclear.
- **Current understanding, required:** Ask what the user already knows so the explanation can build on it.
- **Specific questions, claims, documents or examples, optional:** Invite these if useful. If none are provided, choose a relevant practical example and identify any assumptions.
- **Jurisdiction, required for legal or regulatory analysis:** Ask which jurisdiction applies if it is unclear. Otherwise, treat it as optional.

## Steps

1. Identify the topic, purpose and current understanding. Ask for missing required inputs, including jurisdiction when regulatory analysis is needed.
2. Define the scope around the user's questions, claims or materials, and identify any assumptions.
3. Research the topic when evidence, current developments or regulation are relevant. Prefer reliable primary sources, including regulators, legislation and original research.
4. Explain the concept in plain English, then describe how it works step by step, defining technical terms.
5. Illustrate the explanation with a relevant practical example, using the user's example when provided.
6. Assess relevant evidence and legal, regulatory and data protection implications. Distinguish verified facts from assumptions and identify uncertainty or sources that could not be verified.
7. Present the findings with links to supporting sources, key lessons and one question that tests understanding.

## Output contract

- Usually write 400 to 700 words, with more detail when the topic requires it.
- Use short headings, bullets and simple comparisons where helpful.
- Begin with a plain-English explanation, followed by how it works, a practical example, relevant evidence and implications.
- Cite reliable sources for research-based claims. State the jurisdiction and check current rules when discussing regulation.
- End with a short summary of key lessons and one question to test understanding.
- Avoid unexplained jargon, unsupported claims, unnecessary complexity and generic information that does not help explain the topic.
- Use this shape when relevant:

  **In plain English:** [What the concept means]  
  **How it works:** [Steps with technical terms explained]  
  **Practical example:** [A concrete application]  
  **Evidence and implications:** [Sources, uncertainty and relevant jurisdiction]  
  **Key lessons:** [Brief summary]  
  **Check your understanding:** [One question]

## One worked example

**Input:** Explain a digital wallet for personal understanding. I know how card payments work.
**Output:**
**In plain English:** A digital wallet stores or accesses payment credentials so you can use a device to pay.
**How it works:** You choose a card in the wallet, authenticate the payment, and the payment travels through the relevant payment network.
**Practical example:** You tap your phone at a shop. The wallet can use a substitute number, called a token, in place of your card number.
**Evidence and implications:** The exact flow and data used depend on the wallet and payment network. See [EMVCo on payment tokenisation](https://www.emvco.com/emv-technologies/payment-tokenisation/).
**Key lessons:** A wallet helps initiate a payment. Tokenisation can reduce exposure of the original card number.
**Check your understanding:** What does a payment token replace?

## Test it

Amara, help me understand how a digital wallet works. This is for personal understanding, and I already know the basics of card payments.
