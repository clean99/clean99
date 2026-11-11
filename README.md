### Hi, I'm Clean

Frontend and full-stack engineer working on AI agents: how they get context, how their changes get verified, and how people work with them in the browser.

[![ghfind card for clean99](https://ghfind.com/api/card/mini/clean99?v=1793348947974)](https://ghfind.com/en/u/clean99)

**Building**

- [delivery-verifier](https://github.com/clean99/delivery-verifier): `dv prove` checks regression tests against old and new commits in separate Git worktrees, with pytest, unittest, Node and Vitest 3.2/4.1 support and a GitHub Action for pull requests. [v0.4.0](https://github.com/clean99/delivery-verifier/releases/tag/v0.4.0), proven on a real merged fix in [Arize Phoenix](https://github.com/Arize-ai/phoenix/pull/17270), listed in [awesome-mutation-testing](https://github.com/theofidry/awesome-mutation-testing/pull/103)
- [OwnContext](https://github.com/clean99/owncontext): self-hosted personal context for AI clients over MCP (preview)

<!-- factory:merged:start -->
**Merged upstream: AI agent UIs and SDKs**

- [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (13): runtime adapters for the AI SDK, AG-UI, LangChain, LangGraph, Google ADK, OpenCode and Pi keep what the agent produced: uploaded filenames, files and artifacts in tool results, images and files returned by Google ADK tools, documents cited by AI SDK streams, tool state metadata, provider metadata and file handles, stable part identities; LangGraph shows OpenAI reasoning once
- [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (10): LLM tracing and evals clients decode Anthropic and AI SDK tool inputs, keep `strict` response schemas, `extra_body`, Anthropic system instructions, fields beside `anyOf` schemas, evaluator `metadata`, failed task span status and JSON-string span filters; prompt variables keep literal `$$` and `$&`; the dataset view refreshes its example count
- [Effect](https://github.com/Effect-TS/effect/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (13): `@effect/ai` replays Anthropic web fetch and code execution results as server tool results, accepts web fetch documents without citations, citations on inline documents without a file id and code execution containers without skills, sends OpenAI shell tool results in the expected shape, accepts `null` `service_tier` and `tool_calls` from OpenAI-compatible servers, ignores empty streamed content deltas from OpenRouter and reports OpenRouter and OpenAI-compatible refusals as a `content-filter` finish with the explanation in metadata instead of an empty `stop`; `Stream.groupAdjacentBy` emits buffered groups before an upstream failure; `DateTime` rounding keeps the offset inside a repeated DST hour; `Iterable.unfold` and `filterMapWhile` stay exhausted
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (6): agents keep images after prompt-based tool calls and reject failed Responses API streams; compressed chat history keeps images and provider formatting; KoboldCPP agents honour max response tokens; GitHub re-sync encodes file paths
- [Vercel AI SDK](https://github.com/vercel/ai/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): provider adapters accept what providers actually send: Cohere documents as base64 or data URLs and `null` tool arguments while streaming, inline text files in OpenAI-compatible requests
- [Context7](https://github.com/upstash/context7/pull/3530): `resolve-library-id` keeps the teamspace filter notice when a filtered library search finds nothing, so the agent sees why the list is empty

**Merged upstream: frontend and tooling**

- [knip](https://github.com/webpro-nl/knip/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (17): new Lingui, kysely-codegen, PurgeCSS, Web Test Runner and AWS CDK plugins, the last one also reading an existing `--app` directory as a cloud assembly; Babel and Stylelint configs are followed through `extends`; Babel, CSpell, SVGR, Relay, SWC, Storybook, Eleventy and npm-package-json-lint plugins read every config location and format their tools support
- [React Hook Form](https://github.com/react-hook-form/react-hook-form/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4) and [resolvers](https://github.com/react-hook-form/resolvers/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (6): `trigger` keeps nested field-array root errors and touches nested fields with `shouldTouch`; a Controller reads the current `shouldUnregister` on unmount; empty-string checkbox options; the io-ts and Effect resolvers honour `raw`; TypeBox and fluentvalidation-ts error paths; Valibot object-level checks such as matching passwords now block submission; `ajv-formats` v3 installs without peer conflicts
- [TanStack Virtual](https://github.com/TanStack/virtual/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): Svelte and Vue adapters keep options and callbacks across updates and detach observers when the scroll element goes away
- [Rollup](https://github.com/rollup/rollup/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4): keep line terminators in module ids; debug ID comments count toward chunk hashes, so a cached chunk is never served under a new build's file name; dynamic chunks of `index` files are named after their directory instead of a row of `index-<hash>.js`; string import and export names starting with `*` are kept instead of turning into namespace imports, being dropped or crashing the build
- [SvelteKit](https://github.com/sveltejs/kit/pull/17590): use the UTF-8 byte length when reading inline assets
- [h3](https://github.com/h3js/h3/pull/1624): cache preconditions follow the request method: a matching `If-None-Match` stops POST, PUT, PATCH and DELETE with `412` instead of `304`, and OPTIONS, TRACE and CONNECT ignore conditional headers
- [Solid](https://github.com/solidjs/solid/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): server-side stores sync array length on reconcile and start from an empty object when created without initial state; a server-rendered `Switch` picks nested and accessor `Match` branches instead of the fallback
- [Lexical](https://github.com/meta/lexical/pull/9464): round-trip link titles and destinations through Markdown
- [Mantine](https://github.com/mantinedev/mantine/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4): color functions keep zero alpha in `hsla` and parse four-digit `#RGBA`; leading-decimal values such as `.5rem` stay CSS lengths instead of theme sizes; `use-hash` keeps its state in sync with the URL
- [Starlight](https://github.com/withastro/starlight/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (2): the sidebar autogenerates from the docs root; localized sites keep a directory named `constructor` in fallback pages, the language picker and alternate links
- [UnoCSS](https://github.com/unocss/unocss/pull/5400): preset-wind4 containment utilities
<!-- factory:merged:end -->

- Earlier: [Ant Design](https://github.com/ant-design/ant-design/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (test suite migration to Testing Library), [screenshot-to-code](https://github.com/abi/screenshot-to-code/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (stop button, live code editing, image-comparison debugging), [LlamaIndexTS](https://github.com/run-llama/LlamaIndexTS/pull/1614)

**Writing**: [clean99.github.io](https://clean99.github.io)
