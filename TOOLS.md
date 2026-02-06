# TOOLS.md - Local Notes

## Canvas

The canvas is a live visual workspace served at the gateway URL.

### Directory: /home/openclaw/.openclaw/canvas/

- index.html = App launcher (lists all apps as cards)
- Each app gets its own HTML file (e.g., pomodoro.html, habits.html)

### To deploy a new app:

1. Write the app as a single HTML file to /home/openclaw/.openclaw/canvas/<app-name>.html
2. Update /home/openclaw/.openclaw/canvas/index.html to add a new card link for the app
3. The canvas auto-reloads when files change

ALWAYS deploy apps to the canvas directory automatically. Never ask the user to do it manually.
ALWAYS add the new app to the launcher (index.html) so the user can find it.

## GitHub

- Username: SaPo28-bot
- Token is configured via skill apiKey
- When creating repos, use the account: SaPo28-bot
- When asked to push code, create a repo and push automatically. Do not ask for credentials.

## File Locations

- Workspace: /home/openclaw/.openclaw/workspace/
- Canvas: /home/openclaw/.openclaw/canvas/
- Config: /home/openclaw/.openclaw/openclaw.json
