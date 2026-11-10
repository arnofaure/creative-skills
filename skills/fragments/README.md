# Fragments — sharing draft

**Status: experimental draft; not yet tested with an independent FLORA account or in FAUNA.**

Fragments is an experiment by Arno Faure. Each invocation produces a different fragment of the same fictionalized childhood memory, not a reconstruction of the participant's own memory. The output is a still and a five-second video; generations use the participant's own project and budget, subject to explicit cost approval.

## Contents

- `SKILL.md` — portable agent instructions.
- `assets/reference.png` — the exact reference. Download and upload it to FLORA if direct URL import is unavailable.

## Potential ways to try it

- **An agent connected to FLORA through MCP:** share the approved `SKILL.md` and reference with a participant who has FLORA access. They can ask their agent to read the file and follow it in their own FLORA workspace. This path is documented in general by FLORA, but this particular package has not yet been tested independently.
- **FAUNA within FLORA:** an experiment could paste approved instructions into the FAUNA chat and attach the approved reference in the participant's own canvas. FAUNA documents image attachments and canvas context, but we have not verified that it can discover or execute this custom skill by name or reliably follow this particular recipe. Use Assist mode to review cost before running.

Prompt to try after the skill and visual reference are accessible:

> Use Fragments — Try to remember again to create one new fragment of the memory in my FLORA project. Show me the image and video prompts and the estimated cost before starting. Do not run without my approval.

## Testing

1. Verify that a participant can retrieve the instructions and exact image without access to Arno's workspace.
2. Test from a separate FLORA account and workspace, with the participant's authorization and budget. Verify actual reference access, model availability, cost estimates, still-to-video wiring, video output and visual quality. Test FAUNA separately if a native-canvas experience is desired.
3. Finish the separate creative validation of five independent invocations and select three results. Development clips do not count toward that goal.
4. Describe only the tested route accurately. Sharing a project link is not equivalent to making a workspace skill public.

Current model defaults in the draft: Krea 3 image-to-image and MiniMax H3 Max Turbo, 5 s, 768P, prompt expansion disabled if supported. Model availability, pricing and interfaces can change. Historical costs are not a price promise.

FLORA's documentation: https://docs.flora.ai/mcp/skills and https://docs.flora.ai/editor/fauna
