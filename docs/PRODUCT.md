# Product direction

**KBP AI is a personal AI assistant for everyday life and work.**

Our philosophy is **Knowledge Becomes Progress**: help a person integrate AI into their life, make decisions and interact with the outside world through authorized actions and verified results.

**Prototype in development.** The experience below is our direction; it is not a released product.

## Who we are building for

People who already use AI but still move context between conversations, documents and apps themselves. We want to make that work easier while giving the person clear control of their assistant. This is an audience hypothesis to test.

## One matter, connected context

Consider an appointment request. The assistant should recognize the person, find the relevant conversation or document, prepare a response and ask for the approval it needs. It should check the outcome and retain the next action, so the matter can continue later.

Relationships between people, messages, documents and commitments form the context we intend to preserve. Sources, uncertainty and corrections must remain visible. A full context graph and personal retention controls still require implementation.

## The factory and your workspaces

The factory is the first contour: it develops and tests capabilities that can become part of your assistant. The intended product will let users shape task-specific agents and add supported integrations.

The first-run guide should make this accessible without showing engine jobs, reviews or pull requests. You see the steps, connection health, decisions and results. Technical history should be available when needed.

Personal and Work spaces are designed to keep their data and permissions separate. Shared execution must not silently share records or expand an agent's authority. Complete enforcement is still a release requirement.

## The intended first-run journey

| Step | What you choose or receive |
| --- | --- |
| Sign in | Your identity. Apple and Google are planned; Sign in with ChatGPT depends on eligibility being confirmed for KBP AI. |
| Connect AI | An API provider and supported subscription routes where available. Identity sign-in alone does not supply model access. |
| Set a budget | Spending limits for models and paid services, with visible usage and a record of costs. |
| Connect a source | An account or service, its permissions and its Personal or Work placement. |
| Configure your assistant | Its responsibilities, voice and the actions it may perform or escalate. |
| Complete one task | A retained result that you can check and reopen on your device. |

The guide is not built yet. Offering assistant setup by default does not enable collection, answering or recording without the user's choice.

## Connections that grow with the assistant

Our direction includes communication, documents, calendars, maps, search, browser tasks and smart-home scenarios. Use supported APIs and MCP where appropriate, with documented operations and permissions for each connection.

Phone assistance is another planned scenario: answer an authorized channel, take a message and retain a follow-up. Twilio and ElevenLabs are candidates; an existing mobile number may need carrier-supported forwarding. No live KBP AI telephone service is claimed.

Every channel needs its own complete acceptance: incoming information, retained history, authorized action, confirmed result and visible failures. Uncertain sends must be reconciled before retrying.

## Devices, runtime and cost

We are targeting iPhone and iPad as the primary interface, with Linux and macOS deployment in mind. Home hardware and hosted virtual machines are intended deployment options. An installer and supported deployment profiles are not released.

The runtime coordinates work, isolated workers execute bounded tasks, and data services retain state. Optional local models and separate storage are directions to investigate. Data sent to a cloud model is not locally processed just because it was stored at home.

API use belongs in the product from the start. Supported subscriptions and separately billed APIs have different limits. Configurable budgets, per-provider usage and a transparent cost ledger are requirements, not implemented billing claims. Payment handling and any KBP AI pricing need separate decisions before launch.

## First demonstrations

The nearest target is an idea retained as a briefing, reviewed by two independent AI models and returned for a decision. Voice capture comes next. An incoming email carried through to an approved reply is a further target for action in the world.

[Development status](STATUS.md) records what is publicly available and what proof is still needed.

[Back to KBP AI](https://github.com/WestCoastKBP)

