# Custom Tokenizers Collection

This repository contains three different tokenizers — **Unigram**, **BPE (Byte Pair Encoding)**, and **WordPiece** — each trained with different tokenization algorithms and configurations. These tokenizers are optimized for text preprocessing in NLP tasks and are available on Hugging Face.

---

## 📌 Tokenizer Descriptions

### 1. **Unigram Tokenizer**
- **Description**: A probabilistic model that starts with a large vocabulary and iteratively removes tokens to minimize the loss function. Unlike deterministic approaches like BPE, Unigram does not guarantee that every merge is kept — it focuses on selecting the most probable tokenization.
- **Use Cases**: Works well with morphologically rich languages and smaller datasets.
- **Hugging Face Model**: [Unigram Tokenizer](https://huggingface.co/yakul259/english-unigram-tokenizer-60k)

---

### 2. **BPE (Byte Pair Encoding) Tokenizer**
- **Description**: A deterministic subword segmentation algorithm that starts with individual characters and merges the most frequent pairs iteratively until a set vocabulary size is reached. BPE is widely used in modern NLP models due to its balance between vocabulary size and handling of rare words.
- **Use Cases**: Suitable for large-scale datasets and general-purpose NLP tasks.
- **Hugging Face Model**: [BPE Tokenizer](https://huggingface.co/yakul259/english_bpe_tokenizer-60k)

---

### 3. **WordPiece Tokenizer**
- **Description**: Similar to BPE but uses a probabilistic scoring method for merges instead of pure frequency counts. WordPiece was popularized by models like BERT and is designed to reduce out-of-vocabulary (OOV) words while maintaining semantic consistency.
- **Use Cases**: Best suited for transformer-based language models like BERT, ALBERT, and DistilBERT.
- **Hugging Face Model**: [WordPiece Tokenizer](https://huggingface.co/yakul259/english-wordpiece-tokenizer-60k)

---

## 🚀 Features
- **Multiple Tokenization Strategies** — Choose between Unigram, BPE, and WordPiece depending on your NLP requirements.
- **Hugging Face Integration** — Directly load the tokenizers into your pipelines.
- **Customizable Vocabulary Sizes** — Fine-tune vocabulary size for your dataset and language.
- **Optimized Preprocessing** — Efficient tokenization for both single and paired sentences.

---


## 📜 License
This repository is licensed under the MIT License.

---

## 🤝 Contributing
Feel free to open issues and pull requests to improve the tokenizers or add new configurations.

---

## 📧 Contact
For queries, reach out via [GitHub Issues](https://github.com/your-username/tokenizers-collection/issues) or [Email](arn23748@gmail.com).

