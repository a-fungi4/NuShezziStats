# Shezzi Hardware Compatibility — Apple Silicon + PC

**Baseline:** 2019 MacBook Pro Intel i7 · CPU inference only · 9GB free RAM  
**Baseline speeds:** 1.5B = 15–25 tok/s · 7B = 3–6 tok/s · 4B = 7–12 tok/s

---

## Current System

| System | Price | 1.5B t/s | 7B t/s | 4B t/s | vs 1.5B | vs 7B | Free RAM | Slots | 7B | 64K | 128K | All 50 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **2019 MBP i7** | — | 15–25 | 3–6 | 7–12 | 1.0x | 1.0x | 9GB | 5 | ✓ | ✓ | ✗ | ✗ |

---

## Apple Silicon

> Prices are approximate USD. Used prices sourced from typical resale market (March 2026). New prices are retail.

| Chip | Year | RAM BW | RAM Options | Price (USD) | Form Factor | 1.5B t/s | 7B t/s | 4B t/s | vs 1.5B | vs 7B | Free RAM | Slots | 7B | 64K | 128K | All 50 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| M1 ⚠ | 2020 | 68 GB/s | 8/16GB | $700 | used MacBook Air | 55–80 | 18–25 | 30–45 | 2.8x | 4.0x | 4–12GB | 0–5 | ✓ | ✓ | ✓ | ✗ |
| M1 Pro | 2021 | 200 GB/s | 16/32GB | $1,100 | used MacBook Pro | 80–120 | 35–50 | 60–85 | 4.0x | 7.8x | 12–28GB | 5–16 | ✓ | ✓ | ✓ | ✗ |
| M1 Max | 2021 | 400 GB/s | 32/64GB | $1,800 | used MacBook Pro | 120–180 | 55–75 | 90–130 | 6.0x | 12.2x | 28–60GB | 16–39 | ✓ | ✓ | ✓ | ✗ |
| M1 Ultra | 2022 | 800 GB/s | 64/128GB | $3,200 | used Mac Studio | 200–300 | 80–110 | 140–200 | 10.0x | 17.8x | 60–124GB | 39–85 | ✓ | ✓ | ✓ | ✓ |
| M2 ⚠ | 2022 | 100 GB/s | 8/16/24GB | $800 | used MacBook Air | 65–95 | 22–32 | 40–60 | 3.2x | 4.9x | 4–20GB | 0–10 | ✓ | ✓ | ✓ | ✗ |
| M2 Pro | 2023 | 200 GB/s | 16/32GB | $1,300 | used MacBook Pro | 85–130 | 38–55 | 65–95 | 4.2x | 8.4x | 12–28GB | 5–16 | ✓ | ✓ | ✓ | ✗ |
| M2 Max | 2023 | 400 GB/s | 32/64/96GB | $2,200 | used MacBook Pro | 130–190 | 60–85 | 100–145 | 6.5x | 13.3x | 28–92GB | 16–62 | ✓ | ✓ | ✓ | ✓ |
| M2 Ultra | 2023 | 800 GB/s | 64/128/192GB | $3,800 | used Mac Studio | 220–320 | 90–120 | 155–220 | 11.0x | 20.0x | 60–188GB | 39–130 | ✓ | ✓ | ✓ | ✓ |
| M3 ⚠ | 2023 | 100 GB/s | 8/16/24GB | $1,100 | new MacBook Air | 65–100 | 23–34 | 42–63 | 3.2x | 5.1x | 4–20GB | 0–10 | ✓ | ✓ | ✓ | ✗ |
| M3 Pro | 2024 | 150 GB/s | 18/36GB | $1,800 | new MacBook Pro | 100–150 | 45–65 | 75–110 | 5.0x | 10.0x | 14–32GB | 6–19 | ✓ | ✓ | ✓ | ✗ |
| M3 Max | 2024 | 400 GB/s | 36/48/96/128GB | $2,800 | new MacBook Pro | 160–240 | 70–95 | 120–170 | 8.0x | 15.6x | 32–124GB | 19–85 | ✓ | ✓ | ✓ | ✓ |
| M3 Ultra | 2024 | 800 GB/s | 128/192GB | $4,500 | new Mac Studio | 230–340 | 95–130 | 165–235 | 11.5x | 21.1x | 124–188GB | 85–130 | ✓ | ✓ | ✓ | ✓ |
| M4 | 2024 | 120 GB/s | 16/32GB | $900 | new MacBook Air | 70–105 | 26–38 | 46–70 | 3.5x | 5.8x | 12–28GB | 5–16 | ✓ | ✓ | ✓ | ✗ |
| M4 Pro | 2024 | 273 GB/s | 24/48GB | $2,200 | new MacBook Pro | 130–190 | 55–80 | 95–140 | 6.5x | 12.2x | 20–44GB | 10–27 | ✓ | ✓ | ✓ | ✗ |
| M4 Max | 2024 | 546 GB/s | 36/48/64/128GB | $3,500 | new MacBook Pro | 200–300 | 90–130 | 160–230 | 10.0x | 20.0x | 32–124GB | 19–85 | ✓ | ✓ | ✓ | ✓ |
| M4 Ultra | 2025 | 1092 GB/s | 128/192GB | $5,500 | new Mac Studio | 300–450 | 130–180 | 240–340 | 15.0x | 28.9x | 124–188GB | 85–130 | ✓ | ✓ | ✓ | ✓ |

