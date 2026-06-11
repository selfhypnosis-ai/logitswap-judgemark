# Detailed Results: RedHatAI/diffusiongemma-26B-A4B-it-FP8-dynamic

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7335
* **Mean Absolute Cliff's Delta**: 0.6839
* **Combined Separability Score**: 70.87%
* **Positional Bias**: Position 1 (A): 49.8% | Position 2 (B): 50.2%
* **Length Bias**: Win Rate: 56.5% | Avg EV Margin: +11.8%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1251.7 |
| 2 | gpt-5.5 | 1244.9 |
| 3 | claude-opus-4-6 | 1242.6 |
| 4 | moonshotai/Kimi-K2.5 | 1241.6 |
| 5 | moonshotai/Kimi-K2.6 | 1237.0 |
| 6 | gpt-5.4 | 1235.5 |
| 7 | moonshotai/Kimi-K2-Thinking | 1232.0 |
| 8 | moonshotai/Kimi-K2-Instruct | 1231.1 |
| 9 | claude-sonnet-4-6 | 1229.1 |
| 10 | gemini-3-pro-preview | 1229.1 |
| 11 | gpt-5-2025-08-07 | 1227.7 |
| 12 | google/gemma-4-31B-it | 1227.3 |
| 13 | deepseek-ai/DeepSeek-V4-Pro | 1227.1 |
| 14 | gemini-3.1-pro-preview | 1226.1 |
| 15 | zai-org/GLM-5.1 | 1225.8 |
| 16 | claude-opus-4-5-20251101 | 1225.4 |
| 17 | openrouter/horizon-beta | 1225.0 |
| 18 | Qwen/Qwen3.5-397B-A17B | 1224.8 |
| 19 | grok-4.1-fast | 1224.7 |
| 20 | deepseek-ai/DeepSeek-R1 | 1224.7 |
| 21 | openrouter/sherlock-dash-alpha | 1224.7 |
| 22 | o3 | 1224.5 |
| 23 | deepseek-ai/DeepSeek-V4-Flash | 1224.1 |
| 24 | openrouter/horizon-alpha | 1222.6 |
| 25 | grok-4.20-beta | 1222.3 |
| 26 | deepseek-ai/DeepSeek-V3.2 | 1221.5 |
| 27 | deepseek-ai/DeepSeek-V3.1 | 1219.6 |
| 28 | gpt-5.2 | 1217.5 |
| 29 | google/gemma-4-26B-A4B-it | 1215.9 |
| 30 | claude-opus-4 | 1215.6 |
| 31 | zai-org/GLM-4.6 | 1215.6 |
| 32 | zai-org/GLM-4.7 | 1214.7 |
| 33 | gpt-5.4-mini | 1214.6 |
| 34 | openrouter/pony-alpha | 1213.9 |
| 35 | claude-sonnet-4.5 | 1213.5 |
| 36 | NousResearch/Hermes-4-405B | 1213.3 |
| 37 | hunter-alpha | 1212.7 |
| 38 | gpt-5.3-chat | 1212.4 |
| 39 | zai-org/GLM-5 | 1211.9 |
| 40 | gemini-2.5-pro-preview-06-05 | 1211.7 |
| 41 | qwen/qwen3-235b-a22b:thinking | 1211.6 |
| 42 | gpt-5-mini-2025-08-07 | 1209.8 |
| 43 | deepseek-ai/DeepSeek-V3-0324 | 1209.1 |
| 44 | deepseek-ai/DeepSeek-R1-0528 | 1207.2 |
| 45 | mistral-medium-3.1 | 1206.9 |
| 46 | claude-3-5-sonnet-20241022 | 1205.8 |
| 47 | zai-org/GLM-4.5 | 1205.0 |
| 48 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.4 |
| 49 | chatgpt-4o-latest-2025-03-27 | 1204.4 |
| 50 | RekaAI/reka-flash-3 | 1203.2 |
| 51 | gemini-2.5-pro-exp-03-25 | 1202.8 |
| 52 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1201.0 |
| 53 | optimus-alpha | 1200.2 |
| 54 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.1 |
| 55 | claude-sonnet-4 | 1200.1 |
| 56 | mistral-small-creative | 1199.7 |
| 57 | qwen/qwq-32b | 1197.8 |
| 58 | minimax/minimax-m2.5 | 1197.6 |
| 59 | claude-3-7-sonnet-20250219 | 1197.4 |
| 60 | anthropic/claude-3.5-haiku-20241022 | 1197.3 |
| 61 | quasar-alpha | 1196.0 |
| 62 | zai-org/GLM-4.7-Flash | 1195.7 |
| 63 | ifable/gemma-2-Ifable-9B | 1195.6 |
| 64 | deepseek-ai/DeepSeek-V3.2-Speciale | 1192.4 |
| 65 | grok-3-beta | 1191.2 |
| 66 | chatgpt-4o-latest-2025-01-29 | 1190.4 |
| 67 | gpt-4.1-mini | 1189.8 |
| 68 | google/gemma-3-27b-it | 1189.3 |
| 69 | gemini-2.5-flash-preview | 1185.4 |
| 70 | CohereForAI/c4ai-command-a-03-2025 | 1184.5 |
| 71 | openai/gpt-oss-120b | 1183.6 |
| 72 | sam-paech/Darkest-muse-v1 | 1183.2 |
| 73 | gpt-4.5-preview | 1183.2 |
| 74 | gpt-5-nano-2025-08-07 | 1183.1 |
| 75 | gemini-2.0-flash-001 | 1182.5 |
| 76 | meta-llama/llama-3.1-405b-instruct | 1181.5 |
| 77 | allura-org/Gemma-3-Glitter-12B | 1180.8 |
| 78 | google/gemma-3-4b-it | 1179.2 |
| 79 | google/gemma-3-12b-it | 1178.5 |
| 80 | meta-llama/llama-3.1-70b-instruct | 1176.6 |
| 81 | google/gemma-2-9b-it | 1175.7 |
| 82 | mistralai/mistral-large-2411 | 1173.4 |
| 83 | THUDM/GLM-4-32B-0414 | 1172.3 |
| 84 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1171.1 |
| 85 | liquid/lfm-7b | 1170.1 |
| 86 | gpt-4o-mini | 1170.0 |
| 87 | gpt-4.1-nano | 1169.3 |
| 88 | openai/gpt-4-0314 | 1168.3 |
| 89 | mistralai/Pixtral-Large-Instruct-2411 | 1168.2 |
| 90 | mistralai/Mistral-Nemo-Instruct-2407 | 1165.6 |
| 91 | meta-llama/llama-3.1-8b-instruct | 1165.5 |
| 92 | anthropic/claude-3-haiku | 1164.3 |
| 93 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1163.6 |
| 94 | openrouter/cypher-alpha | 1162.8 |
| 95 | openai/gpt-oss-20b | 1162.6 |
| 96 | mistralai/Mistral-Small-24B-Instruct-2501 | 1158.3 |
| 97 | meta-llama/llama-3.2-3b-instruct | 1154.8 |
| 98 | openai/gpt-3.5-turbo-0613 | 1154.5 |
| 99 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1154.4 |
| 100 | ToastyPigeon/Gemma-3-Starshine-12B | 1154.1 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1141.4 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9384
* **Mean Absolute Cliff's Delta**: 0.8669
* **Combined Separability Score**: 90.26%
* **Positional Bias**: Position 1 (A): 48.4% | Position 2 (B): 51.6%
* **Length Bias**: Win Rate: 54.3% | Avg EV Margin: +7.4%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | claude-opus-4-7 | 1354.7 ± 22.8 |
| 2 | gpt-5.5 | 1338.4 ± 17.6 |
| 3 | moonshotai/Kimi-K2.5 | 1320.0 ± 18.5 |
| 4 | gpt-5.4 | 1319.5 ± 14.7 |
| 5 | claude-opus-4-6 | 1313.8 ± 17.1 |
| 6 | grok-4.20-beta | 1277.2 ± 19.5 |
| 7 | moonshotai/Kimi-K2-Instruct | 1268.2 ± 7.1 |
| 8 | moonshotai/Kimi-K2.6 | 1265.5 ± 7.9 |
| 9 | moonshotai/Kimi-K2-Thinking | 1262.6 ± 24.1 |
| 10 | gpt-5-2025-08-07 | 1262.4 ± 13.8 |
| 11 | o3 | 1260.5 ± 24.8 |
| 12 | gemini-3-pro-preview | 1258.6 ± 6.7 |
| 13 | openrouter/horizon-alpha | 1255.4 ± 11.0 |
| 14 | openrouter/horizon-beta | 1254.7 ± 13.9 |
| 15 | Qwen/Qwen3.5-397B-A17B | 1252.1 ± 13.0 |
| 16 | deepseek-ai/DeepSeek-V3.2 | 1249.5 ± 6.9 |
| 17 | claude-sonnet-4-6 | 1249.3 ± 5.7 |
| 18 | gpt-5.2 | 1247.8 ± 13.1 |
| 19 | deepseek-ai/DeepSeek-V4-Flash | 1247.6 ± 9.1 |
| 20 | google/gemma-4-31B-it | 1246.9 ± 6.5 |
| 21 | grok-4.1-fast | 1245.8 ± 30.2 |
| 22 | openrouter/sherlock-dash-alpha | 1245.2 ± 14.7 |
| 23 | gpt-5.4-mini | 1242.2 ± 10.7 |
| 24 | gemini-3.1-pro-preview | 1241.8 ± 28.5 |
| 25 | claude-opus-4-5-20251101 | 1241.6 ± 7.6 |
| 26 | zai-org/GLM-5.1 | 1239.9 ± 19.2 |
| 27 | zai-org/GLM-4.7 | 1238.3 ± 11.4 |
| 28 | deepseek-ai/DeepSeek-V3.1 | 1235.5 ± 9.1 |
| 29 | deepseek-ai/DeepSeek-V4-Pro | 1233.2 ± 9.8 |
| 30 | google/gemma-4-26B-A4B-it | 1233.2 ± 10.1 |
| 31 | deepseek-ai/DeepSeek-R1 | 1231.9 ± 9.8 |
| 32 | claude-sonnet-4.5 | 1230.8 ± 16.4 |
| 33 | claude-opus-4 | 1230.0 ± 4.0 |
| 34 | qwen/qwen3-235b-a22b:thinking | 1224.7 ± 13.5 |
| 35 | gemini-2.5-pro-preview-06-05 | 1223.5 ± 5.9 |
| 36 | hunter-alpha | 1221.5 ± 8.5 |
| 37 | gpt-5-mini-2025-08-07 | 1220.1 ± 10.2 |
| 38 | NousResearch/Hermes-4-405B | 1219.1 ± 9.7 |
| 39 | gemini-2.5-pro-exp-03-25 | 1218.3 ± 6.4 |
| 40 | zai-org/GLM-5 | 1217.6 ± 14.2 |
| 41 | openrouter/pony-alpha | 1217.3 ± 9.9 |
| 42 | deepseek-ai/DeepSeek-R1-0528 | 1216.8 ± 9.1 |
| 43 | zai-org/GLM-4.6 | 1215.5 ± 19.4 |
| 44 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1215.3 ± 10.3 |
| 45 | chatgpt-4o-latest-2025-03-27 | 1212.5 ± 9.7 |
| 46 | zai-org/GLM-4.5 | 1211.0 ± 5.7 |
| 47 | gpt-5.3-chat | 1210.2 ± 17.1 |
| 48 | mistral-medium-3.1 | 1207.1 ± 9.5 |
| 49 | deepseek-ai/DeepSeek-V3-0324 | 1206.6 ± 5.9 |
| 50 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1204.4 ± 12.7 |
| 51 | claude-3-5-sonnet-20241022 | 1202.6 ± 9.3 |
| 52 | minimax/minimax-m2.5 | 1201.7 ± 11.2 |
| 53 | claude-3-7-sonnet-20250219 | 1200.4 ± 12.2 |
| 54 | claude-sonnet-4 | 1196.9 ± 8.5 |
| 55 | mistral-small-creative | 1196.5 ± 8.2 |
| 56 | zai-org/GLM-4.7-Flash | 1193.7 ± 9.9 |
| 57 | optimus-alpha | 1193.2 ± 3.8 |
| 58 | grok-3-beta | 1191.4 ± 8.0 |
| 59 | quasar-alpha | 1191.4 ± 6.6 |
| 60 | qwen/qwq-32b | 1190.1 ± 17.3 |
| 61 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1189.2 ± 1.6 |
| 62 | sam-paech/Darkest-muse-v1 | 1188.8 ± 9.5 |
| 63 | ifable/gemma-2-Ifable-9B | 1186.1 ± 10.0 |
| 64 | RekaAI/reka-flash-3 | 1184.6 ± 12.3 |
| 65 | chatgpt-4o-latest-2025-01-29 | 1184.4 ± 17.3 |
| 66 | google/gemma-3-27b-it | 1182.7 ± 13.7 |
| 67 | deepseek-ai/DeepSeek-V3.2-Speciale | 1182.1 ± 14.3 |
| 68 | google/gemma-3-4b-it | 1180.7 ± 10.7 |
| 69 | gpt-5-nano-2025-08-07 | 1180.0 ± 11.9 |
| 70 | openai/gpt-oss-120b | 1179.5 ± 6.1 |
| 71 | google/gemma-3-12b-it | 1179.5 ± 6.7 |
| 72 | gpt-4.5-preview | 1179.0 ± 7.4 |
| 73 | gemini-2.5-flash-preview | 1177.5 ± 14.2 |
| 74 | anthropic/claude-3.5-haiku-20241022 | 1176.2 ± 14.7 |
| 75 | CohereForAI/c4ai-command-a-03-2025 | 1167.9 ± 5.3 |
| 76 | gemini-2.0-flash-001 | 1167.6 ± 10.9 |
| 77 | allura-org/Gemma-3-Glitter-12B | 1167.4 ± 12.1 |
| 78 | gpt-4.1-mini | 1164.6 ± 9.6 |
| 79 | THUDM/GLM-4-32B-0414 | 1159.6 ± 9.8 |
| 80 | google/gemma-2-9b-it | 1158.4 ± 13.3 |
| 81 | gpt-4.1-nano | 1152.9 ± 5.2 |
| 82 | meta-llama/llama-3.1-405b-instruct | 1144.3 ± 5.7 |
| 83 | gpt-4o-mini | 1143.8 ± 15.5 |
| 84 | openai/gpt-oss-20b | 1141.9 ± 8.9 |
| 85 | mistralai/mistral-large-2411 | 1140.4 ± 20.4 |
| 86 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1136.9 ± 12.7 |
| 87 | mistralai/Mistral-Nemo-Instruct-2407 | 1134.4 ± 11.9 |
| 88 | mistralai/Pixtral-Large-Instruct-2411 | 1133.5 ± 10.2 |
| 89 | meta-llama/llama-3.1-70b-instruct | 1133.1 ± 14.2 |
| 90 | ToastyPigeon/Gemma-3-Starshine-12B | 1130.9 ± 10.3 |
| 91 | liquid/lfm-7b | 1125.8 ± 8.1 |
| 92 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1116.7 ± 13.0 |
| 93 | meta-llama/llama-3.1-8b-instruct | 1114.0 ± 5.1 |
| 94 | openai/gpt-4-0314 | 1113.7 ± 12.8 |
| 95 | openrouter/cypher-alpha | 1113.2 ± 24.4 |
| 96 | anthropic/claude-3-haiku | 1105.3 ± 8.8 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1102.0 ± 20.6 |
| 98 | openai/gpt-3.5-turbo-0613 | 1094.9 ± 4.7 |
| 99 | mistralai/Mistral-Small-24B-Instruct-2501 | 1085.5 ± 13.8 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1074.1 ± 10.6 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1014.0 ± 26.9 |
