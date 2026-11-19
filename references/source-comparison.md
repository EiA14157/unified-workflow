# Source comparison for maintaining Unified Workflow

Review scope: 12 representative public SKILL.md bodies, not every path in the catalog. Sources were read as data, not installed or run. The workflow uses original wording and does not bundle upstream scripts or assets.

| Source | Keep | Do not inherit as a blanket rule |
|---|---|---|
| [Superpowers: brainstorming](https://github.com/obra/superpowers/blob/22f0b463e7a5e579904dd6211a520321035526f7/skills/brainstorming/SKILL.md) | Ground choices in existing context | Separate approvals and design stages for small, clear requests |
| [Superpowers: writing plans](https://github.com/obra/superpowers/blob/22f0b463e7a5e579904dd6211a520321035526f7/skills/writing-plans/SKILL.md) | Independently verifiable steps | Long formal plans for bounded changes |
| [Superpowers: systematic debugging](https://github.com/obra/superpowers/blob/22f0b463e7a5e579904dd6211a520321035526f7/skills/systematic-debugging/SKILL.md) | Reproduction and evidence-first hypotheses | Unbounded or sensitive logging; architecture conclusions based on attempt count |
| [Superpowers: test-driven development](https://github.com/obra/superpowers/blob/22f0b463e7a5e579904dd6211a520321035526f7/skills/test-driven-development/SKILL.md) | Isolated regression evidence | Deleting existing implementation to prove a test can fail |
| [Superpowers: verification](https://github.com/obra/superpowers/blob/22f0b463e7a5e579904dd6211a520321035526f7/skills/verification-before-completion/SKILL.md) | Claim-specific evidence | Rerunning equivalent checks on unchanged inputs just to repeat a claim |
| [Anthropic: DOCX](https://github.com/anthropics/skills/blob/main/skills/docx/SKILL.md) | Separate create/edit/extract; verify structure and rendering | Assuming the same converter or validation toolkit exists on every host |
| [Anthropic: frontend design](https://github.com/anthropics/skills/blob/main/skills/frontend-design/SKILL.md) | Intentional hierarchy and user-facing checks | Full design ceremony for one small repair |
| [OpenAI: Jupyter notebook](https://github.com/openai/skills/blob/main/skills/.curated/jupyter-notebook/SKILL.md) | Distinguish experiments from tutorials; check clean execution | Coupling every notebook to one host's package setup |
| [Vercel: React best practices](https://github.com/vercel-labs/agent-skills/blob/main/skills/react-best-practices/SKILL.md) | Prioritized rule routing | Loading or applying the whole rulebook for every React task |
| [Vercel: web design guidelines](https://github.com/vercel-labs/agent-skills/blob/main/skills/web-design-guidelines/SKILL.md) | Concise, located observations | Fetching mutable instructions unnecessarily instead of using a relevant trusted checklist |
| [Hugging Face: community evals](https://github.com/huggingface/skills/blob/main/skills/huggingface-community-evals/SKILL.md) | Smoke test before scale; separate results from publication | Switching execution providers or trusting remote code by default |
| [MicrosoftDocs: Azure AI Vision](https://github.com/MicrosoftDocs/Agent-Skills/blob/main/skills/azure-ai-vision/SKILL.md) | Clear exclusions and official documentation routing | Hard-coding a single connector or fragile line ranges |

The compact route structure is intended to reduce unnecessary reading. It is not a measured runtime token reduction.
