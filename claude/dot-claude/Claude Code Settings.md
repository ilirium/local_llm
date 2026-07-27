# Claude Code Settings

Environment variables - Claude Code Docs
- https://code.claude.com/docs/en/env-vars



- ANTHROPIC_BASE_URL
- ANTHROPIC_API_BASE_URL
- ANTHROPIC_API_KEY

- ANTHROPIC_MODEL
  - Name of the model setting to use (see Model Configuration)  
  - Overrides the default active model dynamically across your shell or IDE configurations.
- ANTHROPIC_SMALL_FAST_MODEL
  - Overrides the model configuration designated for quick, low-latency utility tasks like text summary (defaults to Haiku).
  - Note: ANTHROPIC_SMALL_FAST_MODEL is deprecated in favor of ANTHROPIC_DEFAULT_HAIKU_MODEL.
- ANTHROPIC_DEFAULT_FABLE_MODEL
  - The model to use for fable, and the model ID Claude Code recognizes as Fable 5 for automatic model fallback on third-party providers
- ANTHROPIC_DEFAULT_OPUS_MODEL
  - Binds the opus alias to a designated model version.
- ANTHROPIC_DEFAULT_SONNET_MODEL
  - Binds the sonnet alias to a designated model version.
- ANTHROPIC_DEFAULT_HAIKU_MODEL
  - Binds the haiku alias to a designated model version.

- CLAUDE_CODE_SUBAGENT_MODEL: The model to use for all subagents, agent teams, and the agents a workflow runs. Accepts an alias such as haiku or a full model name, and overrides the per-invocation model parameter and the subagent definition’s model frontmatter. Set to inherit to use normal model resolution instead
