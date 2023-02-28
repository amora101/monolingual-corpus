# Monolingual Corpus Dataset for Low-Resource Languages in the Horn of Africa
This repository contains a monolingual corpus dataset for low-resource languages in the Ethiopia, intended to support the development of natural language processing (NLP) and artificial intelligence (AI) for these languages. The dataset includes text data collected from various sources, including websites, social media, and digital news outlets, and requires to be preprocessed and cleaned for ease of use.

### Table of Contents
-[Background](Background)
-[Data Collection](Data Collection)
-[Data Preprocessing](Data Preprocessing)
-[Data Format](Data Format)
-[Contributing](Contributing)
-[License](License)

## Background
Ethiopia is home to a diverse range of languages, many of which are considered low-resource languages. Low-resource languages lack sufficient digital resources, such as corpora, to enable the development of NLP and AI technologies.

The aim of this repository is to provide a dataset that can be used to develop NLP and AI technologies for low-resource languages in the Horn of Africa. By doing so, we hope to contribute to the development of these languages and support their speakers in a variety of contexts.

## Data Collection
The data in this repository was collected from various sources, including websites, social media, and digital news outlets. The sources were chosen to reflect a diverse range of topics and contexts, including news, social media conversations, and online forums.

To ensure that the dataset is representative of the languages and regions of the Horn of Africa, we used a stratified sampling approach. This involved selecting sources based on a number of factors, including language, region, and topic.

## Data Preprocessing
To ensure that the dataset is clean and easy to use, we carried out a number of preprocessing steps. These included:

* Removing non-text elements, such as images and videos
* Removing URLs and other web-related content
* Normalizing text by removing diacritics and converting to lowercase
* Tokenizing text into sentences and words
* Removing stop words and punctuation
* Lemmatizing words

We used a combination of manual and automatic methods to carry out these preprocessing steps, and we manually checked a sample of the data to ensure that it was of high quality.

## Data Format
The data in this repository is provided in a plain text format (txt, json or csv), with one document per file. Each file is named according to the source of the data, and the language of the document is indicated in the file name. For example:

```
  VOAAmharic.json
  VOATigrigna.json
  dw_amharic.json
  reporter_amhari.json
```
Each document in the dataset consists of one or more sentences, with each sentence on a separate line. The sentences are tokenized, with each token separated by a space.

## Contributing
We welcome contributions to this repository, including additional data, improvements to the existing dataset or making use of the datas. If you would like to contribute, please follow these steps:

1. Fork this repository
2. Create a new branch for your changes
3. Make your changes and commit them to your branch
4. Push your changes to your fork
5. Open a pull request

We will review your changes as soon as possible and merge them if they meet our criteria for inclusion in the dataset.

## License
This dataset is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. You are free to use, share, and adapt the dataset, as long as you give appropriate credit and distribute any adaptations under the same license.

Shield:
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
