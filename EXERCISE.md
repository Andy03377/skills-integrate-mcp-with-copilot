# Exercise: Integrate MCP with Copilot

This repository contains a small FastAPI exercise used to demonstrate integrating the Model Context Protocol (MCP) with GitHub Copilot.

Goals
- Walk through wiring Copilot to call an external MCP server with project context.
- Provide an example MCP manifest and a minimal MCP response handler.
- Verify the exercise runs locally and that Copilot can receive context from the MCP server.

Quick start
1. Create and activate a Python virtual environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the example app:

   ```bash
   python src/app.py
   ```

4. Open the exercise README in `src/README.md` and follow the prompts for the MCP integration steps.

Checklist (for this exercise)
- [ ] Provide an `mcp.json` manifest with endpoints and context fields.
- [ ] Add a small MCP server example (optional) that serves project context.
- [ ] Update the exercise instructions with a verification step (example prompt to send to Copilot).

If you'd like, I can now push these changes and open a PR — or make additional edits first. Tell me how you'd like to proceed.
