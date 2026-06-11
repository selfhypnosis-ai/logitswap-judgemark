# Detailed Results: google/gemma-4-12B-it-qat-w4a16-ct

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7411
* **Mean Absolute Cliff's Delta**: 0.6831
* **Combined Separability Score**: 71.21%
* **Positional Bias**: Position 1 (A): 24.0% | Position 2 (B): 76.0%
* **Length Bias**: Win Rate: 56.7% | Avg EV Margin: +8.6%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1237.9 |
| 2 | claude-opus-4-7 | 1236.8 |
| 3 | claude-opus-4-6 | 1232.6 |
| 4 | moonshotai/Kimi-K2.6 | 1229.2 |
| 5 | moonshotai/Kimi-K2-Thinking | 1225.8 |
| 6 | claude-sonnet-4-6 | 1225.1 |
| 7 | moonshotai/Kimi-K2-Instruct | 1224.3 |
| 8 | gpt-5.4 | 1223.5 |
| 9 | Qwen/Qwen3.5-397B-A17B | 1223.4 |
| 10 | gpt-5.5 | 1222.9 |
| 11 | zai-org/GLM-5.1 | 1221.4 |
| 12 | o3 | 1221.2 |
| 13 | gemini-3-pro-preview | 1220.5 |
| 14 | deepseek-ai/DeepSeek-R1 | 1220.0 |
| 15 | deepseek-ai/DeepSeek-V4-Pro | 1219.0 |
| 16 | gemini-3.1-pro-preview | 1217.8 |
| 17 | openrouter/sherlock-dash-alpha | 1217.7 |
| 18 | openrouter/horizon-alpha | 1217.5 |
| 19 | google/gemma-4-31B-it | 1217.4 |
| 20 | deepseek-ai/DeepSeek-V3.2 | 1216.8 |
| 21 | deepseek-ai/DeepSeek-V4-Flash | 1215.8 |
| 22 | gpt-5-2025-08-07 | 1215.2 |
| 23 | grok-4.1-fast | 1214.8 |
| 24 | deepseek-ai/DeepSeek-V3.1 | 1214.5 |
| 25 | claude-opus-4-5-20251101 | 1214.2 |
| 26 | claude-opus-4 | 1214.1 |
| 27 | zai-org/GLM-4.6 | 1213.9 |
| 28 | openrouter/horizon-beta | 1213.8 |
| 29 | gpt-5.4-mini | 1213.1 |
| 30 | zai-org/GLM-5 | 1213.1 |
| 31 | zai-org/GLM-4.7 | 1212.9 |
| 32 | gemini-2.5-pro-preview-06-05 | 1212.7 |
| 33 | openrouter/pony-alpha | 1212.2 |
| 34 | qwen/qwen3-235b-a22b:thinking | 1212.1 |
| 35 | grok-4.20-beta | 1212.0 |
| 36 | hunter-alpha | 1211.9 |
| 37 | claude-sonnet-4.5 | 1211.8 |
| 38 | gpt-5.2 | 1211.7 |
| 39 | google/gemma-4-26B-A4B-it | 1211.6 |
| 40 | deepseek-ai/DeepSeek-R1-0528 | 1211.3 |
| 41 | gpt-5-mini-2025-08-07 | 1211.1 |
| 42 | mistral-medium-3.1 | 1210.4 |
| 43 | gpt-5.3-chat | 1208.4 |
| 44 | NousResearch/Hermes-4-405B | 1208.2 |
| 45 | chatgpt-4o-latest-2025-03-27 | 1207.4 |
| 46 | deepseek-ai/DeepSeek-V3-0324 | 1205.7 |
| 47 | zai-org/GLM-4.5 | 1205.5 |
| 48 | optimus-alpha | 1204.3 |
| 49 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1204.3 |
| 50 | claude-3-5-sonnet-20241022 | 1202.9 |
| 51 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1201.3 |
| 52 | RekaAI/reka-flash-3 | 1201.3 |
| 53 | mistral-small-creative | 1201.2 |
| 54 | claude-sonnet-4 | 1201.1 |
| 55 | ifable/gemma-2-Ifable-9B | 1200.4 |
| 56 | minimax/minimax-m2.5 | 1200.4 |
| 57 | gemini-2.5-pro-exp-03-25 | 1199.7 |
| 58 | chatgpt-4o-latest-2025-01-29 | 1199.0 |
| 59 | claude-3-7-sonnet-20250219 | 1199.0 |
| 60 | quasar-alpha | 1198.7 |
| 61 | anthropic/claude-3.5-haiku-20241022 | 1198.3 |
| 62 | zai-org/GLM-4.7-Flash | 1197.8 |
| 63 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1196.6 |
| 64 | qwen/qwq-32b | 1196.4 |
| 65 | gpt-4.1-mini | 1195.6 |
| 66 | deepseek-ai/DeepSeek-V3.2-Speciale | 1193.7 |
| 67 | gpt-4.5-preview | 1193.4 |
| 68 | grok-3-beta | 1191.6 |
| 69 | google/gemma-3-27b-it | 1191.2 |
| 70 | google/gemma-3-12b-it | 1190.2 |
| 71 | sam-paech/Darkest-muse-v1 | 1189.9 |
| 72 | google/gemma-3-4b-it | 1189.5 |
| 73 | gpt-5-nano-2025-08-07 | 1189.2 |
| 74 | gemini-2.5-flash-preview | 1189.1 |
| 75 | CohereForAI/c4ai-command-a-03-2025 | 1187.9 |
| 76 | gemini-2.0-flash-001 | 1187.7 |
| 77 | openai/gpt-oss-120b | 1186.6 |
| 78 | allura-org/Gemma-3-Glitter-12B | 1182.4 |
| 79 | meta-llama/llama-3.1-405b-instruct | 1182.1 |
| 80 | google/gemma-2-9b-it | 1180.3 |
| 81 | THUDM/GLM-4-32B-0414 | 1179.3 |
| 82 | liquid/lfm-7b | 1178.0 |
| 83 | gpt-4.1-nano | 1177.5 |
| 84 | meta-llama/llama-3.1-70b-instruct | 1177.4 |
| 85 | mistralai/mistral-large-2411 | 1177.2 |
| 86 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1175.9 |
| 87 | gpt-4o-mini | 1174.5 |
| 88 | mistralai/Mistral-Nemo-Instruct-2407 | 1174.0 |
| 89 | mistralai/Pixtral-Large-Instruct-2411 | 1173.9 |
| 90 | meta-llama/llama-3.1-8b-instruct | 1173.4 |
| 91 | openai/gpt-oss-20b | 1171.7 |
| 92 | openai/gpt-4-0314 | 1171.6 |
| 93 | openrouter/cypher-alpha | 1169.5 |
| 94 | ToastyPigeon/Gemma-3-Starshine-12B | 1168.3 |
| 95 | anthropic/claude-3-haiku | 1168.2 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1167.2 |
| 97 | openai/gpt-3.5-turbo-0613 | 1167.1 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1166.1 |
| 99 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1165.0 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1164.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1146.1 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9405
* **Mean Absolute Cliff's Delta**: 0.8612
* **Combined Separability Score**: 90.09%
* **Positional Bias**: Position 1 (A): 20.6% | Position 2 (B): 79.4%
* **Length Bias**: Win Rate: 54.7% | Avg EV Margin: +5.5%

