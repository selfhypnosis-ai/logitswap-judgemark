# Detailed Results: Qwen/Qwen3.5-27B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7861
* **Mean Absolute Cliff's Delta**: 0.7166
* **Combined Separability Score**: 75.14%
* **Positional Bias**: Position 1 (A): 70.2% | Position 2 (B): 29.8%
* **Length Bias**: Win Rate: 53.9% | Avg EV Margin: +5.1%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1229.6 |
| 2 | claude-opus-4-6 | 1225.4 |
| 3 | moonshotai/Kimi-K2.5 | 1224.2 |
| 4 | moonshotai/Kimi-K2-Thinking | 1220.3 |
| 5 | o3 | 1219.9 |
| 6 | gpt-5.5 | 1219.2 |
| 7 | moonshotai/Kimi-K2-Instruct | 1218.8 |
| 8 | moonshotai/Kimi-K2.6 | 1218.4 |
| 9 | claude-sonnet-4-6 | 1217.9 |
| 10 | gpt-5.4 | 1217.6 |
| 11 | openrouter/pony-alpha | 1217.4 |
| 12 | Qwen/Qwen3.5-397B-A17B | 1217.4 |
| 13 | gemini-3.1-pro-preview | 1216.9 |
| 14 | gemini-3-pro-preview | 1216.7 |
| 15 | deepseek-ai/DeepSeek-V3.2 | 1216.6 |
| 16 | claude-opus-4-5-20251101 | 1216.6 |
| 17 | zai-org/GLM-5.1 | 1215.6 |
| 18 | grok-4.20-beta | 1215.2 |
| 19 | deepseek-ai/DeepSeek-R1 | 1214.6 |
| 20 | claude-sonnet-4.5 | 1214.5 |
| 21 | claude-opus-4 | 1214.3 |
| 22 | google/gemma-4-31B-it | 1214.0 |
| 23 | zai-org/GLM-5 | 1213.5 |
| 24 | deepseek-ai/DeepSeek-V4-Pro | 1212.9 |
| 25 | gemini-2.5-pro-preview-06-05 | 1212.8 |
| 26 | deepseek-ai/DeepSeek-V4-Flash | 1212.7 |
| 27 | deepseek-ai/DeepSeek-V3.1 | 1212.2 |
| 28 | openrouter/horizon-beta | 1212.2 |
| 29 | grok-4.1-fast | 1212.2 |
| 30 | hunter-alpha | 1212.1 |
| 31 | deepseek-ai/DeepSeek-V3-0324 | 1211.7 |
| 32 | gpt-5-2025-08-07 | 1210.5 |
| 33 | gpt-5.4-mini | 1210.4 |
| 34 | openrouter/sherlock-dash-alpha | 1210.3 |
| 35 | zai-org/GLM-4.6 | 1209.3 |
| 36 | claude-3-5-sonnet-20241022 | 1209.1 |
| 37 | chatgpt-4o-latest-2025-03-27 | 1208.9 |
| 38 | google/gemma-4-26B-A4B-it | 1208.7 |
| 39 | zai-org/GLM-4.7 | 1208.6 |
| 40 | gpt-5.2 | 1208.5 |
| 41 | openrouter/horizon-alpha | 1208.4 |
| 42 | gpt-5.3-chat | 1208.1 |
| 43 | NousResearch/Hermes-4-405B | 1207.7 |
| 44 | mistral-medium-3.1 | 1207.3 |
| 45 | qwen/qwen3-235b-a22b:thinking | 1206.8 |
| 46 | deepseek-ai/DeepSeek-R1-0528 | 1206.0 |
| 47 | optimus-alpha | 1205.8 |
| 48 | claude-3-7-sonnet-20250219 | 1204.8 |
| 49 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.6 |
| 50 | claude-sonnet-4 | 1204.0 |
| 51 | gemini-2.5-pro-exp-03-25 | 1203.9 |
| 52 | zai-org/GLM-4.5 | 1203.9 |
| 53 | gpt-5-mini-2025-08-07 | 1203.5 |
| 54 | quasar-alpha | 1202.7 |
| 55 | chatgpt-4o-latest-2025-01-29 | 1201.7 |
| 56 | minimax/minimax-m2.5 | 1201.0 |
| 57 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.7 |
| 58 | mistral-small-creative | 1200.0 |
| 59 | grok-3-beta | 1199.3 |
| 60 | deepseek-ai/DeepSeek-V3.2-Speciale | 1198.3 |
| 61 | qwen/qwq-32b | 1197.5 |
| 62 | google/gemma-3-27b-it | 1197.1 |
| 63 | gpt-4.1-mini | 1196.8 |
| 64 | RekaAI/reka-flash-3 | 1196.3 |
| 65 | ifable/gemma-2-Ifable-9B | 1196.0 |
| 66 | gpt-4.5-preview | 1195.7 |
| 67 | zai-org/GLM-4.7-Flash | 1194.3 |
| 68 | CohereForAI/c4ai-command-a-03-2025 | 1193.8 |
| 69 | gemini-2.5-flash-preview | 1193.4 |
| 70 | anthropic/claude-3.5-haiku-20241022 | 1192.6 |
| 71 | gemini-2.0-flash-001 | 1192.1 |
| 72 | google/gemma-3-12b-it | 1189.4 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1189.3 |
| 74 | gpt-5-nano-2025-08-07 | 1188.6 |
| 75 | google/gemma-3-4b-it | 1187.8 |
| 76 | google/gemma-2-9b-it | 1187.7 |
| 77 | sam-paech/Darkest-muse-v1 | 1187.1 |
| 78 | mistralai/mistral-large-2411 | 1186.7 |
| 79 | meta-llama/llama-3.1-405b-instruct | 1186.5 |
| 80 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1185.3 |
| 81 | openai/gpt-oss-120b | 1185.1 |
| 82 | THUDM/GLM-4-32B-0414 | 1184.7 |
| 83 | gpt-4o-mini | 1183.5 |
| 84 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1182.3 |
| 85 | gpt-4.1-nano | 1181.6 |
| 86 | mistralai/Pixtral-Large-Instruct-2411 | 1181.5 |
| 87 | meta-llama/llama-3.1-70b-instruct | 1181.2 |
| 88 | anthropic/claude-3-haiku | 1178.9 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1178.2 |
| 90 | meta-llama/llama-3.1-8b-instruct | 1177.1 |
| 91 | openai/gpt-4-0314 | 1175.8 |
| 92 | liquid/lfm-7b | 1175.7 |
| 93 | ToastyPigeon/Gemma-3-Starshine-12B | 1175.7 |
| 94 | openai/gpt-oss-20b | 1173.5 |
| 95 | openrouter/cypher-alpha | 1172.6 |
| 96 | openai/gpt-3.5-turbo-0613 | 1172.5 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1171.9 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1170.6 |
| 99 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1169.3 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1167.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1150.4 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9473
* **Mean Absolute Cliff's Delta**: 0.8645
* **Combined Separability Score**: 90.59%
* **Positional Bias**: Position 1 (A): 61.2% | Position 2 (B): 38.8%
* **Length Bias**: Win Rate: 52.2% | Avg EV Margin: +2.9%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1282.6 ± 8.7 |
| 2 | claude-opus-4-6 | 1270.3 ± 8.7 |
| 3 | moonshotai/Kimi-K2.5 | 1253.2 ± 7.2 |
| 4 | gpt-5.5 | 1250.2 ± 11.8 |
| 5 | moonshotai/Kimi-K2.6 | 1247.6 ± 8.6 |
| 6 | gpt-5.4 | 1247.6 ± 5.5 |
| 7 | claude-sonnet-4-6 | 1247.0 ± 6.8 |
| 8 | o3 | 1237.9 ± 12.4 |
| 9 | moonshotai/Kimi-K2-Thinking | 1234.1 ± 10.6 |
| 10 | moonshotai/Kimi-K2-Instruct | 1233.6 ± 9.7 |
| 11 | gemini-3.1-pro-preview | 1231.5 ± 6.6 |
| 12 | claude-opus-4-5-20251101 | 1230.5 ± 6.9 |
| 13 | grok-4.20-beta | 1230.3 ± 15.0 |
| 14 | zai-org/GLM-5.1 | 1228.2 ± 5.5 |
| 15 | deepseek-ai/DeepSeek-V4-Pro | 1227.7 ± 5.9 |
| 16 | deepseek-ai/DeepSeek-V3.2 | 1226.1 ± 8.7 |
| 17 | openrouter/horizon-alpha | 1225.2 ± 4.4 |
| 18 | gpt-5-2025-08-07 | 1224.8 ± 3.4 |
| 19 | claude-opus-4 | 1223.6 ± 5.7 |
| 20 | openrouter/horizon-beta | 1223.5 ± 5.5 |
| 21 | openrouter/pony-alpha | 1222.7 ± 4.4 |
| 22 | gemini-3-pro-preview | 1222.6 ± 4.7 |
| 23 | deepseek-ai/DeepSeek-V4-Flash | 1222.6 ± 6.3 |
| 24 | deepseek-ai/DeepSeek-R1 | 1222.0 ± 5.4 |
| 25 | claude-sonnet-4.5 | 1221.4 ± 6.4 |
| 26 | gpt-5.2 | 1221.0 ± 6.2 |
| 27 | gpt-5.4-mini | 1220.6 ± 5.4 |
| 28 | Qwen/Qwen3.5-397B-A17B | 1220.4 ± 5.6 |
| 29 | deepseek-ai/DeepSeek-V3.1 | 1220.3 ± 5.7 |
| 30 | gemini-2.5-pro-preview-06-05 | 1219.6 ± 2.9 |
| 31 | hunter-alpha | 1219.4 ± 4.0 |
| 32 | zai-org/GLM-5 | 1219.4 ± 5.6 |
| 33 | zai-org/GLM-4.7 | 1217.7 ± 5.9 |
| 34 | grok-4.1-fast | 1217.2 ± 5.1 |
| 35 | openrouter/sherlock-dash-alpha | 1216.7 ± 6.3 |
| 36 | zai-org/GLM-4.6 | 1216.7 ± 4.3 |
| 37 | google/gemma-4-31B-it | 1216.5 ± 4.2 |
| 38 | gpt-5.3-chat | 1216.2 ± 7.1 |
| 39 | google/gemma-4-26B-A4B-it | 1214.4 ± 5.0 |
| 40 | deepseek-ai/DeepSeek-R1-0528 | 1213.5 ± 3.8 |
| 41 | NousResearch/Hermes-4-405B | 1213.4 ± 3.7 |
| 42 | qwen/qwen3-235b-a22b:thinking | 1213.4 ± 4.6 |
| 43 | gemini-2.5-pro-exp-03-25 | 1212.4 ± 5.5 |
| 44 | chatgpt-4o-latest-2025-03-27 | 1211.9 ± 3.6 |
| 45 | claude-3-7-sonnet-20250219 | 1210.5 ± 2.8 |
| 46 | gpt-5-mini-2025-08-07 | 1209.5 ± 5.4 |
| 47 | claude-sonnet-4 | 1208.9 ± 6.3 |
| 48 | claude-3-5-sonnet-20241022 | 1208.9 ± 5.9 |
| 49 | optimus-alpha | 1208.5 ± 4.3 |
| 50 | zai-org/GLM-4.5 | 1208.0 ± 5.2 |
| 51 | deepseek-ai/DeepSeek-V3-0324 | 1207.7 ± 4.3 |
| 52 | mistral-medium-3.1 | 1207.3 ± 4.8 |
| 53 | quasar-alpha | 1206.9 ± 6.4 |
| 54 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1205.6 ± 6.7 |
| 55 | minimax/minimax-m2.5 | 1204.9 ± 7.5 |
| 56 | grok-3-beta | 1204.7 ± 2.7 |
| 57 | mistral-small-creative | 1202.7 ± 3.4 |
| 58 | chatgpt-4o-latest-2025-01-29 | 1202.4 ± 4.2 |
| 59 | zai-org/GLM-4.7-Flash | 1201.2 ± 6.3 |
| 60 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.9 ± 6.3 |
| 61 | google/gemma-3-27b-it | 1199.5 ± 5.0 |
| 62 | deepseek-ai/DeepSeek-V3.2-Speciale | 1199.2 ± 3.9 |
| 63 | gpt-4.5-preview | 1197.3 ± 5.1 |
| 64 | gemini-2.5-flash-preview | 1195.9 ± 7.3 |
| 65 | gpt-5-nano-2025-08-07 | 1194.4 ± 5.2 |
| 66 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1193.6 ± 5.8 |
| 67 | CohereForAI/c4ai-command-a-03-2025 | 1193.2 ± 6.8 |
| 68 | qwen/qwq-32b | 1192.9 ± 5.2 |
| 69 | allura-org/Gemma-3-Glitter-12B | 1192.3 ± 5.2 |
| 70 | RekaAI/reka-flash-3 | 1192.3 ± 5.5 |
| 71 | openai/gpt-oss-120b | 1190.9 ± 8.0 |
| 72 | ifable/gemma-2-Ifable-9B | 1189.6 ± 3.9 |
| 73 | google/gemma-3-12b-it | 1188.9 ± 5.8 |
| 74 | gpt-4.1-mini | 1188.7 ± 4.2 |
| 75 | anthropic/claude-3.5-haiku-20241022 | 1188.7 ± 7.6 |
| 76 | sam-paech/Darkest-muse-v1 | 1188.3 ± 7.4 |
| 77 | gemini-2.0-flash-001 | 1185.2 ± 8.3 |
| 78 | google/gemma-3-4b-it | 1185.2 ± 5.8 |
| 79 | THUDM/GLM-4-32B-0414 | 1182.5 ± 4.7 |
| 80 | meta-llama/llama-3.1-405b-instruct | 1172.9 ± 8.7 |
| 81 | mistralai/mistral-large-2411 | 1172.0 ± 9.3 |
| 82 | mistralai/Pixtral-Large-Instruct-2411 | 1171.3 ± 8.5 |
| 83 | gpt-4.1-nano | 1171.2 ± 11.5 |
| 84 | google/gemma-2-9b-it | 1170.9 ± 5.9 |
| 85 | gpt-4o-mini | 1165.9 ± 8.5 |
| 86 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1161.7 ± 8.8 |
| 87 | meta-llama/llama-3.1-70b-instruct | 1161.7 ± 7.6 |
| 88 | ToastyPigeon/Gemma-3-Starshine-12B | 1159.9 ± 9.8 |
| 89 | openai/gpt-oss-20b | 1159.8 ± 9.0 |
| 90 | openai/gpt-4-0314 | 1159.7 ± 13.4 |
| 91 | mistralai/Mistral-Nemo-Instruct-2407 | 1158.7 ± 11.8 |
| 92 | anthropic/claude-3-haiku | 1151.3 ± 8.1 |
| 93 | openrouter/cypher-alpha | 1150.0 ± 12.2 |
| 94 | meta-llama/llama-3.1-8b-instruct | 1146.5 ± 14.5 |
| 95 | liquid/lfm-7b | 1145.9 ± 11.7 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1139.7 ± 15.3 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1135.8 ± 12.8 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1130.4 ± 15.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1049.6 ± 15.0 |
