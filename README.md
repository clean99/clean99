### Hi, I'm Clean

Frontend and full-stack engineer working on AI agents: how they get context, how their changes get verified, and how people work with them in the browser.

**Building**

- [delivery-verifier](https://github.com/clean99/delivery-verifier): `dv prove` checks regression tests against old and new commits in separate Git worktrees, with Vitest support and a GitHub Action for pull requests. [v0.3.1](https://github.com/clean99/delivery-verifier/releases/tag/v0.3.1), proven on a real merged fix in [Arize Phoenix](https://github.com/Arize-ai/phoenix/pull/17270)
- [OwnContext](https://github.com/clean99/owncontext): self-hosted personal context for AI clients over MCP (preview)

**Merged upstream**

- [Arize Phoenix](https://github.com/Arize-ai/phoenix/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): decode tool-call arguments for Anthropic and the AI SDK; keep `strict` on JSON-schema response formats; preserve Anthropic `extra_body` in the Python client ([#17270](https://github.com/Arize-ai/phoenix/pull/17270))
- [Mantine](https://github.com/mantinedev/mantine/pull/9321): keep zero alpha when converting `hsla` colors
- [assistant-ui](https://github.com/assistant-ui/assistant-ui/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged): keep uploaded image filenames across runtime adapters, keep files in AG-UI tool results, carry `providerMetadata` through AI SDK message conversion, and keep LangChain image filenames
- [React Hook Form](https://github.com/react-hook-form/react-hook-form/pull/13950): check checkbox options whose value is an empty string
- [knip](https://github.com/webpro-nl/knip/pull/2212): Lingui plugin, so Lingui config files and their dependencies are no longer reported as unused
- [Starlight](https://github.com/withastro/starlight/pull/4299): autogenerate the sidebar from the docs root (`directory: ''`) instead of returning an empty group
- Earlier: [Ant Design](https://github.com/ant-design/ant-design/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (test suite migration to Testing Library), [screenshot-to-code](https://github.com/abi/screenshot-to-code/pulls?q=is%3Apr+author%3Aclean99+is%3Amerged) (stop button, live code editing, image-comparison debugging), [LlamaIndexTS](https://github.com/run-llama/LlamaIndexTS/pull/1614)

**Writing**: [clean99.github.io](https://clean99.github.io)
