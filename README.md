## Introduction

![PullRequests](https://img.shields.io/badge/PRs-Welcome-red)

This repository provides a brief summarization of [the OpenAI model API](https://platform.openai.com/docs/api-reference).

Since the OpenAI API is updated and changes quickly, it is usually hard for researchers and developers to decide *which* OpenAI model to use, and *what*'s the API name of a specific model.

To make it easier for researchers to refer to, I displayed several popular NLP models (`text` only; no `code` , embedding, image, or audio models) and attached each model with critical attributes (e.g., **token limit**, **price**, **model size**).

## Summarization

<div align="center">
<img src=./figures/2023-04-07.png width=102% title="summarization" />
</div>



📝 Some Notes:

1. The prices of `Ada`, `Babbage`, `Curie`, `Davinci` are the **fine-tuning** cost; while the prices of `gpt-4` series are the cost of **Completion**. See [OpenAI Pricing](https://openai.com/pricing) for more details.
2. The naming convention of API is `{capability}-{family}[-{input-type}]-{identifier}`. Pls refer to [this website](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/models#naming-convention) for more details.
3. The paper-report size of [InstructGPT](https://arxiv.org/abs/2203.02155) is 175B (i.e., `davinci-instruct-beta`), but there is no official model size information for the other APIs. Therefore, I fill in the table with my guess according to the API name (i.e., `davinci`). See [this forum](https://community.openai.com/t/what-is-the-model-size-of-text-davinci-001-002-003/24351).
4. Some of the imformation, such as API name, might be chaged in the future. I will try to keep it up-to-date.



Feel free to [reach out](https://renzelou.github.io/) or submit a pull request for any fallacies.



## References

1. [OpenAI models doc](https://platform.openai.com/docs/models/overview)
2. [OpenAI models pricing](https://openai.com/pricing)

3. [OpenAI Model index for researchers](https://platform.openai.com/docs/model-index-for-researchers)
4. [On the Sizes of OpenAI API Models](https://blog.eleuther.ai/gpt3-model-sizes/)
5. [How do text-davinci-002 and text-davinci-003 differ?](https://help.openai.com/en/articles/6779149-how-do-text-davinci-002-and-text-davinci-003-differ)

