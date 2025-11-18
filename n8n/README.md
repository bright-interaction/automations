# n8n Automations

Workflow automations built in n8n.

## Workflows

| Name | Trigger | Description | Status |
|------|---------|-------------|--------|
| *Add workflows here* | | | |

## Import Instructions

1. Open your n8n instance
2. Click **"Add workflow"** → **"Import from File"**
3. Select the `.json` file
4. Update credentials for your environment
5. Activate workflow

## File Format

- Export as JSON from n8n
- Include all nodes and connections
- Credentials are excluded (must reconnect after import)

## Credential Requirements

Document required credentials per workflow:
- API keys
- OAuth connections
- Webhook URLs

## Testing

Before committing:
- [ ] Test with sample data
- [ ] Verify error handling
- [ ] Check all credential placeholders noted
