# RAG Learning
- 使用Langchain + LLM搭建
- 过程：Question-->Indexing-->Retrieval-->Generation-->Answer
- 输入问题--把问题转化为计算机理解的语言--把问题对应到相应的数据库--搜索答案--生成答案
Indexing：把知识（文档）通过切分Chunking、向量化Embedding、构建索引数据库Index building、添加元数据matadata的方式转化为可以被计算机存储且检索的格式（向量）。不同的知识占据语义高维向量图中的一个坐标，相似的知识坐标也相近。
Retrieval：把输入的问题向量化，在数据库中找到相似度最高的知识文档，把参考文档和问题送入LLM模型，进行Answer Generation
