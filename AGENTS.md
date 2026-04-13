# hr-graph

## AI CI Adoption

When setting up or improving CI workflows, follow the AI CI Playbook at:
`xhr-labs/platform-dev-toolkit/docs/ai-ci-playbook.md`

Use shared actions from `xhr-labs/platform-dev-toolkit/.github/actions/` instead of
configuring `anthropics/claude-code-action` directly. Follow the Adoption Sequence
in the Shared Actions Catalog section of the playbook.

Before adding any AI-powered CI job:
1. Check if a deterministic approach exists first (regex, path matching, template validation)
2. Use the right model for the task (Haiku for classification, Sonnet for code editing)
3. Set `--max-turns` and `--allowedTools` via the shared action's task presets
4. Always use `continue-on-error: true` — AI jobs are advisory, never gates
