# Claude Code: Which Mode to Pick

**Pick Cloud, and set the environment to "Auto (choose based on repository)".**

The option you pick only decides *where* the work runs. It doesn't change how good the answers are, because it's the same Claude either way.

## The options

| Option | What it does | Use it when |
|---|---|---|
| **Local / This computer** | Claude runs on your Mac and works on your real files. Your iPhone can control it through Remote Control. | The task needs something that only exists on your Mac: local files, desktop Excel, logins or tools installed there. **Your Mac has to be on, awake and running Claude.** |
| **Cloud** | Claude runs on a fresh cloud machine with your GitHub repo copied onto it. | Nearly everything else. It works the same from your iPhone or your Mac, even when the Mac is closed. |
| ↳ **Auto (choose based on repository)** | Picks the cloud setup you saved for that repo, or uses Default if there isn't one. | **Your everyday choice.** |
| ↳ **Default** | One general cloud setup shared by all your repos. | Fine when you have only one or two simple projects. |
| ↳ **+ New environment** | Makes a custom cloud setup with extra websites it can reach, settings, and an install script. | Only when a project needs it, for example an outside service it must reach or a long install you don't want to repeat. You don't need one to get started. |

## Your setup

- **Most of the time:** use Cloud with Auto. You can start a task from your phone, close the app, and check the result later from your Mac.
- **Sometimes:** if a task needs files that live only on your Mac, start it as Local on the Mac and follow along from your phone.
- **Save your work:** a cloud machine is deleted after a while of inactivity, so finished work needs to be pushed to GitHub. Ask Claude to commit and push at the end of a task.

## What actually improves the results

- Use the strongest model (Opus) and a higher effort level for hard tasks.
- For big jobs, use **Plan mode** so Claude proposes a plan before writing code.
- Write clear prompts that say what "done" looks like.
- Add a `CLAUDE.md` file to each repo that describes the project and its rules. Claude reads it at the start of every session.
