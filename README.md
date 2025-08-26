# Enhanced Few-Shot Multilingual Translation Using mBART + LoRA

This repository contains an implementation of an enhanced few-shot learning approach for multilingual Neural Machine Translation (NMT) tailored to low-resource languages. The system fine-tunes the pre-trained `mBART-50` model with Low-Rank Adaptation (LoRA) to efficiently adapt translations on minimal datasets. It supports 7 Indian languages plus Nepali.

---

## Features

- Few-shot learning for low-resource language translation
- Fine-tuning of mBART-50 large multilingual model
- Low-Rank Adaptation (LoRA) for efficient parameter tuning
- Supports Hindi, Bengali, Tamil, Telugu, Marathi, Gujarati, and Nepali
- Language code validation and error handling
- Interactive command-line interface for translations
- Save translations in JSON format with timestamps
- Training pipeline implemented using Hugging Face Transformers and Datasets libraries

---

## Installation

