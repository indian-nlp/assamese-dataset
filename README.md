
<div align="center">
  <a href="https://github.com/indian-nlp/assamese-dataset">
    <img src="https://raw.githubusercontent.com/indian-nlp/assamese-dataset/master/img/indian-nlp-pi.png" alt="Logo" height="120">
  </a>

<h3 align="center">Assamese Datasets</h3>

  <p align="center">
    A collection of various NLP datasets in Assamese. These datasets are split into two: pre-training corpora and fine-tuning datasets.
    <br />
    <a href="https://github.com/indian-nlp/assamese-dataset/blob/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/indian-nlp/assamese-dataset/issues">Report Bug</a>
    <a href="https://github.com/indian-nlp/assamese-dataset/issues">Request Feature</a>
  </p>
</div>

---

# Table of Contents

- [Pre-training Corpora](#pre-training-corpora)
  - [Assamese Wikipedia v1](#assamese-wikipedia-v1)
  - [Assamese Wikipedia v2](#assamese-wikipedia-v2)
  - [CC-100 Monolingual](#cc-100-monolingual)
  - [The C4 Multilingual Dataset](#the-c4-multilingual-dataset)
- [Fine-tuning Datasets](#fine-tuning-datasets)
  - [Sundanese Twitter Dataset for Emotion Classification](#sundanese-twitter-dataset-for-emotion-classification)
  - [Assamese Poem - কবিতা](#assamese-poem---কবিতা)
- [To Be Added](#tba)

---

# Pre-training Corpora

## [Assamese Wikipedia v1](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_10K)

> Assamese Wikipedia documents from Wikidump from 2021. Collected on June 2024.

- Assamese - 10k

---

## [Assamese Wikipedia v2](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K)

> Assamese Wikipedia documents from Wikidump from 2021. Collected on June 2024.

- Assamese - 100k

---

## [CC-100 Monolingual\*](http://data.statmt.org/cc-100/)

> "This corpus comprises of monolingual data for 100+ languages [...] This was constructed using the urls and paragraph indices provided by the CC-Net repository by processing January-December 2018 Commoncrawl snapshots."

- Assamese (7.6 MB)

\*_external resource_

---

## [The C4 Multilingual Dataset\*](https://github.com/allenai/allennlp/discussions/5056)

> "A colossal, cleaned version of Common Crawl's web crawl corpus. Based on Common Crawl dataset."

- Assamese (?)

\*_external resource_

---

# Fine-tuning Datasets

## [Assamese Sentiments Dataset\*](https://www.kaggle.com/datasets/ritikjain00/assamese-sentiments-dataset)

> Ritik Kumar Jain, from [Kaggle.com](https://www.kaggle.com/datasets/ritikjain00/assamese-sentiments-dataset)

\*_external resource_

---

## [Assamese Wikipedia Sentences Dataset\*](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K)

> Sagar Tamang, cleaned and formatted into jsonl format. Assamese Wikipedia documents from Wikidump from 2021. Collected on June 2024.

Non-chat | Non-commmands | TXT "text" atrs:
- [Assamese Wikipedia Sentences TXT Dataset](https://github.com/indian-nlp/assamese-dataset/tree/master/fine-tuning-datasets/asm_wikipedia_10k_sentences/assamese_cleaned.txt)
- [Assamese Wikipedia Sentences JSONL Dataset](https://github.com/indian-nlp/assamese-dataset/tree/master/fine-tuning-datasets/asm_wikipedia_10k_sentences/assamese_cleaned.jsonl)

\*_external resource_

---

## [Assamese ChatGPT Generated Dataset for Fine Tuning\*](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K/output_100k_split_1.jsonl)

> Special thanks to [Prasurjan Pran Borah](https://x.com/iamppborah) for providing me the API for ChatGPT, through which this dataset was generated for the purpose of finetuning an LLM in Assamese.

> The words are taken from [Assamese Wikipedia v2's Word](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K/asm_wikipedia_2021_100K-words.txt) split in 1/10.

> Each word is sent along with a prompted to the ChatGPT to generate valid dataset that describes that word, making it suitable for fine tuning.

Non-Chat | Non-commmands | JSONL "word" and "sentence":
- [Assamese ChatGPT Generated Dataset for Fine Tuning Split 1/10 v1.0](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K/output_100k_split_1.jsonl)

Chat | Non-commmands | JSONL "text" attrs:
- [Assamese ChatGPT Generated Dataset for Fine Tuning Split 1/10 v1.1](https://github.com/indian-nlp/assamese-dataset/tree/master/asm_wikipedia_2021_100K/output_100k_split_1_chat.jsonl)

---

## [Assamese Poem - কবিতা\*](https://www.kaggle.com/datasets/sanikamal/assamese-poem)

> Sani Kamal, from [Kaggle.com](https://www.kaggle.com/datasets/sanikamal/assamese-poem)

\*_external resource_

---

# TBA

- Assamese dictionary datasets
  - [http://xobdo.org/](http://xobdo.org/)
