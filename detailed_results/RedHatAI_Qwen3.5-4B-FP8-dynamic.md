# Detailed Results: RedHatAI/Qwen3.5-4B-FP8-dynamic

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.6668
* **Mean Absolute Cliff's Delta**: 0.6485
* **Combined Separability Score**: 65.76%
* **Positional Bias**: Position 1 (A): 77.6% | Position 2 (B): 22.4%
* **Length Bias**: Win Rate: 55.7% | Avg EV Margin: +2.5%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1210.4 |
| 2 | claude-opus-4-7 | 1210.0 |
| 3 | grok-4.20-beta | 1209.7 |
| 4 | claude-opus-4-6 | 1209.4 |
| 5 | gpt-5.3-chat | 1208.6 |
| 6 | claude-sonnet-4-6 | 1208.1 |
| 7 | gpt-5.4 | 1207.9 |
| 8 | gpt-5.4-mini | 1207.2 |
| 9 | moonshotai/Kimi-K2.6 | 1207.2 |
| 10 | deepseek-ai/DeepSeek-V4-Pro | 1206.7 |
| 11 | claude-sonnet-4.5 | 1206.7 |
| 12 | zai-org/GLM-5.1 | 1206.7 |
| 13 | gpt-5.5 | 1206.5 |
| 14 | grok-4.1-fast | 1205.3 |
| 15 | openrouter/horizon-alpha | 1205.3 |
| 16 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1205.2 |
| 17 | mistral-medium-3.1 | 1204.9 |
| 18 | claude-opus-4-5-20251101 | 1204.8 |
| 19 | deepseek-ai/DeepSeek-V3.2 | 1204.8 |
| 20 | chatgpt-4o-latest-2025-03-27 | 1204.7 |
| 21 | o3 | 1204.7 |
| 22 | google/gemma-4-31B-it | 1204.6 |
| 23 | gemini-2.5-pro-preview-06-05 | 1204.6 |
| 24 | deepseek-ai/DeepSeek-V3.1 | 1204.3 |
| 25 | moonshotai/Kimi-K2-Instruct | 1204.2 |
| 26 | deepseek-ai/DeepSeek-V4-Flash | 1204.2 |
| 27 | moonshotai/Kimi-K2-Thinking | 1204.2 |
| 28 | openrouter/pony-alpha | 1203.8 |
| 29 | openrouter/horizon-beta | 1203.8 |
| 30 | Qwen/Qwen3.5-397B-A17B | 1203.7 |
| 31 | claude-opus-4 | 1203.6 |
| 32 | openrouter/sherlock-dash-alpha | 1203.5 |
| 33 | gpt-5.2 | 1203.4 |
| 34 | gpt-5-2025-08-07 | 1203.2 |
| 35 | zai-org/GLM-4.6 | 1202.8 |
| 36 | gemini-3-pro-preview | 1202.8 |
| 37 | NousResearch/Hermes-4-405B | 1202.8 |
| 38 | qwen/qwen3-235b-a22b:thinking | 1202.6 |
| 39 | gemini-3.1-pro-preview | 1202.6 |
| 40 | deepseek-ai/DeepSeek-V3-0324 | 1202.6 |
| 41 | zai-org/GLM-5 | 1202.4 |
| 42 | hunter-alpha | 1202.4 |
| 43 | zai-org/GLM-4.7 | 1202.3 |
| 44 | gpt-5-mini-2025-08-07 | 1202.1 |
| 45 | google/gemma-4-26B-A4B-it | 1201.9 |
| 46 | minimax/minimax-m2.5 | 1201.6 |
| 47 | zai-org/GLM-4.5 | 1201.6 |
| 48 | sam-paech/Darkest-muse-v1 | 1201.4 |
| 49 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1201.4 |
| 50 | RekaAI/reka-flash-3 | 1201.2 |
| 51 | claude-3-5-sonnet-20241022 | 1201.1 |
| 52 | claude-sonnet-4 | 1201.0 |
| 53 | deepseek-ai/DeepSeek-R1-0528 | 1201.0 |
| 54 | mistral-small-creative | 1200.7 |
| 55 | gpt-4.5-preview | 1200.3 |
| 56 | quasar-alpha | 1200.3 |
| 57 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.2 |
| 58 | deepseek-ai/DeepSeek-R1 | 1200.0 |
| 59 | ifable/gemma-2-Ifable-9B | 1199.9 |
| 60 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.6 |
| 61 | qwen/qwq-32b | 1199.6 |
| 62 | gemini-2.5-pro-exp-03-25 | 1199.6 |
| 63 | chatgpt-4o-latest-2025-01-29 | 1199.6 |
| 64 | optimus-alpha | 1199.5 |
| 65 | google/gemma-3-27b-it | 1199.0 |
| 66 | gpt-4.1-mini | 1198.9 |
| 67 | gemini-2.5-flash-preview | 1198.7 |
| 68 | claude-3-7-sonnet-20250219 | 1198.7 |
| 69 | grok-3-beta | 1198.2 |
| 70 | anthropic/claude-3.5-haiku-20241022 | 1197.9 |
| 71 | zai-org/GLM-4.7-Flash | 1197.8 |
| 72 | gpt-5-nano-2025-08-07 | 1197.3 |
| 73 | gemini-2.0-flash-001 | 1196.9 |
| 74 | google/gemma-3-4b-it | 1196.7 |
| 75 | CohereForAI/c4ai-command-a-03-2025 | 1196.7 |
| 76 | meta-llama/llama-3.1-405b-instruct | 1195.6 |
| 77 | openai/gpt-oss-120b | 1195.2 |
| 78 | google/gemma-3-12b-it | 1195.1 |
| 79 | allura-org/Gemma-3-Glitter-12B | 1195.0 |
| 80 | gpt-4.1-nano | 1194.8 |
| 81 | anthropic/claude-3-haiku | 1194.7 |
| 82 | google/gemma-2-9b-it | 1194.4 |
| 83 | gpt-4o-mini | 1194.0 |
| 84 | THUDM/GLM-4-32B-0414 | 1193.9 |
| 85 | mistralai/mistral-large-2411 | 1193.5 |
| 86 | mistralai/Pixtral-Large-Instruct-2411 | 1192.7 |
| 87 | openai/gpt-oss-20b | 1192.0 |
| 88 | liquid/lfm-7b | 1191.9 |
| 89 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1191.7 |
| 90 | meta-llama/llama-3.1-70b-instruct | 1191.6 |
| 91 | meta-llama/llama-3.1-8b-instruct | 1191.6 |
| 92 | openrouter/cypher-alpha | 1190.9 |
| 93 | openai/gpt-4-0314 | 1190.9 |
| 94 | mistralai/Mistral-Nemo-Instruct-2407 | 1190.7 |
| 95 | ToastyPigeon/Gemma-3-Starshine-12B | 1190.4 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1189.7 |
| 97 | meta-llama/llama-3.2-1b-instruct | 1188.6 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1188.5 |
| 99 | meta-llama/llama-3.2-3b-instruct | 1188.4 |
| 100 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1187.5 |
| 101 | openai/gpt-3.5-turbo-0613 | 1187.3 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9140
* **Mean Absolute Cliff's Delta**: 0.8469
* **Combined Separability Score**: 88.04%
* **Positional Bias**: Position 1 (A): 75.6% | Position 2 (B): 24.4%
* **Length Bias**: Win Rate: 54.1% | Avg EV Margin: +2.1%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | grok-4.20-beta | 1232.5 ± 3.5 |
| 2 | claude-opus-4-7 | 1229.0 ± 6.9 |
| 3 | gpt-5.3-chat | 1223.7 ± 4.5 |
| 4 | claude-sonnet-4-6 | 1220.5 ± 3.3 |
| 5 | gpt-5.4 | 1220.5 ± 4.8 |
| 6 | claude-opus-4-6 | 1220.4 ± 2.9 |
| 7 | gpt-5.4-mini | 1220.1 ± 4.6 |
| 8 | moonshotai/Kimi-K2.5 | 1218.8 ± 3.4 |
| 9 | gpt-5.5 | 1217.8 ± 6.5 |
| 10 | openrouter/horizon-beta | 1216.9 ± 3.2 |
| 11 | gpt-5.2 | 1215.9 ± 7.0 |
| 12 | moonshotai/Kimi-K2.6 | 1215.3 ± 6.5 |
| 13 | moonshotai/Kimi-K2-Instruct | 1214.8 ± 5.6 |
| 14 | openrouter/horizon-alpha | 1214.4 ± 4.3 |
| 15 | gpt-5-2025-08-07 | 1214.3 ± 5.2 |
| 16 | deepseek-ai/DeepSeek-V3.2 | 1212.9 ± 3.0 |
| 17 | claude-opus-4-5-20251101 | 1212.5 ± 2.0 |
| 18 | zai-org/GLM-5.1 | 1211.9 ± 4.9 |
| 19 | moonshotai/Kimi-K2-Thinking | 1211.2 ± 1.9 |
| 20 | claude-sonnet-4.5 | 1210.2 ± 4.2 |
| 21 | o3 | 1210.0 ± 2.0 |
| 22 | gemini-2.5-pro-preview-06-05 | 1209.1 ± 2.2 |
| 23 | deepseek-ai/DeepSeek-V4-Flash | 1208.1 ± 2.1 |
| 24 | gpt-5-mini-2025-08-07 | 1207.7 ± 3.7 |
| 25 | gemini-3.1-pro-preview | 1207.6 ± 4.4 |
| 26 | deepseek-ai/DeepSeek-V4-Pro | 1207.6 ± 2.6 |
| 27 | claude-opus-4 | 1207.5 ± 1.5 |
| 28 | hunter-alpha | 1207.4 ± 2.6 |
| 29 | grok-4.1-fast | 1207.4 ± 4.1 |
| 30 | openrouter/pony-alpha | 1207.4 ± 1.8 |
| 31 | deepseek-ai/DeepSeek-V3.1 | 1206.9 ± 1.7 |
| 32 | zai-org/GLM-4.6 | 1206.6 ± 3.5 |
| 33 | deepseek-ai/DeepSeek-R1 | 1206.1 ± 1.3 |
| 34 | zai-org/GLM-5 | 1206.0 ± 1.1 |
| 35 | claude-sonnet-4 | 1205.8 ± 2.4 |
| 36 | deepseek-ai/DeepSeek-R1-0528 | 1205.3 ± 3.1 |
| 37 | gemini-3-pro-preview | 1205.3 ± 3.3 |
| 38 | NousResearch/Hermes-4-405B | 1205.2 ± 1.7 |
| 39 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.9 ± 2.7 |
| 40 | minimax/minimax-m2.5 | 1204.6 ± 2.7 |
| 41 | openrouter/sherlock-dash-alpha | 1204.3 ± 2.4 |
| 42 | gemini-2.5-pro-exp-03-25 | 1204.1 ± 2.9 |
| 43 | google/gemma-4-26B-A4B-it | 1203.7 ± 2.9 |
| 44 | chatgpt-4o-latest-2025-03-27 | 1203.1 ± 1.5 |
| 45 | Qwen/Qwen3.5-397B-A17B | 1203.1 ± 2.6 |
| 46 | google/gemma-4-31B-it | 1203.1 ± 2.9 |
| 47 | zai-org/GLM-4.7 | 1202.7 ± 2.3 |
| 48 | mistral-medium-3.1 | 1202.4 ± 2.2 |
| 49 | zai-org/GLM-4.5 | 1202.0 ± 2.5 |
| 50 | qwen/qwen3-235b-a22b:thinking | 1202.0 ± 2.3 |
| 51 | optimus-alpha | 1201.9 ± 2.3 |
| 52 | mistral-small-creative | 1201.9 ± 1.7 |
| 53 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1201.8 ± 1.7 |
| 54 | claude-3-7-sonnet-20250219 | 1201.2 ± 2.8 |
| 55 | zai-org/GLM-4.7-Flash | 1200.9 ± 3.4 |
| 56 | chatgpt-4o-latest-2025-01-29 | 1199.9 ± 4.4 |
| 57 | quasar-alpha | 1199.8 ± 2.3 |
| 58 | gpt-4.1-mini | 1199.5 ± 3.6 |
| 59 | sam-paech/Darkest-muse-v1 | 1199.3 ± 1.7 |
| 60 | claude-3-5-sonnet-20241022 | 1199.2 ± 3.2 |
| 61 | deepseek-ai/DeepSeek-V3-0324 | 1199.1 ± 3.4 |
| 62 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.0 ± 3.8 |
| 63 | gpt-5-nano-2025-08-07 | 1197.6 ± 0.7 |
| 64 | qwen/qwq-32b | 1197.5 ± 5.3 |
| 65 | RekaAI/reka-flash-3 | 1197.5 ± 2.6 |
| 66 | google/gemma-3-27b-it | 1197.2 ± 1.2 |
| 67 | grok-3-beta | 1197.2 ± 1.5 |
| 68 | openai/gpt-oss-120b | 1196.9 ± 2.8 |
| 69 | ifable/gemma-2-Ifable-9B | 1196.7 ± 4.2 |
| 70 | gpt-4.5-preview | 1195.8 ± 2.7 |
| 71 | deepseek-ai/DeepSeek-V3.2-Speciale | 1195.5 ± 2.2 |
| 72 | gemini-2.0-flash-001 | 1194.9 ± 2.2 |
| 73 | google/gemma-3-4b-it | 1194.0 ± 3.0 |
| 74 | CohereForAI/c4ai-command-a-03-2025 | 1193.8 ± 2.2 |
| 75 | anthropic/claude-3.5-haiku-20241022 | 1193.5 ± 2.2 |
| 76 | THUDM/GLM-4-32B-0414 | 1193.3 ± 2.3 |
| 77 | gemini-2.5-flash-preview | 1192.9 ± 2.0 |
| 78 | allura-org/Gemma-3-Glitter-12B | 1192.8 ± 3.0 |
| 79 | google/gemma-3-12b-it | 1192.4 ± 3.3 |
| 80 | gpt-4.1-nano | 1189.7 ± 2.7 |
| 81 | gpt-4o-mini | 1189.1 ± 3.8 |
| 82 | openai/gpt-oss-20b | 1188.6 ± 3.2 |
| 83 | ToastyPigeon/Gemma-3-Starshine-12B | 1187.9 ± 3.4 |
| 84 | google/gemma-2-9b-it | 1187.7 ± 4.4 |
| 85 | anthropic/claude-3-haiku | 1184.8 ± 5.2 |
| 86 | mistralai/Pixtral-Large-Instruct-2411 | 1184.7 ± 5.9 |
| 87 | meta-llama/llama-3.1-70b-instruct | 1184.6 ± 2.3 |
| 88 | mistralai/mistral-large-2411 | 1184.3 ± 2.7 |
| 89 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1183.0 ± 5.3 |
| 90 | meta-llama/llama-3.1-405b-instruct | 1181.5 ± 4.9 |
| 91 | meta-llama/llama-3.1-8b-instruct | 1179.3 ± 2.5 |
| 92 | openai/gpt-4-0314 | 1179.2 ± 6.8 |
| 93 | mistralai/Mistral-Nemo-Instruct-2407 | 1178.8 ± 5.2 |
| 94 | liquid/lfm-7b | 1175.9 ± 5.1 |
| 95 | openrouter/cypher-alpha | 1175.8 ± 6.0 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1175.8 ± 4.6 |
| 97 | mistralai/Mistral-Small-24B-Instruct-2501 | 1172.7 ± 5.9 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1171.7 ± 7.2 |
| 99 | meta-llama/llama-3.2-3b-instruct | 1168.8 ± 4.8 |
| 100 | openai/gpt-3.5-turbo-0613 | 1167.6 ± 3.9 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1165.0 ± 3.6 |
