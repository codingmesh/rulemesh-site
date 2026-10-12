# RuleMesh client configurations

Shadowrocket configs are directly importable. Surge, Mihomo and sing-box files are complete structural templates; compose them with a private node base using the source repository CLI.

Policy hierarchy:

1. Choose the default node in the root node selector.
2. AI, social and streaming family selectors inherit that choice.
3. Anthropic, OpenAI, Gemini, Telegram, YouTube and Netflix inherit their family and may be overridden independently.
4. Private and mainland China traffic default to direct. Global fallback defaults to the root node selector.
5. The advertising profile evaluates reject rules before private, service, domestic and global rules; the standard profile contains no advertising rules.
