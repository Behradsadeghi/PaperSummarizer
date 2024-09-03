# PaperSummarizer

Automated tool for fetching and summarizing the latest research papers from PubMed and arXiv using the BART large language model.

## 📚 Table of Contents
- [🌟 Introduction](#-introduction)
- [✨ Features](#-features)
- [⚙️ Installation](#%EF%B8%8F-installation)
- [📂 Dataset](#-dataset)
- [🛠️ Usage](#%EF%B8%8F-usage)
- [📊 Results](#-results)
- [📝 License](#-license)

## 🌟 Introduction
The goal of this project is to simplify the process of reviewing the latest research papers by providing concise summaries generated using BART, a state-of-the-art large language model (LLM). The tool fetches the most recent papers from PubMed and arXiv based on a user-defined query and presents them through an interactive interface. Users can easily select papers and view detailed summaries, making it easier to stay updated with current research.

## ✨ Features
- **Multi-Source Paper Fetching:** Retrieve the latest research papers from both PubMed and arXiv.
- **Automated Summarization:** Uses the BART (`facebook/bart-large-cnn`) model to generate summaries of paper abstracts.
- **Interactive Interface:** Allows users to select a paper and view its summary and details in a user-friendly interface.
- **Date-Based Sorting:** Papers are sorted by publication date to ensure that users review the most recent research.

## ⚙️ Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Pandas
- Biopython
- Transformers
- ipywidgets
- arxiv


## 📂 Dataset
This project dynamically gathers the latest data from PubMed and arXiv based on the search query provided by the user. There is no static dataset involved, ensuring that the tool always retrieves up-to-date research papers.

## 🛠️ Usage

1. **Fetch Papers:**
- The tool retrieves the most recent research papers from PubMed and arXiv based on a specific query.

2. **Summarization:**
- Abstracts of the fetched papers are summarized using the BART large language model, known for its superior summarization capabilities.

3. **Interactive Interface:**
- Select a paper from the dropdown menu to view its summary and other details.

### Running the Script
Simply run the script provided in the repository, and the interactive interface will allow you to select and view summaries of the latest fetched papers.

## 📊 Results
Upon running the script, you can expect:
- An interactive dropdown with titles of the most recent research papers.
- Summaries generated for each paper using the BART model.
- Details such as the publication date, publisher, and a link to the full paper.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.


