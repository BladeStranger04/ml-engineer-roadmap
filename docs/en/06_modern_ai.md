# 💬 6. Modern AI — NLP, LLM, RAG

> Russian version: [06_modern_ai.md](../ru/06_modern_ai.md)

> The hottest and **highest-paid** niche in 2025–2026. In Russia: Yandex (YandexGPT, Alice), Sber (GigaChat, Kandinsky), T-Bank, MTS AI, Avito.

---

## 📝 Classical NLP

- [ ] Tokenization (BPE, WordPiece, SentencePiece)
- [ ] Word embeddings: Word2Vec, GloVe, FastText
- [ ] TF-IDF, BM25 (important for RAG!)
- [ ] Named Entity Recognition, sentiment analysis
- [ ] spaCy, NLTK, Natasha (RU NLP)

---

## 🔥 Transformers

- [ ] **Attention is All You Need** — read the original paper **yourself**
- [ ] Self-attention, multi-head, positional encoding (RoPE, ALiBi)
- [ ] Encoder (BERT) vs Decoder (GPT) vs Encoder-Decoder (T5)
- [ ] Pre-training: MLM, CLM, NSP
- [ ] Fine-tuning vs prompt engineering vs in-context learning

---

## 🤖 Large Language Models

- [ ] Architecture of GPT-style models
- [ ] Scaling laws (Chinchilla)
- [ ] Tokenization tricks, KV-cache
- [ ] **Instruction tuning, RLHF, DPO**
- [ ] Quantization (GPTQ, AWQ, bitsandbytes)
- [ ] **PEFT / LoRA / QLoRA** — fine-tune on your own hardware
- [ ] Inference optimization: vLLM, TGI, llama.cpp, **Triton Inference Server**

### Russian LLMs
- [ ] **YandexGPT** API
- [ ] **GigaChat** API (Sber)
- [ ] Open-source: Saiga, ruGPT, T-lite

---

## 🔎 RAG (Retrieval-Augmented Generation)

> The most in-demand product pattern in 2025–2026.

- [ ] Pipeline: chunking → embeddings → vector DB → retrieve → rerank → generate
- [ ] Embedding models (e5, BGE, sbert), Russian: `intfloat/multilingual-e5`, `ai-forever/sbert_large_nlu_ru`
- [ ] **Vector DB**: **Qdrant** (Russian!), Milvus, pgvector
- [ ] Hybrid search (BM25 + dense)
- [ ] Rerankers (Cohere, BGE-reranker)
- [ ] Frameworks: **LangChain**, **LlamaIndex**, **Haystack**
- [ ] RAG quality evaluation (ragas, your own golden dataset)

---

## 👁️ Modern CV

- [ ] CLIP, SAM, DINOv2
- [ ] Multimodal: LLaVA, Qwen-VL
- [ ] Diffusion: SD, ControlNet, LoRA for SD
- [ ] **Kandinsky** (Sber) — open-source, can be fine-tuned

---

## 🤝 Agents

- [ ] Function/tool calling
- [ ] ReAct, plan-and-execute
- [ ] Multi-agent (CrewAI, AutoGen)
- [ ] MCP (Model Context Protocol)

---

## 📚 Resources

| Resource | Level |
|---|:---:|
| 🥇 [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) | ⭐⭐ |
| 🥇 [Stanford CS224n](https://web.stanford.edu/class/cs224n/) | ⭐⭐⭐ |
| 🎥 Andrej Karpathy — "Let's build GPT" / nanoGPT | ⭐⭐⭐ |
| 🎥 [GPT School — Alexey Zhdanov](https://www.youtube.com/@gptchatru) | ⭐ |
| 📘 "Build a Large Language Model from Scratch" — Sebastian Raschka | ⭐⭐⭐ |
| 🎥 [karpov.courses — NLP / LLM](https://karpov.courses/) | ⭐⭐ |
| 📚 [ai-russia.ru](https://ai-russia.ru/) — RU model reviews | ⭐ |

---

## ✅ Checkpoint projects

1. Write **GPT-mini** from scratch (nanoGPT-style) and train it on a Russian dataset.
2. **RAG bot over your own knowledge base**: documents → Qdrant → YandexGPT/GigaChat → Telegram bot.
3. **Fine-tune Saiga / T-lite** through LoRA for your own task and deploy through vLLM.
