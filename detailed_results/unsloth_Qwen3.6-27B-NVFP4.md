# Detailed Results: unsloth/Qwen3.6-27B-NVFP4

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.8094
* **Mean Absolute Cliff's Delta**: 0.7637
* **Combined Separability Score**: 78.66%
* **Positional Bias**: Position 1 (A): 58.4% | Position 2 (B): 41.6%
* **Length Bias**: Win Rate: 55.7% | Avg EV Margin: +8.0%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1239.0 |
| 2 | claude-opus-4-7 | 1236.7 |
| 3 | claude-opus-4-6 | 1234.2 |
| 4 | moonshotai/Kimi-K2-Instruct | 1227.9 |
| 5 | gpt-5.5 | 1227.7 |
| 6 | gpt-5.4 | 1227.7 |
| 7 | moonshotai/Kimi-K2.6 | 1227.5 |
| 8 | moonshotai/Kimi-K2-Thinking | 1223.6 |
| 9 | claude-opus-4-5-20251101 | 1223.3 |
| 10 | o3 | 1221.0 |
| 11 | grok-4.20-beta | 1220.9 |
| 12 | claude-sonnet-4-6 | 1220.8 |
| 13 | google/gemma-4-31B-it | 1219.7 |
| 14 | openrouter/sherlock-dash-alpha | 1219.7 |
| 15 | gemini-3.1-pro-preview | 1219.6 |
| 16 | claude-opus-4 | 1219.2 |
| 17 | deepseek-ai/DeepSeek-R1 | 1217.6 |
| 18 | mistral-medium-3.1 | 1217.5 |
| 19 | Qwen/Qwen3.5-397B-A17B | 1217.4 |
| 20 | deepseek-ai/DeepSeek-V3.2 | 1217.1 |
| 21 | gemini-3-pro-preview | 1216.9 |
| 22 | deepseek-ai/DeepSeek-V3.1 | 1216.9 |
| 23 | deepseek-ai/DeepSeek-V4-Flash | 1216.1 |
| 24 | zai-org/GLM-5.1 | 1216.0 |
| 25 | deepseek-ai/DeepSeek-V4-Pro | 1215.6 |
| 26 | gpt-5-2025-08-07 | 1215.1 |
| 27 | openrouter/horizon-alpha | 1214.9 |
| 28 | claude-sonnet-4.5 | 1214.6 |
| 29 | qwen/qwen3-235b-a22b:thinking | 1214.2 |
| 30 | zai-org/GLM-4.6 | 1214.0 |
| 31 | claude-3-5-sonnet-20241022 | 1214.0 |
| 32 | deepseek-ai/DeepSeek-R1-0528 | 1212.7 |
| 33 | openrouter/pony-alpha | 1212.6 |
| 34 | gemini-2.5-pro-preview-06-05 | 1211.4 |
| 35 | gpt-5.4-mini | 1210.9 |
| 36 | zai-org/GLM-5 | 1210.2 |
| 37 | NousResearch/Hermes-4-405B | 1210.1 |
| 38 | zai-org/GLM-4.7 | 1209.8 |
| 39 | openrouter/horizon-beta | 1209.4 |
| 40 | chatgpt-4o-latest-2025-03-27 | 1209.0 |
| 41 | google/gemma-4-26B-A4B-it | 1208.7 |
| 42 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1208.7 |
| 43 | grok-4.1-fast | 1208.5 |
| 44 | deepseek-ai/DeepSeek-V3-0324 | 1208.5 |
| 45 | hunter-alpha | 1208.3 |
| 46 | gpt-5.2 | 1207.6 |
| 47 | claude-sonnet-4 | 1207.5 |
| 48 | zai-org/GLM-4.5 | 1206.8 |
| 49 | quasar-alpha | 1206.2 |
| 50 | gpt-5.3-chat | 1204.3 |
| 51 | claude-3-7-sonnet-20250219 | 1202.4 |
| 52 | mistral-small-creative | 1200.1 |
| 53 | optimus-alpha | 1200.0 |
| 54 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.6 |
| 55 | minimax/minimax-m2.5 | 1199.4 |
| 56 | RekaAI/reka-flash-3 | 1198.6 |
| 57 | gpt-4.5-preview | 1198.4 |
| 58 | deepseek-ai/DeepSeek-V3.2-Speciale | 1197.7 |
| 59 | gemini-2.5-pro-exp-03-25 | 1197.5 |
| 60 | chatgpt-4o-latest-2025-01-29 | 1197.2 |
| 61 | gpt-5-mini-2025-08-07 | 1197.1 |
| 62 | zai-org/GLM-4.7-Flash | 1197.0 |
| 63 | qwen/qwq-32b | 1195.4 |
| 64 | anthropic/claude-3.5-haiku-20241022 | 1194.3 |
| 65 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1193.0 |
| 66 | google/gemma-3-27b-it | 1192.9 |
| 67 | CohereForAI/c4ai-command-a-03-2025 | 1191.3 |
| 68 | grok-3-beta | 1190.8 |
| 69 | gemini-2.5-flash-preview | 1190.5 |
| 70 | THUDM/GLM-4-32B-0414 | 1189.8 |
| 71 | google/gemma-3-12b-it | 1189.4 |
| 72 | ifable/gemma-2-Ifable-9B | 1188.2 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1187.9 |
| 74 | gemini-2.0-flash-001 | 1187.8 |
| 75 | mistralai/Pixtral-Large-Instruct-2411 | 1186.1 |
| 76 | sam-paech/Darkest-muse-v1 | 1184.8 |
| 77 | meta-llama/llama-3.1-405b-instruct | 1184.5 |
| 78 | gpt-4.1-mini | 1184.5 |
| 79 | openai/gpt-oss-120b | 1184.0 |
| 80 | google/gemma-2-9b-it | 1183.4 |
| 81 | mistralai/mistral-large-2411 | 1183.1 |
| 82 | gpt-5-nano-2025-08-07 | 1182.9 |
| 83 | google/gemma-3-4b-it | 1182.8 |
| 84 | gpt-4o-mini | 1178.4 |
| 85 | meta-llama/llama-3.1-70b-instruct | 1178.0 |
| 86 | gpt-4.1-nano | 1177.7 |
| 87 | liquid/lfm-7b | 1176.4 |
| 88 | meta-llama/llama-3.1-8b-instruct | 1175.4 |
| 89 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1174.5 |
| 90 | openrouter/cypher-alpha | 1172.0 |
| 91 | mistralai/Mistral-Nemo-Instruct-2407 | 1170.6 |
| 92 | openai/gpt-3.5-turbo-0613 | 1169.3 |
| 93 | anthropic/claude-3-haiku | 1168.4 |
| 94 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1167.8 |
| 95 | openai/gpt-4-0314 | 1167.0 |
| 96 | meta-llama/llama-3.2-3b-instruct | 1166.1 |
| 97 | ToastyPigeon/Gemma-3-Starshine-12B | 1165.8 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1165.6 |
| 99 | openai/gpt-oss-20b | 1164.5 |
| 100 | mistralai/Mistral-Small-24B-Instruct-2501 | 1162.1 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1150.5 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9469
* **Mean Absolute Cliff's Delta**: 0.8761
* **Combined Separability Score**: 91.15%
* **Positional Bias**: Position 1 (A): 61.3% | Position 2 (B): 38.7%
* **Length Bias**: Win Rate: 52.6% | Avg EV Margin: +4.3%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1318.1 ± 13.1 |
| 2 | claude-opus-4-6 | 1264.7 ± 10.9 |
| 3 | moonshotai/Kimi-K2.5 | 1262.9 ± 7.4 |
| 4 | o3 | 1259.4 ± 12.6 |
| 5 | gpt-5.4 | 1257.7 ± 10.6 |
| 6 | gpt-5.5 | 1255.3 ± 6.0 |
| 7 | moonshotai/Kimi-K2.6 | 1245.4 ± 9.3 |
| 8 | grok-4.20-beta | 1243.0 ± 11.2 |
| 9 | moonshotai/Kimi-K2-Instruct | 1242.4 ± 13.1 |
| 10 | claude-sonnet-4-6 | 1239.4 ± 7.5 |
| 11 | moonshotai/Kimi-K2-Thinking | 1238.3 ± 6.1 |
| 12 | gpt-5-2025-08-07 | 1235.0 ± 10.4 |
| 13 | gemini-3.1-pro-preview | 1234.3 ± 12.9 |
| 14 | claude-sonnet-4.5 | 1231.0 ± 7.6 |
| 15 | deepseek-ai/DeepSeek-V4-Pro | 1230.8 ± 10.3 |
| 16 | gemini-3-pro-preview | 1229.5 ± 5.1 |
| 17 | claude-opus-4-5-20251101 | 1229.2 ± 5.1 |
| 18 | openrouter/horizon-alpha | 1228.2 ± 3.3 |
| 19 | deepseek-ai/DeepSeek-V3.2 | 1227.9 ± 6.9 |
| 20 | gpt-5.4-mini | 1227.9 ± 7.6 |
| 21 | zai-org/GLM-5.1 | 1227.4 ± 7.0 |
| 22 | claude-opus-4 | 1225.7 ± 8.1 |
| 23 | gpt-5.2 | 1225.5 ± 3.9 |
| 24 | deepseek-ai/DeepSeek-V4-Flash | 1225.4 ± 6.6 |
| 25 | gpt-5.3-chat | 1224.8 ± 7.5 |
| 26 | deepseek-ai/DeepSeek-V3.1 | 1224.6 ± 6.7 |
| 27 | gemini-2.5-pro-preview-06-05 | 1224.0 ± 5.6 |
| 28 | openrouter/pony-alpha | 1222.1 ± 7.0 |
| 29 | zai-org/GLM-5 | 1221.9 ± 4.5 |
| 30 | zai-org/GLM-4.7 | 1221.9 ± 6.8 |
| 31 | deepseek-ai/DeepSeek-R1 | 1221.6 ± 7.2 |
| 32 | openrouter/horizon-beta | 1221.5 ± 5.0 |
| 33 | grok-4.1-fast | 1220.6 ± 4.5 |
| 34 | openrouter/sherlock-dash-alpha | 1220.0 ± 3.9 |
| 35 | hunter-alpha | 1219.5 ± 6.0 |
| 36 | chatgpt-4o-latest-2025-03-27 | 1218.5 ± 3.0 |
| 37 | Qwen/Qwen3.5-397B-A17B | 1217.7 ± 3.9 |
| 38 | deepseek-ai/DeepSeek-R1-0528 | 1217.7 ± 4.3 |
| 39 | zai-org/GLM-4.6 | 1217.3 ± 11.9 |
| 40 | mistral-medium-3.1 | 1215.6 ± 7.6 |
| 41 | google/gemma-4-26B-A4B-it | 1214.1 ± 4.3 |
| 42 | google/gemma-4-31B-it | 1213.5 ± 1.9 |
| 43 | gemini-2.5-pro-exp-03-25 | 1213.4 ± 4.7 |
| 44 | qwen/qwen3-235b-a22b:thinking | 1213.2 ± 7.0 |
| 45 | optimus-alpha | 1211.0 ± 7.9 |
| 46 | NousResearch/Hermes-4-405B | 1210.9 ± 5.0 |
| 47 | zai-org/GLM-4.5 | 1209.9 ± 3.9 |
| 48 | gpt-5-mini-2025-08-07 | 1209.3 ± 5.2 |
| 49 | claude-3-7-sonnet-20250219 | 1208.7 ± 2.2 |
| 50 | claude-sonnet-4 | 1207.9 ± 5.7 |
| 51 | deepseek-ai/DeepSeek-V3-0324 | 1207.0 ± 5.6 |
| 52 | quasar-alpha | 1206.3 ± 7.3 |
| 53 | claude-3-5-sonnet-20241022 | 1205.6 ± 5.5 |
| 54 | chatgpt-4o-latest-2025-01-29 | 1203.9 ± 6.1 |
| 55 | grok-3-beta | 1203.1 ± 2.1 |
| 56 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1203.0 ± 3.5 |
| 57 | minimax/minimax-m2.5 | 1201.1 ± 3.6 |
| 58 | gpt-4.5-preview | 1199.6 ± 1.5 |
| 59 | zai-org/GLM-4.7-Flash | 1197.6 ± 6.0 |
| 60 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1196.4 ± 3.4 |
| 61 | mistral-small-creative | 1196.3 ± 3.5 |
| 62 | deepseek-ai/DeepSeek-V3.2-Speciale | 1196.3 ± 1.7 |
| 63 | gemini-2.5-flash-preview | 1192.5 ± 6.3 |
| 64 | qwen/qwq-32b | 1191.9 ± 5.8 |
| 65 | google/gemma-3-27b-it | 1191.4 ± 3.7 |
| 66 | ifable/gemma-2-Ifable-9B | 1191.0 ± 2.6 |
| 67 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1190.8 ± 8.9 |
| 68 | CohereForAI/c4ai-command-a-03-2025 | 1189.3 ± 12.0 |
| 69 | gemini-2.0-flash-001 | 1187.9 ± 4.1 |
| 70 | gpt-4.1-mini | 1187.7 ± 5.2 |
| 71 | gpt-5-nano-2025-08-07 | 1187.3 ± 3.2 |
| 72 | openai/gpt-oss-120b | 1187.3 ± 7.1 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1186.7 ± 4.7 |
| 74 | RekaAI/reka-flash-3 | 1186.5 ± 5.1 |
| 75 | sam-paech/Darkest-muse-v1 | 1186.5 ± 5.5 |
| 76 | google/gemma-3-12b-it | 1185.4 ± 6.4 |
| 77 | anthropic/claude-3.5-haiku-20241022 | 1182.1 ± 5.6 |
| 78 | google/gemma-3-4b-it | 1179.3 ± 5.3 |
| 79 | THUDM/GLM-4-32B-0414 | 1178.1 ± 13.5 |
| 80 | mistralai/Pixtral-Large-Instruct-2411 | 1174.3 ± 3.6 |
| 81 | gpt-4o-mini | 1171.9 ± 9.1 |
| 82 | google/gemma-2-9b-it | 1171.5 ± 9.1 |
| 83 | gpt-4.1-nano | 1167.0 ± 10.2 |
| 84 | ToastyPigeon/Gemma-3-Starshine-12B | 1166.9 ± 12.7 |
| 85 | meta-llama/llama-3.1-405b-instruct | 1165.5 ± 7.2 |
| 86 | mistralai/mistral-large-2411 | 1163.1 ± 10.3 |
| 87 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1162.3 ± 4.3 |
| 88 | mistralai/Mistral-Nemo-Instruct-2407 | 1154.5 ± 4.0 |
| 89 | openai/gpt-4-0314 | 1146.4 ± 5.5 |
| 90 | anthropic/claude-3-haiku | 1146.1 ± 8.3 |
| 91 | meta-llama/llama-3.1-70b-instruct | 1145.8 ± 4.5 |
| 92 | liquid/lfm-7b | 1144.2 ± 14.2 |
| 93 | openrouter/cypher-alpha | 1143.2 ± 15.0 |
| 94 | openai/gpt-oss-20b | 1140.4 ± 10.7 |
| 95 | meta-llama/llama-3.1-8b-instruct | 1139.4 ± 13.0 |
| 96 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1136.8 ± 14.0 |
| 97 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1131.3 ± 8.0 |
| 98 | openai/gpt-3.5-turbo-0613 | 1121.4 ± 9.8 |
| 99 | mistralai/Mistral-Small-24B-Instruct-2501 | 1117.5 ± 18.6 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1086.8 ± 8.3 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1059.6 ± 12.7 |
