# Internal project skills

The 4Geeks "Enhancing development with agent skills" rubric asks for the
internal, project-specific skill under `.skills/`. It is also registered in
`.agents/skills/` so coding agents that read the shared skill registry load it
next to the community skills (`accessibility`, `vercel-react-best-practices`,
`webapp-testing`).

| Skill | Purpose |
|---|---|
| [`dashboard-metric-card`](./dashboard-metric-card/SKILL.md) | Add or change a KPI card on this dashboard: typed `KPIMetrics`, pure `computeKPIs` derivation, Vitest cases, shared formatters, inherited accessibility. Includes objective, inputs, expected output, and an acceptance-criteria checklist. |

Keep both copies identical; `diff -r .skills/dashboard-metric-card .agents/skills/dashboard-metric-card` must print nothing.
