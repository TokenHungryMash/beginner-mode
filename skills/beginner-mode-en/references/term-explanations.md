# Short explanations of technical terms

Read only relevant entries when explaining or distinguishing a concept. This is neither an exhaustive vocabulary nor a frequency ranking. Explain unlisted relevant terms too. Preserve formal names and explain their current purpose before expansions or more jargon. Actual tool behavior depends on the environment and official documentation.

## Files and configuration

| Term | Short explanation and important boundary |
|---|---|
| HTML / .html | HTML describes webpage content and structure; .html is a common webpage file extension opened in a browser. Opening does not guarantee offline functionality. |
| Markdown / .md | Text using simple symbols for headings, lists, and links. Editable as text, not exclusive to any AI. |
| README.md | A project's explanation of purpose and usage. Read it; the filename alone proves no capabilities. |
| SKILL.md | Instructions telling an AI when and how to handle a task category. Existence does not prove loading. |
| AGENTS.md | Project work instructions read by some coding assistants. Scope depends on the client and location. |
| JSON / .json | Structured text storing data, such as {"city":"Kyoto","days":3}. Syntax matters; it is not an application to install. |
| YAML / .yaml | Configuration text that often uses indentation for structure; indentation can change meaning. |
| Environment variables / .env | Runtime settings; .env commonly stores them. It is not automatically loaded everywhere and is not encryption. |

## Webpages and interfaces

| Term | Short explanation and important boundary |
|---|---|
| CSS | Rules controlling page colors, fonts, spacing, and layout; HTML provides structure. |
| JavaScript / JS | A programming language often handling webpage interaction and data. Also runs outside browsers; distinct from Java. |
| Component | A reusable organized interface part, such as a search box or product card; not necessarily a plugin or single button. |
| State | Information remembered for the current interface, such as selection or saving status; not necessarily persistent after refresh. |
| Padding | Space inside a box between content and edges; not space between boxes. |
| Margin | Space outside a box. Other layout settings can also cause gaps. |
| Responsive design | Adapting layout and size to available screen space, not merely shrinking a desktop page. |
| Toast | A brief result message such as “Saved.” Important actionable failures need more than a fleeting notification. |
| Tooltip | Short help on hover or keyboard focus; not usually an action dialog, and essential help must not require a mouse. |
| Modal | A dialog that must be handled or closed before interacting with the background; not every floating message is modal. |
| Drawer | A panel opening from a page edge; whether it blocks other interaction varies. |
| Skeleton | Placeholder shapes while content loads; not loaded content and not a speed improvement by itself. |
| Hover | A pointer resting over an element without clicking; not reliably available on touchscreens. |
| Focus | The current target for keyboard input or actions; not identical to pointer position. |

## Projects and versions

| Term | Short explanation and important boundary |
|---|---|
| MIT license | Allows use, modification, and commercial use while requiring preservation of copyright and license notices in copies or substantial portions. Provided as-is without warranty; not unrestricted. |
| Git | Tracks file changes to compare edits and recover recorded versions; cannot guarantee recovery of unrecorded content. |
| GitHub | A website for hosting, sharing, and collaborating on code projects. Distinct from Git; public visibility is not unrestricted reuse permission. |
| Repository | Project files and version history, locally or remotely; not necessarily GitHub. |
| Branch | A line of development within a project; not inherently another folder. |
| Worktree | A directory of editable project files; additional worktrees allow simultaneous versions in separate directories. They share repository history, not independent backups or security isolation. |
| Clone | Copying a Git project and its history locally; not installation or proof it runs. |
| Staging area | Selected changes prepared for the next commit. Staging is neither committing nor uploading; later edits need staging too. |
| Commit | Recording selected changes as a traceable version, usually locally; not an upload. |
| Push | Sending local version history to a remote repository; not necessarily publishing a site. |
| Diff | A comparison of added, removed, or changed content; not a runtime result. |
| PR / pull request | A request to review and merge changes; creation is not merging. |

## AI concepts

| Term | Short explanation and important boundary |
|---|---|
| LLM | An AI model that processes and generates language and other content. Fluency is not proof of correctness or execution. |
| Prompt | Requirements and reference information supplied to AI; no special incantation is necessary. |
| System prompt | Application-provided behavioral instructions and context; not access permission or a way around tool checks. |
| Context | Information available for the current answer; not all files or all past conversations. |
| Context window | The amount of information a model can process at once; not a guarantee that every detail is used correctly. |
| Context compaction | Summarizing long history to continue work; may lose details but does not delete project files. |
| Token | A unit used to measure model input/output length; not always a word or character. |
| Agent | An assistant that can use tools and execute task steps; actual capability depends on tools and permissions. |
| Skill | Instructions and supporting resources for a task workflow; cannot supply missing tools, accounts, or permissions by itself. |
| Tool call | Actually using a search, file, or other tool; saying “I'll search” is not a search. |
| API | An interface for programs to request functions or exchange data; may require accounts, permissions, or payment. |
| MCP | A standard for AI applications to connect to external tools and data; not a model or automatic access grant. |
| RAG | Retrieving relevant material before answering with it; helpful evidence, not guaranteed correctness. |

