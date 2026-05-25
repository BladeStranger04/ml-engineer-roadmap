# 6. Modern AI: NLP, LLM, RAG

> Russian version: [06_modern_ai.md](../ru/06_modern_ai.md)

> LLM and RAG work is one of the most active ML hiring areas in 2025-2026.

---

## Classical NLP

- [ ] Tokenization: BPE, WordPiece, SentencePiece
- [ ] Word embeddings: Word2Vec, GloVe, FastText
- [ ] TF-IDF, BM25, important for RAG
- [ ] Named Entity Recognition, sentiment analysis
- [ ] spaCy, NLTK, Natasha for Russian NLP

---

## Transformers

- [ ] Read Attention Is All You Need
- [ ] Self-attention, multi-head attention, positional encoding, RoPE, ALiBi
- [ ] Encoder models: BERT
- [ ] Decoder models: GPT
- [ ] Encoder-decoder models: T5
- [ ] Pre-training: MLM, CLM, NSP
- [ ] Fine-tuning vs prompt engineering vs in-context learning

---

## Large Language Models

- [ ] GPT-style architecture
- [ ] Scaling laws, Chinchilla
- [ ] Tokenization details, KV-cache
- [ ] Instruction tuning, RLHF, DPO
- [ ] Quantization: GPTQ, AWQ, bitsandbytes
- [ ] PEFT, LoRA, QLoRA
- [ ] Inference optimization: vLLM, TGI, llama.cpp, Triton Inference Server

### Russian-market LLMs
- [ ] YandexGPT API
- [ ] GigaChat API
- [ ] Open-source: Saiga, ruGPT, T-lite

---

## RAG

- [ ] Pipeline: chunking, embeddings, vector DB, retrieve, rerank, generate
- [ ] Embedding models: e5, BGE, sbert
- [ ] Russian-friendly embeddings: `intfloat/multilingual-e5`, `ai-forever/sbert_large_nlu_ru`
- [ ] Vector DB: Qdrant, Milvus, pgvector
- [ ] Hybrid search: BM25 + dense retrieval
- [ ] Rerankers: Cohere, BGE-reranker
- [ ] Frameworks: LangChain, LlamaIndex, Haystack
- [ ] RAG evaluation: Ragas, custom golden dataset

---

## Modern CV and multimodal

- [ ] CLIP, SAM, DINOv2
- [ ] Multimodal models: LLaVA, Qwen-VL
- [ ] Diffusion: Stable Diffusion, ControlNet, LoRA for SD
- [ ] Kandinsky: useful for Russian-market projects

---

## Agents

- [ ] Function and tool calling
- [ ] ReAct, plan-and-execute
- [ ] Multi-agent systems: CrewAI, AutoGen
- [ ] MCP, Model Context Protocol

---

## Resources

| Resource | Level |
|---|:---:|
| [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) | ** |
| [Stanford CS224n](https://web.stanford.edu/class/cs224n/) | *** |
| [Let's build GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY), Andrej Karpathy | *** |
| Build a Large Language Model from Scratch, Sebastian Raschka | *** |
| [Full Stack Deep Learning](https://fullstackdeeplearning.com/) | ** |
| [LangChain docs](https://python.langchain.com/docs/) | * |
| [LlamaIndex docs](https://docs.llamaindex.ai/) | * |

---

## Checkpoint projects

1. Build a GPT-mini model from scratch, following nanoGPT, and train it on a small corpus.
2. Build a RAG bot over your own knowledge base: documents, Qdrant, LLM API, Telegram bot.
3. Fine-tune Saiga or T-lite with LoRA and serve it with vLLM.
