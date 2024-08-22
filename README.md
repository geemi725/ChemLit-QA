# ChemLit-QA
A comprehensive, expert-validated dataset comprising over 1,000 entries specifically designed for the field of chemistry. The dataset was curated by an initial generation and filtering of a QAC dataset using an automated framework based on GPT-4, followed by rigorous evaluation by Chemistry experts. Additionally, we provide two supplementary datasets **ChemLit-QA-neg** focused on negative data, and **ChemLit-QA-multi** focused on multihop reasoning tasks for LLMs, further enhancing the resources available for advanced scientific research.

We provide the full **ChemLit-QA** dataset and its variants in this repository, as well as the exact train-test split of **ChemLit-QA** that was used in the fine-tuning task.

## Overview
![abstract-fig](https://github.com/user-attachments/assets/ecb0fb9a-4200-47c9-bf35-b3a3a1680a9f)

## Dataset description
| Field | Description |
| --- | --- |
| chunk | The text chunk from which the Question-Answer-Context (QAC) triple is generated. |
| Reasoning_type | Expert-corrected reasoning type. Includes 7 categories: Explanatory, Comparative, Causal, Conditional, Analogical, Evaluative, Predictive |
| Question | LLM-generated question|
| Answer | Expert-corrected answer|
| Difficulty | Expert-assigned difficulty. Includes 3 categories: Easy, Medium, Hard|
| Context | Expert-corrected context. Contains the **full sentences** that supports the answer.|
| A_start_end | The start-end indices of the most similar sentences in the chunk|
| similar_chunks| The top 6 most similar chunks to the given chunk in terms of cosine similarity|
| Cluster_labels | 2-level hierarchical label describing the topic of this chunk|
| ID | Identifier of the entry|
| Answer Relevancy Scores_gpt-4o | How relevant the answer is to the question, assessd by GPT-4o|
| Faithfulness Scores_gpt-4o | How faithful the answer is to the context, assessd by GPT-4o|
| Hallucination Scores_gpt-4o | How much information in the answer is not mentioned in the context, assessd by GPT-4o|
| Question Faithfulness Scores_gpt-4o | How faithful the question is to the context, assessd by GPT-4o|
| SE_penalized | Penalized Semantic Entropy of the question|
| Keywords | Keywords of the question|


<img src="https://github.com/user-attachments/assets/99d462d4-e0b6-41e9-8a7a-5b9ee5fe3b22" width=50% height=50%>

Percentage distribution of reasoning types in ChemLit-QA.

<img src="https://github.com/user-attachments/assets/ac596029-6fa5-42af-9c3f-565dae394b8e" width=50% height=50%>

Proportion of difficulty levels in each reasoning type.

<img src="https://github.com/user-attachments/assets/34569ba4-2352-4836-9d45-9ecac487bf8f" width=50% height=50%>

Distribution of topic in ChemLit-QA.

