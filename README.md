# Worklog

A Mac menu-bar app that keeps a timeline of your day. It takes a Screenshot every few seconds and turns them into a timeline of what you worked on, summarised by Claude or ChatGPT on your own subscription. It also tracks your Claude Code and Codex sessions. Everything stays on your Mac.

## Install (once, about 2 minutes)

You need macOS 14 or later, and Claude Code or Codex installed and signed in.

1. Download [Worklog.dmg](https://github.com/SheroCommerce/shero-worklog-releases/releases/latest/download/Worklog.dmg) and open it.
2. Drag **Worklog** onto **Applications**.
3. Open Worklog from Applications.
   - *Apple could not verify "Worklog"?* Click **Done**, open **System Settings → Privacy & Security**, click **Open Anyway** next to *Worklog*, and confirm. You only need to do this once.
4. Setup opens. It walks you through Screen Recording, picking Claude or ChatGPT, connecting your agents, and your recording settings.

You can delete the DMG afterwards.

## Update

When there's a new version, **Update to Worklog …** appears in the menu bar panel and in **Settings → About**. Click **Update and Relaunch**. Worklog also checks once a day on its own.

## Problems

- **Nothing on the timeline:** open **Settings → Providers** and click **Test**. If it fails, make sure Claude Code or Codex is signed in.
- **"No permission" in the menu bar:** allow Worklog in **System Settings → Privacy & Security → Screen & System Audio Recording**, then reopen it.
- Anything else: take a screenshot of **Settings → About** and send it to whoever maintains Worklog.
