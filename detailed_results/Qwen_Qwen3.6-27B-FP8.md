# Detailed Results: Qwen/Qwen3.6-27B-FP8

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7950
* **Mean Absolute Cliff's Delta**: 0.7468
* **Combined Separability Score**: 77.09%
* **Positional Bias**: Position 1 (A): 60.0% | Position 2 (B): 40.0%
* **Length Bias**: Win Rate: 54.6% | Avg EV Margin: +6.9%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1236.4 |
| 2 | moonshotai/Kimi-K2.5 | 1230.3 |
| 3 | claude-opus-4-6 | 1227.2 |
| 4 | gpt-5.5 | 1227.0 |
| 5 | o3 | 1225.5 |
| 6 | gpt-5.4 | 1225.3 |
| 7 | Qwen/Qwen3.5-397B-A17B | 1222.1 |
| 8 | moonshotai/Kimi-K2.6 | 1221.4 |
| 9 | moonshotai/Kimi-K2-Instruct | 1219.9 |
| 10 | moonshotai/Kimi-K2-Thinking | 1219.4 |
| 11 | claude-sonnet-4.5 | 1218.5 |
| 12 | claude-sonnet-4-6 | 1218.2 |
| 13 | zai-org/GLM-5.1 | 1218.1 |
| 14 | deepseek-ai/DeepSeek-V3.2 | 1218.0 |
| 15 | claude-opus-4 | 1217.3 |
| 16 | claude-opus-4-5-20251101 | 1216.1 |
| 17 | gpt-5-2025-08-07 | 1216.1 |
| 18 | deepseek-ai/DeepSeek-V4-Flash | 1216.0 |
| 19 | google/gemma-4-31B-it | 1215.8 |
| 20 | deepseek-ai/DeepSeek-V4-Pro | 1214.8 |
| 21 | openrouter/sherlock-dash-alpha | 1214.7 |
| 22 | claude-3-5-sonnet-20241022 | 1214.3 |
| 23 | gpt-5.3-chat | 1214.2 |
| 24 | gemini-3-pro-preview | 1214.1 |
| 25 | gemini-3.1-pro-preview | 1212.5 |
| 26 | hunter-alpha | 1212.1 |
| 27 | openrouter/pony-alpha | 1211.5 |
| 28 | openrouter/horizon-beta | 1211.5 |
| 29 | zai-org/GLM-4.6 | 1211.3 |
| 30 | deepseek-ai/DeepSeek-R1 | 1210.6 |
| 31 | openrouter/horizon-alpha | 1210.6 |
| 32 | grok-4.20-beta | 1210.5 |
| 33 | zai-org/GLM-5 | 1210.2 |
| 34 | gpt-5.4-mini | 1210.2 |
| 35 | gemini-2.5-pro-preview-06-05 | 1210.2 |
| 36 | grok-4.1-fast | 1210.0 |
| 37 | mistral-medium-3.1 | 1209.8 |
| 38 | deepseek-ai/DeepSeek-V3.1 | 1209.6 |
| 39 | qwen/qwen3-235b-a22b:thinking | 1208.7 |
| 40 | google/gemma-4-26B-A4B-it | 1208.4 |
| 41 | gpt-5.2 | 1207.8 |
| 42 | NousResearch/Hermes-4-405B | 1207.3 |
| 43 | optimus-alpha | 1206.5 |
| 44 | claude-sonnet-4 | 1206.0 |
| 45 | deepseek-ai/DeepSeek-R1-0528 | 1205.7 |
| 46 | deepseek-ai/DeepSeek-V3-0324 | 1205.6 |
| 47 | zai-org/GLM-4.7 | 1205.0 |
| 48 | claude-3-7-sonnet-20250219 | 1203.9 |
| 49 | chatgpt-4o-latest-2025-03-27 | 1203.0 |
| 50 | zai-org/GLM-4.5 | 1202.9 |
| 51 | quasar-alpha | 1202.7 |
| 52 | qwen/qwq-32b | 1202.4 |
| 53 | mistral-small-creative | 1201.3 |
| 54 | minimax/minimax-m2.5 | 1201.2 |
| 55 | gpt-5-mini-2025-08-07 | 1201.2 |
| 56 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.8 |
| 57 | gemini-2.5-pro-exp-03-25 | 1200.3 |
| 58 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1199.8 |
| 59 | chatgpt-4o-latest-2025-01-29 | 1199.5 |
| 60 | grok-3-beta | 1199.4 |
| 61 | deepseek-ai/DeepSeek-V3.2-Speciale | 1199.1 |
| 62 | google/gemma-3-27b-it | 1199.1 |
| 63 | RekaAI/reka-flash-3 | 1198.4 |
| 64 | gpt-4.5-preview | 1198.4 |
| 65 | anthropic/claude-3.5-haiku-20241022 | 1195.8 |
| 66 | gpt-4.1-mini | 1195.1 |
| 67 | ifable/gemma-2-Ifable-9B | 1194.5 |
| 68 | zai-org/GLM-4.7-Flash | 1193.6 |
| 69 | sam-paech/Darkest-muse-v1 | 1192.1 |
| 70 | google/gemma-3-12b-it | 1192.1 |
| 71 | gemini-2.5-flash-preview | 1191.2 |
| 72 | gemini-2.0-flash-001 | 1190.5 |
| 73 | gpt-5-nano-2025-08-07 | 1187.5 |
| 74 | meta-llama/llama-3.1-405b-instruct | 1187.0 |
| 75 | CohereForAI/c4ai-command-a-03-2025 | 1186.2 |
| 76 | meta-llama/llama-3.1-70b-instruct | 1185.4 |
| 77 | google/gemma-2-9b-it | 1185.3 |
| 78 | gpt-4.1-nano | 1185.3 |
| 79 | allura-org/Gemma-3-Glitter-12B | 1185.2 |
| 80 | google/gemma-3-4b-it | 1184.5 |
| 81 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1183.9 |
| 82 | mistralai/mistral-large-2411 | 1182.8 |
| 83 | openai/gpt-oss-120b | 1182.6 |
| 84 | gpt-4o-mini | 1181.5 |
| 85 | openai/gpt-4-0314 | 1181.3 |
| 86 | THUDM/GLM-4-32B-0414 | 1180.5 |
| 87 | liquid/lfm-7b | 1179.9 |
| 88 | meta-llama/llama-3.1-8b-instruct | 1178.8 |
| 89 | mistralai/Pixtral-Large-Instruct-2411 | 1178.4 |
| 90 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1177.5 |
| 91 | anthropic/claude-3-haiku | 1176.4 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1174.3 |
| 93 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1174.0 |
| 94 | meta-llama/llama-3.2-3b-instruct | 1173.8 |
| 95 | openrouter/cypher-alpha | 1171.7 |
| 96 | ToastyPigeon/Gemma-3-Starshine-12B | 1167.6 |
| 97 | openai/gpt-oss-20b | 1167.6 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1167.2 |
| 99 | mistralai/Mistral-Small-24B-Instruct-2501 | 1165.5 |
| 100 | openai/gpt-3.5-turbo-0613 | 1165.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1152.3 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9447
* **Mean Absolute Cliff's Delta**: 0.8598
* **Combined Separability Score**: 90.22%
* **Positional Bias**: Position 1 (A): 62.5% | Position 2 (B): 37.5%
* **Length Bias**: Win Rate: 51.9% | Avg EV Margin: +2.6%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1284.4 ± 4.5 |
| 2 | claude-opus-4-6 | 1275.9 ± 6.4 |
| 3 | moonshotai/Kimi-K2.5 | 1254.8 ± 6.0 |
| 4 | gpt-5.5 | 1250.8 ± 8.3 |
| 5 | gpt-5.4 | 1250.4 ± 10.3 |
| 6 | moonshotai/Kimi-K2.6 | 1243.5 ± 10.4 |
| 7 | moonshotai/Kimi-K2-Instruct | 1240.6 ± 11.5 |
| 8 | o3 | 1238.9 ± 8.5 |
| 9 | moonshotai/Kimi-K2-Thinking | 1238.5 ± 10.5 |
| 10 | claude-sonnet-4-6 | 1237.9 ± 8.0 |
| 11 | zai-org/GLM-5.1 | 1232.4 ± 9.9 |
| 12 | claude-opus-4-5-20251101 | 1230.1 ± 8.8 |
| 13 | deepseek-ai/DeepSeek-V3.2 | 1227.3 ± 7.1 |
| 14 | gemini-3-pro-preview | 1226.8 ± 3.9 |
| 15 | grok-4.20-beta | 1226.2 ± 18.7 |
| 16 | deepseek-ai/DeepSeek-V4-Pro | 1226.1 ± 4.9 |
| 17 | gpt-5-2025-08-07 | 1225.1 ± 10.2 |
| 18 | gemini-3.1-pro-preview | 1224.9 ± 2.9 |
| 19 | openrouter/pony-alpha | 1223.3 ± 3.5 |
| 20 | claude-sonnet-4.5 | 1223.1 ± 9.3 |
| 21 | deepseek-ai/DeepSeek-V3.1 | 1220.6 ± 4.3 |
| 22 | openrouter/horizon-beta | 1220.4 ± 4.2 |
| 23 | deepseek-ai/DeepSeek-V4-Flash | 1220.3 ± 6.0 |
| 24 | claude-opus-4 | 1219.9 ± 5.5 |
| 25 | openrouter/horizon-alpha | 1219.3 ± 2.3 |
| 26 | gemini-2.5-pro-preview-06-05 | 1219.1 ± 4.2 |
| 27 | gpt-5.4-mini | 1218.3 ± 5.9 |
| 28 | Qwen/Qwen3.5-397B-A17B | 1217.8 ± 2.6 |
| 29 | hunter-alpha | 1217.5 ± 2.5 |
| 30 | deepseek-ai/DeepSeek-R1 | 1216.6 ± 5.5 |
| 31 | zai-org/GLM-5 | 1216.5 ± 1.0 |
| 32 | deepseek-ai/DeepSeek-R1-0528 | 1216.4 ± 4.7 |
| 33 | openrouter/sherlock-dash-alpha | 1216.4 ± 6.3 |
| 34 | gpt-5.2 | 1216.1 ± 3.6 |
| 35 | gpt-5.3-chat | 1215.6 ± 2.1 |
| 36 | NousResearch/Hermes-4-405B | 1215.4 ± 1.9 |
| 37 | zai-org/GLM-4.7 | 1215.3 ± 3.8 |
| 38 | chatgpt-4o-latest-2025-03-27 | 1215.2 ± 3.3 |
| 39 | grok-4.1-fast | 1214.9 ± 4.3 |
| 40 | google/gemma-4-31B-it | 1214.0 ± 6.1 |
| 41 | zai-org/GLM-4.6 | 1213.8 ± 4.9 |
| 42 | gemini-2.5-pro-exp-03-25 | 1213.0 ± 7.2 |
| 43 | mistral-medium-3.1 | 1213.0 ± 4.3 |
| 44 | google/gemma-4-26B-A4B-it | 1212.6 ± 8.5 |
| 45 | claude-3-7-sonnet-20250219 | 1212.2 ± 2.3 |
| 46 | deepseek-ai/DeepSeek-V3-0324 | 1211.1 ± 1.8 |
| 47 | gpt-5-mini-2025-08-07 | 1210.7 ± 4.8 |
| 48 | claude-3-5-sonnet-20241022 | 1209.9 ± 6.6 |
| 49 | optimus-alpha | 1209.7 ± 3.8 |
| 50 | zai-org/GLM-4.5 | 1209.1 ± 5.0 |
| 51 | qwen/qwen3-235b-a22b:thinking | 1208.4 ± 4.5 |
| 52 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1207.9 ± 7.7 |
| 53 | minimax/minimax-m2.5 | 1206.5 ± 5.7 |
| 54 | claude-sonnet-4 | 1206.0 ± 4.5 |
| 55 | quasar-alpha | 1205.1 ± 5.9 |
| 56 | gpt-4.5-preview | 1200.2 ± 6.8 |
| 57 | grok-3-beta | 1199.1 ± 5.7 |
| 58 | zai-org/GLM-4.7-Flash | 1197.8 ± 4.1 |
| 59 | deepseek-ai/DeepSeek-V3.2-Speciale | 1197.3 ± 5.8 |
| 60 | chatgpt-4o-latest-2025-01-29 | 1197.0 ± 7.5 |
| 61 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1196.5 ± 5.1 |
| 62 | mistral-small-creative | 1196.4 ± 2.9 |
| 63 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1195.1 ± 3.1 |
| 64 | CohereForAI/c4ai-command-a-03-2025 | 1194.7 ± 7.0 |
| 65 | google/gemma-3-27b-it | 1194.3 ± 3.6 |
| 66 | gpt-4.1-mini | 1193.9 ± 4.9 |
| 67 | openai/gpt-oss-120b | 1192.6 ± 3.4 |
| 68 | ifable/gemma-2-Ifable-9B | 1192.3 ± 4.7 |
| 69 | gemini-2.5-flash-preview | 1192.2 ± 5.9 |
| 70 | allura-org/Gemma-3-Glitter-12B | 1191.8 ± 4.2 |
| 71 | sam-paech/Darkest-muse-v1 | 1191.6 ± 2.9 |
| 72 | google/gemma-3-12b-it | 1191.2 ± 4.2 |
| 73 | gpt-5-nano-2025-08-07 | 1190.8 ± 9.7 |
| 74 | qwen/qwq-32b | 1190.7 ± 4.8 |
| 75 | RekaAI/reka-flash-3 | 1187.7 ± 3.9 |
| 76 | anthropic/claude-3.5-haiku-20241022 | 1185.7 ± 5.9 |
| 77 | gemini-2.0-flash-001 | 1184.2 ± 4.2 |
| 78 | google/gemma-3-4b-it | 1182.1 ± 7.9 |
| 79 | mistralai/Pixtral-Large-Instruct-2411 | 1180.5 ± 6.3 |
| 80 | THUDM/GLM-4-32B-0414 | 1178.0 ± 8.7 |
| 81 | meta-llama/llama-3.1-405b-instruct | 1173.4 ± 2.1 |
| 82 | gpt-4o-mini | 1171.3 ± 6.8 |
| 83 | gpt-4.1-nano | 1168.7 ± 5.0 |
| 84 | google/gemma-2-9b-it | 1167.9 ± 5.7 |
| 85 | mistralai/mistral-large-2411 | 1162.0 ± 13.0 |
| 86 | meta-llama/llama-3.1-70b-instruct | 1161.5 ± 7.7 |
| 87 | liquid/lfm-7b | 1160.0 ± 13.2 |
| 88 | anthropic/claude-3-haiku | 1159.9 ± 6.5 |
| 89 | ToastyPigeon/Gemma-3-Starshine-12B | 1159.1 ± 12.3 |
| 90 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1158.9 ± 7.7 |
| 91 | openai/gpt-4-0314 | 1158.8 ± 9.7 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1158.5 ± 11.6 |
| 93 | openai/gpt-oss-20b | 1158.1 ± 6.5 |
| 94 | meta-llama/llama-3.1-8b-instruct | 1151.4 ± 8.8 |
| 95 | openrouter/cypher-alpha | 1148.1 ± 5.6 |
| 96 | mistralai/Mistral-Small-24B-Instruct-2501 | 1143.9 ± 9.6 |
| 97 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1137.3 ± 12.1 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1133.9 ± 16.9 |
| 99 | openai/gpt-3.5-turbo-0613 | 1132.6 ± 11.2 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1104.3 ± 12.5 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1061.7 ± 11.7 |
