# Detailed Results: Qwen/Qwen3.6-35B-A3B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.6164
* **Mean Absolute Cliff's Delta**: 0.6592
* **Combined Separability Score**: 63.78%
* **Positional Bias**: Position 1 (A): 9.9% | Position 2 (B): 90.1%
* **Length Bias**: Win Rate: 55.4% | Avg EV Margin: +1.8%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1209.2 |
| 2 | gpt-5.5 | 1207.0 |
| 3 | claude-opus-4-7 | 1206.9 |
| 4 | moonshotai/Kimi-K2-Thinking | 1205.7 |
| 5 | gpt-5.4 | 1205.6 |
| 6 | claude-opus-4-6 | 1205.6 |
| 7 | google/gemma-4-31B-it | 1205.4 |
| 8 | o3 | 1205.4 |
| 9 | deepseek-ai/DeepSeek-V3.2 | 1205.3 |
| 10 | Qwen/Qwen3.5-397B-A17B | 1205.2 |
| 11 | moonshotai/Kimi-K2.6 | 1205.0 |
| 12 | gemini-3.1-pro-preview | 1204.9 |
| 13 | gpt-5-2025-08-07 | 1204.8 |
| 14 | deepseek-ai/DeepSeek-V4-Pro | 1204.5 |
| 15 | moonshotai/Kimi-K2-Instruct | 1204.4 |
| 16 | openrouter/horizon-beta | 1204.4 |
| 17 | openrouter/horizon-alpha | 1204.3 |
| 18 | gemini-3-pro-preview | 1204.3 |
| 19 | claude-sonnet-4-6 | 1204.2 |
| 20 | openrouter/pony-alpha | 1203.6 |
| 21 | hunter-alpha | 1203.6 |
| 22 | deepseek-ai/DeepSeek-V4-Flash | 1203.6 |
| 23 | claude-opus-4 | 1203.5 |
| 24 | gpt-5.4-mini | 1203.4 |
| 25 | gemini-2.5-pro-preview-06-05 | 1203.3 |
| 26 | zai-org/GLM-5.1 | 1203.2 |
| 27 | deepseek-ai/DeepSeek-V3.1 | 1203.1 |
| 28 | zai-org/GLM-4.6 | 1203.1 |
| 29 | claude-opus-4-5-20251101 | 1203.0 |
| 30 | gpt-5.2 | 1202.9 |
| 31 | google/gemma-4-26B-A4B-it | 1202.8 |
| 32 | deepseek-ai/DeepSeek-R1 | 1202.7 |
| 33 | grok-4.20-beta | 1202.4 |
| 34 | claude-sonnet-4.5 | 1202.4 |
| 35 | chatgpt-4o-latest-2025-03-27 | 1202.3 |
| 36 | claude-3-5-sonnet-20241022 | 1202.1 |
| 37 | zai-org/GLM-5 | 1202.1 |
| 38 | zai-org/GLM-4.7 | 1201.9 |
| 39 | gpt-5-mini-2025-08-07 | 1201.7 |
| 40 | NousResearch/Hermes-4-405B | 1201.7 |
| 41 | deepseek-ai/DeepSeek-R1-0528 | 1201.6 |
| 42 | openrouter/sherlock-dash-alpha | 1201.5 |
| 43 | zai-org/GLM-4.5 | 1201.4 |
| 44 | grok-4.1-fast | 1201.3 |
| 45 | mistral-medium-3.1 | 1201.2 |
| 46 | qwen/qwen3-235b-a22b:thinking | 1201.1 |
| 47 | gemini-2.5-pro-exp-03-25 | 1201.1 |
| 48 | gpt-5.3-chat | 1201.0 |
| 49 | deepseek-ai/DeepSeek-V3-0324 | 1201.0 |
| 50 | optimus-alpha | 1200.7 |
| 51 | zai-org/GLM-4.7-Flash | 1200.6 |
| 52 | chatgpt-4o-latest-2025-01-29 | 1200.5 |
| 53 | claude-sonnet-4 | 1200.4 |
| 54 | mistral-small-creative | 1200.2 |
| 55 | minimax/minimax-m2.5 | 1200.2 |
| 56 | ifable/gemma-2-Ifable-9B | 1200.2 |
| 57 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1200.1 |
| 58 | claude-3-7-sonnet-20250219 | 1200.0 |
| 59 | quasar-alpha | 1200.0 |
| 60 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.8 |
| 61 | deepseek-ai/DeepSeek-V3.2-Speciale | 1199.7 |
| 62 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1199.5 |
| 63 | RekaAI/reka-flash-3 | 1199.4 |
| 64 | gpt-4.5-preview | 1199.3 |
| 65 | grok-3-beta | 1199.3 |
| 66 | google/gemma-3-27b-it | 1198.8 |
| 67 | gpt-4.1-mini | 1198.8 |
| 68 | anthropic/claude-3.5-haiku-20241022 | 1198.5 |
| 69 | allura-org/Gemma-3-Glitter-12B | 1198.4 |
| 70 | gemini-2.5-flash-preview | 1198.2 |
| 71 | sam-paech/Darkest-muse-v1 | 1198.1 |
| 72 | gemini-2.0-flash-001 | 1198.0 |
| 73 | qwen/qwq-32b | 1198.0 |
| 74 | CohereForAI/c4ai-command-a-03-2025 | 1197.6 |
| 75 | google/gemma-3-12b-it | 1197.5 |
| 76 | google/gemma-3-4b-it | 1197.4 |
| 77 | google/gemma-2-9b-it | 1196.8 |
| 78 | gpt-5-nano-2025-08-07 | 1196.7 |
| 79 | meta-llama/llama-3.1-405b-instruct | 1196.7 |
| 80 | openai/gpt-oss-120b | 1196.2 |
| 81 | THUDM/GLM-4-32B-0414 | 1196.1 |
| 82 | openai/gpt-4-0314 | 1195.5 |
| 83 | meta-llama/llama-3.1-70b-instruct | 1195.4 |
| 84 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1195.0 |
| 85 | mistralai/mistral-large-2411 | 1194.9 |
| 86 | gpt-4o-mini | 1194.8 |
| 87 | gpt-4.1-nano | 1194.8 |
| 88 | mistralai/Pixtral-Large-Instruct-2411 | 1194.5 |
| 89 | anthropic/claude-3-haiku | 1194.2 |
| 90 | meta-llama/llama-3.1-8b-instruct | 1193.9 |
| 91 | mistralai/Mistral-Nemo-Instruct-2407 | 1193.9 |
| 92 | ToastyPigeon/Gemma-3-Starshine-12B | 1193.7 |
| 93 | openrouter/cypher-alpha | 1193.5 |
| 94 | liquid/lfm-7b | 1193.3 |
| 95 | openai/gpt-3.5-turbo-0613 | 1192.4 |
| 96 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1192.3 |
| 97 | meta-llama/llama-3.2-3b-instruct | 1191.7 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1191.7 |
| 99 | openai/gpt-oss-20b | 1191.5 |
| 100 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1191.3 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1188.0 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9008
* **Mean Absolute Cliff's Delta**: 0.8314
* **Combined Separability Score**: 86.61%
* **Positional Bias**: Position 1 (A): 9.5% | Position 2 (B): 90.5%
* **Length Bias**: Win Rate: 54.2% | Avg EV Margin: +0.9%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1217.5 ± 3.0 |
| 2 | gpt-5.5 | 1216.1 ± 2.3 |
| 3 | gpt-5.4 | 1214.8 ± 3.9 |
| 4 | moonshotai/Kimi-K2.5 | 1213.9 ± 2.8 |
| 5 | claude-opus-4-6 | 1212.2 ± 2.3 |
| 6 | openrouter/horizon-alpha | 1210.2 ± 2.0 |
| 7 | gpt-5-2025-08-07 | 1209.7 ± 2.4 |
| 8 | deepseek-ai/DeepSeek-V4-Flash | 1209.7 ± 3.6 |
| 9 | moonshotai/Kimi-K2.6 | 1209.5 ± 1.7 |
| 10 | deepseek-ai/DeepSeek-V3.2 | 1209.3 ± 2.7 |
| 11 | claude-sonnet-4-6 | 1209.1 ± 3.5 |
| 12 | moonshotai/Kimi-K2-Instruct | 1209.1 ± 1.2 |
| 13 | deepseek-ai/DeepSeek-V4-Pro | 1208.9 ± 4.3 |
| 14 | gemini-3.1-pro-preview | 1208.7 ± 0.9 |
| 15 | gemini-3-pro-preview | 1208.6 ± 1.7 |
| 16 | moonshotai/Kimi-K2-Thinking | 1208.3 ± 2.8 |
| 17 | openrouter/horizon-beta | 1207.9 ± 1.5 |
| 18 | gpt-5.2 | 1207.9 ± 2.2 |
| 19 | Qwen/Qwen3.5-397B-A17B | 1207.9 ± 1.6 |
| 20 | gemini-2.5-pro-preview-06-05 | 1207.6 ± 1.3 |
| 21 | gpt-5.4-mini | 1207.2 ± 1.7 |
| 22 | o3 | 1207.1 ± 1.6 |
| 23 | claude-opus-4-5-20251101 | 1207.0 ± 1.7 |
| 24 | google/gemma-4-31B-it | 1206.6 ± 2.8 |
| 25 | zai-org/GLM-5.1 | 1206.2 ± 3.4 |
| 26 | zai-org/GLM-4.7 | 1206.1 ± 4.0 |
| 27 | deepseek-ai/DeepSeek-R1-0528 | 1206.0 ± 2.2 |
| 28 | claude-sonnet-4.5 | 1205.9 ± 1.6 |
| 29 | deepseek-ai/DeepSeek-V3.1 | 1205.6 ± 1.5 |
| 30 | zai-org/GLM-4.6 | 1205.6 ± 1.5 |
| 31 | openrouter/pony-alpha | 1205.5 ± 1.8 |
| 32 | google/gemma-4-26B-A4B-it | 1205.4 ± 1.6 |
| 33 | hunter-alpha | 1205.2 ± 2.4 |
| 34 | claude-opus-4 | 1205.0 ± 2.8 |
| 35 | grok-4.20-beta | 1205.0 ± 2.8 |
| 36 | gpt-5-mini-2025-08-07 | 1204.4 ± 2.4 |
| 37 | chatgpt-4o-latest-2025-03-27 | 1203.8 ± 1.4 |
| 38 | zai-org/GLM-5 | 1203.6 ± 1.5 |
| 39 | optimus-alpha | 1203.5 ± 2.0 |
| 40 | openrouter/sherlock-dash-alpha | 1202.9 ± 2.6 |
| 41 | deepseek-ai/DeepSeek-R1 | 1202.8 ± 1.1 |
| 42 | NousResearch/Hermes-4-405B | 1202.7 ± 1.1 |
| 43 | zai-org/GLM-4.5 | 1202.7 ± 3.0 |
| 44 | gemini-2.5-pro-exp-03-25 | 1202.5 ± 0.8 |
| 45 | deepseek-ai/DeepSeek-V3-0324 | 1202.4 ± 4.3 |
| 46 | claude-3-5-sonnet-20241022 | 1202.4 ± 1.5 |
| 47 | qwen/qwen3-235b-a22b:thinking | 1202.3 ± 2.2 |
| 48 | mistral-medium-3.1 | 1202.0 ± 2.2 |
| 49 | claude-3-7-sonnet-20250219 | 1201.6 ± 1.2 |
| 50 | grok-4.1-fast | 1201.4 ± 0.7 |
| 51 | gpt-5.3-chat | 1201.2 ± 1.9 |
| 52 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1200.8 ± 1.1 |
| 53 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.6 ± 0.8 |
| 54 | claude-sonnet-4 | 1200.4 ± 1.9 |
| 55 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1199.8 ± 1.5 |
| 56 | quasar-alpha | 1199.7 ± 1.3 |
| 57 | minimax/minimax-m2.5 | 1199.7 ± 1.1 |
| 58 | google/gemma-3-27b-it | 1199.6 ± 2.5 |
| 59 | chatgpt-4o-latest-2025-01-29 | 1199.4 ± 0.8 |
| 60 | grok-3-beta | 1199.4 ± 1.0 |
| 61 | sam-paech/Darkest-muse-v1 | 1199.1 ± 1.1 |
| 62 | gpt-4.5-preview | 1198.9 ± 1.8 |
| 63 | RekaAI/reka-flash-3 | 1198.7 ± 2.0 |
| 64 | ifable/gemma-2-Ifable-9B | 1198.5 ± 2.3 |
| 65 | zai-org/GLM-4.7-Flash | 1198.4 ± 2.4 |
| 66 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1198.3 ± 2.8 |
| 67 | google/gemma-3-12b-it | 1197.9 ± 1.9 |
| 68 | CohereForAI/c4ai-command-a-03-2025 | 1197.6 ± 0.9 |
| 69 | gemini-2.0-flash-001 | 1197.5 ± 2.5 |
| 70 | allura-org/Gemma-3-Glitter-12B | 1197.4 ± 2.4 |
| 71 | gpt-4.1-mini | 1197.3 ± 1.8 |
| 72 | mistral-small-creative | 1197.2 ± 1.9 |
| 73 | openai/gpt-oss-120b | 1197.0 ± 2.6 |
| 74 | google/gemma-3-4b-it | 1196.9 ± 2.3 |
| 75 | gpt-5-nano-2025-08-07 | 1196.7 ± 1.8 |
| 76 | gemini-2.5-flash-preview | 1196.7 ± 1.4 |
| 77 | qwen/qwq-32b | 1196.6 ± 1.0 |
| 78 | THUDM/GLM-4-32B-0414 | 1196.2 ± 2.6 |
| 79 | anthropic/claude-3.5-haiku-20241022 | 1195.0 ± 1.4 |
| 80 | gpt-4.1-nano | 1194.2 ± 3.9 |
| 81 | google/gemma-2-9b-it | 1193.6 ± 2.2 |
| 82 | gpt-4o-mini | 1192.9 ± 2.3 |
| 83 | meta-llama/llama-3.1-405b-instruct | 1192.0 ± 2.2 |
| 84 | ToastyPigeon/Gemma-3-Starshine-12B | 1191.4 ± 2.2 |
| 85 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1190.8 ± 2.8 |
| 86 | mistralai/mistral-large-2411 | 1190.5 ± 2.7 |
| 87 | meta-llama/llama-3.1-70b-instruct | 1189.9 ± 1.9 |
| 88 | openai/gpt-4-0314 | 1189.9 ± 2.3 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1189.5 ± 1.9 |
| 90 | mistralai/Pixtral-Large-Instruct-2411 | 1189.0 ± 2.4 |
| 91 | openai/gpt-oss-20b | 1188.2 ± 2.8 |
| 92 | anthropic/claude-3-haiku | 1187.9 ± 1.9 |
| 93 | liquid/lfm-7b | 1187.3 ± 4.1 |
| 94 | meta-llama/llama-3.1-8b-instruct | 1186.1 ± 1.3 |
| 95 | openrouter/cypher-alpha | 1184.0 ± 2.8 |
| 96 | openai/gpt-3.5-turbo-0613 | 1183.3 ± 4.1 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1192.3 ± 6.6 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1191.7 ± 6.5 |
| 99 | openai/gpt-oss-20b | 1191.5 ± 2.8 |
| 100 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1191.3 ± 7.0 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1188.0 ± 1.8 |
