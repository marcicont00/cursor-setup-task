# cursor-setup-task

Setup of an AI-assisted development environment using Cursor IDE with the
Claude Code and Codex extensions, plus a public GitHub repository. This repo
documents the tools I installed, the steps I completed, and the issues I ran into.

## Tools installed
- **Cursor IDE** – an AI-powered, VS Code–based editor. Signed in with my GitHub account.
- **Claude Code (by Anthropic)** – the official Claude Code extension for the editor.
- **Codex (by OpenAI)** – OpenAI's coding agent extension.

## Steps completed
1. Downloaded and installed Cursor from cursor.com and signed in with GitHub.
2. Opened the Extensions panel (Cmd+Shift+X) and installed **Claude Code for VS Code** (publisher: Anthropic, verified).
3. Installed **Codex – OpenAI's coding agent** (publisher: OpenAI, verified).
4. Logged in to Claude Code.
5. Cloned and opened the repository in Cursor.
6. Wrote this README describing the process.
7. Committed and pushed the changes to GitHub.

## Issues I ran into and how I solved them
- **"Install" seemed to do nothing.** Clicking Install on the Claude Code extension didn't appear to react at first. It was just downloading in the background; after a few seconds the button changed to "Disable / Uninstall", confirming success.
- **Finding the Extensions panel in the new Cursor UI.** Cursor opens on an "agent" home screen instead of the classic editor. I had to open the Editor Window and use Cmd+Shift+X to reach the Extensions marketplace.
- **Claude Code login.** No "Sign in" command appeared, only "Logout" — which indicated I was already authenticated.
- **Codex login requires a paid plan.** The Codex extension page states it works with paid ChatGPT plans (Plus, Pro, Business, Edu, Enterprise). With a free account I could install the extension but could not complete a functional login. I documented this as a limitation.
- **Git authentication when pushing.** Pushing from the terminal triggered a GitHub device-code login that was hard to complete, so I published the README directly through the GitHub web editor.
