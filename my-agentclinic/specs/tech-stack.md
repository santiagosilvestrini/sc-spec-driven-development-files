# AgentClinic Technology Stack

## Application

- **Language:** TypeScript.
- **Runtime:** Node.js.
- **Server framework:** NestJS.
- **HTTP adapter:** Fastify.
- **Data store:** SQLite for the initial implementation and local demonstrations.
- **Build:** TypeScript compiler through the existing npm build workflow.

## Engineering conventions

- Keep domain behavior independent from HTTP transport where practical.
- Prefer small modules with explicit responsibilities over broad utility layers.
- Validate inputs at application boundaries and return predictable errors.
- Favor accessible, responsive browser experiences for both staff and agent-facing workflows.
- Keep local setup simple enough for course exercises and conference demos.

## Quality bar

- Every completed phase should have a focused way to verify its behavior.
- Configuration and data access should be replaceable without rewriting domain rules.
- The application should fail clearly and safely when required data or services are unavailable.