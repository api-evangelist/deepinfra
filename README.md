# DeepInfra (deepinfra)

DeepInfra is a serverless inference platform for open-source models. Hosts 100+ LLMs (Llama, Qwen, DeepSeek, Mixtral) plus image (Flux, Stable Diffusion), video, audio (Whisper, TTS, Voxtral), embeddings/reranking, and vision/OCR models. Includes fine-tuning, dedicated GPU rentals, and private deployments. OpenAI- and Anthropic-compatible endpoints.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/deepinfra/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=deepinfra-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, Serverless, Open Source, OpenAI Compatible, Anthropic Compatible, Image Generation, Audio, Embeddings

## APIs
- **DeepInfra Platform API** — Chat completions (OpenAI + Anthropic compatible), embeddings, reranking, audio (Whisper / TTS / Voxtral), image (Flux/SD), video, vision/OCR, fine-tuning, dedicated-model deployments, account, billing, webhooks. Base URL `https://api.deepinfra.com/v1/openai`. [Docs](https://docs.deepinfra.com/) · [Pricing](https://deepinfra.com/pricing) · [Rate Limits](https://docs.deepinfra.com/account/rate-limits)

### Pricing Examples (May 2026)
- DeepSeek-V3: $0.32/M input · $0.89/M output
- Voxtral Mini audio: $0.001/minute
- Flux schnell image: $0.0005 × (w/1024) × (h/1024) × iterations
- Dedicated GPU rentals: A100 from $0.89/hour, B300 up to $4.20/hour

## Plans, Rate Limits, FinOps
- [Plans](plans/deepinfra-plans-pricing.yml) — PAYG per-token / per-minute / per-image, dedicated-GPU hourly. 5 usage tiers ($20-$10K).
- [RateLimits](rate-limits/deepinfra-rate-limits.yml) — 200 concurrent requests default; rate/GPU limit increases on request.
- [FinOps](finops/deepinfra-finops.yml) — FOCUS-aligned, Usage Record API + automatic invoicing thresholds.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://deepinfra.com/)
- [Documentation](https://docs.deepinfra.com/)

## Notes
- A documented OpenAPI URL exists (`https://docs.deepinfra.com/api-reference/openapi.json`) but currently returns a placeholder "Plant Store" sample spec rather than the real DeepInfra schema. Spec not copied locally.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
