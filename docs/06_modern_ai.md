# 💬 6. Modern AI — NLP, LLM, RAG

> Самая горячая и **самая высокооплачиваемая** ниша 2025–2026. В РФ — Yandex (YandexGPT, Алиса), Sber (GigaChat, Kandinsky), T-Bank, MTS AI, Avito.

---

## 📝 Классический NLP

- [ ] Токенизация (BPE, WordPiece, SentencePiece)
- [ ] Word embeddings: Word2Vec, GloVe, FastText
- [ ] TF-IDF, BM25 (важно для RAG!)
- [ ] Named Entity Recognition, sentiment analysis
- [ ] spaCy, NLTK, Natasha (RU NLP)

---

## 🔥 Transformers

- [ ] **Attention is All You Need** — прочитать **сам** оригинал
- [ ] Self-attention, multi-head, positional encoding (RoPE, ALiBi)
- [ ] Encoder (BERT) vs Decoder (GPT) vs Encoder-Decoder (T5)
- [ ] Pre-training: MLM, CLM, NSP
- [ ] Fine-tuning vs prompt engineering vs in-context learning

---

## 🤖 Large Language Models

- [ ] Архитектура GPT-style моделей
- [ ] Scaling laws (Chinchilla)
- [ ] Tokenization трюки, KV-cache
- [ ] **Instruction tuning, RLHF, DPO**
- [ ] Quantization (GPTQ, AWQ, bitsandbytes)
- [ ] **PEFT / LoRA / QLoRA** — fine-tune на своём железе
- [ ] Inference оптимизация: vLLM, TGI, llama.cpp, **Triton Inference Server**

### Российские LLM
- [ ] **YandexGPT** API
- [ ] **GigaChat** API (Sber)
- [ ] Open-source: Saiga, ruGPT, T-lite

---

## 🔎 RAG (Retrieval-Augmented Generation)

> Самый востребованный паттерн в продуктах 2025–2026.

- [ ] Pipeline: chunking → embeddings → vector DB → retrieve → rerank → generate
- [ ] Embedding модели (e5, BGE, sbert), русские: `intfloat/multilingual-e5`, `ai-forever/sbert_large_nlu_ru`
- [ ] **Vector DB**: **Qdrant** (русская!), Milvus, pgvector
- [ ] Hybrid search (BM25 + dense)
- [ ] Rerankers (Cohere, BGE-reranker)
- [ ] Frameworks: **LangChain**, **LlamaIndex**, **Haystack**
- [ ] Оценка качества RAG (ragas, своя golden dataset)

---

## 👁️ Современный CV

- [ ] CLIP, SAM, DINOv2
- [ ] Multimodal: LLaVA, Qwen-VL
- [ ] Diffusion: SD, ControlNet, LoRA для SD
- [ ] **Kandinsky** (Sber) — open-source, можно дообучать

---

## 🤝 Agents

- [ ] Function/tool calling
- [ ] ReAct, plan-and-execute
- [ ] Multi-agent (CrewAI, AutoGen)
- [ ] MCP (Model Context Protocol)

---

## 📚 Ресурсы

| Ресурс | Уровень |
|---|:---:|
| 🥇 [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) | ⭐⭐ |
| 🥇 [Stanford CS224n](https://web.stanford.edu/class/cs224n/) | ⭐⭐⭐ |
| 🎥 Andrej Karpathy — «Let's build GPT» / nanoGPT | ⭐⭐⭐ |
| 🎥 [Школа GPT — Алексей Жданов](https://www.youtube.com/@gptchatru) | ⭐ |
| 📘 «Build a Large Language Model from Scratch» — Sebastian Raschka | ⭐⭐⭐ |
| 🎥 [karpov.courses — NLP / LLM](https://karpov.courses/) | ⭐⭐ |
| 📚 [ai-russia.ru](https://ai-russia.ru/) — обзоры RU моделей | ⭐ |

---

## ✅ Контрольные проекты

1. С нуля написать **GPT-mini** (по nanoGPT) и обучить на русском датасете.
2. **RAG-бот по своей базе знаний**: документы → Qdrant → YandexGPT/GigaChat → Telegram-бот.
3. **Fine-tune Saiga / T-lite** через LoRA на своей задаче и задеплоить через vLLM.
