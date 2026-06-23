# Detailed Results: RedHatAI/Qwen3.5-9B-FP8-dynamic

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7514
* **Mean Absolute Cliff's Delta**: 0.6808
* **Combined Separability Score**: 71.61%
* **Positional Bias**: Position 1 (A): 64.4% | Position 2 (B): 35.6%
* **Length Bias**: Win Rate: 54.7% | Avg EV Margin: +6.5%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1237.0 |
| 2 | moonshotai/Kimi-K2.5 | 1229.7 |
| 3 | claude-opus-4-6 | 1227.6 |
| 4 | gpt-5.4 | 1224.8 |
| 5 | moonshotai/Kimi-K2.6 | 1224.6 |
| 6 | moonshotai/Kimi-K2-Instruct | 1224.5 |
| 7 | o3 | 1224.0 |
| 8 | gpt-5.5 | 1223.9 |
| 9 | moonshotai/Kimi-K2-Thinking | 1220.5 |
| 10 | grok-4.20-beta | 1219.9 |
| 11 | deepseek-ai/DeepSeek-R1 | 1219.7 |
| 12 | claude-opus-4-5-20251101 | 1218.8 |
| 13 | deepseek-ai/DeepSeek-V3.2 | 1218.6 |
| 14 | claude-sonnet-4-6 | 1218.5 |
| 15 | zai-org/GLM-5.1 | 1217.9 |
| 16 | deepseek-ai/DeepSeek-V4-Pro | 1217.8 |
| 17 | grok-4.1-fast | 1217.7 |
| 18 | claude-opus-4 | 1216.5 |
| 19 | openrouter/pony-alpha | 1216.3 |
| 20 | openrouter/sherlock-dash-alpha | 1216.0 |
| 21 | claude-sonnet-4.5 | 1215.1 |
| 22 | openrouter/horizon-beta | 1215.1 |
| 23 | Qwen/Qwen3.5-397B-A17B | 1214.5 |
| 24 | mistral-medium-3.1 | 1214.5 |
| 25 | qwen/qwen3-235b-a22b:thinking | 1214.4 |
| 26 | gemini-3-pro-preview | 1214.3 |
| 27 | gemini-3.1-pro-preview | 1214.2 |
| 28 | deepseek-ai/DeepSeek-V4-Flash | 1214.0 |
| 29 | gpt-5.3-chat | 1213.9 |
| 30 | gpt-5-2025-08-07 | 1213.5 |
| 31 | gemini-2.5-pro-preview-06-05 | 1213.3 |
| 32 | google/gemma-4-31B-it | 1212.5 |
| 33 | gpt-5.4-mini | 1212.0 |
| 34 | deepseek-ai/DeepSeek-V3.1 | 1211.4 |
| 35 | zai-org/GLM-5 | 1211.1 |
| 36 | gpt-5.2 | 1210.8 |
| 37 | zai-org/GLM-4.6 | 1210.7 |
| 38 | chatgpt-4o-latest-2025-03-27 | 1210.5 |
| 39 | deepseek-ai/DeepSeek-V3-0324 | 1210.3 |
| 40 | hunter-alpha | 1209.5 |
| 41 | openrouter/horizon-alpha | 1209.3 |
| 42 | zai-org/GLM-4.7 | 1208.9 |
| 43 | claude-3-5-sonnet-20241022 | 1208.4 |
| 44 | deepseek-ai/DeepSeek-R1-0528 | 1208.1 |
| 45 | RekaAI/reka-flash-3 | 1208.1 |
| 46 | gpt-5-mini-2025-08-07 | 1208.0 |
| 47 | optimus-alpha | 1206.7 |
| 48 | google/gemma-4-26B-A4B-it | 1206.6 |
| 49 | NousResearch/Hermes-4-405B | 1206.5 |
| 50 | mistral-small-creative | 1206.3 |
| 51 | claude-sonnet-4 | 1206.0 |
| 52 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1205.9 |
| 53 | zai-org/GLM-4.5 | 1204.4 |
| 54 | quasar-alpha | 1203.9 |
| 55 | claude-3-7-sonnet-20250219 | 1203.4 |
| 56 | gemini-2.5-pro-exp-03-25 | 1202.9 |
| 57 | qwen/qwq-32b | 1202.8 |
| 58 | minimax/minimax-m2.5 | 1201.8 |
| 59 | chatgpt-4o-latest-2025-01-29 | 1201.6 |
| 60 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1201.4 |
| 61 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.6 |
| 62 | ifable/gemma-2-Ifable-9B | 1199.0 |
| 63 | anthropic/claude-3.5-haiku-20241022 | 1198.0 |
| 64 | deepseek-ai/DeepSeek-V3.2-Speciale | 1197.6 |
| 65 | gpt-4.1-mini | 1197.3 |
| 66 | grok-3-beta | 1195.7 |
| 67 | google/gemma-3-27b-it | 1194.5 |
| 68 | zai-org/GLM-4.7-Flash | 1193.7 |
| 69 | gemini-2.5-flash-preview | 1190.4 |
| 70 | gpt-4.5-preview | 1190.3 |
| 71 | gemini-2.0-flash-001 | 1190.2 |
| 72 | CohereForAI/c4ai-command-a-03-2025 | 1190.0 |
| 73 | google/gemma-3-12b-it | 1188.7 |
| 74 | google/gemma-3-4b-it | 1186.7 |
| 75 | sam-paech/Darkest-muse-v1 | 1186.5 |
| 76 | gpt-5-nano-2025-08-07 | 1185.8 |
| 77 | meta-llama/llama-3.1-405b-instruct | 1183.3 |
| 78 | openai/gpt-oss-120b | 1183.0 |
| 79 | allura-org/Gemma-3-Glitter-12B | 1182.4 |
| 80 | google/gemma-2-9b-it | 1181.7 |
| 81 | gpt-4.1-nano | 1179.7 |
| 82 | mistralai/mistral-large-2411 | 1178.9 |
| 83 | THUDM/GLM-4-32B-0414 | 1178.7 |
| 84 | meta-llama/llama-3.1-70b-instruct | 1177.8 |
| 85 | liquid/lfm-7b | 1177.8 |
| 86 | gpt-4o-mini | 1177.5 |
| 87 | anthropic/claude-3-haiku | 1177.3 |
| 88 | openai/gpt-4-0314 | 1175.3 |
| 89 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1174.6 |
| 90 | meta-llama/llama-3.1-8b-instruct | 1173.9 |
| 91 | mistralai/Pixtral-Large-Instruct-2411 | 1173.9 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1172.1 |
| 93 | openai/gpt-oss-20b | 1167.9 |
| 94 | openrouter/cypher-alpha | 1167.6 |
| 95 | ToastyPigeon/Gemma-3-Starshine-12B | 1166.3 |
| 96 | mistralai/Mistral-Small-24B-Instruct-2501 | 1166.1 |
| 97 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1165.5 |
| 98 | meta-llama/llama-3.2-3b-instruct | 1165.2 |
| 99 | openai/gpt-3.5-turbo-0613 | 1164.3 |
| 100 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1156.7 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1148.1 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9285
* **Mean Absolute Cliff's Delta**: 0.8412
* **Combined Score**: 88.49%
* **Positional Bias**: Position 1 (A): 74.0% | Position 2 (B): 26.0%
* **Length Bias**: Win Rate: 53.1% | Avg EV Margin: +1.6%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | o3 | 1232.9 ± 6.2 |
| 2 | grok-4.20-beta | 1232.4 ± 5.3 |
| 3 | moonshotai/Kimi-K2.5 | 1232.3 ± 5.4 |
| 4 | moonshotai/Kimi-K2-Instruct | 1225.6 ± 2.8 |
| 5 | claude-opus-4-7 | 1225.2 ± 6.5 |
| 6 | gpt-5.4 | 1225.1 ± 3.3 |
| 7 | moonshotai/Kimi-K2-Thinking | 1222.2 ± 5.3 |
| 8 | moonshotai/Kimi-K2.6 | 1220.5 ± 4.4 |
| 9 | claude-opus-4-6 | 1219.6 ± 4.7 |
| 10 | gpt-5.5 | 1219.6 ± 5.5 |
| 11 | zai-org/GLM-5.1 | 1217.9 ± 6.2 |
| 12 | deepseek-ai/DeepSeek-V3.2 | 1215.4 ± 3.1 |
| 13 | gemini-3-pro-preview | 1214.9 ± 1.7 |
| 14 | grok-4.1-fast | 1214.2 ± 5.3 |
| 15 | openrouter/sherlock-dash-alpha | 1214.0 ± 3.5 |
| 16 | openrouter/horizon-beta | 1212.8 ± 1.4 |
| 17 | deepseek-ai/DeepSeek-V4-Flash | 1212.8 ± 4.0 |
| 18 | google/gemma-4-31B-it | 1212.1 ± 3.4 |
| 19 | gpt-5.4-mini | 1212.1 ± 1.9 |
| 20 | deepseek-ai/DeepSeek-R1 | 1212.1 ± 1.8 |
| 21 | gemini-2.5-pro-preview-06-05 | 1212.0 ± 1.2 |
| 22 | gemini-3.1-pro-preview | 1211.9 ± 2.5 |
| 23 | deepseek-ai/DeepSeek-V4-Pro | 1211.8 ± 3.1 |
| 24 | claude-opus-4-5-20251101 | 1211.5 ± 3.4 |
| 25 | claude-sonnet-4-6 | 1211.0 ± 4.0 |
| 26 | deepseek-ai/DeepSeek-V3.1 | 1211.0 ± 5.1 |
| 27 | deepseek-ai/DeepSeek-R1-0528 | 1210.4 ± 2.0 |
| 28 | claude-opus-4 | 1210.4 ± 2.7 |
| 29 | gpt-5-2025-08-07 | 1210.2 ± 3.3 |
| 30 | gpt-5.2 | 1210.2 ± 3.5 |
| 31 | gpt-5.3-chat | 1209.9 ± 4.8 |
| 32 | openrouter/pony-alpha | 1209.4 ± 2.8 |
| 33 | zai-org/GLM-4.7 | 1209.3 ± 3.0 |
| 34 | openrouter/horizon-alpha | 1209.2 ± 3.4 |
| 35 | hunter-alpha | 1209.1 ± 2.1 |
| 36 | Qwen/Qwen3.5-397B-A17B | 1209.0 ± 3.7 |
| 37 | mistral-medium-3.1 | 1208.7 ± 2.4 |
| 38 | qwen/qwen3-235b-a22b:thinking | 1208.7 ± 3.8 |
| 39 | claude-sonnet-4.5 | 1208.5 ± 4.7 |
| 40 | zai-org/GLM-5 | 1208.4 ± 3.5 |
| 41 | zai-org/GLM-4.6 | 1208.0 ± 4.0 |
| 42 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1207.7 ± 1.0 |
| 43 | claude-3-5-sonnet-20241022 | 1207.3 ± 3.3 |
| 44 | quasar-alpha | 1206.7 ± 3.9 |
| 45 | google/gemma-4-26B-A4B-it | 1206.6 ± 2.9 |
| 46 | chatgpt-4o-latest-2025-03-27 | 1206.6 ± 2.0 |
| 47 | gpt-5-mini-2025-08-07 | 1206.5 ± 4.1 |
| 48 | NousResearch/Hermes-4-405B | 1206.0 ± 2.9 |
| 49 | optimus-alpha | 1205.5 ± 5.7 |
| 50 | RekaAI/reka-flash-3 | 1204.5 ± 2.9 |
| 51 | zai-org/GLM-4.5 | 1204.4 ± 1.3 |
| 52 | deepseek-ai/DeepSeek-V3-0324 | 1203.7 ± 4.6 |
| 53 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1203.4 ± 2.9 |
| 54 | claude-3-7-sonnet-20250219 | 1203.2 ± 1.4 |
| 55 | gemini-2.5-pro-exp-03-25 | 1202.9 ± 2.6 |
| 56 | qwen/qwq-32b | 1202.5 ± 2.3 |
| 57 | mistral-small-creative | 1202.1 ± 2.6 |
| 58 | deepseek-ai/DeepSeek-V3.2-Speciale | 1201.3 ± 2.5 |
| 59 | minimax/minimax-m2.5 | 1201.2 ± 1.5 |
| 60 | claude-sonnet-4 | 1201.1 ± 1.9 |
| 61 | ifable/gemma-2-Ifable-9B | 1201.0 ± 2.8 |
| 62 | grok-3-beta | 1199.8 ± 2.1 |
| 63 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.4 ± 4.6 |
| 64 | gpt-4.5-preview | 1198.9 ± 5.6 |
| 65 | zai-org/GLM-4.7-Flash | 1198.7 ± 4.7 |
| 66 | chatgpt-4o-latest-2025-01-29 | 1198.7 ± 3.4 |
| 67 | google/gemma-3-12b-it | 1197.7 ± 3.4 |
| 68 | openai/gpt-oss-120b | 1197.5 ± 4.1 |
| 69 | gpt-4.1-mini | 1197.4 ± 2.0 |
| 70 | sam-paech/Darkest-muse-v1 | 1196.8 ± 2.6 |
| 71 | gpt-5-nano-2025-08-07 | 1196.7 ± 3.7 |
| 72 | google/gemma-3-27b-it | 1196.6 ± 2.2 |
| 73 | google/gemma-3-4b-it | 1196.2 ± 5.2 |
| 74 | anthropic/claude-3.5-haiku-20241022 | 1195.8 ± 3.0 |
| 75 | allura-org/Gemma-3-Glitter-12B | 1195.4 ± 2.8 |
| 76 | CohereForAI/c4ai-command-a-03-2025 | 1194.4 ± 1.8 |
| 77 | gemini-2.5-flash-preview | 1193.7 ± 4.4 |
| 78 | gemini-2.0-flash-001 | 1191.5 ± 1.6 |
| 79 | THUDM/GLM-4-32B-0414 | 1189.6 ± 5.3 |
| 80 | google/gemma-2-9b-it | 1187.1 ± 3.8 |
| 81 | gpt-4.1-nano | 1186.1 ± 2.0 |
| 82 | ToastyPigeon/Gemma-3-Starshine-12B | 1185.9 ± 7.3 |
| 83 | meta-llama/llama-3.1-70b-instruct | 1183.7 ± 4.0 |
| 84 | mistralai/mistral-large-2411 | 1183.6 ± 3.4 |
| 85 | meta-llama/llama-3.1-405b-instruct | 1183.6 ± 5.0 |
| 86 | mistralai/Pixtral-Large-Instruct-2411 | 1181.7 ± 3.3 |
| 87 | gpt-4o-mini | 1181.0 ± 2.0 |
| 88 | openai/gpt-oss-20b | 1179.3 ± 9.9 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1179.3 ± 2.7 |
| 90 | liquid/lfm-7b | 1179.0 ± 4.1 |
| 91 | anthropic/claude-3-haiku | 1178.3 ± 5.4 |
| 92 | openai/gpt-4-0314 | 1177.2 ± 4.5 |
| 93 | meta-llama/llama-3.1-8b-instruct | 1172.2 ± 8.4 |
| 94 | openrouter/cypher-alpha | 1171.0 ± 5.3 |
| 95 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1170.2 ± 4.9 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1157.4 ± 10.3 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1157.2 ± 10.1 |
| 98 | openai/gpt-3.5-turbo-0613 | 1152.7 ± 5.2 |
| 99 | meta-llama/llama-3.2-3b-instruct | 1148.4 ± 10.4 |
| 100 | mistralai/Mistral-Small-24B-Instruct-2501 | 1147.6 ± 12.2 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1135.8 ± 8.9 |
