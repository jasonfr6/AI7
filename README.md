# **Model Details**

The Mistral AI-7B-v0.1 Large Language Model (LLM) is a pretrained generative text model with 7 billion parameters. Mistral AI-7B-v0.1 outperforms Llama 2 13B on all benchmarks we tested.

**Model Developers** Mistral AI.

**Variations** None.

**Input** Text only.

**Output** Text only.

**Model Architecture** Mistral AI-7B-v0.1 is a transformer model, with the following architecture choices:
- Grouped-Query Attention
- Sliding-Window Attention
- Byte-fallback BPE tokenizer

**Model Dates** Mistral AI-7B-v0.1 was trained between June and September 2023.

**Status** This is a static model. Future models will have new version numbers.

**License** Apache 2.0 license.

**Research Paper** TODO: Coming soon.

**Where to send questions or comments about the model** TODO: How do people send comments?

# **Intended Use**
**Intended Use Cases** Mistral AI-7B-v0.1 is for commercial and research use. It can be adapted for a variety of natural language generation tasks.

# **Evaluation Results**
We report the standard benchmark results for Mistral AI-7B-v0.1. We use a custom evaluation library to produce the results.

| Model           | Size | hellaswag | winogrande | piqa   | boolq  | arc_easy | arc_challenge | naturalqs | naturalqs_5shot | triviaqa_5shot | triviaqa | humaneval_pass@1 | mbpp_pass@1 | mmlu   | math   | gsm8k  |
|-----------------|------|-----------|------------|--------|--------|----------|---------------|-----------|-----------------|----------------|----------|------------------|-------------|--------|--------|--------|
| Mistral-7B-v0.1 | 7B   | 81.19%    | 75.53%     | 82.92% | 83.52% | 80.01%   | 55.38%        | 23.96%    | 28.92%          | 69.88%         | 63.22%   | 29.88%           | 47.86%      | 59.99% | 11.94% | 39.35% |

**Theme-based grouping**
-   Commonsense Reasoning: 0-shot average of Hellaswag, Winogrande, PIQA, SIQA, OpenbookQA, ARC-Easy, ARC-Challenge, and CommonsenseQA.
    
-   World Knowledge: 5-shot average of NaturalQuestions and TriviaQA.
    
-   Reading Comprehension: 0-shot average of BoolQ and QuAC.
    
-   Math: Average of 8-shot GSM8K with maj@8 and 4-shot MATH with maj@4
    
-   Code: Average of 0-shot Humaneval and 3-shot MBPP
    
-   Popular aggregated results: 5-shot MMLU, 3-shot BBH, and 3-5-shot AGI Eval (English multiple-choice questions only)

# **Ethical Considerations and Limitations**
TODO: what do we say here?