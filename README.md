# BA865 Neural Networks in Business: Clickbait Detection

## Project Overview

This project focuses on building a machine learning and deep learning pipeline to detect clickbait content from online post text. The objective is to classify whether a given post is clickbait or non-clickbait based on its textual content, and to evaluate how neural network models can improve classification performance compared with baseline approaches.

Clickbait detection is a relevant business problem for digital platforms, news publishers, advertisers, and content moderation teams. Misleading or exaggerated headlines can increase short-term engagement but may reduce user trust, damage brand credibility, and create poor information quality. This project applies natural language processing and neural network methods to support more reliable content classification.

---

## Business Problem

Online platforms often need to identify clickbait-style posts at scale. Manual review is costly and inconsistent, while rule-based systems may fail to capture language patterns such as curiosity gaps, emotional wording, exaggeration, and misleading framing.

This project addresses the following question:

**Can a neural network model accurately classify clickbait and non-clickbait posts using post text data?**

The model output can support business decisions such as:

- Flagging potentially misleading content
- Improving content recommendation quality
- Supporting editorial review workflows
- Reducing low-quality engagement incentives
- Protecting long-term user trust

---

## Dataset


The full dataset is not stored in this GitHub repository due to file size limitations.

To reproduce the project, download the dataset from Google Drive and place the folders in the project root directory:

- train1/
- train2/
- test/
- unlabeled/

Each split contains:
- instances.jsonl
- truth.jsonl

- Google Drive data link:https://drive.google.com/drive/folders/1sSrchVpp9GNTZmMSgZvD8Ed6JpdYm5FC?usp=sharing
