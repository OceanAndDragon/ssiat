# ssiat (씨앗)

A learning repository: understanding AI end-to-end by building a small
Korean–English language model from scratch — tokenizer to chat.

The goal is learning, not the model. Code here is written by hand first and
compared with library implementations afterwards.

## Milestones

| Folder          | Milestone                      |
|-----------------|--------------------------------|
| `m1_basics/`    | M1 — How learning works (autograd, MLP language model) |
| `m2_gpt/`       | M2 — Mini GPT (Transformer from scratch)               |
| `m3_pretrain/`  | M3 — Bilingual pretraining (BPE, data, cloud training) |
| `m4_chat/`      | M4 — A model that converses (SFT, DPO)                 |
| `m5_inference/` | M5 — Inference engine (KV cache, quantization)         |

## Notes

- `notes/lab-notebook.md` — one line per experiment: change, prediction, result, lesson
- `notes/essays/` — weekly one-paragraph essays: where this week's concept is used in AI and why
- `notes/foundation/` — written answers to each milestone's foundation questions

## Setup

```bash
uv sync
uv run pytest
```