## Running and delivery

| Term | Short explanation and important boundary |
|---|---|
| Terminal | A window for controlling a computer with commands; commands depend on OS and current directory. |
| Dependency | Another package required to build or run a project; installing it does not complete the project. |
| Runtime environment | Software and versions needed to run a program; identical code may behave differently elsewhere. |
| Frontend / backend | User-facing interface versus programs handling requests and data behind it; a simple webpage may have no separate backend. |
| Build | Processing source into runnable or publishable output; success is not proof every feature was tested. |
| Deployment | Placing and configuring an application in its target environment; audience depends on configuration. |
| Static site | Serves prepared pages, styles, and scripts, potentially with browser interaction; does not automatically supply login or shared databases. |
| Cloudflare Pages | Website hosting with direct-upload or repository-based routes depending on the project. A URL does not prove data synchronization or dependency support; check current conditions. |
| GitHub Pages | Static site publishing from repositories; uploading source alone does not activate it, and arbitrary servers are not supported. |
| Localhost | The device accessing that address itself; sending it to a friend does not point to your computer. |
| API key | A credential for a service, not an ordinary link; never publish real values in source or documentation. |
| Sandbox | An environment limiting operations, files, or networks; verify actual boundaries, not absolute safety. |

## Identity and permissions

| Term | Short explanation and important boundary |
|---|---|
| Authentication | Checking who is using a service, such as login; not permission to view everything. |
| Authorization | Deciding what a user can access or change; hiding buttons does not replace enforcement. |

## Verification and evaluation

| Term | Short explanation and important boundary |
|---|---|
| SHA-256 | Computes a fixed-length content fingerprint to compare data. Not encryption or proof a file is safe or authentic. |
| Hash | A computed compact value for comparison or lookup; different algorithms have different uses, and collisions are possible. |
| Checksum | A value used to detect data errors; not every checksum provides security verification. |
| Benchmark | Defined tasks and scoring for comparison; results depend on conditions and may not predict real use. |
| Eval | Checking AI behavior using tasks and criteria; need not be a public leaderboard. |
| Test set | Samples used to check performance; a few samples do not represent every use case. |
| Baseline | A reference approach for comparison; not necessarily the minimum or best possible standard. |
| A/B test | Comparing alternatives under comparable conditions; asking once per version is not a reliable conclusion. |
| Regression test | Rechecking existing functionality after changes; covers only what was actually checked. |
| Latency | Waiting time for a response; specify first response versus complete result. |
| Throughput | Amount processed or produced over time; not single-request wait or answer quality. |

Check unfamiliar product names against context and primary sources. An ambiguous phrase such as “Jev benchmark” is not enough to identify a product. Explain the generic term without unrelated research when that is all the task requires.

## Bridge everyday descriptions to the task

Understand the desired effect first. Name concepts only when useful, and continue without requiring resubmission. These are phrasing examples, not claims of completed edits:

- “The text hugs the input edge.” → “I'll increase its padding, the space between text and edge, and check narrow screens.”
- “I can't tell whether the bookmark worked.” → “After saving succeeds, I'll show a brief Saved toast and a selected bookmark state.”
- “My colleague logged in but cannot open my project.” → “Login identifies them; permissions determine which project they can open. I'll check the sharing scope and account.”

Newly explained terms still belong in the current-turn recap.

## References

Original short explanations, informed by [Git worktrees](https://git-scm.com/docs/git-worktree), [Git staging and commits](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository), [Markdown](https://www.markdownguide.org/getting-started/), [MCP](https://modelcontextprotocol.io/docs/getting-started/intro), [NIST SHA standard](https://nvlpubs.nist.gov/nistpubs/fips/nist.fips.180-4.pdf), [JSON](https://www.rfc-editor.org/rfc/rfc8259), [MIT](https://opensource.org/license/mit), [Hugging Face Evaluate](https://huggingface.co/docs/evaluate/index), [MDN box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model), [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript), [responsive design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design), [hover](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:hover), [focus](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:focus), [React components](https://react.dev/learn/your-first-component), [React state](https://react.dev/learn/state-a-components-memory), [W3C tooltips](https://www.w3.org/WAI/ARIA/apg/patterns/tooltip/), [modal dialogs](https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/), [MUI toasts](https://mui.com/material-ui/react-snackbar/), [drawers](https://mui.com/material-ui/react-drawer/), [skeletons](https://mui.com/material-ui/react-skeleton/), [OWASP authorization](https://cheatsheetseries.owasp.org/cheatsheets/Authorization_Cheat_Sheet.html), and [system prompts](https://platform.claude.com/docs/en/release-notes/system-prompts/overview). These explain concepts, not replace current tool documentation. Do not require any one terminology website.
