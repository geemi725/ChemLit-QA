This directory contains:

A. The prompted train-test splits of ChemLit-QA for finetuning GPT-4o-mini, Llama2 and Mistral-7b. 
  1. llama2_mistral_train.csv: The prompted train set for finetuning Llama2 and Mistral-7b.
  2. llama2_mistral_test.csv: The prompted test set for finetuning Llama2 and Mistral-4b.
  3. gpt_train.jsonl: The prompted train set for finetuning GPT-4o-mini.
  4. gpt_test.jsonl: The prompted test set for finetuning GPT-4o-mini.

B. The evaluation results of finetuned and non-finetuned GPT-4o-mini, Llama2 and Mistral-7b on the test split of ChemLit-QA and the entire ChemLit-QA-multi. Necessary to reproduce the figures in the publication.
  1. gpt-4o-mini_eval.csv: The evaluation result for GPT-4o-mini on the test split of ChemLit-QA.
  2. multihop_gpt-4o-mini_eval.csv: The evaluation result for GPT-4o-mini on ChemLit-QA-multi.
  3. llama2-7b_eval.csv: The evaluation result for Llama2-7b on the test split of ChemLit-QA.
  4. multihop_llama2-7b_eval.csv: The evaluation result for Llama2-7b on ChemLit-QA-multi.
  5. mistal_eval.csv: The evaluation result for Mistral-7b on the test split of ChemLit-QA.
  6. multihiop_mistal_eval.csv: The evaluation result for Mistral-7b on ChemLit-QA-multi.

