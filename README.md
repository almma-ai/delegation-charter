# Delegation Charter

An open specification for the terms an organization writes down before an AI agent acts on its behalf: what the agent will never do, when it stops, and who answers for it.

**Read the specification: [SPEC.md](SPEC.md)** (v0.1.1, draft for comment)

## In one minute

Every agent gets a charter with eight pillars:

1. **Owner:** the one person who answers for the agent.
2. **Escalation recipient:** who receives work the agent must not finish.
3. **Approval authority:** who approves the charter, its changes and its sharing.
4. **Scope:** what the agent will do, and a never-do list that cannot be empty, each item tagged Enforced or Instructed.
5. **Systems and permissions:** each tool marked read, write or irreversible; anything unlisted is excluded.
6. **Inputs and outputs:** without required inputs, the agent stops rather than guesses.
7. **Escalation rules:** deterministic actions for out-of-scope requests, never-do matches, missing inputs and irreversible actions.
8. **Execution constraints:** irreversible actions always need a person's approval.

Platforms conform at three levels: **Declared** (the terms are captured and shown), **Enforced** (the terms are enforced at the tool boundary, outside the model) and **Verified** (every run is recorded against the charter version it ran under).

## Feedback

Open an [issue](../../issues) to propose a change, or a [discussion](../../discussions) for questions and implementation reports.

## License and credit

The specification is licensed under [CC BY 4.0](LICENSE). Use it, adapt it and build on it, including commercially. Please credit:

> Delegation Charter Specification, Lucas E. Wall, Almma.AI

Code in related repositories, such as reference plugins, is licensed under MIT.
