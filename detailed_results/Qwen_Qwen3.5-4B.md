# Detailed Results: Qwen/Qwen3.5-4B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.6827
* **Mean Absolute Cliff's Delta**: 0.6443
* **Combined Separability Score**: 66.35%
* **Positional Bias**: Position 1 (A): 67.6% | Position 2 (B): 32.4%
* **Length Bias**: Win Rate: 54.7% | Avg EV Margin: +2.7%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | gpt-5.3-chat | 1214.5 |
| 2 | claude-opus-4-7 | 1213.1 |
| 3 | grok-4.20-beta | 1212.2 |
| 4 | gpt-5.4 | 1209.6 |
| 5 | claude-opus-4-6 | 1209.5 |
| 6 | claude-sonnet-4-6 | 1208.7 |
| 7 | moonshotai/Kimi-K2.5 | 1208.6 |
| 8 | gpt-5.5 | 1208.3 |
| 9 | moonshotai/Kimi-K2.6 | 1207.5 |
| 10 | o3 | 1207.2 |
| 11 | zai-org/GLM-5.1 | 1206.9 |
| 12 | moonshotai/Kimi-K2-Instruct | 1206.8 |
| 13 | gpt-5.4-mini | 1206.5 |
| 14 | moonshotai/Kimi-K2-Thinking | 1206.4 |
| 15 | deepseek-ai/DeepSeek-V3.2 | 1206.3 |
| 16 | claude-opus-4-5-20251101 | 1206.3 |
| 17 | openrouter/horizon-beta | 1206.0 |
| 18 | openrouter/sherlock-dash-alpha | 1205.7 |
| 19 | claude-sonnet-4.5 | 1205.6 |
| 20 | grok-4.1-fast | 1205.4 |
| 21 | gpt-5.2 | 1205.3 |
| 22 | claude-opus-4 | 1205.1 |
| 23 | gpt-5-2025-08-07 | 1204.9 |
| 24 | gemini-2.5-pro-preview-06-05 | 1204.9 |
| 25 | zai-org/GLM-5 | 1204.7 |
| 26 | openrouter/horizon-alpha | 1204.6 |
| 27 | deepseek-ai/DeepSeek-V4-Pro | 1204.4 |
| 28 | gemini-3-pro-preview | 1204.4 |
| 29 | deepseek-ai/DeepSeek-V4-Flash | 1204.4 |
| 30 | openrouter/pony-alpha | 1204.2 |
| 31 | gemini-3.1-pro-preview | 1204.2 |
| 32 | deepseek-ai/DeepSeek-V3-0324 | 1203.6 |
| 33 | chatgpt-4o-latest-2025-03-27 | 1203.5 |
| 34 | Qwen/Qwen3.5-397B-A17B | 1203.5 |
| 35 | deepseek-ai/DeepSeek-V3.1 | 1203.4 |
| 36 | deepseek-ai/DeepSeek-R1 | 1203.3 |
| 37 | claude-3-5-sonnet-20241022 | 1203.2 |
| 38 | zai-org/GLM-4.6 | 1203.1 |
| 39 | google/gemma-4-31B-it | 1203.1 |
| 40 | gpt-5-mini-2025-08-07 | 1202.8 |
| 41 | mistral-medium-3.1 | 1202.6 |
| 42 | hunter-alpha | 1202.4 |
| 43 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1202.3 |
| 44 | chatgpt-4o-latest-2025-01-29 | 1202.2 |
| 45 | zai-org/GLM-4.7 | 1202.2 |
| 46 | NousResearch/Hermes-4-405B | 1202.0 |
| 47 | zai-org/GLM-4.5 | 1201.9 |
| 48 | minimax/minimax-m2.5 | 1201.8 |
| 49 | deepseek-ai/DeepSeek-R1-0528 | 1201.8 |
| 50 | claude-sonnet-4 | 1201.7 |
| 51 | mistral-small-creative | 1201.4 |
| 52 | google/gemma-4-26B-A4B-it | 1201.3 |
| 53 | optimus-alpha | 1201.3 |
| 54 | sam-paech/Darkest-muse-v1 | 1200.6 |
| 55 | ifable/gemma-2-Ifable-9B | 1200.5 |
| 56 | RekaAI/reka-flash-3 | 1200.4 |
| 57 | gemini-2.5-pro-exp-03-25 | 1200.2 |
| 58 | qwen/qwen3-235b-a22b:thinking | 1200.1 |
| 59 | claude-3-7-sonnet-20250219 | 1200.1 |
| 60 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1200.1 |
| 61 | quasar-alpha | 1199.9 |
| 62 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1199.8 |
| 63 | qwen/qwq-32b | 1199.5 |
| 64 | gpt-4.1-mini | 1199.2 |
| 65 | deepseek-ai/DeepSeek-V3.2-Speciale | 1198.7 |
| 66 | zai-org/GLM-4.7-Flash | 1198.6 |
| 67 | grok-3-beta | 1197.9 |
| 68 | anthropic/claude-3.5-haiku-20241022 | 1197.7 |
| 69 | google/gemma-3-27b-it | 1197.5 |
| 70 | gpt-4.5-preview | 1197.4 |
| 71 | gemini-2.5-flash-preview | 1197.1 |
| 72 | CohereForAI/c4ai-command-a-03-2025 | 1196.7 |
| 73 | google/gemma-3-4b-it | 1195.7 |
| 74 | gpt-5-nano-2025-08-07 | 1195.5 |
| 75 | openai/gpt-oss-120b | 1195.5 |
| 76 | allura-org/Gemma-3-Glitter-12B | 1195.4 |
| 77 | google/gemma-2-9b-it | 1195.2 |
| 78 | google/gemma-3-12b-it | 1195.0 |
| 79 | gemini-2.0-flash-001 | 1194.4 |
| 80 | meta-llama/llama-3.1-405b-instruct | 1194.2 |
| 81 | THUDM/GLM-4-32B-0414 | 1194.0 |
| 82 | gpt-4.1-nano | 1194.0 |
| 83 | anthropic/claude-3-haiku | 1192.1 |
| 84 | mistralai/mistral-large-2411 | 1192.0 |
| 85 | meta-llama/llama-3.1-70b-instruct | 1191.7 |
| 86 | gpt-4o-mini | 1191.6 |
| 87 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1191.4 |
| 88 | meta-llama/llama-3.1-8b-instruct | 1191.0 |
| 89 | ToastyPigeon/Gemma-3-Starshine-12B | 1191.0 |
| 90 | openai/gpt-oss-20b | 1190.8 |
| 91 | liquid/lfm-7b | 1190.2 |
| 92 | mistralai/Mistral-Nemo-Instruct-2407 | 1190.2 |
| 93 | mistralai/Pixtral-Large-Instruct-2411 | 1189.9 |
| 94 | openai/gpt-4-0314 | 1188.9 |
| 95 | openrouter/cypher-alpha | 1188.7 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1188.4 |
| 97 | mistralai/Mistral-Small-24B-Instruct-2501 | 1187.4 |
| 98 | meta-llama/llama-3.2-3b-instruct | 1187.4 |
| 99 | meta-llama/llama-3.2-1b-instruct | 1187.1 |
| 100 | openai/gpt-3.5-turbo-0613 | 1186.8 |
| 101 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1186.0 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.9201
* **Mean Absolute Cliff's Delta**: 0.8290
* **Combined Separability Score**: 87.46%
* **Positional Bias**: Position 1 (A): 68.3% | Position 2 (B): 31.7%
* **Length Bias**: Win Rate: 52.8% | Avg EV Margin: +1.9%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | gpt-5.3-chat | 1235.0 ± 5.5 |
| 2 | grok-4.20-beta | 1232.3 ± 4.6 |
| 3 | claude-opus-4-7 | 1228.2 ± 5.4 |
| 4 | gpt-5.4 | 1225.6 ± 5.2 |
| 5 | claude-sonnet-4-6 | 1223.3 ± 5.5 |
| 6 | claude-opus-4-6 | 1223.1 ± 5.1 |
| 7 | gpt-5.5 | 1221.7 ± 5.1 |
| 8 | gpt-5.4-mini | 1217.3 ± 2.6 |
| 9 | moonshotai/Kimi-K2.5 | 1217.3 ± 4.7 |
| 10 | openrouter/horizon-alpha | 1215.8 ± 5.9 |
| 11 | openrouter/horizon-beta | 1215.0 ± 6.8 |
| 12 | gpt-5.2 | 1214.7 ± 4.9 |
| 13 | moonshotai/Kimi-K2.6 | 1214.4 ± 4.9 |
| 14 | gpt-5-2025-08-07 | 1214.3 ± 5.2 |
| 15 | moonshotai/Kimi-K2-Instruct | 1213.1 ± 4.0 |
| 16 | claude-opus-4-5-20251101 | 1212.8 ± 4.4 |
| 17 | o3 | 1212.7 ± 3.9 |
| 18 | claude-sonnet-4.5 | 1211.5 ± 4.8 |
| 19 | zai-org/GLM-5.1 | 1210.5 ± 5.9 |
| 20 | moonshotai/Kimi-K2-Thinking | 1210.3 ± 3.8 |
| 21 | deepseek-ai/DeepSeek-V4-Flash | 1209.3 ± 3.3 |
| 22 | claude-opus-4 | 1209.3 ± 1.9 |
| 23 | deepseek-ai/DeepSeek-V4-Pro | 1208.9 ± 2.9 |
| 24 | deepseek-ai/DeepSeek-V3.2 | 1207.5 ± 3.4 |
| 25 | gemini-3-pro-preview | 1207.4 ± 2.7 |
| 26 | gemini-2.5-pro-preview-06-05 | 1207.3 ± 2.6 |
| 27 | gemini-3.1-pro-preview | 1207.2 ± 4.2 |
| 28 | zai-org/GLM-4.6 | 1207.0 ± 3.7 |
| 29 | openrouter/pony-alpha | 1207.0 ± 2.3 |
| 30 | grok-4.1-fast | 1206.9 ± 3.6 |
| 31 | hunter-alpha | 1206.4 ± 3.2 |
| 32 | gpt-5-mini-2025-08-07 | 1206.3 ± 2.7 |
| 33 | openrouter/sherlock-dash-alpha | 1206.0 ± 2.7 |
| 34 | zai-org/GLM-5 | 1206.0 ± 3.9 |
| 35 | deepseek-ai/DeepSeek-R1 | 1205.5 ± 3.2 |
| 36 | mistral-medium-3.1 | 1205.4 ± 2.7 |
| 37 | deepseek-ai/DeepSeek-R1-0528 | 1205.2 ± 3.0 |
| 38 | deepseek-ai/DeepSeek-V3.1 | 1205.1 ± 3.3 |
| 39 | Qwen/Qwen3.5-397B-A17B | 1205.1 ± 3.8 |
| 40 | NousResearch/Hermes-4-405B | 1204.8 ± 2.1 |
| 41 | zai-org/GLM-4.5 | 1204.5 ± 3.7 |
| 42 | claude-sonnet-4 | 1204.4 ± 4.1 |
| 43 | google/gemma-4-31B-it | 1204.3 ± 2.3 |
| 44 | zai-org/GLM-4.7 | 1203.8 ± 3.6 |
| 45 | chatgpt-4o-latest-2025-03-27 | 1203.0 ± 3.5 |
| 46 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1202.8 ± 2.7 |
| 47 | qwen/qwen3-235b-a22b:thinking | 1202.2 ± 4.6 |
| 48 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1202.0 ± 1.3 |
| 49 | google/gemma-4-26B-A4B-it | 1201.4 ± 2.8 |
| 50 | quasar-alpha | 1201.4 ± 3.4 |
| 51 | deepseek-ai/DeepSeek-V3-0324 | 1201.0 ± 3.4 |
| 52 | chatgpt-4o-latest-2025-01-29 | 1201.0 ± 2.6 |
| 53 | gemini-2.5-pro-exp-03-25 | 1200.9 ± 3.1 |
| 54 | sam-paech/Darkest-muse-v1 | 1200.8 ± 5.2 |
| 55 | claude-3-5-sonnet-20241022 | 1200.5 ± 2.4 |
| 56 | claude-3-7-sonnet-20250219 | 1200.4 ± 2.2 |
| 57 | minimax/minimax-m2.5 | 1200.3 ± 1.8 |
| 58 | optimus-alpha | 1200.2 ± 2.0 |
| 59 | mistral-small-creative | 1200.1 ± 3.7 |
| 60 | grok-3-beta | 1199.5 ± 2.6 |
| 61 | gemini-2.5-flash-preview | 1199.3 ± 4.4 |
| 62 | zai-org/GLM-4.7-Flash | 1198.1 ± 2.9 |
| 63 | RekaAI/reka-flash-3 | 1197.7 ± 2.6 |
| 64 | gpt-5-nano-2025-08-07 | 1197.5 ± 2.3 |
| 65 | ifable/gemma-2-Ifable-9B | 1197.4 ± 2.9 |
| 66 | qwen/qwq-32b | 1197.3 ± 4.2 |
| 67 | google/gemma-3-27b-it | 1197.1 ± 2.7 |
| 68 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1196.9 ± 2.0 |
| 69 | gpt-4.1-mini | 1196.9 ± 4.6 |
| 70 | openai/gpt-oss-120b | 1196.2 ± 3.1 |
| 71 | deepseek-ai/DeepSeek-V3.2-Speciale | 1195.9 ± 3.9 |
| 72 | allura-org/Gemma-3-Glitter-12B | 1195.6 ± 4.6 |
| 73 | google/gemma-3-12b-it | 1194.2 ± 2.9 |
| 74 | google/gemma-3-4b-it | 1194.1 ± 4.4 |
| 75 | CohereForAI/c4ai-command-a-03-2025 | 1194.0 ± 4.2 |
| 76 | gpt-4.5-preview | 1193.7 ± 3.0 |
| 77 | gemini-2.0-flash-001 | 1193.5 ± 5.6 |
| 78 | anthropic/claude-3.5-haiku-20241022 | 1192.1 ± 3.6 |
| 79 | THUDM/GLM-4-32B-0414 | 1191.4 ± 2.8 |
| 80 | gpt-4o-mini | 1189.8 ± 2.9 |
| 81 | google/gemma-2-9b-it | 1188.2 ± 3.2 |
| 82 | gpt-4.1-nano | 1187.1 ± 3.5 |
| 83 | openai/gpt-oss-20b | 1186.6 ± 5.0 |
| 84 | ToastyPigeon/Gemma-3-Starshine-12B | 1185.4 ± 3.1 |
| 85 | anthropic/claude-3-haiku | 1184.4 ± 3.4 |
| 86 | meta-llama/llama-3.1-405b-instruct | 1184.1 ± 3.4 |
| 87 | meta-llama/llama-3.1-70b-instruct | 1182.3 ± 4.6 |
| 88 | mistralai/mistral-large-2411 | 1182.1 ± 3.7 |
| 89 | mistralai/Mistral-Nemo-Instruct-2407 | 1182.0 ± 3.1 |
| 90 | mistralai/Pixtral-Large-Instruct-2411 | 1181.5 ± 2.0 |
| 91 | openai/gpt-4-0314 | 1180.7 ± 2.8 |
| 92 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1180.6 ± 4.3 |
| 93 | liquid/lfm-7b | 1179.3 ± 2.6 |
| 94 | meta-llama/llama-3.1-8b-instruct | 1179.0 ± 6.5 |
| 95 | openrouter/cypher-alpha | 1166.1 ± 7.3 |
| 96 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1159.1 ± 5.2 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1157.1 ± 2.3 |
| 98 | mistralai/Mistral-Small-24B-Instruct-2501 | 1131.1 ± 13.4 |
| 101 | meta-llama/llama-3.2-1b-instruct | 1135.4 ± 8.8 |
