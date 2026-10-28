### Hi, I'm Clean

Frontend and full-stack engineer working on AI agents: how they get context, how their changes get verified, and how people work with them in the browser.

**Building**

- [delivery-verifier](https://github.com/clean99/delivery-verifier): `dv prove` checks regression tests against old and new commits in separate Git worktrees, with pytest, unittest, Node and Vitest 3.2/4.1 support and a GitHub Action for pull requests. [v0.4.0](https://github.com/clean99/delivery-verifier/releases/tag/v0.4.0), proven on a real merged fix in [Arize Phoenix](https://github.com/Arize-ai/phoenix/pull/17270)
- [OwnContext](https://github.com/clean99/owncontext): self-hosted personal context for AI clients over MCP (preview)

**Merged upstream**

- [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): decode tool-call arguments for Anthropic and the AI SDK; keep `strict` on JSON-schema response formats; preserve Anthropic `extra_body` in the Python client ([#17270](https://github.com/Arize-ai/phoenix/pull/17270)); keep fields beside `anyOf` schemas and evaluator `metadata` in the TypeScript client
- [Mantine](https://github.com/mantinedev/mantine/pull/9321): keep zero alpha when converting `hsla` colors
- [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): keep uploaded image filenames across runtime adapters, keep files in AG-UI tool results, carry `providerMetadata` through AI SDK message conversion, and keep LangChain image filenames, keep OpenCode part IDs stable, and send provider file handles as AG-UI file sources
- [React Hook Form](https://github.com/react-hook-form/react-hook-form/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): check checkbox options whose value is an empty string; read the current `shouldUnregister` when a Controller unmounts
- [knip](https://github.com/webpro-nl/knip/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): Lingui, kysely-codegen and PurgeCSS plugins, and CSpell settings read from `package.json`, so their config files and dependencies are no longer reported as unused
- [React Hook Form resolvers](https://github.com/react-hook-form/resolvers/pull/886): decode JSON Pointer escapes in TypeBox error paths
- [Starlight](https://github.com/withastro/starlight/pull/4299): autogenerate the sidebar from the docs root (`directory: ''`) instead of returning an empty group
- [Vercel AI SDK](https://github.com/vercel/ai/pull/24037): decode base64 and data-URL documents before sending them to Cohere (released in `ai` 7.0.155)
- [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm/pull/6840): keep images and other message fields when long prompts are compressed
- Earlier: [Ant Design](https://github.com/ant-design/ant-design/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (test suite migration to Testing Library), [screenshot-to-code](https://github.com/abi/screenshot-to-code/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (stop button, live code editing, image-comparison debugging), [LlamaIndexTS](https://github.com/run-llama/LlamaIndexTS/pull/1614)

**Writing**: [clean99.github.io](https://clean99.github.io)
