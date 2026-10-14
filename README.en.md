# Beginner Mode

**Learn while building—without finishing every tutorial first.**

[简体中文](README.md) · [Skill instructions](SKILL.md) · [Downloads](https://github.com/TokenHungryMash/beginner-mode/releases/latest)

Tell your AI what you want to make. Beginner Mode adds a short explanation or reminder when it matters, then keeps working.

| Feature | What it does |
|---|---|
| 🔎 Find existing solutions | Research GitHub before new software projects, explain what can be reused or adapted, then build. |
| 💬 Explain and recap terminology | Explain necessary unfamiliar terms where they appear and recap new vocabulary at the end of the turn. |
| 💾 Remind you to save versions | Suggest checkpoints after verified milestones, before major changes, or when finishing important unrecorded work. |
| 🌐 Explain website use and sharing | Check actual files and explain how to open, share, or publish them as appropriate. |

## Installation

One skill, one installation package, with Chinese and English descriptions. The shared instructions and references are maintained in Chinese; this English page explains the same skill. There is no separate English edition to install.

Download `beginner-mode-1.0.0.zip` from [Releases](https://github.com/TokenHungryMash/beginner-mode/releases/latest), extract it, and place the complete `beginner-mode` folder in your client's skill directory. Keep `SKILL.md`, `agents`, and `references` together. You can also clone this repository into a folder named `beginner-mode` in that directory.

For local Codex installations, `~/.codex/skills/` is a supported skill directory. For other clients, use their supported skill installation flow. Preserve an existing same-name version before replacing it. The client may need to reload or start a new conversation to discover the skill; installed, enabled, and read by the current task are distinct states.

Or give an installation-capable AI this request:

> Install the beginner-mode skill from the root of https://github.com/TokenHungryMash/beginner-mode, preserving its complete directory structure. After verifying installation and reading the rules, activate Beginner Mode in this conversation.

## Use

```text
Use $beginner-mode to help me build an expense tracker webpage.
```

For “The button text is too close to the edge,” an example response is: “I'll increase the padding—the space between the text and button edges—and check that the surrounding content still fits.” The assistant then continues the task.

| Say | Effect |
|---|---|
| Less explanation / just do it | Reduce teaching and vocabulary recap; retain necessary work and brief reminders. |
| No extra advice | Disable unsolicited advice and saving/publishing reminders; explicit tasks still proceed. |
| No commit reminders / no deployment suggestions | Disable the corresponding reminder independently. |
| Skip research | Skip searching within the requested scope. |
| Exit beginner mode | Return to ordinary behavior; updating or rereading the skill does not reactivate it. |

## Boundaries

This is an AI instruction package, not a standalone application. It does not provide tools, accounts, or permissions. Search, file changes, Git, and publication depend on the host and authorization. A saving reminder is not permission to commit; explaining hosting is not permission to upload. Copying files alone cannot send messages or activate behavior; post-install activation requires an assistant to read and follow the instructions. Cross-chat memory and universal client compatibility are not guaranteed.

Version **1.0.0**. Release checks cover structure, internal links, language content, and archive consistency. They do not constitute real installation or end-to-end verification in every client. See `SKILL.md` for the full behavior.

Created by 土豆泥 (Tudouni) · [TokenHungryMash](https://github.com/TokenHungryMash)
