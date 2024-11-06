# LERE: A Method Based on LLMs and Enhanced EARS in Requirements Engineering

## Overview
LERE is a method designed to improve the accuracy of Chinese requirements normalization. It utilizes carefully crafted prompts to guide Large Language Models (LLMs) like Qwen2.5 and ChatGPT-4.0 in generating normalized output texts. The prompt design incorporates an enhanced version of the **EARS (Easy Approach to Requirements Syntax)** paradigm, divided into two stages to improve performance in addressing standardization issues.

### Key Features:
- **EARS enhancement**: An enhanced version of the EARS paradigm tailored for better normalization of Chinese requirements.
- **Two-stage prompt processing**: Improves accuracy by applying separate prompts in sequence.

The primary objective of this method is to resolve common issues found in Chinese requirement texts such as uniqueness, conciseness, verifiability, feasibility, and more, ensuring that the output adheres to industry standards.

## Dataset
For testing purposes, we created a dataset consisting of 138 Chinese requirement texts extracted from project-specific requirement documents. These texts were analyzed based on industry standards, the enhanced EARS paradigm, and norms for Chinese expressions. The identified standardization issues in the dataset are categorized into eight types:

1. **Uniqueness**
2. **Conciseness**
3. **Verifiability**
4. **Feasibility**
5. **Avoidance of passive voice**
6. **Adherence to paradigms**
7. **Prohibition of symbols** (e.g., parentheses, slashes "/")
8. **Prohibition of pronouns**

## Prompt Code
The repository contains the prompt code used for both the LERE method and the baseline model. Additionally, it includes the prompts used for ablation experiments: LERE without EARS  and LERE without two-step processing

These prompts can be utilized to test the impact of different components of the LERE method on the normalization process.

## Usage Instructions
1. **Models Used**: 
   - Qwen2.5
   - ChatGPT-4.0
   
2. **Steps**:
   - Input the designed prompt into the model through an interactive interface.
   - Provide the test text after inputting the prompt.
   - If using the two-step process, apply the second step's prompt to the output generated from the first step.

---

Feel free to contribute or raise issues if you encounter any problems during usage!
