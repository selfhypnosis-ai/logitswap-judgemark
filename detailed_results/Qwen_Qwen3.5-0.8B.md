# Detailed Results: Qwen/Qwen3.5-0.8B

### Option A: Prompt-Isolated Elo Separability
* **Omega-Squared (ANOVA effect size)**: 0.1048
* **Mean Absolute Cliff's Delta**: 0.2474
* **Combined Separability Score**: 17.61%
* **Positional Bias**: Position 1 (A): 6.4% | Position 2 (B): 93.6%
* **Length Bias**: Win Rate: 50.1% | Avg EV Margin: +0.0%

#### Option A: Leaderboard (Across 32 Prompts)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | openrouter/horizon-alpha | 1200.8 |
| 2 | zai-org/GLM-4.7 | 1200.7 |
| 3 | google/gemma-4-31B-it | 1200.7 |
| 4 | gemini-2.5-pro-preview-06-05 | 1200.6 |
| 5 | claude-opus-4-7 | 1200.6 |
| 6 | claude-opus-4-6 | 1200.6 |
| 7 | deepseek-ai/DeepSeek-V4-Pro | 1200.6 |
| 8 | gemini-3.1-pro-preview | 1200.5 |
| 9 | openrouter/horizon-beta | 1200.5 |
| 10 | gemini-3-pro-preview | 1200.5 |
| 11 | zai-org/GLM-4.6 | 1200.5 |
| 12 | gpt-5-2025-08-07 | 1200.5 |
| 13 | claude-3-5-sonnet-20241022 | 1200.5 |
| 14 | deepseek-ai/DeepSeek-V4-Flash | 1200.4 |
| 15 | google/gemma-4-26B-A4B-it | 1200.4 |
| 16 | deepseek-ai/DeepSeek-V3.1 | 1200.4 |
| 17 | grok-4.20-beta | 1200.4 |
| 18 | o3 | 1200.3 |
| 19 | deepseek-ai/DeepSeek-R1 | 1200.3 |
| 20 | THUDM/GLM-4-32B-0414 | 1200.3 |
| 21 | NousResearch/Hermes-4-405B | 1200.3 |
| 22 | zai-org/GLM-4.7-Flash | 1200.3 |
| 23 | allura-org/Gemma-3-Glitter-12B | 1200.3 |
| 24 | claude-sonnet-4-6 | 1200.3 |
| 25 | gpt-5.4-mini | 1200.3 |
| 26 | gpt-5.2 | 1200.3 |
| 27 | claude-3-7-sonnet-20250219 | 1200.3 |
| 28 | claude-sonnet-4.5 | 1200.3 |
| 29 | moonshotai/Kimi-K2-Instruct | 1200.2 |
| 30 | moonshotai/Kimi-K2.5 | 1200.2 |
| 31 | moonshotai/Kimi-K2.6 | 1200.2 |
| 32 | claude-sonnet-4 | 1200.2 |
| 33 | moonshotai/Kimi-K2-Thinking | 1200.2 |
| 34 | gemini-2.0-flash-001 | 1200.2 |
| 35 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1200.2 |
| 36 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.2 |
| 37 | sam-paech/Darkest-muse-v1 | 1200.2 |
| 38 | grok-3-beta | 1200.2 |
| 39 | gpt-5.5 | 1200.2 |
| 40 | gpt-5.4 | 1200.2 |
| 41 | google/gemma-3-27b-it | 1200.1 |
| 42 | grok-4.1-fast | 1200.1 |
| 43 | optimus-alpha | 1200.1 |
| 44 | mistral-medium-3.1 | 1200.1 |
| 45 | claude-opus-4-5-20251101 | 1200.1 |
| 46 | zai-org/GLM-5.1 | 1200.1 |
| 47 | deepseek-ai/DeepSeek-V3-0324 | 1200.1 |
| 48 | hunter-alpha | 1200.1 |
| 49 | Qwen/Qwen3.5-397B-A17B | 1200.1 |
| 50 | deepseek-ai/DeepSeek-V3.2 | 1200.1 |
| 51 | meta-llama/llama-3.1-405b-instruct | 1200.1 |
| 52 | chatgpt-4o-latest-2025-01-29 | 1200.0 |
| 53 | mistral-small-creative | 1200.0 |
| 54 | minimax/minimax-m2.5 | 1200.0 |
| 55 | qwen/qwen3-235b-a22b:thinking | 1200.0 |
| 56 | openai/gpt-4-0314 | 1200.0 |
| 57 | openrouter/sherlock-dash-alpha | 1200.0 |
| 58 | chatgpt-4o-latest-2025-03-27 | 1200.0 |
| 59 | qwen/qwq-32b | 1200.0 |
| 60 | zai-org/GLM-5 | 1199.9 |
| 61 | google/gemma-3-4b-it | 1199.9 |
| 62 | gemini-2.5-pro-exp-03-25 | 1199.9 |
| 63 | zai-org/GLM-4.5 | 1199.9 |
| 64 | claude-opus-4 | 1199.9 |
| 65 | RekaAI/reka-flash-3 | 1199.9 |
| 66 | CohereForAI/c4ai-command-a-03-2025 | 1199.9 |
| 67 | deepseek-ai/DeepSeek-R1-0528 | 1199.9 |
| 68 | anthropic/claude-3-haiku | 1199.9 |
| 69 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1199.9 |
| 70 | gpt-4o-mini | 1199.9 |
| 71 | google/gemma-2-9b-it | 1199.9 |
| 72 | gpt-5-mini-2025-08-07 | 1199.8 |
| 73 | meta-llama/llama-3.1-70b-instruct | 1199.8 |
| 74 | quasar-alpha | 1199.8 |
| 75 | openrouter/cypher-alpha | 1199.8 |
| 76 | gpt-4.5-preview | 1199.8 |
| 77 | google/gemma-3-12b-it | 1199.8 |
| 78 | ToastyPigeon/Gemma-3-Starshine-12B | 1199.8 |
| 79 | openrouter/pony-alpha | 1199.7 |
| 80 | openai/gpt-oss-120b | 1199.7 |
| 81 | gpt-4.1-mini | 1199.6 |
| 82 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1199.6 |
| 83 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1199.6 |
| 84 | gemini-2.5-flash-preview | 1199.6 |
| 85 | meta-llama/llama-3.1-8b-instruct | 1199.6 |
| 86 | meta-llama/llama-3.2-3b-instruct | 1199.6 |
| 87 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1199.6 |
| 88 | mistralai/mistral-large-2411 | 1199.5 |
| 89 | liquid/lfm-7b | 1199.5 |
| 90 | openai/gpt-3.5-turbo-0613 | 1199.5 |
| 91 | mistralai/Pixtral-Large-Instruct-2411 | 1199.5 |
| 92 | meta-llama/llama-3.2-1b-instruct | 1199.4 |
| 93 | mistralai/Mistral-Nemo-Instruct-2407 | 1199.4 |
| 94 | mistralai/Mistral-Small-24B-Instruct-2501 | 1199.4 |
| 95 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1199.3 |
| 96 | anthropic/claude-3.5-haiku-20241022 | 1199.3 |
| 97 | ifable/gemma-2-Ifable-9B | 1199.3 |
| 98 | gpt-4.1-nano | 1199.2 |
| 99 | openai/gpt-oss-20b | 1199.2 |
| 100 | gpt-5-nano-2025-08-07 | 1199.0 |
| 101 | gpt-5.3-chat | 1198.3 |

