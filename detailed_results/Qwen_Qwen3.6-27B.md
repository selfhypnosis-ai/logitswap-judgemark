# Detailed Results: Qwen/Qwen3.6-27B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7844
* **Mean Absolute Cliff's Delta**: 0.7209
* **Combined Separability Score**: 75.27%
* **Positional Bias**: Position 1 (A): 59.8% | Position 2 (B): 40.2%
* **Length Bias**: Win Rate: 54.4% | Avg EV Margin: +6.8%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1233.1 |
| 2 | moonshotai/Kimi-K2.5 | 1227.6 |
| 3 | claude-opus-4-6 | 1227.1 |
| 4 | gpt-5.5 | 1222.8 |
| 5 | moonshotai/Kimi-K2.6 | 1221.6 |
| 6 | o3 | 1220.7 |
| 7 | claude-sonnet-4-6 | 1220.2 |
| 8 | gpt-5.4 | 1220.1 |
| 9 | moonshotai/Kimi-K2-Thinking | 1219.8 |
| 10 | moonshotai/Kimi-K2-Instruct | 1219.2 |
| 11 | zai-org/GLM-5.1 | 1218.8 |
| 12 | claude-opus-4-5-20251101 | 1217.8 |
| 13 | gemini-3.1-pro-preview | 1217.5 |
| 14 | deepseek-ai/DeepSeek-V4-Pro | 1217.2 |
| 15 | deepseek-ai/DeepSeek-V3.2 | 1216.8 |
| 16 | Qwen/Qwen3.5-397B-A17B | 1216.6 |
| 17 | gemini-3-pro-preview | 1216.3 |
| 18 | deepseek-ai/DeepSeek-V4-Flash | 1215.9 |
| 19 | claude-opus-4 | 1215.3 |
| 20 | openrouter/pony-alpha | 1215.0 |
| 21 | grok-4.20-beta | 1214.5 |
| 22 | deepseek-ai/DeepSeek-R1 | 1214.4 |
| 23 | gpt-5-2025-08-07 | 1214.0 |
| 24 | google/gemma-4-31B-it | 1213.7 |
| 25 | grok-4.1-fast | 1213.5 |
| 26 | claude-sonnet-4.5 | 1213.3 |
| 27 | openrouter/horizon-beta | 1212.8 |
| 28 | gpt-5.3-chat | 1212.7 |
| 29 | zai-org/GLM-5 | 1212.1 |
| 30 | gpt-5.4-mini | 1212.0 |
| 31 | deepseek-ai/DeepSeek-V3.1 | 1211.8 |
| 32 | openrouter/horizon-alpha | 1211.7 |
| 33 | gemini-2.5-pro-preview-06-05 | 1211.7 |
| 34 | hunter-alpha | 1211.6 |
| 35 | chatgpt-4o-latest-2025-03-27 | 1210.5 |
| 36 | deepseek-ai/DeepSeek-V3-0324 | 1209.9 |
| 37 | gpt-5.2 | 1209.4 |
| 38 | zai-org/GLM-4.7 | 1209.2 |
| 39 | claude-3-5-sonnet-20241022 | 1208.8 |
| 40 | zai-org/GLM-4.6 | 1208.8 |
| 41 | mistral-medium-3.1 | 1208.1 |
| 42 | openrouter/sherlock-dash-alpha | 1208.0 |
| 43 | NousResearch/Hermes-4-405B | 1207.9 |
| 44 | qwen/qwen3-235b-a22b:thinking | 1207.6 |
| 45 | google/gemma-4-26B-A4B-it | 1207.4 |
| 46 | deepseek-ai/DeepSeek-R1-0528 | 1205.5 |
| 47 | optimus-alpha | 1205.2 |
| 48 | zai-org/GLM-4.5 | 1204.1 |
| 49 | gemini-2.5-pro-exp-03-25 | 1203.5 |
| 50 | claude-3-7-sonnet-20250219 | 1202.3 |
| 51 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1202.1 |
| 52 | deepseek-ai/DeepSeek-V3.2-Speciale | 1201.4 |
| 53 | claude-sonnet-4 | 1201.3 |
| 54 | chatgpt-4o-latest-2025-01-29 | 1200.9 |
| 55 | gpt-5-mini-2025-08-07 | 1200.4 |
| 56 | minimax/minimax-m2.5 | 1199.1 |
| 57 | quasar-alpha | 1199.0 |
| 58 | mistral-small-creative | 1199.0 |
| 59 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1198.2 |
| 60 | grok-3-beta | 1197.7 |
| 61 | RekaAI/reka-flash-3 | 1196.7 |
| 62 | anthropic/claude-3.5-haiku-20241022 | 1196.6 |
| 63 | ifable/gemma-2-Ifable-9B | 1196.2 |
| 64 | qwen/qwq-32b | 1196.0 |
| 65 | zai-org/GLM-4.7-Flash | 1195.5 |
| 66 | gpt-4.1-mini | 1195.4 |
| 67 | gpt-4.5-preview | 1195.3 |
| 68 | google/gemma-3-27b-it | 1193.3 |
| 69 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1191.9 |
| 70 | gemini-2.5-flash-preview | 1191.7 |
| 71 | gemini-2.0-flash-001 | 1191.6 |
| 72 | CohereForAI/c4ai-command-a-03-2025 | 1190.3 |
| 73 | sam-paech/Darkest-muse-v1 | 1190.2 |
| 74 | google/gemma-3-12b-it | 1189.7 |
| 75 | allura-org/Gemma-3-Glitter-12B | 1189.5 |
| 76 | gpt-5-nano-2025-08-07 | 1187.8 |
| 77 | THUDM/GLM-4-32B-0414 | 1187.6 |
| 78 | openai/gpt-oss-120b | 1185.8 |
| 79 | google/gemma-3-4b-it | 1185.1 |
| 80 | mistralai/mistral-large-2411 | 1184.9 |
| 81 | meta-llama/llama-3.1-405b-instruct | 1184.8 |
| 82 | google/gemma-2-9b-it | 1182.8 |
| 83 | meta-llama/llama-3.1-70b-instruct | 1182.0 |
| 84 | mistralai/Pixtral-Large-Instruct-2411 | 1180.7 |
| 85 | gpt-4.1-nano | 1180.2 |
| 86 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1180.2 |
| 87 | gpt-4o-mini | 1180.0 |
| 88 | mistralai/Mistral-Nemo-Instruct-2407 | 1179.1 |
| 89 | openai/gpt-4-0314 | 1178.7 |
| 90 | anthropic/claude-3-haiku | 1178.3 |
| 91 | meta-llama/llama-3.1-8b-instruct | 1177.3 |
| 92 | liquid/lfm-7b | 1174.0 |
| 93 | ToastyPigeon/Gemma-3-Starshine-12B | 1173.7 |
| 94 | openrouter/cypher-alpha | 1173.0 |
| 95 | openai/gpt-oss-20b | 1171.9 |
| 96 | openai/gpt-3.5-turbo-0613 | 1170.8 |
| 97 | mistralai/Mistral-Small-24B-Instruct-2501 | 1170.4 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1169.9 |
| 99 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1169.9 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1168.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1148.4 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9421
* **Mean Absolute Cliff's Delta**: 0.8614
* **Combined Separability Score**: 90.18%
* **Positional Bias**: Position 1 (A): 61.3% | Position 2 (B): 38.7%
* **Length Bias**: Win Rate: 53.4% | Avg EV Margin: +4.2%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1281.8 ± 11.9 |
| 2 | claude-opus-4-6 | 1266.0 ± 10.7 |
| 3 | moonshotai/Kimi-K2.5 | 1250.9 ± 11.4 |
| 4 | gpt-5.5 | 1248.5 ± 11.1 |
| 5 | gpt-5.4 | 1242.3 ± 10.3 |
| 6 | moonshotai/Kimi-K2.6 | 1239.3 ± 9.9 |
| 7 | claude-sonnet-4-6 | 1238.4 ± 10.0 |
| 8 | o3 | 1237.2 ± 6.5 |
| 9 | moonshotai/Kimi-K2-Instruct | 1236.9 ± 5.7 |
| 10 | moonshotai/Kimi-K2-Thinking | 1236.0 ± 9.4 |
| 11 | grok-4.20-beta | 1234.9 ± 9.4 |
| 12 | zai-org/GLM-5.1 | 1230.1 ± 7.7 |
| 13 | claude-opus-4-5-20251101 | 1229.7 ± 5.0 |
| 14 | gemini-3.1-pro-preview | 1228.2 ± 7.1 |
| 15 | gemini-3-pro-preview | 1228.0 ± 4.4 |
| 16 | openrouter/horizon-alpha | 1226.9 ± 7.0 |
| 17 | deepseek-ai/DeepSeek-V4-Pro | 1226.6 ± 5.8 |
| 18 | deepseek-ai/DeepSeek-V3.2 | 1225.2 ± 4.0 |
| 19 | gpt-5-2025-08-07 | 1224.0 ± 4.6 |
| 20 | gemini-2.5-pro-preview-06-05 | 1223.8 ± 4.3 |
| 21 | claude-sonnet-4.5 | 1222.1 ± 4.1 |
| 22 | openrouter/horizon-beta | 1222.0 ± 3.6 |
| 23 | deepseek-ai/DeepSeek-V3.1 | 1221.5 ± 7.8 |
| 24 | gpt-5.2 | 1220.7 ± 7.9 |
| 25 | deepseek-ai/DeepSeek-V4-Flash | 1220.6 ± 5.5 |
| 26 | claude-opus-4 | 1220.6 ± 2.9 |
| 27 | gpt-5.3-chat | 1220.4 ± 5.3 |
| 28 | google/gemma-4-31B-it | 1220.1 ± 4.4 |
| 29 | gpt-5.4-mini | 1219.5 ± 5.4 |
| 30 | zai-org/GLM-5 | 1219.4 ± 6.6 |
| 31 | deepseek-ai/DeepSeek-R1 | 1219.2 ± 5.9 |
| 32 | openrouter/pony-alpha | 1219.1 ± 3.7 |
| 33 | hunter-alpha | 1218.1 ± 7.1 |
| 34 | zai-org/GLM-4.7 | 1217.7 ± 7.4 |
| 35 | Qwen/Qwen3.5-397B-A17B | 1217.7 ± 4.4 |
| 36 | grok-4.1-fast | 1217.2 ± 4.4 |
| 37 | zai-org/GLM-4.6 | 1216.8 ± 3.0 |
| 38 | deepseek-ai/DeepSeek-R1-0528 | 1215.6 ± 7.5 |
| 39 | NousResearch/Hermes-4-405B | 1213.6 ± 5.5 |
| 40 | openrouter/sherlock-dash-alpha | 1213.4 ± 7.1 |
| 41 | qwen/qwen3-235b-a22b:thinking | 1213.1 ± 3.3 |
| 42 | chatgpt-4o-latest-2025-03-27 | 1212.4 ± 4.0 |
| 43 | google/gemma-4-26B-A4B-it | 1212.3 ± 3.1 |
| 44 | gpt-5-mini-2025-08-07 | 1211.9 ± 3.9 |
| 45 | gemini-2.5-pro-exp-03-25 | 1210.9 ± 4.7 |
| 46 | mistral-medium-3.1 | 1209.5 ± 5.9 |
| 47 | deepseek-ai/DeepSeek-V3-0324 | 1208.7 ± 4.8 |
| 48 | zai-org/GLM-4.5 | 1207.8 ± 6.6 |
| 49 | claude-3-5-sonnet-20241022 | 1206.9 ± 6.6 |
| 50 | optimus-alpha | 1206.5 ± 5.6 |
| 51 | claude-3-7-sonnet-20250219 | 1206.3 ± 2.7 |
| 52 | claude-sonnet-4 | 1205.1 ± 6.6 |
| 53 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.5 ± 4.2 |
| 54 | quasar-alpha | 1203.9 ± 4.6 |
| 55 | mistral-small-creative | 1203.6 ± 5.9 |
| 56 | minimax/minimax-m2.5 | 1202.6 ± 6.5 |
| 57 | google/gemma-3-27b-it | 1200.9 ± 6.1 |
| 58 | grok-3-beta | 1200.9 ± 2.3 |
| 59 | zai-org/GLM-4.7-Flash | 1200.5 ± 3.8 |
| 60 | chatgpt-4o-latest-2025-01-29 | 1200.5 ± 8.1 |
| 61 | gpt-4.5-preview | 1198.3 ± 5.7 |
| 62 | deepseek-ai/DeepSeek-V3.2-Speciale | 1197.5 ± 4.1 |
| 63 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1197.3 ± 5.2 |
| 64 | qwen/qwq-32b | 1197.0 ± 5.1 |
| 65 | CohereForAI/c4ai-command-a-03-2025 | 1195.7 ± 4.6 |
| 66 | gemini-2.5-flash-preview | 1195.2 ± 6.4 |
| 67 | google/gemma-3-12b-it | 1195.0 ± 4.9 |
| 68 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1194.9 ± 6.5 |
| 69 | RekaAI/reka-flash-3 | 1194.0 ± 5.8 |
| 70 | gpt-5-nano-2025-08-07 | 1192.5 ± 2.8 |
| 71 | ifable/gemma-2-Ifable-9B | 1192.0 ± 6.8 |
| 72 | sam-paech/Darkest-muse-v1 | 1191.2 ± 8.0 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1191.0 ± 5.5 |
| 74 | openai/gpt-oss-120b | 1192.4 ± 5.4 |
| 75 | gemini-2.0-flash-001 | 1188.3 ± 5.1 |
| 76 | gpt-4.1-mini | 1187.6 ± 6.0 |
| 77 | anthropic/claude-3.5-haiku-20241022 | 1186.6 ± 6.8 |
| 78 | THUDM/GLM-4-32B-0414 | 1184.5 ± 7.4 |
| 79 | google/gemma-3-4b-it | 1184.2 ± 5.8 |
| 80 | mistralai/mistral-large-2411 | 1176.5 ± 9.6 |
| 81 | meta-llama/llama-3.1-405b-instruct | 1172.5 ± 10.6 |
| 82 | gpt-4o-mini | 1171.5 ± 9.7 |
| 83 | mistralai/Pixtral-Large-Instruct-2411 | 1170.4 ± 10.9 |
| 84 | google/gemma-2-9b-it | 1169.3 ± 7.6 |
| 85 | gpt-4.1-nano | 1169.0 ± 11.0 |
| 86 | meta-llama/llama-3.1-70b-instruct | 1163.3 ± 9.0 |
| 87 | mistralai/Mistral-Nemo-Instruct-2407 | 1162.7 ± 8.4 |
| 88 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1160.4 ± 8.6 |
| 89 | ToastyPigeon/Gemma-3-Starshine-12B | 1160.3 ± 11.4 |
| 90 | anthropic/claude-3-haiku | 1154.9 ± 6.1 |
| 91 | openai/gpt-4-0314 | 1153.8 ± 9.6 |
| 92 | liquid/lfm-7b | 1152.8 ± 6.8 |
| 93 | openai/gpt-oss-20b | 1149.9 ± 9.9 |
| 94 | openrouter/cypher-alpha | 1148.7 ± 11.3 |
| 95 | meta-llama/llama-3.1-8b-instruct | 1145.5 ± 13.8 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1140.8 ± 13.3 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1135.9 ± 16.8 |
| 98 | openai/gpt-3.5-turbo-0613 | 1134.8 ± 10.8 |
| 99 | mistralai/Mistral-Small-24B-Instruct-2501 | 1131.1 ± 13.4 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1112.4 ± 15.2 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1052.6 ± 23.1 |
