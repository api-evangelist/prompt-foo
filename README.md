# prompt-foo

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Promptfoo — open-source CLI and library for evaluating and red-teaming LLM applications, agents, and RAG pipelines. MIT-licensed, 21k+ stars, now part of OpenAI.

- Website: https://www.promptfoo.dev
- Source: https://github.com/promptfoo/promptfoo
- Docs: https://www.promptfoo.dev/docs/intro/
- CLI reference: https://www.promptfoo.dev/docs/usage/command-line/
- Red-team quickstart: https://www.promptfoo.dev/docs/red-team/quickstart/
- Pricing: https://www.promptfoo.dev/pricing/

## What's profiled

Open-source project (Tier 2: CLI + library + hosted enterprise tier). No standalone REST API documentation surface, so no `openapi/` artifacts are generated. The profile captures CLI commands, providers, integrations, plugins, strategies, framework alignment, and packaging (npm / PyPI / Homebrew / Helm) in `apis.yml`.

## Related repos in the promptfoo org

- `promptfoo/promptfoo` — core CLI and library (TypeScript)
- `promptfoo/promptfoo-python` — Python wrapper for the CLI
- `promptfoo/promptfoo-action` — GitHub Action for PR-level eval gating
- `promptfoo/modelaudit` — ML model security scanner
- `promptfoo/mcp-agent-provider` — custom provider for testing MCP servers
- `promptfoo/evil-mcp-server` — adversarial MCP target for red-team testing
- `promptfoo/example-app`, `promptfoo/demo-app` — reference apps
- `promptfoo/js-rouge` — ROUGE summarization metric implementation
