# Detailed Results: RedHatAI/Qwen3.5-9B-FP8-dynamic

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.7541
* **Mean Absolute Cliff's Delta**: 0.7135
* **Combined Separability Score**: 73.38%
* **Positional Bias**: Position 1 (A): 72.2% | Position 2 (B): 27.8%
* **Length Bias**: Win Rate: 57.0% | Avg EV Margin: +4.0%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | moonshotai/Kimi-K2.5 | 1218.7 |
| 2 | o3 | 1217.1 |
| 3 | grok-4.20-beta | 1216.9 |
| 4 | gpt-5.5 | 1214.3 |
| 5 | moonshotai/Kimi-K2-Instruct | 1213.8 |
| 6 | moonshotai/Kimi-K2-Thinking | 1212.5 |
| 7 | claude-opus-4-7 | 1212.0 |
| 8 | gpt-5.4 | 1211.5 |
| 9 | moonshotai/Kimi-K2.6 | 1211.3 |
| 10 | deepseek-ai/DeepSeek-V3.2 | 1210.9 |
| 11 | claude-opus-4-6 | 1210.8 |
| 12 | openrouter/sherlock-dash-alpha | 1210.6 |
| 13 | grok-4.1-fast | 1210.5 |
| 14 | claude-opus-4-5-20251101 | 1208.5 |
| 15 | chatgpt-4o-latest-2025-03-27 | 1208.4 |
| 16 | deepseek-ai/DeepSeek-R1 | 1208.1 |
| 17 | google/gemma-4-31B-it | 1207.5 |
| 18 | deepseek-ai/DeepSeek-V3.1 | 1207.5 |
| 19 | zai-org/GLM-5.1 | 1207.4 |
| 20 | claude-sonnet-4.5 | 1207.4 |
| 21 | claude-opus-4 | 1207.4 |
| 22 | gemini-3.1-pro-preview | 1207.2 |
| 23 | quasar-alpha | 1207.1 |
| 24 | gemini-2.5-pro-preview-06-05 | 1207.0 |
| 25 | deepseek-ai/DeepSeek-V4-Flash | 1206.7 |
| 26 | mistral-medium-3.1 | 1206.6 |
| 27 | Qwen/Qwen3.5-397B-A17B | 1206.6 |
| 28 | deepseek-ai/DeepSeek-V3-0324 | 1206.4 |
| 29 | RekaAI/reka-flash-3 | 1206.4 |
| 30 | openrouter/horizon-alpha | 1205.8 |
| 31 | deepseek-ai/DeepSeek-V4-Pro | 1205.8 |
| 32 | hunter-alpha | 1205.7 |
| 33 | gpt-5-2025-08-07 | 1205.4 |
| 34 | claude-3-5-sonnet-20241022 | 1205.2 |
| 35 | gpt-5.2 | 1205.1 |
| 36 | NousResearch/Hermes-4-405B | 1205.0 |
| 37 | gemini-3-pro-preview | 1205.0 |
| 38 | zai-org/GLM-5 | 1204.5 |
| 39 | google/gemma-4-26B-A4B-it | 1204.0 |
| 40 | zai-org/GLM-4.7 | 1204.0 |
| 41 | qwen/qwq-32b | 1203.7 |
| 42 | gpt-5.4-mini | 1203.5 |
| 43 | zai-org/GLM-4.6 | 1203.4 |
| 44 | openrouter/horizon-beta | 1203.4 |
| 45 | claude-sonnet-4-6 | 1203.3 |
| 46 | qwen/qwen3-235b-a22b:thinking | 1203.0 |
| 47 | zai-org/GLM-4.5 | 1202.8 |
| 48 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1202.6 |
| 49 | mistral-small-creative | 1202.5 |
| 50 | openrouter/pony-alpha | 1202.5 |
| 51 | claude-3-7-sonnet-20250219 | 1202.3 |
| 52 | gpt-5.3-chat | 1202.2 |
| 53 | claude-sonnet-4 | 1202.1 |
| 54 | optimus-alpha | 1201.7 |
| 55 | minimax/minimax-m2.5 | 1201.1 |
| 56 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1200.9 |
| 57 | deepseek-ai/DeepSeek-R1-0528 | 1200.9 |
| 58 | gemini-2.5-pro-exp-03-25 | 1200.9 |
| 59 | chatgpt-4o-latest-2025-01-29 | 1199.6 |
| 60 | google/gemma-3-27b-it | 1199.4 |
| 61 | gpt-5-mini-2025-08-07 | 1199.4 |
| 62 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1198.8 |
| 63 | grok-3-beta | 1198.7 |
| 64 | CohereForAI/c4ai-command-a-03-2025 | 1198.4 |
| 65 | gpt-4.5-preview | 1198.1 |
| 66 | zai-org/GLM-4.7-Flash | 1197.8 |
| 67 | deepseek-ai/DeepSeek-V3.2-Speciale | 1197.2 |
| 68 | anthropic/claude-3.5-haiku-20241022 | 1196.6 |
| 69 | gpt-4.1-mini | 1196.5 |
| 70 | ifable/gemma-2-Ifable-9B | 1196.1 |
| 71 | google/gemma-3-12b-it | 1195.5 |
| 72 | gemini-2.0-flash-001 | 1194.5 |
| 73 | gpt-5-nano-2025-08-07 | 1194.2 |
| 74 | meta-llama/llama-3.1-405b-instruct | 1194.1 |
| 75 | sam-paech/Darkest-muse-v1 | 1194.1 |
| 76 | google/gemma-3-4b-it | 1193.7 |
| 77 | gemini-2.5-flash-preview | 1193.3 |
| 78 | google/gemma-2-9b-it | 1192.4 |
| 79 | allura-org/Gemma-3-Glitter-12B | 1192.2 |
| 80 | gpt-4.1-nano | 1191.7 |
| 81 | meta-llama/llama-3.1-70b-instruct | 1191.2 |
| 82 | gpt-4o-mini | 1190.8 |
| 83 | openai/gpt-oss-120b | 1190.6 |
| 84 | ToastyPigeon/Gemma-3-Starshine-12B | 1190.0 |
| 85 | mistralai/mistral-large-2411 | 1189.9 |
| 86 | THUDM/GLM-4-32B-0414 | 1189.6 |
| 87 | openai/gpt-4-0314 | 1188.2 |
| 88 | anthropic/claude-3-haiku | 1188.1 |
| 89 | mistralai/Pixtral-Large-Instruct-2411 | 1188.0 |
| 90 | liquid/lfm-7b | 1187.8 |
| 91 | meta-llama/llama-3.1-8b-instruct | 1187.6 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1186.7 |
| 93 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1186.7 |
| 94 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1185.6 |
| 95 | openrouter/cypher-alpha | 1182.4 |
| 96 | openai/gpt-3.5-turbo-0613 | 1181.7 |
| 97 | openai/gpt-oss-20b | 1181.5 |
| 98 | meta-llama/llama-3.2-1b-instruct | 1179.8 |
| 99 | meta-llama/llama-3.2-3b-instruct | 1179.4 |
| 100 | mistralai/Mistral-Small-24B-Instruct-2501 | 1179.2 |
| 101 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1177.8 |

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