> ⚠ = 8GB config has less free RAM than current Intel machine — functionally worse despite faster generation speed

---

## PC Equivalents

> PC GPU systems: VRAM is the bottleneck, not system RAM. Slots column reflects VRAM capacity. Routing infra lives in system RAM.

| System | Price | 1.5B t/s | 7B t/s | 4B t/s | vs 1.5B | vs 7B | Slots | All 50 | Notes |
|---|---|---|---|---|---|---|---|---|---|
| Budget PC (CPU only) | $650 | 20–35 | 5–9 | 10–18 | 1.0x | 1.1x | 3–5 | ✗ | AMD Ryzen 7 7700X, 32GB DDR5. CPU inference, no GPU. |
| Mid PC + RTX 3090 | $1,400 | 120–180 | 40–60 | 70–100 | 6.0x | 8.9x | 5–8 | ✗ | Ryzen 9 7900X + RTX 3090 24GB. 7B fits in VRAM. |
| Mid PC + RTX 4090 | $2,800 | 150–220 | 55–80 | 90–130 | 7.5x | 12.2x | 5–8 | ✗ | Ryzen 9 7950X + RTX 4090 24GB. Fastest consumer GPU. |
| Workstation + A6000 | $7,500 | 180–260 | 65–95 | 110–160 | 9.0x | 14.4x | 25+ | ✗ | Threadripper 7960X + A6000 48GB. Professional tier. |
| Server + H100 80GB | $35,000 | 400–600 | 200–300 | 300–450 | 20x | 44x | 25+ | ✓ | EPYC 9354 + H100 SXM 80GB. Requires rack + cooling. |

---

## Column Reference

| Column | Meaning |
|---|---|
| RAM BW | Unified memory bandwidth (Apple) or GPU VRAM bandwidth (PC) |
| vs 1.5B / vs 7B | Speed multiplier over 2019 MBP baseline — calculated from lower bound of range |
| Free RAM | Available after macOS overhead (~3.5GB) |
| Slots | Pool A specialists simultaneously in RAM |
| 7B | 7B shezzi-identity (EliteCoder) fits in available memory |
| 64K | 64K native context window achievable |
| 128K | 128K native context window achievable |
| All 50 | All 50 specialist LoRAs resident in RAM simultaneously |

---

## Upgrade Decision Guide

| Budget | Best Option | Key Gain |
|---|---|---|
| ~$700 | M1 16GB (used) | 3–4x faster, Metal GPU, same slot count as current |
| ~$1,100 | M1 Pro 32GB / M3 16GB (used/new) | 5x faster 1.5B, 9x faster 7B, 16 Pool A slots |
| ~$1,400 | Mid PC + RTX 3090 | CUDA, 6x faster 1.5B, 24GB VRAM — but 5–8 VRAM slots only |
| ~$1,800 | M1 Max 64GB / M3 Pro 36GB | 7–8x faster, 39 slots, 64K native, no RAM pressure |
| ~$2,200 | M2 Max 64GB / M4 Pro 48GB | 8x faster, 128K context, 27–62 slots |
| ~$2,800 | M3 Max 128GB / Mid PC + RTX 4090 | 10x faster, all 50 specialists in RAM (Mac only) |
| ~$3,200+ | M1 Ultra / M2 Ultra / M4 Max | 12–15x faster, 85+ slots, full architecture in RAM |
| $7,500+ | Workstation + A6000 | 48GB VRAM, professional workstation, not portable |
| $35,000+ | Server + H100 | 20–44x faster, data centre hardware, rack required |


