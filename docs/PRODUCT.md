# Product direction

**Knowledge Becomes Progress.**

KBP AI is being built as a workspace where the AI and tools you choose help you carry a real matter from a request to a checked result. KBP stands for Knowledge Becomes Progress; AI stands for Artificial Intelligence. See our [brand and philosophy](BRAND.md).

The recurring problem is fragmented work. A request arrives in one app, supporting context lives elsewhere, and someone has to carry the next action between conversations. KBP AI is intended to keep the goal, relevant information, permissions and next action together.

## Who we are building for

Our initial audience hypothesis is people who already use ChatGPT or Claude but still coordinate messages, documents, tasks and follow-up themselves. We want to test whether a shared workspace reduces that coordination work. This is a direction to validate, not a claim of established demand or measured time savings.

## One engine, workspaces you can shape

The design direction is one execution engine with separate workspaces for personal matters, engineering and other work. A person should be able to organize projects, tasks, AI roles and connections around their needs.

Shared execution must not mean shared access to everything. Each workspace keeps its own data and permissions. Switching an assistant must not silently expand those permissions or lose the matter's history.

The main interface is a web application designed for iPhone and iPad as well as a computer. These are product goals; configurable workspaces and supported devices need their own demonstrated acceptance.

## Connections and incoming information

We distinguish two jobs in the interface we are developing:

- **Connections:** which accounts and tools are authorized, what they may do, whether they are working, and how to revoke access.
- **Inbox:** incoming messages and actionable updates, with the relevant matter, source, next action and any decision needed from the person.

A configured connector is not a completed integration. Each supported channel needs a verified incoming-message and reply path, retained history, safe handling of duplicates and uncertain sends, recovery after interruption, and visible failure reporting. Channel support is accepted separately; this page does not claim that email, Telegram or WhatsApp are publicly available.

## The experience we are working toward

For example, a message arrives about an appointment. The assistant keeps it with the relevant matter and proposes a response. The person reviews the intended reply before it is sent. A confirmed reply can lead to an appointment being recorded; an unanswered message stays visibly pending.

This is an illustrative target workflow, not a working public demo. Progress means the expected result was checked, not simply that a draft was generated or a task was marked complete.

## Your AI, explicit access

KBP AI is intended to work with the assistants and tools a person chooses. OpenAI, Anthropic, GitHub and Google are relevant to this direction; supported interfaces such as MCP should be used where appropriate.

Account sign-in, access to tools and permission to perform an action are separate requirements. We will document the supported client, account requirements, available operations, limits and billing for each integration. A subscription or sign-in must not be presented as universal access to a vendor's tools.

## What you can do today

**KBP AI is a prototype in development.** This repository provides the public product presentation and a place to discuss use cases. A public installer, implementation source release and reproducible product demo are not yet available here.

Read the [project status](STATUS.md), [suggest a concrete use case](https://github.com/WestCoastKBP/.github/issues), or follow [KBP AI](https://github.com/WestCoastKBP) for demonstrations and releases. Please keep private records and credentials out of public discussions.

[Back to KBP AI](https://github.com/WestCoastKBP)
