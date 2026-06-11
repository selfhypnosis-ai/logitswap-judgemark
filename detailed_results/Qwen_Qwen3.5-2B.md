# Detailed Results: Qwen/Qwen3.5-2B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.4747
* **Mean Absolute Cliff's Delta**: 0.5077
* **Combined Separability Score**: 49.12%
* **Positional Bias**: Position 1 (A): 75.1% | Position 2 (B): 24.9%
* **Length Bias**: Win Rate: 54.7% | Avg EV Margin: +1.8%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1206.5 |
| 2 | o3 | 1205.0 |
| 3 | gpt-5.3-chat | 1205.0 |
| 4 | moonshotai/Kimi-K2-Instruct | 1204.9 |
| 5 | deepseek-ai/DeepSeek-V3.2 | 1204.2 |
| 6 | gpt-5.5 | 1204.1 |
| 7 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1203.9 |
| 8 | deepseek-ai/DeepSeek-V4-Pro | 1203.8 |
| 9 | grok-4.20-beta | 1203.8 |
| 10 | mistral-small-creative | 1203.6 |
| 11 | zai-org/GLM-4.6 | 1203.6 |
| 12 | deepseek-ai/DeepSeek-V3.1 | 1203.5 |
| 13 | openrouter/horizon-alpha | 1203.5 |
| 14 | deepseek-ai/DeepSeek-R1-0528 | 1203.4 |
| 15 | gemini-3.1-pro-preview | 1203.3 |
| 16 | zai-org/GLM-4.5 | 1203.2 |
| 17 | mistral-medium-3.1 | 1203.2 |
| 18 | deepseek-ai/DeepSeek-V4-Flash | 1203.2 |
| 19 | moonshotai/Kimi-K2-Thinking | 1203.1 |
| 20 | gpt-5.4 | 1203.1 |
| 21 | gemini-2.5-pro-preview-06-05 | 1202.9 |
| 22 | gpt-5.2 | 1202.9 |
| 23 | google/gemma-4-31B-it | 1202.8 |
| 24 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1202.7 |
| 25 | claude-opus-4-7 | 1202.7 |
| 26 | claude-opus-4-6 | 1202.4 |
| 27 | NousResearch/Hermes-4-405B | 1202.4 |
| 28 | hunter-alpha | 1202.3 |
| 29 | gemini-3-pro-preview | 1202.3 |
| 30 | openrouter/horizon-beta | 1202.2 |
| 31 | Qwen/Qwen3.5-397B-A17B | 1202.2 |
| 32 | gpt-5-2025-08-07 | 1202.2 |
| 33 | qwen/qwen3-235b-a22b:thinking | 1202.2 |
| 34 | gpt-5-mini-2025-08-07 | 1201.9 |
| 35 | chatgpt-4o-latest-2025-03-27 | 1201.9 |
| 36 | gpt-5.4-mini | 1201.9 |
| 37 | zai-org/GLM-4.7 | 1201.8 |
| 38 | RekaAI/reka-flash-3 | 1201.8 |
| 39 | sam-paech/Darkest-muse-v1 | 1201.8 |
| 40 | deepseek-ai/DeepSeek-R1 | 1201.8 |
| 41 | ifable/gemma-2-Ifable-9B | 1201.7 |
| 42 | zai-org/GLM-5.1 | 1201.7 |
| 43 | optimus-alpha | 1201.6 |
| 44 | google/gemma-4-26B-A4B-it | 1201.5 |
| 45 | gemini-2.5-pro-exp-03-25 | 1201.0 |
| 46 | claude-opus-4-5-20251101 | 1201.0 |
| 47 | claude-sonnet-4.5 | 1200.9 |
| 48 | minimax/minimax-m2.5 | 1200.9 |
| 49 | google/gemma-3-4b-it | 1200.8 |
| 50 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.7 |
| 51 | moonshotai/Kimi-K2.6 | 1200.6 |
| 52 | claude-opus-4 | 1200.5 |
| 53 | deepseek-ai/DeepSeek-V3-0324 | 1200.4 |
| 54 | claude-sonnet-4-6 | 1200.3 |
| 55 | google/gemma-3-27b-it | 1200.3 |
| 56 | grok-3-beta | 1200.3 |
| 57 | zai-org/GLM-4.7-Flash | 1200.1 |
| 58 | openai/gpt-oss-120b | 1200.1 |
| 59 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.0 |
| 60 | quasar-alpha | 1200.0 |
| 61 | gemini-2.5-flash-preview | 1199.9 |
| 62 | claude-3-5-sonnet-20241022 | 1199.9 |
| 63 | claude-sonnet-4 | 1199.5 |
| 64 | chatgpt-4o-latest-2025-01-29 | 1199.5 |
| 65 | gpt-5-nano-2025-08-07 | 1199.3 |
| 66 | gpt-4.1-mini | 1199.3 |
| 67 | allura-org/Gemma-3-Glitter-12B | 1199.0 |
| 68 | openrouter/pony-alpha | 1198.9 |
| 69 | gpt-4.5-preview | 1198.7 |
| 70 | zai-org/GLM-5 | 1198.7 |
| 71 | qwen/qwq-32b | 1198.7 |
| 72 | gemini-2.0-flash-001 | 1198.7 |
| 73 | grok-4.1-fast | 1198.6 |
| 74 | google/gemma-3-12b-it | 1198.6 |
| 75 | claude-3-7-sonnet-20250219 | 1198.6 |
| 76 | openrouter/sherlock-dash-alpha | 1198.2 |
| 77 | CohereForAI/c4ai-command-a-03-2025 | 1198.1 |
| 78 | google/gemma-2-9b-it | 1197.8 |
| 79 | anthropic/claude-3.5-haiku-20241022 | 1197.5 |
| 80 | meta-llama/llama-3.1-405b-instruct | 1197.2 |
| 81 | THUDM/GLM-4-32B-0414 | 1196.7 |
| 82 | gpt-4.1-nano | 1196.6 |
| 83 | meta-llama/llama-3.1-70b-instruct | 1196.4 |
| 84 | anthropic/claude-3-haiku | 1196.2 |
| 85 | gpt-4o-mini | 1195.9 |
| 86 | openai/gpt-4-0314 | 1195.8 |
| 87 | mistralai/mistral-large-2411 | 1195.5 |
| 88 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1195.5 |
| 89 | ToastyPigeon/Gemma-3-Starshine-12B | 1195.5 |
| 90 | openai/gpt-oss-20b | 1195.3 |
| 91 | mistralai/Mistral-Nemo-Instruct-2407 | 1195.1 |
| 92 | mistralai/Pixtral-Large-Instruct-2411 | 1194.7 |
| 93 | meta-llama/llama-3.1-8b-instruct | 1194.4 |
| 94 | meta-llama/llama-3.2-3b-instruct | 1194.3 |
| 95 | liquid/lfm-7b | 1193.9 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1193.6 |
| 97 | openrouter/cypher-alpha | 1193.4 |
| 98 | openai/gpt-3.5-turbo-0613 | 1193.2 |
| 99 | meta-llama/llama-3.2-1b-instruct | 1192.1 |
| 100 | mistralai/Mistral-Small-24B-Instruct-2501 | 1192.1 |
| 101 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1191.7 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.8466
* **Mean Absolute Cliff's Delta**: 0.7874
* **Combined Separability Score**: 81.70%
* **Positional Bias**: Position 1 (A): 72.5% | Position 2 (B): 27.5%
* **Length Bias**: Win Rate: 52.7% | Avg EV Margin: +1.2%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1218.9 ± 2.6 |
| 2 | moonshotai/Kimi-K2-Instruct | 1218.3 ± 3.0 |
| 3 | o3 | 1216.4 ± 4.1 |
| 4 | zai-org/GLM-4.5 | 1214.8 ± 6.7 |
| 5 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1214.2 ± 6.6 |
| 6 | gpt-5.3-chat | 1214.2 ± 4.3 |
| 7 | gpt-5.4 | 1213.5 ± 3.7 |
| 8 | deepseek-ai/DeepSeek-V4-Pro | 1213.3 ± 3.9 |
| 9 | deepseek-ai/DeepSeek-R1-0528 | 1212.7 ± 1.4 |
| 10 | gpt-5.4-mini | 1212.1 ± 4.9 |
| 11 | deepseek-ai/DeepSeek-V3.2 | 1211.0 ± 2.0 |
| 12 | deepseek-ai/DeepSeek-V4-Flash | 1210.2 ± 3.3 |
| 13 | gemini-2.5-pro-preview-06-05 | 1210.2 ± 1.9 |
| 14 | zai-org/GLM-4.6 | 1209.5 ± 1.7 |
| 15 | gemini-3.1-pro-preview | 1209.4 ± 4.5 |
| 16 | openrouter/horizon-alpha | 1209.1 ± 3.5 |
| 17 | openrouter/horizon-beta | 1208.7 ± 3.7 |
| 18 | NousResearch/Hermes-4-405B | 1208.4 ± 5.5 |
| 19 | moonshotai/Kimi-K2-Thinking | 1208.3 ± 2.9 |
| 20 | gpt-5.5 | 1208.2 ± 1.4 |
| 21 | deepseek-ai/DeepSeek-V3.1 | 1207.6 ± 1.6 |
| 22 | gpt-5.2 | 1207.1 ± 4.5 |
| 23 | mistral-small-creative | 1206.9 ± 3.8 |
| 24 | gemini-2.5-pro-exp-03-25 | 1206.7 ± 2.9 |
| 25 | gpt-5-2025-08-07 | 1206.4 ± 0.7 |
| 26 | gpt-5-mini-2025-08-07 | 1206.3 ± 2.0 |
| 27 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1206.1 ± 1.4 |
| 28 | google/gemma-4-26B-A4B-it | 1206.0 ± 4.7 |
| 29 | Qwen/Qwen3.5-397B-A17B | 1205.7 ± 2.8 |
| 30 | gemini-3-pro-preview | 1205.7 ± 4.8 |
| 31 | qwen/qwen3-235b-a22b:thinking | 1205.3 ± 5.8 |
| 32 | zai-org/GLM-4.7 | 1205.3 ± 4.6 |
| 33 | zai-org/GLM-5.1 | 1205.1 ± 4.0 |
| 34 | sam-paech/Darkest-muse-v1 | 1205.0 ± 3.7 |
| 35 | mistral-medium-3.1 | 1204.8 ± 3.3 |
| 36 | google/gemma-4-31B-it | 1204.7 ± 5.4 |
| 37 | hunter-alpha | 1204.5 ± 2.8 |
| 38 | optimus-alpha | 1204.4 ± 1.6 |
| 39 | claude-opus-4-6 | 1204.4 ± 1.6 |
| 40 | ifable/gemma-2-Ifable-9B | 1203.6 ± 1.8 |
| 41 | quasar-alpha | 1203.6 ± 4.5 |
| 42 | minimax/minimax-m2.5 | 1203.1 ± 3.5 |
| 43 | claude-opus-4-7 | 1203.1 ± 3.4 |
| 44 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1201.9 ± 7.3 |
| 45 | gpt-5-nano-2025-08-07 | 1201.8 ± 2.8 |
| 46 | claude-opus-4 | 1201.7 ± 1.9 |
| 47 | grok-4.20-beta | 1201.6 ± 3.1 |
| 48 | deepseek-ai/DeepSeek-R1 | 1201.3 ± 3.5 |
| 49 | grok-3-beta | 1201.2 ± 1.0 |
| 50 | moonshotai/Kimi-K2.6 | 1201.1 ± 3.0 |
| 51 | chatgpt-4o-latest-2025-03-27 | 1201.1 ± 2.2 |
| 52 | openai/gpt-oss-120b | 1200.5 ± 4.3 |
| 53 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.3 ± 2.9 |
| 54 | chatgpt-4o-latest-2025-01-29 | 1200.0 ± 4.4 |
| 55 | zai-org/GLM-4.7-Flash | 1200.0 ± 3.5 |
| 56 | gemini-2.5-flash-preview | 1199.5 ± 2.3 |
| 57 | claude-sonnet-4-6 | 1199.5 ± 3.1 |
| 58 | qwen/qwq-32b | 1199.2 ± 2.3 |
| 59 | RekaAI/reka-flash-3 | 1199.0 ± 2.0 |
| 60 | claude-sonnet-4.5 | 1198.9 ± 3.4 |
| 61 | claude-opus-4-5-20251101 | 1198.3 ± 3.3 |
| 62 | google/gemma-3-27b-it | 1198.2 ± 3.6 |
| 63 | zai-org/GLM-5 | 1198.1 ± 2.5 |
| 64 | allura-org/Gemma-3-Glitter-12B | 1198.0 ± 1.4 |
| 65 | claude-sonnet-4 | 1198.0 ± 1.3 |
| 66 | google/gemma-3-12b-it | 1197.5 ± 1.7 |
| 67 | gemini-2.0-flash-001 | 1197.1 ± 3.3 |
| 68 | google/gemma-3-4b-it | 1197.1 ± 1.9 |
| 69 | claude-3-7-sonnet-20250219 | 1197.0 ± 3.3 |
| 70 | gpt-4.1-mini | 1197.0 ± 1.7 |
| 71 | claude-3-5-sonnet-20241022 | 1196.4 ± 3.1 |
| 72 | gpt-4.5-preview | 1196.1 ± 0.8 |
| 73 | openrouter/pony-alpha | 1196.0 ± 4.4 |
| 74 | openrouter/sherlock-dash-alpha | 1196.0 ± 3.6 |
| 75 | grok-4.1-fast | 1195.5 ± 2.0 |
| 76 | deepseek-ai/DeepSeek-V3-0324 | 1195.5 ± 1.4 |
| 77 | CohereForAI/c4ai-command-a-03-2025 | 1195.3 ± 1.2 |
| 78 | anthropic/claude-3-haiku | 1193.7 ± 1.9 |
| 79 | anthropic/claude-3.5-haiku-20241022 | 1193.6 ± 2.8 |
| 80 | openai/gpt-oss-20b | 1193.2 ± 2.2 |
| 81 | THUDM/GLM-4-32B-0414 | 1192.6 ± 3.7 |
| 82 | gpt-4o-mini | 1192.1 ± 3.7 |
| 83 | gpt-4.1-nano | 1190.9 ± 5.4 |
| 84 | google/gemma-2-9b-it | 1190.1 ± 3.3 |
| 85 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1189.0 ± 3.2 |
| 86 | mistralai/mistral-large-2411 | 1188.9 ± 4.6 |
| 87 | mistralai/Mistral-Nemo-Instruct-2407 | 1188.8 ± 0.9 |
| 88 | meta-llama/llama-3.1-70b-instruct | 1188.7 ± 1.9 |
| 89 | ToastyPigeon/Gemma-3-Starshine-12B | 1188.6 ± 2.6 |
| 90 | openai/gpt-4-0314 | 1187.4 ± 0.9 |
| 91 | meta-llama/llama-3.1-405b-instruct | 1187.0 ± 3.3 |
| 92 | mistralai/Pixtral-Large-Instruct-2411 | 1185.3 ± 1.6 |
| 93 | meta-llama/llama-3.1-8b-instruct | 1185.0 ± 2.2 |
| 94 | liquid/lfm-7b | 1184.5 ± 2.2 |
| 95 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1182.6 ± 1.7 |
| 96 | meta-llama/llama-3.2-3b-instruct | 1182.2 ± 2.5 |
| 97 | openrouter/cypher-alpha | 1181.7 ± 3.1 |
| 98 | openai/gpt-3.5-turbo-0613 | 1180.9 ± 5.3 |
| 99 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1178.9 ± 5.9 |
| 100 | meta-llama/llama-3.2-1b-instruct | 1178.4 ± 3.8 |
| 101 | mistralai/Mistral-Small-24B-Instruct-2501 | 1177.1 ± 9.4 |
