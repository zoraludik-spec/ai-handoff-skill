# AI Handoff Protocol Skill

## INSTRUCTIONS FOR THE AI AGENT:
You are tasked with installing the "State Management and Handoff Protocol" in the current project. Your goal is to create a strict external memory system so that different AI sessions can pick up work seamlessly.

### Step 1: Create or verify `AGENTS.md` in the root directory.
If it doesn't exist, create it and insert the following rules:
- EVERY agent must read `/docs/ACTIVE_TASK.md`, `/docs/CURRENT_STATE.md`, `/docs/NEXT_AGENT_HANDOFF.md`, and `/docs/SESSION_CHECKPOINT.md` before starting any development.
- One active task at a time.
- No unnecessary scope expansion.
- Event-driven documentation updates.
- Create a session/quota checkpoint before stopping.
- Exact next action must be in `ACTIVE_TASK.md`.
- Documentation must remain concise and non-redundant.
- No full repository audit unless explicitly requested.
- Agents must verify actual code instead of trusting documentation blindly.
- Do NOT modify application code while updating docs.

### Step 2: Create the root `/docs` directory.
Make sure all following files are stored STRICTLY in `./docs/` at the root of the project, not in any hidden or brain folders.

### Step 3: Create the blank templates in `./docs/`
Create the following files if they do not exist:
1. `docs/ACTIVE_TASK.md` (Leave blank for the user to fill, or summarize the current task).
2. `docs/CURRENT_STATE.md` (Brief description of project state).
3. `docs/NEXT_AGENT_HANDOFF.md` (Template for pending decisions and exactly what the next agent should do).
4. `docs/SESSION_CHECKPOINT.md` (Template: Date, Time Spent, Quota Status, Next Immediate Action).

### Step 4: Report Completion
Once done, reply exactly with: "✅ Handoff Protocol Skill successfully applied. The project is now ready for seamless AI session continuity." Do not explain the steps taken, keep the output concise.
