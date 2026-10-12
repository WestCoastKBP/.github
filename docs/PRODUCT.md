# Product direction

**KBP AI — Knowledge Becomes Progress.**

We are building a personal AI assistant for everyday life and work. Our purpose is to help a person integrate AI into their life and interact with the outside world: understand context, make decisions, perform authorized actions and verify what happened.

## A matter that continues over time

Information arrives through different channels. A conversation, document, appointment and commitment may belong to the same matter, yet the person has to reconnect them each time.

KBP AI is intended to retain relevant context and relationships between people, messages, documents, deadlines and next actions. Sources and uncertainty should stay visible; the user should be able to correct information and control retention. A comprehensive context graph is a development goal, not an implemented capability claimed by this page.

## The factory: first contour

The factory is the intended first workspace for developing and testing capabilities. Over time, it should help users configure task-specific agents, add supported integrations and build out further workspaces.

The engineering factory currently develops the product. A self-service factory for nontechnical users, runtime agent configuration and guided installation are not publicly available.

Personal and Work spaces must have separate data and permissions. Shared execution must not silently share records, broaden access or lose a matter's history. These boundaries require technical enforcement and verification.

## Set up your personal assistant

Assistant setup is part of the intended default onboarding. A person should be able to choose:

- The assistant's identity, voice and responsibilities.
- Which incoming accounts and channels it can access.
- What it may prepare, perform or escalate to the person.
- Which models and paid services it can use, within a chosen budget.

Offering setup by default does not mean enabling collection, answering or recording by default. Each channel needs its own authorization.

## Connect to the outside world

The direction spans communication, documents, calendars, maps, search, browser tasks and smart-home scenarios. Use supported APIs and MCP where appropriate; browser interaction is another route when the task and site permit it. Each integration must document its supported accounts, actions and limits.

For a browser task, the assistant should inspect the current page, act within the request and check the result. Website content cannot grant permissions. When an external action has an uncertain outcome, the assistant should reconcile it before retrying.

Phone assistance is a planned scenario: take a message, retain it in the appropriate workspace and present a follow-up. A Twilio number or carrier-supported forwarding may provide the telephone connection; voice services such as ElevenLabs are candidates. No working KBP AI telephone service is claimed here.

## Devices and deployment

We are targeting iPhone and iPad as the primary interface, with Linux and macOS deployment in mind and a Mac client as a possible extension.

The intended runtime can live on a home computer or hosted virtual machine. Separate execution, workers and data services form the architecture direction. Dedicated storage and local models are optional configurations to investigate; deployment profiles and an installer are not yet released.

Local storage does not imply fully local processing. Cloud models and connected services may receive task data. The user needs to understand that path.

## Choice of AI and cost control

Supported subscription-based tools and separately billed APIs are both relevant. One vendor subscription does not grant every API or product feature.

Configurable spending limits are a product requirement: a total budget, allocation across models and paid channels, visible usage and a defined response when a limit is reached. Enforcement and billing visibility still need implementation and acceptance; we do not promise an exact spending cap before it is verified.

## What makes a scenario accepted

A connection probe alone is insufficient. Acceptance requires the whole task: input → retained context → intended action → necessary approval → execution → confirmed result → history after reopening.

Communication scenarios also need duplicate handling, interruption recovery, reconciliation of uncertain sends and visible stale or failed connections. Sensitive actions require the appropriate permission and a human escalation path.

## First demonstrations

The nearest demonstration target is an idea captured into a retained briefing, examined by two independent AI models and returned to the person for a decision. Voice capture is a further step. A complete incoming-email and approved-reply cycle is another target for demonstrating action in the world.

These are targets, not publicly available demos. Release evidence will determine what we can claim.

## Join the discussion

**Prototype in development.** There is no public installer, implementation source release or reproducible product demo available through this repository.

[Describe a non-confidential task](https://github.com/WestCoastKBP/.github/issues) and the result you need, or contact [hello@kbp-ai.com](mailto:hello@kbp-ai.com) about collaboration.

[Current status](STATUS.md) · [Our philosophy](BRAND.md) · [KBP AI](https://github.com/WestCoastKBP)

