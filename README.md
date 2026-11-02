### Hi, I'm Clean

Frontend and full-stack engineer working on AI agents: how they get context, how their changes get verified, and how people work with them in the browser.

[![ghfind card for clean99](https://ghfind.com/api/card/mini/clean99?v=1793348947974)](https://ghfind.com/en/u/clean99)

**Building**

- [delivery-verifier](https://github.com/clean99/delivery-verifier): `dv prove` checks regression tests against old and new commits in separate Git worktrees, with pytest, unittest, Node and Vitest 3.2/4.1 support and a GitHub Action for pull requests. [v0.4.0](https://github.com/clean99/delivery-verifier/releases/tag/v0.4.0), proven on a real merged fix in [Arize Phoenix](https://github.com/Arize-ai/phoenix/pull/17270)
- [OwnContext](https://github.com/clean99/owncontext): self-hosted personal context for AI clients over MCP (preview)

**Merged upstream: AI agent UIs and SDKs**

- [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (9): runtime adapters for the AI SDK, AG-UI, LangChain, Google ADK, OpenCode and Pi keep what the agent produced: uploaded filenames, files and artifacts in tool results, provider metadata and file handles, stable part identities
- [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (7): LLM tracing and evals clients decode Anthropic and AI SDK tool inputs, keep `strict` response schemas, `extra_body`, fields beside `anyOf`, evaluator `metadata` and JSON-string span filters; the dataset view refreshes its example count
- [Effect](https://github.com/Effect-TS/effect/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (4): `Stream.groupAdjacentBy` emits buffered groups before an upstream failure; `DateTime` rounding keeps the offset inside a repeated DST hour; `Iterable.unfold` and `filterMapWhile` stay exhausted
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): long-prompt compression keeps images; KoboldCPP agents honour max response tokens; GitHub re-sync encodes file paths
- [Vercel AI SDK](https://github.com/vercel/ai/pull/24037): decode base64 and data-URL documents before sending them to Cohere

**Merged upstream: frontend and tooling**

- [knip](https://github.com/webpro-nl/knip/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (11): new Lingui, kysely-codegen and PurgeCSS plugins; Babel, CSpell, SVGR, Relay, SWC, Eleventy and npm-package-json-lint plugins read every config location and format their tools support
- [React Hook Form](https://github.com/react-hook-form/react-hook-form/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3) and [resolvers](https://github.com/react-hook-form/resolvers/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (2): `trigger` keeps nested field-array root errors; a Controller reads the current `shouldUnregister` on unmount; empty-string checkbox options; TypeBox and fluentvalidation-ts error paths
- [TanStack Virtual](https://github.com/TanStack/virtual/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (3): Svelte and Vue adapters keep options and callbacks across updates and detach observers when the scroll element goes away
- [Rollup](https://github.com/rollup/rollup/pull/6620): keep line terminators in module ids
- [SvelteKit](https://github.com/sveltejs/kit/pull/17590): use the UTF-8 byte length when reading inline assets
- [Solid](https://github.com/solidjs/solid/pull/4266): sync array length when reconciling server-side stores
- [Lexical](https://github.com/meta/lexical/pull/9464): round-trip link titles and destinations through Markdown
- [Mantine](https://github.com/mantinedev/mantine/pull/9321), [UnoCSS](https://github.com/unocss/unocss/pull/5400), [Starlight](https://github.com/withastro/starlight/pull/4299): zero alpha in `hsla` colors, preset-wind4 containment utilities, sidebar autogeneration from the docs root
- Earlier: [Ant Design](https://github.com/ant-design/ant-design/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (test suite migration to Testing Library), [screenshot-to-code](https://github.com/abi/screenshot-to-code/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (stop button, live code editing, image-comparison debugging), [LlamaIndexTS](https://github.com/run-llama/LlamaIndexTS/pull/1614)

**Writing**: [clean99.github.io](https://clean99.github.io)
