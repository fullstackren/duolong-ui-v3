# LangChain 的独白

我们都知道[市面上的大型语言模型（LLM）](https://ai.fullstack.ren/basic/large-model-material)都是回答**通用问题**。我们的开发者是在实际工作中，所在公司多多少少都会有自己的产品，这些产品会有对应的[知识库](https://ai.fullstack.ren/basic/large-model-architecture)，但这些知识库是不对外开放的（商业机密哈），所以市面上的大型语言模型（LLM）是无法回答**关于公司产品的问题**。那如何让大型语言模型（LLM）除了回答**通用问题**，还能回答**关于公司产品的问题**呢？如何将这些回复通过**邮件或钉钉**通知呢？我（LangChain） 就是为了解决这些问题而生的。

我（LangChain）是一个语言模型驱动、开源的 AI 应用程序框架，允许开发人员像 GPT-4 这样的大型语言模型（LLM）与**外部的计算机和数据源**结合。