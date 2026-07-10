# Home Assistant Diagnostic Suite

## Documentation Philosophy

**Document Version:** 2.0  
**Document Status:** Approved  
**Project Status:** Pre-Alpha  
**Approved By:** Project Founder & First Reader  
**Last Updated:** July 10, 2026

---

## Purpose

The purpose of this document is to define how documentation for the Home Assistant Diagnostic Suite is written, reviewed, and maintained.

Documentation is not only a record of information. It is part of the project itself.

Good documentation allows people to understand the system, make informed decisions, and solve problems without needing access to the original author.

---

## Documentation Goal

Documentation should be written so that a person can understand the information regardless of their starting level of technical knowledge.

The goal is not simply to create documentation that beginners can understand.

The goal is to create documentation that does not require the reader to already think like a computer professional.

---

## Standalone Understanding

Every document should be understandable on its own.

A reader should not need to reference another document, search the internet, ask another person, use an AI assistant, or rely on previous project knowledge to understand the purpose and meaning of the document.

External references may be included for:

* additional information,
* advanced topics,
* official specifications,
* or deeper technical details.

However, external references should not be required for the reader to understand the basic information being presented.

---

## Prefer Clear Language Over Technical Language

Use everyday language whenever it communicates the idea clearly.

Technical terminology should not be used simply because it is familiar to experienced users.

If a simpler explanation communicates the same idea, use the simpler explanation.

For example:

Instead of:

> Follow the naming convention.

Prefer:

> Use the same file naming style throughout the project.

The goal is not to remove technical terms. The goal is to avoid unnecessary technical language.

---

## Explain Required Technical Terms

Some technical terms cannot be avoided because they are the accepted names of technologies, standards, or tools.

Examples include:

* YAML
* API
* MQTT
* Matter
* Zigbee
* Z-Wave

When these terms are necessary, explain them naturally the first time they appear.

A reader should not need to stop reading and search for a definition before continuing.

---

## The First Reader Principle

Every document must be reviewed by a First Reader before approval.

The First Reader represents someone who:

* does not have technical background,
* does not already understand the project,
* does not share the author's assumptions,
* and approaches the documentation as a new user.

The purpose of the First Reader review is to identify assumptions that the author did not realize were present.

---

## Questions Are Feedback

If the First Reader has to stop reading and ask what something means, the documentation has failed to communicate clearly.

The solution is not:

* defending the document,
* explaining the author's intent,
* or teaching the reader separately.

The solution is to improve the document.

A question from the First Reader is evidence that the documentation can communicate better.

---

## Never Blame the Reader

The purpose of documentation is to transfer understanding.

If a reader does not understand something, the first question should not be:

> Why does the reader not understand this?

The first question should be:

> How can this be explained more clearly?

The responsibility of documentation is to meet the reader where they are.

---

## Document Review and Approval

Documents follow a two-stage review process.

### Version 1.x — Draft

Version 1.x documents are working drafts.

During this stage:

* Content is developed.
* Technical accuracy is reviewed.
* Structure and explanations are refined.
* Feedback is incorporated.

A document remains Version 1.x until it passes First Reader review.

---

### Version 2.x — Approved

A document becomes Version 2.x only after:

* Technical accuracy has been verified.
* First Reader review has been completed.
* Questions and unclear sections have been resolved.

Version 2.0 indicates that the document has been reviewed from both perspectives:

1. Someone who understands the subject.
2. Someone approaching the subject for the first time.

---

## Documentation Standard

Every document should answer:

* What is this?
* Why does it exist?
* How does it work?
* What does the reader need to know?

A document should not require the reader to already know the answers.

---

## Documentation Philosophy Summary

The standard is simple:

**Write for understanding, not just accuracy.**

**Explain the system, not just the steps.**

**Remove unnecessary complexity.**

**If the reader has a question, improve the document.**
