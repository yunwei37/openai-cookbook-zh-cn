# OpenAI Cookbook

OpenAI Cookbook 分享使用 [OpenAI API] 完成常见任务的示例代码。

要运行这些示例，您需要 OpenAI 帐户和关联的 API 密钥（[创建免费帐户] [api signup]）。

大多数代码示例都是用 Python 编写的，但这些概念也可以应用在任何语言中。

## 最近添加的 🆕 ✨

- [如何为 ChatGPT 模型格式化输入]（examples/How_to_format_inputs_to_ChatGPT_models.ipynb）[2023年3月1日]
- [使用向量数据库和Redis进行嵌入搜索]（https://github.com/openai/openai-cookbook/tree/main/examples/vector_databases/redis）[2023年2月15日]
- [使用嵌入进行网站问答]（https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a）[2023年2月11日]
- [使用嵌入进行文件问答]（https://github.com/openai/openai-cookbook/tree/main/apps/file-q-and-a）[2023年2月11日]
- [在 Weights＆Biases 中可视化嵌入]（https://github.com/openai/openai-cookbook/blob/main/examples/Visualizing_embeddings_in_W%26B.ipynb）[2023年2月9日]
- [使用 Pinecone 进行检索增强生成式问答]（https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/pinecone/Gen_QA.ipynb）[2023年2月8日]

## 指南和示例

- API用法
  - [如何处理速率限制]（examples/How_to_handle_rate_limits.ipynb）
    - [避免命中速率限制的示例并行处理脚本](examples/api_request_parallel_processor.py)
  - [如何使用 tiktoken 计算令牌数量](examples/How_to_count_tokens_with_tiktoken.ipynb)
  - [如何流式完成](examples/How_to_stream_completions.ipynb)
- ChatGPT
  - [如何为 ChatGPT 模型格式化输入]（examples/How_to_format_inputs_to_ChatGPT_models.ipynb）
- GPT-3
  - [指南：如何使用大型语言模型]（how_to_work_with_large_language_models.md）
  - [指南：提高可靠性的技术]（techniques_to_improve_reliability.md）
  - [如何使用多步提示编写单元测试]（examples/Unit_test_writing_using_a_multi-step_prompt.ipynb）- [文本写作示例](text_writing_examples.md)
  - [文本解释示例](text_explanation_examples.md)
  - [文本编辑示例](text_editing_examples.md)
  - [代码编写示例](code_writing_examples.md)
  - [代码解释示例](code_explanation_examples.md)
  - [代码编辑示例](code_editing_examples.md)
- 嵌入
  - [文本比较示例](text_comparison_examples.md)
  - [如何获取嵌入](examples/Get_embeddings.ipynb)
  - [使用嵌入进行问答](examples/Question_answering_using_embeddings.ipynb)
  - [使用嵌入进行语义搜索](examples/Semantic_text_search_using_embeddings.ipynb)
  - [使用嵌入进行推荐](examples/Recommendation_using_embeddings.ipynb)
  - [聚类嵌入](examples/Clustering.ipynb)
  - [在2D中可视化嵌入](examples/Visualizing_embeddings_in_2D.ipynb) 或 [在3D中](examples/Visualizing_embeddings_in_3D.ipynb)
  - [嵌入长文本](examples/Embedding_long_inputs.ipynb)
- 对GPT-3进行微调
  - [指南：微调GPT-3以分类文本的最佳实践](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  - [经过微调的分类](examples/Fine-tuned_classification.ipynb)
- DALL-E
  - [如何使用DALL-E生成和编辑图像](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
- Azure OpenAI（来自Microsoft Azure的替代API）
  - [如何从Azure OpenAI中获取完成](examples/azure/completions.ipynb)
  - [如何从Azure OpenAI中获得嵌入](examples/azure/embeddings.ipynb)
  - [如何使用Azure OpenAI微调GPT-3](examples/azure/finetuning.ipynb)
- 应用程序
  - [文件问答](apps/file-q-and-a/)
  - [Web爬取问答](apps/web-crawl-q-and-a)

## 相关资源

除了这里的代码示例，您还可以从以下资源中了解有关[OpenAI API]的信息：

- 在[OpenAI Playground]中尝试API
- 在[OpenAI文档]中阅读有关API的信息
- 在[OpenAI社区论坛]中讨论API".- 在[OpenAI Help Center](https://help.openai.com/en/)中寻求帮助
- 查看[OpenAI Examples](https://beta.openai.com/examples)中的示例提示
- 通过[ChatGPT](https://chat.openai.com/)免费试用研究预览
- 通过[OpenAI Blog](https://openai.com/blog/)保持最新

## 参与贡献

如果您想要查看示例或指南，请随时在[issues page](https://github.com/openai/openai-cookbook/issues)上提出建议。