---

## Cloud API Reference

> **Comparison baseline: 2019 MacBook Pro Intel i7 — 1.5B primary engine at 15–25 tok/s, TTFT ~80–150ms (hot slot).**  
> Shezzi does not run on cloud APIs — this section shows how the current local hardware compares to cloud inference for context. `vs 2019 MBP` columns refer specifically to the 2019 MBP i7 baseline above. Cloud t/s = observed server-side output speed. TTFT = time to first token including network round-trip.

| Service | Provider | Cost ($/1M out) | Output t/s | TTFT | vs 2019 MBP t/s | vs 2019 MBP TTFT |
|---|---|---|---|---|---|---|
| GPT-4o | OpenAI | $15.00 | 80 | 800ms | 4.0x faster output | **8.0x slower TTFT** |
| GPT-4o mini | OpenAI | $0.60 | 110 | 400ms | 5.5x faster output | **4.0x slower TTFT** |
| Claude Sonnet 4.6 | Anthropic | $3.00 | 85 | 900ms | 4.2x faster output | **9.0x slower TTFT** |
| Claude Haiku 4.5 | Anthropic | $0.25 | 160 | 300ms | 8.0x faster output | **3.0x slower TTFT** |
| DeepSeek-V3 | DeepSeek | $0.27 | 80 | 1,500ms | 4.0x faster output | **15.0x slower TTFT** |
| DeepSeek-R1 | DeepSeek | $0.55 | 55 | 3,000ms | 2.8x faster output | **30.0x slower TTFT** |
| Llama 3.3 70B | Groq | $0.59 | 650 | 100ms | 32.5x faster output | same TTFT |
| Llama 3.1 8B | Groq | $0.06 | 800 | 80ms | 40.0x faster output | 1.2x faster TTFT |
| Gemini 2.0 Flash | Google | $0.10 | 250 | 200ms | 12.5x faster output | **2.0x slower TTFT** |
| Gemini 1.5 Pro | Google | $3.50 | 90 | 800ms | 4.5x faster output | **8.0x slower TTFT** |
| Qwen2.5 72B | Together | $0.90 | 95 | 400ms | 4.8x faster output | **4.0x slower TTFT** |
| Mistral Large | Mistral | $2.00 | 75 | 600ms | 3.8x faster output | **6.0x slower TTFT** |

### Cloud vs Local — Key Observations

| Observation | Detail |
|---|---|
| Local TTFT beats every major cloud API | 2019 MBP i7 first-token (~100ms) is faster than GPT-4o, Claude, Gemini, DeepSeek |
| Cloud output throughput generally wins | Cloud servers run large models on A100/H100 clusters — raw output speed is higher |
| Groq is the exception | Custom LPU silicon — 650–800 t/s with ~100ms TTFT — fastest available, but runs Llama not Shezzi |
| DeepSeek-R1 TTFT is painful | 3,000ms average — 30x slower first token than current local machine |
| Cost accumulates fast on cloud | At $15/1M tokens (GPT-4o), a 300-token response costs $0.0045. Unlimited on local hardware. |
| Apple Silicon M1 Pro closes the gap | At 100 t/s local, matches or beats GPT-4o and Claude output speed with local TTFT advantage |
| M4 Max matches frontier cloud throughput | 250 t/s local ≈ Gemini 2.0 Flash cloud, with better TTFT and $0 per query |

---

## Notes

- All Apple Silicon figures assume llama.cpp with Metal GPU backend enabled
- PC GPU figures assume llama.cpp with CUDA backend (NVIDIA) or ROCm (AMD)
- Token speeds are estimates based on published benchmarks for similar models (Llama-2 7B Q4, Mistral 7B Q4)
- M1 8GB is omitted from the decision guide — it has less free RAM than the current Intel machine
- 'Slots' for PC GPU systems = models loadable into VRAM simultaneously; routing infra (3.5GB) lives in system RAM
- Context window figures assume Q4_K_M quantized models and INT8 KV cache where noted
- Cloud TTFT includes typical network latency — add 50–200ms outside US
- Groq LPU is custom inference hardware, not a GPU — throughput numbers are not comparable to standard GPU inference
- Prices reflect approximate market conditions March 2026 — verify current listings before purchasing
