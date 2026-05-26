# Automation & QA Assignment

## Task 2 — n8n API Integration Workflow

### APIs Used
- GitHub REST API
- Discord Webhook API

### Workflow Logic
1. Schedule Trigger starts the workflow.
2. GitHub API fetches repository data.
3. JavaScript node filters top repositories.
4. IF node checks conditions.
5. Second HTTP request enriches repository details.
6. Final output is sent to Discord webhook.

### Error Handling
Configured using "Continue Regular Output" in HTTP Request nodes.

### Output
Workflow successfully posts repository details to Discord.