### Option B: Bootstrapped Tournament Stability
* **Omega-Squared (ANOVA effect size)**: 0.4959
* **Mean Absolute Cliff's Delta**: 0.5313
* **Combined Separability Score**: 51.36%
* **Positional Bias**: Position 1 (A): 5.7% | Position 2 (B): 94.3%
* **Length Bias**: Win Rate: 50.8% | Avg EV Margin: +0.1%

#### Option B: Leaderboard (Resampled Tournaments)

| Rank | Model Name | Avg Elo |
| :---: | :--- | :---: |
| 1 | gpt-5-2025-08-07 | 1203.1 ± 1.9 |
| 2 | openrouter/horizon-alpha | 1202.9 ± 1.2 |
| 3 | zai-org/GLM-4.6 | 1202.5 ± 1.3 |
| 4 | claude-opus-4-6 | 1202.5 ± 0.9 |
| 5 | claude-opus-4-7 | 1202.3 ± 1.2 |
| 6 | zai-org/GLM-4.7 | 1202.3 ± 1.7 |
| 7 | deepseek-ai/DeepSeek-V4-Pro | 1202.1 ± 1.1 |
| 8 | google/gemma-4-31B-it | 1202.1 ± 0.9 |
| 9 | deepseek-ai/DeepSeek-V4-Flash | 1202.0 ± 1.2 |
| 10 | zai-org/GLM-4.7-Flash | 1201.9 ± 0.8 |
| 11 | claude-sonnet-4.5 | 1201.9 ± 1.7 |
| 12 | gemini-3-pro-preview | 1201.8 ± 1.2 |
| 13 | sam-paech/Darkest-muse-v1 | 1201.8 ± 1.7 |
| 14 | NousResearch/Hermes-4-405B | 1201.8 ± 0.9 |
| 15 | openrouter/horizon-beta | 1201.5 ± 1.7 |
| 16 | moonshotai/Kimi-K2.5 | 1201.5 ± 1.7 |
| 17 | google/gemma-4-26B-A4B-it | 1201.5 ± 1.7 |
| 18 | claude-sonnet-4 | 1201.5 ± 1.3 |
| 19 | deepseek-ai/DeepSeek-V3.1 | 1201.4 ± 0.9 |
| 20 | zai-org/GLM-5.1 | 1201.3 ± 1.0 |
| 21 | gemini-3.1-pro-preview | 1201.3 ± 1.0 |
| 22 | grok-4.20-beta | 1201.2 ± 1.6 |
| 23 | gemini-2.5-pro-preview-06-05 | 1201.2 ± 1.3 |
| 24 | optimus-alpha | 1201.0 ± 1.3 |
| 25 | deepseek-ai/DeepSeek-R1 | 1201.0 ± 1.1 |
| 26 | claude-sonnet-4-6 | 1201.0 ± 1.6 |
| 27 | gpt-5.4 | 1201.0 ± 1.9 |
| 28 | hunter-alpha | 1200.8 ± 1.7 |
| 29 | zai-org/GLM-4.5 | 1200.8 ± 1.0 |
| 30 | moonshotai/Kimi-K2-Instruct | 1200.8 ± 1.5 |
| 31 | gemini-2.0-flash-001 | 1200.8 ± 1.1 |
| 32 | o3 | 1200.8 ± 1.4 |
| 33 | moonshotai/Kimi-K2-Thinking | 1200.7 ± 1.2 |
| 34 | deepseek-ai/DeepSeek-V3.2 | 1200.7 ± 0.8 |
| 35 | openrouter/sherlock-dash-alpha | 1200.7 ± 1.8 |
| 36 | claude-3-5-sonnet-20241022 | 1200.7 ± 1.6 |
| 37 | grok-3-beta | 1200.7 ± 0.8 |
| 38 | google/gemma-3-27b-it | 1200.5 ± 1.3 |
| 39 | THUDM/GLM-4-32B-0414 | 1200.5 ± 1.5 |
| 40 | deepseek-ai/DeepSeek-V3.2-Speciale | 1200.5 ± 1.2 |
| 41 | qwen/qwq-32b | 1200.5 ± 1.7 |
| 42 | meta-llama/llama-3.1-405b-instruct | 1200.3 ± 1.2 |
| 43 | allura-org/Gemma-3-Glitter-12B | 1200.3 ± 1.5 |
| 44 | gemini-2.5-pro-exp-03-25 | 1200.3 ± 2.1 |
| 45 | gpt-5.2 | 1200.3 ± 1.5 |
| 46 | gpt-5.5 | 1200.2 ± 1.2 |
| 47 | qwen/qwen3-235b-a22b:thinking | 1200.2 ± 1.5 |
| 48 | openai/gpt-4-0314 | 1200.2 ± 0.9 |
| 49 | claude-opus-4-5-20251101 | 1200.2 ± 1.5 |
| 50 | zai-org/GLM-5 | 1200.2 ± 1.3 |
| 51 | Qwen/Qwen3.5-397B-A17B | 1200.2 ± 0.8 |
| 52 | deepseek-ai/DeepSeek-R1-0528 | 1200.2 ± 1.2 |
| 53 | grok-4.1-fast | 1200.1 ± 1.5 |
| 54 | deepseek-ai/DeepSeek-V3-0324 | 1200.1 ± 1.8 |
| 55 | mistral-small-creative | 1200.0 ± 1.1 |
| 56 | gpt-5.4-mini | 1200.0 ± 1.3 |
| 57 | quasar-alpha | 1199.9 ± 2.2 |
| 58 | gpt-5-mini-2025-08-07 | 1199.9 ± 1.9 |
| 59 | RekaAI/reka-flash-3 | 1199.8 ± 1.2 |
| 60 | claude-opus-4 | 1199.8 ± 1.3 |
| 61 | moonshotai/Kimi-K2.6 | 1199.8 ± 1.3 |
| 62 | mistral-medium-3.1 | 1199.8 ± 1.6 |
| 63 | minimax/minimax-m2.5 | 1199.7 ± 1.2 |
| 64 | openai/gpt-oss-120b | 1199.7 ± 0.6 |
| 65 | Nanbeige/Nanbeige4-3B-Thinking-2511 | 1199.7 ± 1.6 |
| 66 | claude-3-7-sonnet-20250219 | 1199.7 ± 1.2 |
| 67 | google/gemma-3-4b-it | 1199.5 ± 1.1 |
| 68 | chatgpt-4o-latest-2025-01-29 | 1199.4 ± 1.2 |
| 69 | openrouter/pony-alpha | 1199.4 ± 1.3 |
| 70 | CohereForAI/c4ai-command-a-03-2025 | 1199.4 ± 1.4 |
| 71 | google/gemma-3-12b-it | 1199.3 ± 1.5 |
| 72 | gpt-4o-mini | 1199.3 ± 1.1 |
| 73 | chatgpt-4o-latest-2025-03-27 | 1199.3 ± 1.5 |
| 74 | meta-llama/llama-3.2-1b-instruct | 1199.3 ± 1.4 |
| 75 | anthropic/claude-3-haiku | 1199.2 ± 1.5 |
| 76 | gemini-2.5-flash-preview | 1199.2 ± 1.2 |
| 77 | mistralai/Mistral-Large-3-675B-Instruct-2512 | 1199.2 ± 1.1 |
| 78 | meta-llama/Llama-4-Maverick-17B-128E-Instruct | 1199.1 ± 0.7 |
| 79 | ToastyPigeon/Gemma-3-Starshine-12B | 1199.1 ± 0.9 |
| 80 | gpt-4.5-preview | 1199.1 ± 1.5 |
| 81 | meta-llama/llama-3.1-8b-instruct | 1198.7 ± 0.8 |
| 82 | meta-llama/llama-3.1-70b-instruct | 1198.6 ± 1.6 |
| 83 | gpt-4.1-mini | 1198.4 ± 1.8 |
| 84 | openai/gpt-3.5-turbo-0613 | 1198.4 ± 1.7 |
| 85 | meta-llama/llama-3.2-3b-instruct | 1198.2 ± 1.2 |
| 86 | mistralai/Mistral-Small-24B-Instruct-2501 | 1198.2 ± 1.6 |
| 87 | openrouter/cypher-alpha | 1198.1 ± 2.2 |
| 88 | ifable/gemma-2-Ifable-9B | 1198.1 ± 1.3 |
| 89 | gpt-4.1-nano | 1198.0 ± 1.2 |
| 90 | google/gemma-2-9b-it | 1198.0 ± 1.1 |
| 91 | liquid/lfm-7b | 1198.0 ± 1.8 |
| 92 | mistralai/mistral-large-2411 | 1197.9 ± 1.2 |
| 93 | gpt-5-nano-2025-08-07 | 1197.9 ± 1.3 |
| 94 | mistralai/Mistral-Nemo-Instruct-2407 | 1197.8 ± 1.3 |
| 95 | meta-llama/Llama-4-Scout-17B-16E-Instruct | 1197.7 ± 1.3 |
| 96 | openai/gpt-oss-20b | 1197.6 ± 1.9 |
| 97 | mistralai/mistral-small-3.1-24b-instruct-2503 | 1197.3 ± 1.1 |
| 98 | mistralai/Mistral-Small-3.2-24B-Instruct-2506 | 1197.3 ± 1.4 |
| 99 | mistralai/Pixtral-Large-Instruct-2411 | 1196.8 ± 1.0 |
| 100 | anthropic/claude-3.5-haiku-20241022 | 1196.6 ± 1.1 |
| 101 | gpt-5.3-chat | 1194.9 ± 1.3 |
