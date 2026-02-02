# 毕业论文大纲

## 整体写作思路

在面向大模型的推理任务批式调度和 KV 缓存优化这个主题下完成了两个方法：UELLM和Banaserve。


## 1. 目录部分

1. 绪论
   1. 研究背景
      - 参考UELLM和banaserve的研究背景
   2. 研究意义
   3. 国内外研究现状
   4. 论文主要工作
   5. 论文组织架构
2. 现有LLM的推理任务批式任务调度和KV 缓存优化的方法
   1. 现有的LLM的推理任务的批式任务调度方法
      1. S3
      2. continues batching
      3. Orca 中的In-flight Batching批处理机制
      4. 传统组合（FIFO，短作业优先，长作业优先）
   2. 现有的KV 缓存优化方法
      1. mooncake
      2. memserve
      3. vLLM
      4. 量化
   3. 现有方法的缺陷
3. 面向LLM推理任务的高效批式调度和部署方法
   1. 参考（翻译）UELLM这个论文
4. 面向PD分离架构的资源管理和KV缓存优化方法
   1. 参考（翻译）BanaServe这个论文
5. 总结

