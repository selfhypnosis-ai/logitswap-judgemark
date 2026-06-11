# Detailed Results: AxionML/Qwen3.5-9B-NVFP4

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.6151
* **Mean Absolute Cliff's Delta**: 0.5961
* **Combined Separability Score**: 60.56%
* **Positional Bias**: Position 1 (A): 62.7% | Position 2 (B): 37.3%
* **Length Bias**: Win Rate: 52.7% | Avg EV Margin: +2.4%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | o3 | 1213.3 |
| 2 | moonshotai/Kimi-K2.5 | 1212.8 |
| 3 | openrouter/sherlock-dash-alpha | 1211.7 |
| 4 | moonshotai/Kimi-K2.6 | 1210.4 |
| 5 | deepseek-ai/DeepSeek-R1 | 1209.8 |
| 6 | moonshotai/Kimi-K2-Instruct | 1208.8 |
| 7 | claude-sonnet-4-6 | 1208.2 |
| 8 | gemini-3.1-pro-preview | 1207.8 |
| 9 | gpt-5.5 | 1207.7 |
| 10 | gpt-5.3-chat | 1207.5 |
| 11 | zai-org/GLM-5.1 | 1207.5 |
| 12 | google/gemma-4-31B-it | 1207.3 |
| 13 | claude-opus-4-5-20251101 | 1207.3 |
| 14 | claude-opus-4 | 1207.3 |
| 15 | mistral-small-creative | 1207.2 |
| 16 | deepseek-ai/DeepSeek-V3.1 | 1207.2 |
| 17 | grok-4.20-beta | 1207.0 |
| 18 | gpt-5.4-mini | 1206.8 |
| 19 | claude-opus-4-6 | 1206.7 |
| 20 | moonshotai/Kimi-K2-Thinking | 1206.2 |
| 21 | gpt-5.4 | 1206.2 |
| 22 | claude-3-5-sonnet-20241022 | 1206.0 |
| 23 | claude-sonnet-4.5 | 1206.0 |
| 24 | claude-opus-4-7 | 1206.0 |
| 25 | deepseek-ai/DeepSeek-V3-0324 | 1205.9 |
| 26 | grok-4.1-fast | 1205.8 |
| 27 | deepseek-ai/DeepSeek-V4-Flash | 1205.8 |
| 28 | gpt-5-mini-2025-08-07 | 1205.6 |
| 29 | openrouter/horizon-alpha | 1205.6 |
| 30 | deepseek-ai/DeepSeek-V3.2 | 1205.4 |
| 31 | qwen/qwen3-235b-a22b:thinking | 1205.2 |
| 32 | zai-org/GLM-5 | 1205.0 |
| 33 | mistral-medium-3.1 | 1205.0 |
| 34 | deepseek-ai/DeepSeek-V4-Pro | 1204.9 |
| 35 | hunter-alpha | 1204.7 |
| 36 | chatgpt-4o-latest-2025-03-27 | 1204.5 |
| 37 | RekaAI/reka-flash-3 | 1204.4 |
| 38 | gemini-3-pro-preview | 1204.3 |
| 39 | gpt-5.2 | 1204.0 |
| 40 | gpt-5-2025-08-07 | 1203.6 |
| 41 | gemini-2.5-pro-preview-06-05 | 1203.4 |
| 42 | deepseek-ai/DeepSeek-R1-0528 | 1203.4 |
| 43 | optimus-alpha | 1203.3 |
| 44 | Qwen/Qwen3.5-397B-A17B | 1203.2 |
| 45 | claude-3-7-sonnet-20250219 | 1203.2 |
| 46 | NousResearch/Hermes-4-405B | 1203.0 |
| 47 | zai-org/GLM-4.7 | 1202.9 |
| 48 | zai-org/GLM-4.6 | 1202.7 |
| 49 | gemini-2.5-pro-exp-03-25 | 1202.6 |
| 50 | openrouter/horizon-beta | 1202.5 |
| 51 | chatgpt-4o-latest-2025-01-29 | 1202.4 |
| 52 | zai-org/GLM-4.7-Flash | 1202.2 |
| 53 | quasar-alpha | 1202.1 |
| 54 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1202.1 |
| 55 | qwen/qwq-32b | 1202.0 |
| 56 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1201.6 |
| 57 | claude-sonnet-4 | 1201.6 |
| 58 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1201.5 |
| 59 | gpt-4.1-mini | 1201.4 |
| 60 | minimax/minimax-m2.5 | 1200.9 |
| 61 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.7 |
| 62 | openrouter/pony-alpha | 1200.4 |
| 63 | zai-org/GLM-4.5 | 1199.9 |
| 64 | anthropic/claude-3.5-haiku-20241022 | 1199.9 |
| 65 | gemini-2.5-flash-preview | 1199.3 |
| 66 | google/gemma-4-26B-A4B-it | 1199.1 |
| 67 | gemini-2.0-flash-001 | 1199.1 |
| 68 | gpt-4.5-preview | 1198.6 |
| 69 | google/gemma-3-27b-it | 1198.1 |
| 70 | meta-llama/llama-3.1-405b-instruct | 1198.0 |
| 71 | google/gemma-3-4b-it | 1197.5 |
| 72 | ifable/gemma-2-Ifable-9B | 1197.5 |
| 73 | grok-3-beta | 1197.4 |
| 74 | gpt-5-nano-2025-08-07 | 1196.3 |
| 75 | google/gemma-3-12b-it | 1196.1 |
| 76 | CohereForAI/c4ai-command-a-03-2025 | 1195.8 |
| 77 | sam-paech/Darkest-muse-v1 | 1195.5 |
| 78 | meta-llama/llama-3.1-70b-instruct | 1194.2 |
| 79 | allura-org/Gemma-3-Glitter-12B | 1194.0 |
| 80 | gpt-4.1-nano | 1193.6 |
| 81 | openai/gpt-oss-120b | 1193.0 |
| 82 | meta-llama/llama-3.1-8b-instruct | 1192.9 |
| 83 | THUDM/GLM-4-32B-0414 | 1191.4 |
| 84 | gpt-4o-mini | 1190.9 |
| 85 | mistralai/mistral-large-2411 | 1190.7 |
| 86 | liquid/lfm-7b | 1190.4 |
| 87 | mistralai/Pixtral-Large-Instruct-2411 | 1190.1 |
| 88 | google/gemma-2-9b-it | 1190.0 |
| 89 | anthropic/claude-3-haiku | 1189.6 |
| 90 | openai/gpt-4-0314 | 1188.0 |
| 91 | ToastyPigeon/Gemma-3-Starshine-12B | 1187.0 |
| 92 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1186.6 |
| 93 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1186.5 |
| 94 | meta-llama/llama-3.2-3b-instruct | 1185.6 |
| 95 | openrouter/cypher-alpha | 1185.5 |
| 96 | mistralai/Mistral-Nemo-Instruct-2407 | 1184.6 |
| 97 | openai/gpt-3.5-turbo-0613 | 1184.4 |
| 98 | openai/gpt-oss-20b | 1182.3 |
| 99 | mistralai/Mistral-Small-24B-Instruct-2501 | 1182.1 |
| 100 | meta-llama/llama-3.2-1b-instruct | 1179.5 |
| 101 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1177.4 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.8438
* **Mean Absolute Cliff's Delta**: 0.7743
* **Combined Separability Score**: 80.90%
* **Positional Bias**: Position 1 (A): 65.0% | Position 2 (B): 35.0%
* **Length Bias**: Win Rate: 53.6% | Avg EV Margin: +2.0%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | o3 | 1232.6 ± 16.7 |
| 2 | gpt-5.4 | 1226.0 ± 8.3 |
| 3 | gpt-5.5 | 1222.9 ± 7.8 |
| 4 | claude-opus-4-7 | 1222.7 ± 9.1 |
| 5 | grok-4.20-beta | 1222.0 ± 8.2 |
| 6 | moonshotai/Kimi-K2.6 | 1219.7 ± 4.9 |
| 7 | deepseek-ai/DeepSeek-R1 | 1219.2 ± 7.7 |
| 8 | gpt-5.4-mini | 1219.2 ± 8.9 |
| 9 | moonshotai/Kimi-K2-Thinking | 1218.7 ± 5.8 |
| 10 | qwen/qwen3-235b-a22b:thinking | 1218.6 ± 4.0 |
| 11 | moonshotai/Kimi-K2-Instruct | 1218.4 ± 11.8 |
| 12 | grok-4.1-fast | 1218.0 ± 5.3 |
| 13 | moonshotai/Kimi-K2.5 | 1218.0 ± 3.6 |
| 14 | openrouter/sherlock-dash-alpha | 1217.7 ± 6.0 |
| 15 | gpt-5.2 | 1217.0 ± 4.5 |
| 16 | claude-opus-4-6 | 1216.0 ± 5.8 |
| 17 | gemini-3.1-pro-preview | 1215.9 ± 5.9 |
| 18 | openrouter/horizon-alpha | 1215.2 ± 5.5 |
| 19 | gpt-5.3-chat | 1214.7 ± 5.3 |
| 20 | zai-org/GLM-5 | 1213.9 ± 4.9 |
| 21 | deepseek-ai/DeepSeek-V3-0324 | 1213.1 ± 3.0 |
| 22 | gemini-3-pro-preview | 1212.8 ± 8.8 |
| 23 | deepseek-ai/DeepSeek-V3.2 | 1212.4 ± 6.2 |
| 24 | zai-org/GLM-4.6 | 1212.2 ± 8.9 |
| 25 | claude-opus-4-5-20251101 | 1212.1 ± 6.7 |
| 26 | openrouter/pony-alpha | 1212.0 ± 6.4 |
| 27 | gpt-5-mini-2025-08-07 | 1212.0 ± 7.4 |
| 28 | deepseek-ai/DeepSeek-V3.1 | 1211.9 ± 6.7 |
| 29 | gpt-5-2025-08-07 | 1211.9 ± 10.5 |
| 30 | claude-sonnet-4.5 | 1211.8 ± 7.5 |
| 31 | claude-opus-4 | 1211.1 ± 3.0 |
| 32 | hunter-alpha | 1210.7 ± 4.9 |
| 33 | zai-org/GLM-5.1 | 1210.4 ± 5.8 |
| 34 | claude-sonnet-4-6 | 1208.9 ± 3.9 |
| 35 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1208.9 ± 3.4 |
| 36 | deepseek-ai/DeepSeek-V4-Flash | 1207.9 ± 6.3 |
| 37 | mistral-medium-3.1 | 1207.9 ± 4.6 |
| 38 | google/gemma-4-31B-it | 1207.3 ± 4.9 |
| 39 | chatgpt-4o-latest-2025-03-27 | 1206.9 ± 7.7 |
| 40 | openrouter/horizon-beta | 1206.9 ± 3.8 |
| 41 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1205.9 ± 9.2 |
| 42 | RekaAI/reka-flash-3 | 1205.9 ± 8.2 |
| 43 | optimus-alpha | 1205.9 ± 4.0 |
| 44 | claude-3-7-sonnet-20250219 | 1205.6 ± 8.5 |
| 45 | NousResearch/Hermes-4-405B | 1205.5 ± 4.0 |
| 46 | deepseek-ai/DeepSeek-V4-Pro | 1204.9 ± 6.6 |
| 47 | deepseek-ai/DeepSeek-R1-0528 | 1204.8 ± 5.6 |
| 48 | quasar-alpha | 1204.7 ± 6.1 |
| 49 | gemini-2.5-pro-exp-03-25 | 1204.4 ± 4.4 |
| 50 | mistral-small-creative | 1204.2 ± 1.8 |
| 51 | zai-org/GLM-4.7 | 1203.2 ± 7.9 |
| 52 | claude-3-5-sonnet-20241022 | 1203.2 ± 4.8 |
| 53 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1202.7 ± 3.4 |
| 54 | gemini-2.5-pro-preview-06-05 | 1202.6 ± 3.6 |
| 55 | minimax/minimax-m2.5 | 1202.4 ± 4.3 |
| 56 | Qwen/Qwen3.5-397B-A17B | 1201.8 ± 3.5 |
| 57 | zai-org/GLM-4.5 | 1201.7 ± 5.3 |
| 58 | google/gemma-4-26B-A4B-it | 1201.5 ± 3.4 |
| 59 | chatgpt-4o-latest-2025-01-29 | 1199.8 ± 2.2 |
| 60 | CohereForAI/c4ai-command-a-03-2025 | 1198.7 ± 2.9 |
| 61 | gpt-4.1-mini | 1198.1 ± 2.7 |
| 62 | claude-sonnet-4 | 1197.9 ± 2.9 |
| 63 | grok-3-beta | 1197.6 ± 4.7 |
| 64 | zai-org/GLM-4.7-Flash | 1197.1 ± 2.6 |
| 65 | qwen/qwq-32b | 1197.1 ± 3.2 |
| 66 | gpt-4.5-preview | 1197.0 ± 4.9 |
| 67 | deepseek-ai/DeepSeek-V3.2-Speciale | 1196.5 ± 3.6 |
| 68 | anthropic/claude-3.5-haiku-20241022 | 1196.4 ± 7.3 |
| 69 | google/gemma-3-27b-it | 1196.1 ± 6.0 |
| 70 | gpt-5-nano-2025-08-07 | 1195.9 ± 4.0 |
| 71 | sam-paech/Darkest-muse-v1 | 1195.4 ± 7.2 |
| 72 | openai/gpt-oss-120b | 1194.6 ± 3.4 |
| 73 | ifable/gemma-2-Ifable-9B | 1193.9 ± 4.6 |
| 74 | gemini-2.0-flash-001 | 1193.8 ± 8.9 |
| 75 | allura-org/Gemma-3-Glitter-12B | 1193.1 ± 3.5 |
| 76 | gemini-2.5-flash-preview | 1192.5 ± 6.6 |
| 77 | google/gemma-3-12b-it | 1192.4 ± 3.2 |
| 78 | google/gemma-3-4b-it | 1192.0 ± 3.4 |
| 79 | THUDM/GLM-4-32B-0414 | 1189.0 ± 3.1 |
| 80 | gpt-4.1-nano | 1187.9 ± 3.8 |
| 81 | anthropic/claude-3-haiku | 1185.9 ± 4.5 |
| 82 | mistralai/mistral-large-2411 | 1185.0 ± 7.3 |
| 83 | ToastyPigeon/Gemma-3-Starshine-12B | 1183.7 ± 4.7 |
| 84 | gpt-4o-mini | 1183.2 ± 4.0 |
| 85 | google/gemma-2-9b-it | 1183.2 ± 3.1 |
| 86 | meta-llama/llama-3.1-405b-instruct | 1181.9 ± 8.3 |
| 87 | mistralai/Pixtral-Large-Instruct-2411 | 1180.9 ± 4.2 |
| 88 | liquid/lfm-7b | 1179.5 ± 5.4 |
| 89 | openai/gpt-4-0314 | 1178.7 ± 5.0 |
| 90 | openai/gpt-oss-20b | 1176.6 ± 6.7 |
| 91 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1176.6 ± 2.7 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1176.6 ± 5.8 |
| 93 | meta-llama/llama-3.1-70b-instruct | 1175.0 ± 8.8 |
| 94 | openrouter/cypher-alpha | 1174.8 ± 6.2 |
| 95 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1164.8 ± 4.4 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1163.6 ± 9.4 |
| 97 | meta-llama/llama-3.1-8b-instruct | 1163.6 ± 8.2 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1162.5 ± 8.1 |
| 99 | openai/gpt-3.5-turbo-0613 | 1161.1 ± 4.1 |
| 100 | meta-llama/llama-3.2-3b-instruct | 1151.7 ± 14.7 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1151.7 ± 9.3 |
