<!-- factory:portfolio:start -->
<a href="https://clean99.github.io/software-factory/"><picture><source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="https://clean99.github.io/software-factory/profile-dark-compact.svg"><source media="(max-width: 600px)" srcset="https://clean99.github.io/software-factory/profile-light-compact.svg"><source media="(prefers-color-scheme: dark)" srcset="https://clean99.github.io/software-factory/profile-dark.svg"><img src="https://clean99.github.io/software-factory/profile-light.svg" width="880" alt="Run by Software Factory: merged pull requests, merge rate and merged-without-rework rate with the snapshot date, and the steps the factory takes. The counts are repeated in the text below."></picture></a>

**All in on AI.** Since 2026-10-24 this account's upstream contributions are run by [Software Factory](https://clean99.github.io/software-factory/), an agent pipeline I design and operate. It opens the pull requests, files the issues and writes the replies in other people's projects. From 2026-11-20 each new pull request says so.

```text
software-factory
snapshot 2026-11-24, Asia/Singapore date

opened   144  since 2026-10-24
merged   103  in 21 projects
closed    10  without merge
open      31

merge rate         98/125  78%
merged, no rework  70/98   71%
cohort: opened 14+ days ago (UTC dates)

today    +3 opened  +1 merged  +0 closed
7 days   +15 opened  +3 merged  +0 closed
```

Printed by `bin/factory metrics card` from the public snapshot named in its second line. The figures are redrawn each time the site is published; this block is rewritten when the profile is synced. Nothing on this page runs live.

<a href="https://clean99.github.io/software-factory/board.html"><picture><source media="(prefers-color-scheme: dark)" srcset="https://clean99.github.io/software-factory/activity-dark.svg"><img src="https://clean99.github.io/software-factory/activity-light.svg" width="880" alt="Daily activity from 2026-10-28 to 2026-11-24, Asia/Singapore dates: 111 pull requests opened, 92 merged and 8 closed without merge. Each event is dated by when it happened."></picture></a>

