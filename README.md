# Recipe Generation Using Small Language Models

This repository presents a Natural Language Processing project focused on generating cooking instructions from a given recipe title and list of ingredients using small transformer-based models. The primary objective is to develop efficient models suitable for low-resource environments while maintaining quality and fluency in text generation.

---

## Project Overview

* **Goal**: Automate recipe instruction generation using compact NLP models.
* **Approach**: Fine-tune small transformer architectures including DistilBERT, DistilRoBERTa, and T5-Small.
* **Tools & Frameworks**: Python, PyTorch, HuggingFace Transformers, Google Colab, BLEU, ROUGE.

---

## Repository Contents

| File Name             | Description                                                     |
| --------------------- | --------------------------------------------------------------- |
| `DistilBert.ipynb`    | Recipe generation using the DistilBERT model                    |
| `DistilRoberta.ipynb` | Implementation using the DistilRoBERTa model                    |
| `T5.ipynb`            | Text-to-text instruction generation using the T5-Small model    |
| `Report.pdf`          | Detailed report including methodology, experiments, and results |
| `Poster.pdf`          | Project poster summarizing the key contributions                |

---

## Features

* End-to-end NLP pipeline from preprocessing to instruction generation
* Tokenizer-specific data handling
* Evaluation using BLEU and ROUGE metrics for content quality
* Focus on lightweight models for deployment in constrained environments

---

## Key Results

* The T5-Small model showed the most coherent and contextually appropriate instruction generation.
* Evaluation scores using BLEU and ROUGE highlighted the model's ability to produce high-quality outputs.
* Models were optimized for performance while minimizing resource usage.

---

## Future Work

* Incorporate ingredient-level embeddings for enhanced context
* Extend to multi-modal inputs (e.g., image + ingredients)
* Develop a lightweight deployment interface for mobile or web

---

## Authors

* Kanak Yadav
This project was developed as part of the **CSE556: Natural Language Processing (Spring 2025)** course at IIIT-Delhi.

---

## How to Run

1. Clone the repository.
2. Open any of the `.ipynb` files in Google Colab or Jupyter Notebook.
3. Run the cells in sequence to train or evaluate the models.
4. GPU acceleration (e.g., on Colab) is recommended for faster execution.

---

## License

This repository is intended for academic and educational use only. All rights reserved by the authors.

