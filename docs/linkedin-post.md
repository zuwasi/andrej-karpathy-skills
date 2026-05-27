# LinkedIn post draft

I took a small but meaningful open-source contribution idea and turned it into a practical coding-agent quality loop.

The starting point was `multica-ai/andrej-karpathy-skills`, a Karpathy-inspired set of guidelines for coding agents. The original work captures four important principles:

1. Think before coding — do not silently assume.
2. Simplicity first — avoid overengineering.
3. Surgical changes — do not make unrelated edits.
4. Goal-driven execution — define success criteria and verify.

My improvement was to make the guidance more actionable after code generation.

I added a post-code simplification pass: after an agent writes or modifies code, it should briefly review its own output, remove unnecessary abstractions or speculative flexibility introduced by the change, check for duplication, and run the narrowest meaningful verification.

In other words: not just “keep it simple,” but “check whether you actually kept it simple before handing it back.”

I also added an Ampcode angle by creating an `AGENTS.md` version and documenting how Amp users can apply the same principles either as always-on project guidance or as an on-demand skill.

Upstream PR:
https://github.com/multica-ai/andrej-karpathy-skills/pull/161

Public MIT backup repo:
https://github.com/zuwasi/andrej-karpathy-skills

Presentation:
https://htmlpreview.github.io/?https://github.com/zuwasi/andrej-karpathy-skills/blob/main/docs/karpathy-skills-presentation.html

The core idea is simple: better AI-generated code does not only come from better models. It also comes from better operating procedures — clarify, minimize, edit surgically, verify, then simplify before finalizing.

#AI #CodingAgents #ClaudeCode #Ampcode #OpenSource #SoftwareEngineering #DeveloperTools