#### Option B: Leaderboard (Across 10 Bootstraps)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1289.3 ± 9.0 |
| 2 | claude-opus-4-7 | 1287.2 ± 12.7 |
| 3 | claude-opus-4-6 | 1277.0 ± 14.9 |
| 4 | moonshotai/Kimi-K2-Thinking | 1269.6 ± 15.1 |
| 5 | moonshotai/Kimi-K2.6 | 1262.3 ± 16.3 |
| 6 | gpt-5.4 | 1258.9 ± 16.3 |
| 7 | gpt-5.5 | 1258.2 ± 7.4 |
| 8 | o3 | 1253.4 ± 9.8 |
| 9 | openrouter/horizon-alpha | 1249.5 ± 6.1 |
| 10 | moonshotai/Kimi-K2-Instruct | 1247.1 ± 13.0 |
| 11 | zai-org/GLM-5.1 | 1245.3 ± 7.9 |
| 12 | claude-sonnet-4-6 | 1244.4 ± 8.4 |
| 13 | gpt-5-2025-08-07 | 1242.6 ± 8.8 |
| 14 | gemini-3-pro-preview | 1242.4 ± 10.1 |
| 15 | deepseek-ai/DeepSeek-V4-Pro | 1241.7 ± 11.7 |
| 16 | deepseek-ai/DeepSeek-V3.2 | 1239.6 ± 12.9 |
| 17 | openrouter/horizon-beta | 1237.4 ± 16.9 |
| 18 | gemini-3.1-pro-preview | 1234.7 ± 15.9 |
| 19 | google/gemma-4-31B-it | 1234.3 ± 8.3 |
| 20 | grok-4.1-fast | 1233.3 ± 11.5 |
| 21 | openrouter/sherlock-dash-alpha | 1232.8 ± 12.3 |
| 22 | Qwen/Qwen3.5-397B-A17B | 1231.9 ± 14.6 |
| 23 | claude-opus-4-5-20251101 | 1229.4 ± 3.8 |
| 24 | deepseek-ai/DeepSeek-V3.1 | 1228.9 ± 4.7 |
| 25 | gpt-5.2 | 1228.9 ± 5.7 |
| 26 | gpt-5.4-mini | 1226.3 ± 5.8 |
| 27 | grok-4.20-beta | 1226.2 ± 11.1 |
| 28 | deepseek-ai/DeepSeek-V4-Flash | 1226.0 ± 4.1 |
| 29 | hunter-alpha | 1225.8 ± 3.2 |
| 30 | zai-org/GLM-5 | 1225.7 ± 8.1 |
| 31 | deepseek-ai/DeepSeek-R1 | 1225.5 ± 5.6 |
| 32 | claude-sonnet-4.5 | 1224.3 ± 6.3 |
| 33 | claude-opus-4 | 1223.6 ± 9.2 |
| 34 | gemini-2.5-pro-preview-06-05 | 1222.7 ± 7.3 |
| 35 | google/gemma-4-26B-A4B-it | 1221.2 ± 13.1 |
| 36 | zai-org/GLM-4.7 | 1220.7 ± 11.1 |
| 37 | zai-org/GLM-4.6 | 1220.4 ± 6.5 |
| 38 | qwen/qwen3-235b-a22b:thinking | 1217.2 ± 9.9 |
| 39 | deepseek-ai/DeepSeek-R1-0528 | 1215.6 ± 10.2 |
| 40 | gpt-5-mini-2025-08-07 | 1215.3 ± 9.9 |
| 41 | openrouter/pony-alpha | 1214.6 ± 7.0 |
| 42 | mistral-medium-3.1 | 1213.4 ± 3.1 |
| 43 | NousResearch/Hermes-4-405B | 1212.7 ± 8.3 |
| 44 | gemini-2.5-pro-exp-03-25 | 1211.7 ± 7.8 |
| 45 | gpt-5.3-chat | 1210.8 ± 10.5 |
| 46 | chatgpt-4o-latest-2025-03-27 | 1210.2 ± 9.0 |
| 47 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1209.3 ± 5.0 |
| 48 | claude-sonnet-4 | 1206.3 ± 6.9 |
| 49 | optimus-alpha | 1205.1 ± 6.4 |
| 50 | claude-3-5-sonnet-20241022 | 1205.1 ± 5.3 |
| 51 | claude-3-7-sonnet-20250219 | 1204.9 ± 5.1 |
| 52 | zai-org/GLM-4.5 | 1203.2 ± 6.8 |
| 53 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1203.2 ± 9.5 |
| 54 | deepseek-ai/DeepSeek-V3-0324 | 1201.0 ± 6.3 |
| 55 | mistral-small-creative | 1200.6 ± 7.1 |
| 56 | RekaAI/reka-flash-3 | 1198.6 ± 13.2 |
| 57 | minimax/minimax-m2.5 | 1198.6 ± 7.2 |
| 58 | quasar-alpha | 1197.4 ± 9.9 |
| 59 | zai-org/GLM-4.7-Flash | 1196.2 ± 10.4 |
| 60 | qwen/qwq-32b | 1195.1 ± 3.3 |
| 61 | grok-3-beta | 1194.6 ± 7.7 |
| 62 | ifable/gemma-2-Ifable-9B | 1193.7 ± 8.7 |
| 63 | gpt-4.1-mini | 1191.0 ± 9.1 |
| 64 | openai/gpt-oss-120b | 1190.7 ± 6.7 |
| 65 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1190.2 ± 8.4 |
| 66 | gpt-4.5-preview | 1188.2 ± 2.8 |
| 67 | deepseek-ai/DeepSeek-V3.2-Speciale | 1186.4 ± 10.1 |
| 68 | chatgpt-4o-latest-2025-01-29 | 1185.9 ± 5.0 |
| 69 | sam-paech/Darkest-muse-v1 | 1185.5 ± 8.6 |
| 70 | google/gemma-3-27b-it | 1184.8 ± 5.4 |
| 71 | gemini-2.5-flash-preview | 1184.3 ± 8.4 |
| 72 | gpt-5-nano-2025-08-07 | 1184.0 ± 9.4 |
| 73 | allura-org/Gemma-3-Glitter-12B | 1182.9 ± 4.0 |
| 74 | google/gemma-3-12b-it | 1181.9 ± 9.8 |
| 75 | google/gemma-3-4b-it | 1180.9 ± 4.8 |
| 76 | CohereForAI/c4ai-command-a-03-2025 | 1179.9 ± 7.8 |
| 77 | gemini-2.0-flash-001 | 1179.2 ± 10.7 |
| 78 | anthropic/claude-3.5-haiku-20241022 | 1177.2 ± 13.7 |
| 79 | THUDM/GLM-4-32B-0414 | 1172.3 ± 11.1 |
| 80 | google/gemma-2-9b-it | 1166.7 ± 10.2 |
| 81 | gpt-4.1-nano | 1158.8 ± 9.1 |
| 82 | mistralai/Pixtral-Large-Instruct-2411 | 1157.9 ± 5.7 |
| 83 | meta-llama/llama-3.1-405b-instruct | 1157.7 ± 7.1 |
| 84 | gpt-4o-mini | 1155.9 ± 5.8 |
| 85 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1152.6 ± 8.8 |
| 86 | openai/gpt-oss-20b | 1152.4 ± 3.6 |
| 87 | mistralai/mistral-large-2411 | 1149.6 ± 12.8 |
| 88 | liquid/lfm-7b | 1148.3 ± 6.7 |
| 89 | openai/gpt-4-0314 | 1147.2 ± 7.7 |
| 90 | mistralai/Mistral-Nemo-Instruct-2407 | 1146.1 ± 6.3 |
| 91 | meta-llama/llama-3.1-70b-instruct | 1143.8 ± 7.5 |
| 92 | ToastyPigeon/Gemma-3-Starshine-12B | 1143.7 ± 14.7 |
| 93 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1140.9 ± 8.4 |
| 94 | openrouter/cypher-alpha | 1140.5 ± 10.1 |
| 95 | anthropic/claude-3-haiku | 1137.2 ± 5.8 |
| 96 | meta-llama/llama-3.1-8b-instruct | 1135.5 ± 5.9 |
| 97 | mistralai/Mistral-Small-24B-Instruct-2501 | 1133.3 ± 10.7 |
| 98 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1129.7 ± 12.8 |
| 99 | openai/gpt-3.5-turbo-0613 | 1119.1 ± 12.4 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1098.3 ± 11.2 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1036.8 ± 5.1 |
