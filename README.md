# A Cross-Lingual Question Answering Architecture Based on Pre-trained Token-Free Model with Instruction Fine-tuning
**Yi Dai, Franklin Kong, Chenshun Ni, Xiyu Tian**

## Project Overview:
Most widely used cross-lingual question answering (QA) systems are operated with human/machine translation, which use large language models (LLM) based on sequences of tokens corresponding to words or subwords units. 
However, current cross-lingual QA systems have limitations, such as difficulty on answering questions independently on the source language.
In this report, we propose a cross-lingual QA architecture that fine-tunes state-of-the-art token-free LLM ByT5 on the modified XQuAD to extract answers from the source in different language. 
We set ByT5-base without fined-tuned as baseline, and test several fine-tuned variants of ByT5. We evaluate the performance of not only all variants of ByT5 on the cross-lingual QA task, but also the architecture with machine translation with different variants of ByT5. Results demonstrate that mono-lingual instruction-tuned ByT5 model outperforms others on mono-lingual QA task, and cross-lingual instruction-tuned ByT5 model has the best performance on the cross-lingual QA task.
