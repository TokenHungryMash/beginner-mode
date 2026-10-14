# Beginner Mode

**Learn while building—without finishing every tutorial first.**

[简体中文](https://github.com/TokenHungryMash/beginner-mode/blob/main/README.md) · [English skill](SKILL.md) · [Chinese skill](https://github.com/TokenHungryMash/beginner-mode/blob/main/skills/beginner-mode/SKILL.md) · [Downloads](https://github.com/TokenHungryMash/beginner-mode/releases/latest)

Tell your AI what you want to make. Beginner Mode adds a short explanation or reminder when it matters, then keeps working.

| Feature | What it does |
|---|---|
| 🔎 Find existing solutions | Research GitHub before new software projects, explain what can be reused or adapted, then build. |
| 💬 Explain and recap terminology | Explain necessary unfamiliar terms where they appear and recap new vocabulary at the end of the turn. |
| 💾 Remind you to save versions | Suggest checkpoints after verified milestones, before major changes, or when finishing important unrecorded work. |
| 🌐 Explain website use and sharing | Check actual files and explain how to open, share, or publish them as appropriate. |

## Install one language edition

Both editions provide the same core behavior. The English edition includes English instructions, reference documents, and interface metadata—not just an English landing page.

| Edition | Skill folder | Invocation |
|---|---|---|
| English | `skills/beginner-mode-en` | `$beginner-mode-en` |
| Chinese | `skills/beginner-mode` | `$beginner-mode` |

Download your preferred ZIP from [Releases](https://github.com/TokenHungryMash/beginner-mode/releases/latest), extract it, and place the complete skill folder in the directory your client reads. **Normally install only one edition** to avoid overlapping behavior. Keep `SKILL.md`, `agents`, and `references` together.

For local Codex installations, `~/.codex/skills/` is a supported skill directory. For other clients, use their supported skill installation flow. Preserve an existing same-name version before replacing it. The client may need to reload or start a new conversation to discover the skill; installed, enabled, and read by the current task are distinct states.

Or give an installation-capable AI this request:

> Install the English edition at skills/beginner-mode-en from https://github.com/TokenHungryMash/beginner-mode, preserving its complete directory structure. After verifying installation and reading the rules, activate Beginner Mode in this conversation.

## Use

```text
Use $beginner-mode-en to help me build an expense tracker webpage.
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

Version **1.0.0**. Release checks cover structure, internal links, language content, and archive consistency. They do not constitute real installation or end-to-end verification in every client. See each edition's `SKILL.md` for the full behavior.

Created by 土豆泥 (Tudouni) · [TokenHungryMash](https://github.com/TokenHungryMash)
