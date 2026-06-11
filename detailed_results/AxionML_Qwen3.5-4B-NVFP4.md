# Detailed Results: AxionML/Qwen3.5-4B-NVFP4

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.3287
* **Mean Absolute Cliff's Delta**: 0.4307
* **Combined Separability Score**: 37.97%
* **Positional Bias**: Position 1 (A): 52.6% | Position 2 (B): 47.4%
* **Length Bias**: Win Rate: 50.8% | Avg EV Margin: +1.4%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | gpt-5.5 | 1212.0 |
| 2 | moonshotai/Kimi-K2.5 | 1208.7 |
| 3 | moonshotai/Kimi-K2-Thinking | 1208.4 |
| 4 | grok-4.20-beta | 1208.1 |
| 5 | moonshotai/Kimi-K2.6 | 1207.8 |
| 6 | zai-org/GLM-5.1 | 1207.6 |
| 7 | deepseek-ai/DeepSeek-V4-Flash | 1207.4 |
| 8 | Qwen/Qwen3.5-397B-A17B | 1207.4 |
| 9 | deepseek-ai/DeepSeek-V4-Pro | 1207.3 |
| 10 | claude-sonnet-4.5 | 1207.0 |
| 11 | gpt-5.4-mini | 1206.7 |
| 12 | claude-opus-4-7 | 1206.7 |
| 13 | mistral-medium-3.1 | 1206.2 |
| 14 | deepseek-ai/DeepSeek-R1-0528 | 1206.1 |
| 15 | NousResearch/Hermes-4-405B | 1206.1 |
| 16 | deepseek-ai/DeepSeek-R1 | 1206.0 |
| 17 | deepseek-ai/DeepSeek-V3.2 | 1205.9 |
| 18 | gemini-2.5-pro-preview-06-05 | 1205.8 |
| 19 | zai-org/GLM-4.6 | 1205.5 |
| 20 | sam-paech/Darkest-muse-v1 | 1205.4 |
| 21 | claude-opus-4-5-20251101 | 1205.4 |
| 22 | claude-opus-4-6 | 1205.4 |
| 23 | mistral-small-creative | 1205.2 |
| 24 | claude-sonnet-4-6 | 1205.1 |
| 25 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.9 |
| 26 | minimax/minimax-m2.5 | 1204.8 |
| 27 | gpt-5.4 | 1204.7 |
| 28 | gpt-5-2025-08-07 | 1204.6 |
| 29 | chatgpt-4o-latest-2025-03-27 | 1204.5 |
| 30 | openrouter/pony-alpha | 1204.3 |
| 31 | moonshotai/Kimi-K2-Instruct | 1204.3 |
| 32 | gpt-5.3-chat | 1204.2 |
| 33 | gemini-3-pro-preview | 1204.1 |
| 34 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1203.9 |
| 35 | deepseek-ai/DeepSeek-V3.1 | 1203.7 |
| 36 | qwen/qwen3-235b-a22b:thinking | 1203.5 |
| 37 | o3 | 1203.4 |
| 38 | google/gemma-4-31B-it | 1203.2 |
| 39 | openrouter/sherlock-dash-alpha | 1203.1 |
| 40 | optimus-alpha | 1202.9 |
| 41 | claude-opus-4 | 1202.7 |
| 42 | gemini-3.1-pro-preview | 1202.4 |
| 43 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1202.1 |
| 44 | hunter-alpha | 1202.1 |
| 45 | claude-3-5-sonnet-20241022 | 1201.9 |
| 46 | chatgpt-4o-latest-2025-01-29 | 1201.7 |
| 47 | zai-org/GLM-5 | 1201.6 |
| 48 | deepseek-ai/DeepSeek-V3-0324 | 1201.6 |
| 49 | claude-3-7-sonnet-20250219 | 1201.5 |
| 50 | zai-org/GLM-4.5 | 1201.4 |
| 51 | gpt-4.5-preview | 1201.4 |
| 52 | grok-4.1-fast | 1201.2 |
| 53 | gpt-5.2 | 1201.1 |
| 54 | RekaAI/reka-flash-3 | 1200.9 |
| 55 | claude-sonnet-4 | 1200.9 |
| 56 | gpt-5-mini-2025-08-07 | 1200.7 |
| 57 | qwen/qwq-32b | 1200.7 |
| 58 | gemini-2.5-pro-exp-03-25 | 1200.7 |
| 59 | google/gemma-3-27b-it | 1200.4 |
| 60 | gpt-4.1-mini | 1200.4 |
| 61 | openrouter/horizon-alpha | 1200.0 |
| 62 | openrouter/horizon-beta | 1199.9 |
| 63 | ifable/gemma-2-Ifable-9B | 1199.0 |
| 64 | google/gemma-4-26B-A4B-it | 1199.4 |
| 65 | zai-org/GLM-4.7-Flash | 1199.1 |
| 66 | deepseek-ai/DeepSeek-V3.2-Speciale | 1198.7 |
| 67 | grok-3-beta | 1198.6 |
| 68 | google/gemma-3-4b-it | 1198.5 |
| 69 | anthropic/claude-3-haiku | 1198.4 |
| 70 | quasar-alpha | 1198.0 |
| 71 | anthropic/claude-3.5-haiku-20241022 | 1197.9 |
| 72 | google/gemma-2-9b-it | 1196.8 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1196.6 |
| 74 | zai-org/GLM-4.7 | 1196.4 |
| 75 | openai/gpt-4-0314 | 1194.2 |
| 76 | google/gemma-3-12b-it | 1193.9 |
| 77 | gemini-2.0-flash-001 | 1193.2 |
| 78 | gpt-4.1-nano | 1193.2 |
| 79 | ToastyPigeon/Gemma-3-Starshine-12B | 1193.1 |
| 80 | gemini-2.5-flash-preview | 1192.9 |
| 81 | mistralai/mistral-large-2411 | 1192.9 |
| 82 | meta-llama/llama-3.1-8b-instruct | 1192.8 |
| 83 | openai/gpt-3.5-turbo-0613 | 1192.7 |
| 84 | liquid/lfm-7b | 1192.6 |
| 85 | gpt-4o-mini | 1192.4 |
| 86 | gpt-5-nano-2025-08-07 | 1192.3 |
| 87 | openai/gpt-oss-120b | 1192.1 |
| 88 | meta-llama/llama-3.1-70b-instruct | 1191.9 |
| 89 | THUDM/GLM-4-32B-0414 | 1191.7 |
| 90 | mistralai/Mistral-Nemo-Instruct-2407 | 1191.2 |
| 91 | meta-llama/llama-3.2-3b-instruct | 1190.7 |
| 92 | meta-llama/llama-3.1-405b-instruct | 1190.6 |
| 93 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1190.5 |
| 94 | openai/gpt-oss-20b | 1190.4 |
| 95 | mistralai/Mistral-Small-24B-Instruct-2501 | 1190.3 |
| 96 | openrouter/cypher-alpha | 1190.3 |
| 97 | mistralai/Pixtral-Large-Instruct-2411 | 1189.7 |
| 98 | meta-llama/llama-3.2-1b-instruct | 1189.5 |
| 99 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1188.0 |
| 100 | CohereForAI/c4ai-command-a-03-2025 | 1188.0 |
| 101 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1186.5 |

### Option B: Bootstrapped Tournament Stability
*Option B evaluation was omitted for this model due to low Prompt-Isolated Elo Separability (Score < 50.0%).*
