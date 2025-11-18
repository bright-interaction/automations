# Automations

Central repository for workflow automations across platforms.

## Structure

- `/n8n` - Automations built in n8n
- `/Make` - Automations built in Make (formerly Integromat)

## Naming Convention

`[trigger]-[action]-[target].json`

Example: `webhook-create-slack-notification.json`

## How to Use

### n8n
1. Export workflow as JSON from n8n
2. Add to `/n8n` folder
3. Import via n8n's "Import from File" option

### Make
1. Export scenario blueprint from Make
2. Add to `/Make` folder
3. Import via Make's "Import Blueprint" option

## Documentation

Each automation should include:
- Purpose (what it does)
- Trigger (what starts it)
- Dependencies (APIs, credentials needed)

---

*Add documentation as comments within each workflow or as companion `.md` files.*
