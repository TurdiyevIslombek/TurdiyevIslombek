# Islombek Turdiyev

**I build language models and software from scratch — starting with my own language.**

Self-taught builder from Bukhara, Uzbekistan. I trained a 103M-parameter Uzbek language model from an empty file, built a custom Uzbek tokenizer, and founded a learning platform that's live for 1,000+ students. I ship real things, and I test them honestly.

[![Website](https://img.shields.io/badge/Website-turdiyevislombek.github.io-164257?style=flat-square)](https://turdiyevislombek.github.io)
[![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-IslombekT-A9772B?style=flat-square)](https://huggingface.co/IslombekT)
[![EduBoost](https://img.shields.io/badge/EduBoost-eduboostonline.com-1C6C86?style=flat-square)](https://www.eduboostonline.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-164257?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/islombek-turdiyev)

---

### 🛠️ What I've built

**[uzbek-gpt-103m](https://huggingface.co/IslombekT/uzbek-gpt-103m)** — a 103M-parameter decoder-only transformer (RoPE · RMSNorm · SwiGLU), pre-trained **from scratch** on ~1.06B Uzbek tokens.
> Single RTX 4090 · ~3.4 hours · ~$3.60 to train · **1.038 bits/byte** on held-out Uzbek — beats mGPT-1.3B, as-is (1.080) and fine-tuned (1.077), at ~1/13th the size.

**[uzbek-bpe-16k](https://huggingface.co/IslombekT/uzbek-bpe-16k)** — a custom BPE tokenizer built specifically for Uzbek (handles `oʻ`, `gʻ`, and apostrophes that multilingual tokenizers fragment).
> 16,384 vocab · **1.749 tokens/word**, the fewest of 11 tokenizers I tested. A controlled experiment showed what it buys: comparable model quality with less than half the parameters and about a third of the training compute.

**[uzbek-gpt-from-scratch](https://github.com/TurdiyevIslombek/uzbek-gpt-from-scratch)** — the full training code, data pipeline, a from-scratch-vs-fine-tuning study, and an audit of my own evaluation that found and fixed four problems. Paper included.

**[EduBoost](https://www.eduboostonline.com)** — a free full-stack learning platform (Next.js · TypeScript · PostgreSQL) where students teach students. Built solo, running in production for **1,000+ learners** in underserved regions of Uzbekistan.

---

### 🧰 Tools I reach for

`Python` · `PyTorch` · `Transformers` · `TypeScript` · `Next.js` · `PostgreSQL` · `Node.js`
Low-resource NLP · tokenization · from-scratch training · full-stack web · Kaggle tabular ML (XGBoost / LightGBM / CatBoost)

---

### 📍 About

Bukhara → Navoiy, Uzbekistan · speaks **Uzbek, Russian, Tajik, English**
**Goal:** build frontier-capable language models and start my own AI company.

<!--
  Tip: pin these 3 repos on your profile (Customize your pins):
  uzbek-gpt-from-scratch · your uzbek-bpe repo · EduBoost (if the source is on GitHub)
-->
