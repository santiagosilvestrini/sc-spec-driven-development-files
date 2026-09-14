# AgentClinic Roadmap

Implementation proceeds in small, demonstrable phases. Each phase should leave the project buildable and provide a clear verification point before the next phase begins.

## Phase 1: Project foundation

- Establish the NestJS and Fastify application shell.
- Confirm TypeScript compilation and a repeatable local start command.
- Add environment configuration and a health endpoint.
- Verify the application starts and the health check responds successfully.

## Phase 2: Staff dashboard shell

- Create the browser entry point for staff.
- Add primary navigation and the dashboard layout.
- Show placeholder summary areas for agents, care items, and appointments.
- Verify the dashboard loads in a modern browser at desktop and mobile widths.

## Phase 3: Agent records

- Define the agent record shape in SQLite.
- Add the staff view for listing and inspecting agents.
- Add empty, loading, and error states.
- Verify an agent can be found and its details can be viewed.

## Phase 4: Ailments and therapies

- Model ailments and therapies and their relationship to agents.
- Add care status and therapy details to the agent view.
- Add the staff workflow for recording or updating care information.
- Verify changes persist and are visible after reload.

## Phase 5: Appointment booking

- Model appointments and availability.
- Add appointment creation, listing, and cancellation or rescheduling.
- Prevent invalid or conflicting bookings with clear feedback.
- Verify the complete booking flow from the dashboard.

## Phase 6: Reliability and demonstration polish

- Add focused automated checks around core workflows.
- Improve accessibility, responsive behavior, and useful empty states.
- Add representative demo data and a concise local setup path.
- Verify a clean build and a complete staff demonstration flow.