**Active contributor to** [knip](https://github.com/webpro-nl/knip/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (18 merged, 7th of 344 contributors) · [Effect](https://github.com/Effect-TS/effect/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (14, 28th of 428) · [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (13, 16th of 220) · [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (11, 36th of 267) · [React Hook Form resolvers](https://github.com/react-hook-form/resolvers/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (8, 5th of 77) · [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (6, 13th of 293). Ranks are by commits in GitHub's contributor list on 2026-11-22.

**Selected pull requests**

- [rollup#6630](https://github.com/rollup/rollup/pull/6630): dynamic imports of a directory's index file name their chunk after the directory, closing an issue open since February 2023
- [effect#10370](https://github.com/Effect-TS/effect/pull/10370): OpenRouter streaming ignores empty content deltas instead of emitting empty text parts
- [resolvers#893](https://github.com/react-hook-form/resolvers/pull/893): Valibot object-level checks, such as two passwords matching, now reach the form as an error
- [assistant-ui#10291](https://github.com/assistant-ui/assistant-ui/pull/10291): OpenCode tool output and edit diffs reach UI renderers through the artifact field
- [context7#3530](https://github.com/upstash/context7/pull/3530): an empty library search keeps its filter notice, so an agent can see why the list is empty
- [knip#2228](https://github.com/webpro-nl/knip/pull/2228): Knip reads CSpell configuration from the `cspell` key in package.json

[The factory](https://clean99.github.io/software-factory/) · [Source](https://github.com/clean99/software-factory) · [Status board](https://clean99.github.io/software-factory/board.html) · [Metric definitions](https://github.com/clean99/software-factory/blob/HEAD/docs/metrics.md)
<!-- factory:portfolio:end -->

### Hi, I'm Clean

Frontend and full-stack engineer working on AI agents: how they get context, how their changes get verified, and how people work with them in the browser.

[![ghfind card for clean99](https://ghfind.com/api/card/mini/clean99?v=1793348947974)](https://ghfind.com/en/u/clean99)

**Building**

- [software-factory](https://github.com/clean99/software-factory): the automated pipeline behind this account's pull requests: scouting, independent review, scanned publication and unattended shifts, measured on a [public dashboard](https://clean99.github.io/software-factory/)
- [delivery-verifier](https://github.com/clean99/delivery-verifier): `dv prove` checks regression tests against old and new commits in separate Git worktrees, with pytest, unittest, Node and Vitest 3.2/4.1 support and a GitHub Action for pull requests. [v0.4.0](https://github.com/clean99/delivery-verifier/releases/tag/v0.4.0), proven on a real merged fix in [Arize Phoenix](https://github.com/Arize-ai/phoenix/pull/17270), listed in [awesome-mutation-testing](https://github.com/theofidry/awesome-mutation-testing/pull/103)
- [OwnContext](https://github.com/clean99/owncontext): self-hosted personal context for AI clients over MCP (preview)

<!-- factory:merged:start -->
**Merged upstream: AI agent UIs and SDKs**

- [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (13): runtime adapters for the AI SDK, AG-UI, LangChain, LangGraph, Google ADK, OpenCode and Pi keep what the agent produced: uploaded filenames, files and artifacts in tool results, images and files returned by Google ADK tools, documents cited by AI SDK streams, tool state metadata, provider metadata and file handles, stable part identities; LangGraph shows OpenAI reasoning once
- [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (11): LLM tracing and evals clients decode Anthropic and AI SDK tool inputs, keep `strict` response schemas, Anthropic `extra_body`, Anthropic system instructions, fields beside `anyOf` schemas, evaluator `metadata`, failed task span status and JSON-string span filters; prompt `extra_body` fields go out as top-level SDK parameters; prompt variables keep literal `$$` and `$&`; the dataset view refreshes its example count
- [Effect](https://github.com/Effect-TS/effect/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (14): `@effect/ai` accepts [Bash and text-editor calls](https://github.com/Effect-TS/effect/pull/10552) from `CodeExecution_20250825`, replays Anthropic web fetch and code execution results as server tool results, accepts web fetch documents without citations, citations on inline documents without a file id and code execution containers without skills, sends OpenAI shell tool results in the expected shape, accepts `null` `service_tier` and `tool_calls` from OpenAI-compatible servers, ignores empty streamed content deltas from OpenRouter and reports OpenRouter and OpenAI-compatible refusals as a `content-filter` finish with the explanation in metadata instead of an empty `stop`; `Stream.groupAdjacentBy` emits buffered groups before an upstream failure; `DateTime` rounding keeps the offset inside a repeated DST hour; `Iterable.unfold` and `filterMapWhile` stay exhausted
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (6): agents keep images after prompt-based tool calls and reject failed Responses API streams; compressed chat history keeps images and provider formatting; KoboldCPP agents honour max response tokens; GitHub re-sync encodes file paths
- [Vercel AI SDK](https://github.com/vercel/ai/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): provider adapters accept what providers actually send: Cohere documents as base64 or data URLs and `null` tool arguments while streaming, inline text files in OpenAI-compatible requests
- [Context7](https://github.com/upstash/context7/pull/3530): `resolve-library-id` keeps the teamspace filter notice when a filtered library search finds nothing, so the agent sees why the list is empty

**Merged upstream: frontend and tooling**

- [knip](https://github.com/webpro-nl/knip/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (18): new Lingui, kysely-codegen, PurgeCSS, Web Test Runner and AWS CDK plugins, the last one also reading an existing `--app` directory as a cloud assembly; Babel and Stylelint configs are followed through `extends`; Babel, CSpell, SVGR, Relay, SWC, Storybook, Eleventy and npm-package-json-lint plugins read every config location and format their tools support; WebdriverIO runners, services and community reporters are no longer reported unused
- [React Hook Form](https://github.com/react-hook-form/react-hook-form/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4) and [resolvers](https://github.com/react-hook-form/resolvers/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (8): `trigger` keeps nested field-array root errors and touches nested fields with `shouldTouch`; a Controller reads the current `shouldUnregister` on unmount; empty-string checkbox options; the io-ts and Effect resolvers honour `raw`; TypeBox and fluentvalidation-ts error paths; Valibot and arktype object-level checks such as matching passwords now block submission, including [path-less issues through typeschema](https://github.com/react-hook-form/resolvers/pull/898); `ajv-formats` v3 installs without peer conflicts
- [TanStack Virtual](https://github.com/TanStack/virtual/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): Svelte and Vue adapters keep options and callbacks across updates and detach observers when the scroll element goes away
- [Rollup](https://github.com/rollup/rollup/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4): keep line terminators in module ids; debug ID comments count toward chunk hashes, so a cached chunk is never served under a new build's file name; dynamic chunks of `index` files are named after their directory instead of a row of `index-<hash>.js`; string import and export names starting with `*` are kept instead of turning into namespace imports, being dropped or crashing the build
- [SvelteKit](https://github.com/sveltejs/kit/pull/17590): use the UTF-8 byte length when reading inline assets
- [h3](https://github.com/h3js/h3/pull/1624): cache preconditions follow the request method: a matching `If-None-Match` stops POST, PUT, PATCH and DELETE with `412` instead of `304`, and OPTIONS, TRACE and CONNECT ignore conditional headers
- [Solid](https://github.com/solidjs/solid/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): server-side stores sync array length on reconcile and start from an empty object when created without initial state; a server-rendered `Switch` picks nested and accessor `Match` branches instead of the fallback
- [Lexical](https://github.com/meta/lexical/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (2): round-trip link titles and destinations through Markdown; preserve edits to imported bare links' destinations, labels and text formatting in `@lexical/mdast`
- [Mantine](https://github.com/mantinedev/mantine/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (6): color functions keep zero alpha in `hsla` and parse four-digit `#RGBA`; leading-decimal values such as `.5rem` stay CSS lengths instead of theme sizes; `use-hash` keeps its state in sync with the URL; hotkeys accept [physical letter codes such as `KeyK`](https://github.com/mantinedev/mantine/pull/9381); [Home and End activate tabs](https://github.com/mantinedev/mantine/pull/9382), not just focus them
- [Starlight](https://github.com/withastro/starlight/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (2): the sidebar autogenerates from the docs root; localized sites keep a directory named `constructor` in fallback pages, the language picker and alternate links
- [UnoCSS](https://github.com/unocss/unocss/pull/5400): preset-wind4 containment utilities
- [awesome-mutation-testing](https://github.com/theofidry/awesome-mutation-testing/pull/103): lists delivery-verifier among mutation-testing tools
- [NestJS](https://github.com/nestjs/nest/pull/18655): the native Node HTTP adapter adds the default UTF-8 charset to text and JSON replies whose `Content-Type` was set directly on the response, matching `send()` and `json()`
- [rc-select](https://github.com/react-component/select/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (2): pressing ArrowUp with no active option starts at the last option, and canceling a delayed close releases the option lock so the next selection is not ignored
<!-- factory:merged:end -->

- Earlier: [Ant Design](https://github.com/ant-design/ant-design/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (test suite migration to Testing Library), [screenshot-to-code](https://github.com/abi/screenshot-to-code/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (stop button, live code editing, image-comparison debugging), [LlamaIndexTS](https://github.com/run-llama/LlamaIndexTS/pull/1614)

**Writing**: [clean99.github.io](https://clean99.github.io)
