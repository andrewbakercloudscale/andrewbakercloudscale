## Andrew Baker

**Group Chief Information Officer, [Capitec Bank](https://www.capitecbank.co.za/)** — Cape Town, South Africa.
20+ years in technology leadership across financial services.

I write about AI engineering, banking technology, cloud architecture, cybersecurity and
engineering leadership at **[andrewbaker.ninja](https://andrewbaker.ninja/)** — and the code
behind most of those posts ends up here.

Everything below is production tooling I actually run, not demos.

---

### AI / LLM engineering

Cost, observability and safety for coding agents — the unglamorous infrastructure around LLMs.

| | |
|---|---|
| **[claude-code-cost-sidebar](https://github.com/andrewbakercloudscale/claude-code-cost-sidebar)** | Live cost, token and context usage sidebar for Claude Code: cost per turn, cache hit rate, burn rate, plan limits and 30-day spend, inside the session. [Write-up](https://andrewbaker.ninja/2026/08/22/ai-coding-costs-are-guesswork-without-this-instrumenting-opencode-and-claude-code/) |
| **[claude-burst](https://github.com/andrewbakercloudscale/claude-burst)** | Local gateway that arbitrages Anthropic subscription vs. metered pricing, with AWS Bedrock overflow. [Write-up](https://andrewbaker.ninja/2026/08/28/two-prices-for-the-same-model-building-claude-burst/) |
| **[cloudscale-claude-code-extender](https://github.com/andrewbakercloudscale/cloudscale-claude-code-extender)** | Floating iTerm2 panel showing live Claude Code command history. |
| **[wp-plugin-standards-claude-skills](https://github.com/andrewbakercloudscale/wp-plugin-standards-claude-skills)** | Claude Code skill enforcing WordPress.org submission standards, security hardening and PCP compliance. |
| **[bash-analyse-repo-claude-skill](https://github.com/andrewbakercloudscale/bash-analyse-repo-claude-skill)** | Claude Code skill that audits bash across a repo into a prioritised Critical/High/Medium/Low report. |

### AWS, FinOps & infrastructure

| | |
|---|---|
| **[cloudtorepo](https://cloudtorepo.com)** | Reverse-engineer an existing AWS estate into Terraform — with scripts, not click-ops. [Guide](https://andrewbaker.ninja/2026/03/21/reverse-engineer-aws-to-terraform-cloudtorepo-guide/) |
| **[aws-bvr](https://github.com/andrewbakercloudscale/aws-bvr)** | AWS Business Value Ratio — cost posture auditor for product accounts. [Write-up](https://andrewbaker.ninja/2026/06/10/aws-business-value-ratio-the-cost-health-check-your-finops-team-is-missing/) |
| **[pi2s3](https://github.com/andrewbakercloudscale/pi2s3)** | Block-level nightly backup of a Raspberry Pi to S3; restore to new hardware in one command. [Write-up](https://andrewbaker.ninja/2026/04/16/pi2s3-an-ami-for-your-raspberry-pi/) |

### WordPress

Free, no-upsell plugins built for sites running behind Cloudflare.

| | |
|---|---|
| **[cloudscale-site-analytics](https://github.com/andrewbakercloudscale/cloudscale-site-analytics)** | Analytics that survive CDN caching — a JS beacon counts every view, including cached pages. |
| **[wordpress-database-cleanup-plugin](https://github.com/andrewbakercloudscale/wordpress-database-cleanup-plugin)** | Revisions, transients, orphaned meta and unused media — dry-run preview, chunked processing. |

---

**Elsewhere:** [andrewbaker.ninja](https://andrewbaker.ninja/) ·
[LinkedIn](https://www.linkedin.com/in/andrew-baker-ninja/) ·
[X](https://x.com/andrewbaker007/)
