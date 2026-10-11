<p align="center">
  <h1 align="center">awesome-free-llm-apis — Ranking em português</h1>
</p>

<p align="center">
  🌐 <a href="README.md">English</a> · <a href="README.pt-BR.md">Português (BR)</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.zh-TW.md">繁體中文</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a>
</p>

Lista de **29 provedores** de APIs de LLM gratuitas (28 com plano grátis permanente, mais o OpenRouter, com créditos renováveis; a xAI aparece duas vezes no `README.md` e foi contada uma só vez), ordenados por importância e relevância na internet.

> **Como ler o ranking:** o repositório original não mede o uso de cada provedor, apenas o uso semanal de alguns modelos. A ordem abaixo é uma avaliação editorial, baseada no porte da empresa, no reconhecimento da marca e na adoção entre desenvolvedores. Não é uma métrica oficial.
>
> **Dados:** o número de modelos, os limites e as URLs vêm do [README.md](README.md) (fonte: [freellm.net](https://freellm.net)) em 2026-10-11 e mudam com frequência. Confira sempre no site do provedor.

## Nível 1 — Grandes e muito conhecidos

| # | Provedor | Modelos grátis | Base URL | Destaque |
|---|---|---|---|---|
| 1 | Google Gemini | 19 | `https://generativelanguage.googleapis.com/v1beta` | Gemini 3.x Flash, contexto de 1M, sem cartão |
| 2 | OpenRouter | 31 | `https://openrouter.ai/api/v1` | Reúne centenas de modelos; tem os modelos grátis mais usados da lista (renovável: plano grátis + US$ 10 de recarga → 1K RPD) |
| 3 | xAI (Grok) | 3 + 2 | `https://api.x.ai/v1` | Grok 4.x, contexto de até 2M |
| 4 | DeepSeek | 2 | `https://api.deepseek.com/v1` | DeepSeek V3.2 e R1 (raciocínio) |
| 5 | NVIDIA NIM | 132 | `https://integrate.api.nvidia.com/v1` | O maior catálogo; GLM 5.2 e Kimi K2.6 |
| 6 | Mistral AI | 15 | `https://api.mistral.ai/v1` | Mistral Medium 3.5, sem cartão |
| 7 | Hugging Face | 9 | `https://router.huggingface.co/v1` | A maior comunidade de modelos abertos |
| 8 | Groq | 12 | `https://api.groq.com/openai/v1` | Inferência muito rápida; Kimi K2 |
| 9 | Cloudflare Workers AI | 40 | `https://api.cloudflare.com/client/v4/accounts/{account_id}/ai/run` | Llama 3.3 70B, sem cartão |
| 10 | Alibaba Cloud Model Studio (Qwen) | 5 | `https://dashscope-intl.aliyuncs.com/compatible-mode/v1` | Qwen3-Max e Qwen3-Plus (1M) |

## Nível 2 — Relevantes e consolidados

| # | Provedor | Modelos grátis | Base URL | Destaque |
|---|---|---|---|---|
| 11 | Cohere | 12 | `https://api.cohere.com/v2` | Command A+, voltado para empresas |
| 12 | Ollama Cloud | 17 | `https://ollama.com/api` | DeepSeek V4 Pro e MiniMax M3 |
| 13 | Cerebras | 6 | `https://api.cerebras.ai/v1` | Inferência ultrarrápida |
| 14 | Z AI (Zhipu / GLM) | 8 | `https://open.bigmodel.cn/api/paas/v4` | GLM-4.7-Flash |
| 15 | SambaNova | 4 | `https://api.sambanova.ai/v1` | DeepSeek V3.x |
| 16 | ModelScope | 61 | `https://api-inference.modelscope.cn/v1` | Plataforma do Alibaba; Qwen 3.5 e MiniMax |
| 17 | SiliconFlow | 4 | `https://api.siliconflow.cn/v1` | Muito usada na China; 1.000 RPM |
| 18 | Nebius | 1 | `https://api.studio.nebius.com/v1` | Qwen3-235B |
| 19 | AI21 Labs | 2 | `https://api.ai21.com/studio/v1` | Jamba (contexto de 256K) |
| 20 | OVHcloud AI Endpoints | 15 | `https://oai.endpoints.kepler.ai.cloud.ovh.net/v1` | Qwen 3.5 397B; nuvem europeia |

## Nível 3 — Nichos ou menos conhecidos

| # | Provedor | Modelos grátis | Base URL | Destaque |
|---|---|---|---|---|
| 21 | Cline | 4 | *(não informada na lista original)* | Ferramenta de código no VS Code |
| 22 | Kilo Code | 22 | `https://api.kilo.ai/api/gateway` | Nemotron 3 Ultra; 200 requisições por hora |
| 23 | OpenCode Zen | 34 | `https://opencode.ai/zen/v1` | DeepSeek V4 Flash |
| 24 | Chutes.ai | 2 | `https://api.chutes.ai/v1` | Rede comunitária e descentralizada |
| 25 | LLM7.io | 24 | `https://api.llm7.io/v1` | Sem cartão; 60 RPM |
| 26 | Nscale | 2 | `https://inference.api.nscale.com/v1` | Llama 3.3 70B |
| 27 | Glhf.chat | 2 | `https://glhf.chat/api/openai/v1` | Modelos grátis sem limite |
| 28 | Agnes AI | 5 | `https://apihub.agnes-ai.com/v1` | Modelos próprios |
| 29 | Aion Labs | 11 | `https://api.aionlabs.ai/v1` | Limite de 20K tokens por dia |

*RPM e RPD são os limites de requisições por minuto e por dia.*

## Por onde começar

Google Gemini, OpenRouter, Groq e NVIDIA NIM. Os quatro têm planos grátis generosos e funcionam com o SDK da OpenAI.

## Observações sobre a lista original

- **xAI duplicado:** "xAI" e "Grok (xAI)" são a mesma empresa e aparecem como duas entradas, com a mesma Base URL. Aqui foram contadas como um só provedor: as 30 entradas do `README.md` viram 29 linhas nas tabelas acima.
- **Cline incompleto:** está sem Base URL e sem link para gerar a chave.

As tabelas do `README.md` são geradas automaticamente a partir do freellm.net (blocos `BEGIN_*`/`END_*`), então essas duas correções precisam ser feitas na origem dos dados; uma edição direta seria sobrescrita na próxima atualização.
