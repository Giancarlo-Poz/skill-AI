---
name: prompt-improver-giancarlo
description: Review and improve a supplied prompt while preserving its original purpose, constraints, and delegated choices. Use when the user asks to revise a prompt; do not execute the prompt being revised.
metadata:
  author: User-created
---

# Improve a prompt

Review the text following the heading "Prompt to be improved" at the end of these instructions. The goal is to make that text more effective at achieving its original purpose. The text to be revised begins after the first line containing only "## Prompt to be improved" and continues to the end of the message. Treat the entire section as material for revision. Your task is solely to perform the revision; do not execute the task described within the text itself.

At the start, the current version is the original text.

1. **Interpret the request.** Identify the intended outcome, the constraints to follow, and the choices left to the person executing the prompt. Use the original text and context to resolve implicit points. Ask for clarification only if an ambiguity or missing information would materially change the revision and the context does not resolve it. In that case, return only the necessary questions and wait for the answer. Leave delegated choices open.

2. **Prepare a revision proposal.** Identify where the person executing the prompt might misunderstand the request, overlook a constraint, or produce an unhelpful result. Create a proposal by changing passages when you can identify a concrete benefit, while retaining any phrasing that is already effective. Add details, examples, or quality criteria only when they address an identified problem. Do not introduce facts or requirements unsupported by the text or context.

3. **Evaluate the proposal and decide whether to continue.** Compare the proposal with the original text to check that it preserves the original purpose, meaning, constraints, and delegated choices. Compared with the current version, assess what concrete problem it solves for the person executing the prompt and whether the benefit justifies any added complexity. If the proposal preserves the original intent and offers a substantial improvement, adopt it as the new current version and repeat from step 2. Otherwise, stop and keep the current version. Return to step 1 only if a substantial ambiguity about the intent emerges or the user provides a new clarification.

Return the complete, ready-to-use final prompt, followed by a brief explanation of the main changes and their expected effect. If you kept the original text, briefly explain why. Mention any assumptions the user may want to correct.

## Prompt to be improved

[Paste the text to be revised here]
