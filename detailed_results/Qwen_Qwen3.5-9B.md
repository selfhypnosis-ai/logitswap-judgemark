# Detailed Results: Qwen/Qwen3.5-9B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7299
* **Mean Absolute Cliff's Delta**: 0.6637
* **Combined Separability Score**: 69.68%
* **Positional Bias**: Position 1 (A): 68.4% | Position 2 (B): 31.6%
* **Length Bias**: Win Rate: 54.5% | Avg EV Margin: +3.3%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | o3 | 1216.6 |
| 2 | grok-4.20-beta | 1214.4 |
| 3 | moonshotai/Kimi-K2.5 | 1213.8 |
| 4 | claude-opus-4-7 | 1213.2 |
| 5 | moonshotai/Kimi-K2-Instruct | 1213.1 |
| 6 | moonshotai/Kimi-K2-Thinking | 1212.6 |
| 7 | moonshotai/Kimi-K2.6 | 1211.9 |
| 8 | openrouter/sherlock-dash-alpha | 1211.5 |
| 9 | gpt-5.5 | 1210.7 |
| 10 | google/gemma-4-31B-it | 1209.9 |
| 11 | grok-4.1-fast | 1209.9 |
| 12 | deepseek-ai/DeepSeek-V3.2 | 1209.4 |
| 13 | gpt-5.4 | 1209.4 |
| 14 | claude-opus-4-6 | 1208.8 |
| 15 | Qwen/Qwen3.5-397B-A17B | 1208.6 |
| 16 | deepseek-ai/DeepSeek-R1 | 1208.5 |
| 17 | gemini-3.1-pro-preview | 1207.7 |
| 18 | gemini-3-pro-preview | 1207.7 |
| 19 | zai-org/GLM-5.1 | 1207.7 |
| 20 | deepseek-ai/DeepSeek-V4-Flash | 1207.4 |
| 21 | qwen/qwen3-235b-a22b:thinking | 1207.3 |
| 22 | claude-opus-4 | 1207.3 |
| 23 | claude-opus-4-5-20251101 | 1207.2 |
| 24 | openrouter/pony-alpha | 1207.2 |
| 25 | chatgpt-4o-latest-2025-03-27 | 1206.9 |
| 26 | deepseek-ai/DeepSeek-V4-Pro | 1206.8 |
| 27 | mistral-medium-3.1 | 1206.4 |
| 28 | gpt-5.3-chat | 1206.3 |
| 29 | hunter-alpha | 1206.3 |
| 30 | claude-3-5-sonnet-20241022 | 1205.8 |
| 31 | gemini-2.5-pro-preview-06-05 | 1205.8 |
| 32 | claude-sonnet-4.5 | 1205.5 |
| 33 | deepseek-ai/DeepSeek-V3-0324 | 1205.4 |
| 34 | gpt-5-2025-08-07 | 1205.3 |
| 35 | claude-sonnet-4-6 | 1205.3 |
| 36 | openrouter/horizon-beta | 1205.3 |
| 37 | zai-org/GLM-4.7 | 1205.3 |
| 38 | NousResearch/Hermes-4-405B | 1205.3 |
| 39 | gpt-5.4-mini | 1205.2 |
| 40 | deepseek-ai/DeepSeek-V3.1 | 1205.1 |
| 41 | RekaAI/reka-flash-3 | 1205.0 |
| 42 | zai-org/GLM-4.6 | 1204.9 |
| 43 | openrouter/horizon-alpha | 1204.6 |
| 44 | gpt-5.2 | 1204.5 |
| 45 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.3 |
| 46 | zai-org/GLM-5 | 1204.1 |
| 47 | google/gemma-4-26B-A4B-it | 1203.6 |
| 48 | mistral-small-creative | 1203.5 |
| 49 | gpt-5-mini-2025-08-07 | 1203.5 |
| 50 | optimus-alpha | 1202.9 |
| 51 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1202.6 |
| 52 | claude-sonnet-4 | 1202.4 |
| 53 | deepseek-ai/DeepSeek-R1-0528 | 1202.4 |
| 54 | zai-org/GLM-4.5 | 1201.9 |
| 55 | quasar-alpha | 1201.8 |
| 56 | chatgpt-4o-latest-2025-01-29 | 1201.6 |
| 57 | qwen/qwq-32b | 1201.4 |
| 58 | minimax/minimax-m2.5 | 1201.2 |
| 59 | gemini-2.5-pro-exp-03-25 | 1200.8 |
| 60 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1200.6 |
| 61 | deepseek-ai/DeepSeek-V3.2-Speciale | 1199.7 |
| 62 | claude-3-7-sonnet-20250219 | 1199.5 |
| 63 | gpt-4.1-mini | 1198.6 |
| 64 | grok-3-beta | 1198.5 |
| 65 | gpt-4.5-preview | 1198.1 |
| 66 | zai-org/GLM-4.7-Flash | 1197.9 |
| 67 | google/gemma-3-27b-it | 1197.4 |
| 68 | anthropic/claude-3.5-haiku-20241022 | 1197.4 |
| 69 | ifable/gemma-2-Ifable-9B | 1196.8 |
| 70 | CohereForAI/c4ai-command-a-03-2025 | 1195.9 |
| 71 | gemini-2.5-flash-preview | 1195.4 |
| 72 | google/gemma-3-4b-it | 1195.0 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1194.7 |
| 74 | sam-paech/Darkest-muse-v1 | 1193.7 |
| 75 | gemini-2.0-flash-001 | 1193.7 |
| 76 | google/gemma-3-12b-it | 1193.6 |
| 77 | openai/gpt-oss-120b | 1193.5 |
| 78 | gpt-5-nano-2025-08-07 | 1193.0 |
| 79 | meta-llama/llama-3.1-405b-instruct | 1192.6 |
| 80 | THUDM/GLM-4-32B-0414 | 1191.2 |
| 81 | google/gemma-2-9b-it | 1191.0 |
| 82 | mistralai/mistral-large-2411 | 1190.8 |
| 83 | gpt-4.1-nano | 1190.4 |
| 84 | openai/gpt-4-0314 | 1188.3 |
| 85 | anthropic/claude-3-haiku | 1188.3 |
| 86 | gpt-4o-mini | 1188.2 |
| 87 | liquid/lfm-7b | 1188.1 |
| 88 | mistralai/Pixtral-Large-Instruct-2411 | 1187.8 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1187.8 |
| 90 | meta-llama/llama-3.1-70b-instruct | 1187.7 |
| 91 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1186.4 |
| 92 | meta-llama/llama-3.1-8b-instruct | 1186.3 |
| 93 | ToastyPigeon/Gemma-3-Starshine-12B | 1185.6 |
| 94 | openrouter/cypher-alpha | 1183.1 |
| 95 | openai/gpt-oss-20b | 1182.6 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1181.8 |
| 97 | openai/gpt-3.5-turbo-0613 | 1180.8 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1180.4 |
| 99 | meta-llama/llama-3.2-3b-instruct | 1179.8 |
| 100 | mistralai/Mistral-Small-24B-Instruct-2501 | 1179.6 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1177.5 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9308
* **Mean Absolute Cliff's Delta**: 0.8235
* **Combined Separability Score**: 87.72%
* **Positional Bias**: Position 1 (A): 69.3% | Position 2 (B): 30.7%
* **Length Bias**: Win Rate: 53.1% | Avg EV Margin: +2.3%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | o3 | 1234.8 ± 5.1 |
| 2 | grok-4.20-beta | 1234.0 ± 6.3 |
| 3 | moonshotai/Kimi-K2-Instruct | 1233.2 ± 7.7 |
| 4 | moonshotai/Kimi-K2.5 | 1228.8 ± 4.8 |
| 5 | claude-opus-4-7 | 1227.6 ± 4.7 |
| 6 | moonshotai/Kimi-K2-Thinking | 1226.2 ± 8.9 |
| 7 | gpt-5.4 | 1225.0 ± 6.3 |
| 8 | moonshotai/Kimi-K2.6 | 1224.0 ± 7.5 |
| 9 | gpt-5.5 | 1219.6 ± 4.3 |
| 10 | claude-opus-4-6 | 1219.1 ± 4.7 |
| 11 | deepseek-ai/DeepSeek-V3.2 | 1217.6 ± 5.4 |
| 12 | gemini-3-pro-preview | 1215.5 ± 3.1 |
| 13 | zai-org/GLM-5.1 | 1215.4 ± 3.2 |
| 14 | gemini-3.1-pro-preview | 1215.0 ± 4.2 |
| 15 | grok-4.1-fast | 1213.9 ± 5.2 |
| 16 | deepseek-ai/DeepSeek-R1 | 1213.8 ± 3.0 |
| 17 | claude-opus-4-5-20251101 | 1213.8 ± 5.7 |
| 18 | hunter-alpha | 1213.5 ± 4.7 |
| 19 | deepseek-ai/DeepSeek-V4-Pro | 1213.2 ± 3.2 |
| 20 | deepseek-ai/DeepSeek-V4-Flash | 1213.1 ± 4.8 |
| 21 | openrouter/sherlock-dash-alpha | 1212.8 ± 4.3 |
| 22 | gpt-5.2 | 1212.6 ± 3.6 |
| 23 | claude-opus-4 | 1212.5 ± 3.8 |
| 24 | deepseek-ai/DeepSeek-V3.1 | 1212.2 ± 3.9 |
| 25 | claude-sonnet-4-6 | 1211.6 ± 2.8 |
| 26 | gpt-5-2025-08-07 | 1211.6 ± 4.8 |
| 27 | Qwen/Qwen3.5-397B-A17B | 1211.5 ± 4.3 |
| 28 | gpt-5.4-mini | 1211.0 ± 2.2 |
| 29 | google/gemma-4-31B-it | 1210.8 ± 2.9 |
| 30 | openrouter/horizon-beta | 1210.7 ± 4.4 |
| 31 | chatgpt-4o-latest-2025-03-27 | 1210.5 ± 3.7 |
| 32 | openrouter/horizon-alpha | 1210.1 ± 3.0 |
| 33 | gpt-5.3-chat | 1210.1 ± 4.3 |
| 34 | openrouter/pony-alpha | 1210.0 ± 4.3 |
| 35 | qwen/qwen3-235b-a22b:thinking | 1209.7 ± 3.3 |
| 36 | gemini-2.5-pro-preview-06-05 | 1209.5 ± 3.3 |
| 37 | mistral-medium-3.1 | 1209.3 ± 3.9 |
| 38 | deepseek-ai/DeepSeek-R1-0528 | 1209.2 ± 4.6 |
| 39 | zai-org/GLM-4.7 | 1209.1 ± 4.5 |
| 40 | zai-org/GLM-4.6 | 1209.1 ± 4.1 |
| 41 | claude-sonnet-4.5 | 1209.0 ± 3.5 |
| 42 | zai-org/GLM-4.5 | 1208.8 ± 2.8 |
| 43 | zai-org/GLM-5 | 1208.4 ± 3.9 |
| 44 | google/gemma-4-26B-A4B-it | 1208.1 ± 3.5 |
| 45 | NousResearch/Hermes-4-405B | 1207.5 ± 2.9 |
| 46 | quasar-alpha | 1206.9 ± 5.2 |
| 47 | gpt-5-mini-2025-08-07 | 1206.5 ± 4.5 |
| 48 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1206.5 ± 1.9 |
| 49 | RekaAI/reka-flash-3 | 1205.6 ± 4.0 |
| 50 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1205.4 ± 3.0 |
| 51 | claude-3-5-sonnet-20241022 | 1205.2 ± 4.7 |
| 52 | deepseek-ai/DeepSeek-V3-0324 | 1205.0 ± 2.2 |
| 53 | qwen/qwq-32b | 1203.4 ± 4.7 |
| 54 | claude-3-7-sonnet-20250219 | 1203.4 ± 3.6 |
| 55 | optimus-alpha | 1203.2 ± 4.2 |
| 56 | claude-sonnet-4 | 1203.2 ± 4.2 |
| 57 | mistral-small-creative | 1203.1 ± 3.5 |
| 58 | gemini-2.5-pro-exp-03-25 | 1202.4 ± 3.0 |
| 59 | minimax/minimax-m2.5 | 1201.0 ± 3.5 |
| 60 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.9 ± 5.1 |
| 61 | zai-org/GLM-4.7-Flash | 1200.8 ± 3.9 |
| 62 | grok-3-beta | 1200.8 ± 3.5 |
| 63 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.7 ± 2.5 |
| 64 | CohereForAI/c4ai-command-a-03-2025 | 1199.3 ± 4.0 |
| 65 | chatgpt-4o-latest-2025-01-29 | 1199.3 ± 2.0 |
| 66 | google/gemma-3-27b-it | 1199.0 ± 6.1 |
| 67 | gpt-4.5-preview | 1198.5 ± 3.7 |
| 68 | gemini-2.5-flash-preview | 1196.5 ± 4.6 |
| 69 | google/gemma-3-12b-it | 1196.3 ± 2.6 |
| 70 | gpt-4.1-mini | 1196.3 ± 2.4 |
| 71 | gemini-2.0-flash-001 | 1196.2 ± 4.3 |
| 72 | gpt-5-nano-2025-08-07 | 1196.0 ± 1.9 |
| 73 | anthropic/claude-3.5-haiku-20241022 | 1195.5 ± 3.3 |
| 74 | ifable/gemma-2-Ifable-9B | 1195.3 ± 4.6 |
| 75 | sam-paech/Darkest-muse-v1 | 1194.4 ± 3.9 |
| 76 | allura-org/Gemma-3-Glitter-12B | 1193.8 ± 3.9 |
| 77 | google/gemma-3-4b-it | 1192.9 ± 6.8 |
| 78 | openai/gpt-oss-120b | 1192.4 ± 5.4 |
| 79 | THUDM/GLM-4-32B-0414 | 1189.4 ± 3.2 |
| 80 | google/gemma-2-9b-it | 1183.5 ± 5.9 |
| 81 | gpt-4o-mini | 1182.6 ± 5.8 |
| 82 | gpt-4.1-nano | 1182.1 ± 4.2 |
| 83 | meta-llama/llama-3.1-405b-instruct | 1180.8 ± 6.9 |
| 84 | mistralai/mistral-large-2411 | 1179.5 ± 5.8 |
| 85 | liquid/lfm-7b | 1178.7 ± 5.2 |
| 86 | mistralai/Pixtral-Large-Instruct-2411 | 1178.6 ± 7.0 |
| 87 | anthropic/claude-3-haiku | 1178.4 ± 5.4 |
| 88 | ToastyPigeon/Gemma-3-Starshine-12B | 1177.9 ± 6.0 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1176.3 ± 6.0 |
| 90 | meta-llama/llama-3.1-70b-instruct | 1173.1 ± 4.3 |
| 91 | openai/gpt-oss-20b | 1172.6 ± 4.2 |
| 92 | openai/gpt-4-0314 | 1172.1 ± 4.6 |
| 93 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1171.0 ± 6.2 |
| 94 | meta-llama/llama-3.1-8b-instruct | 1168.2 ± 6.2 |
| 95 | openrouter/cypher-alpha | 1166.1 ± 7.3 |
| 96 | mistralai/Mistral-Small-24B-Instruct-2501 | 1170.7 ± 5.0 |
| 97 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1159.1 ± 7.6 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1157.1 ± 2.3 |
| 99 | openai/gpt-3.5-turbo-0613 | 1154.0 ± 6.6 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1143.9 ± 11.6 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1135.4 ± 8.8 |
