# 工作流程
1.准备数据集，txt

2.切割 chunk

3.embedding向量化

4.储存向量化之后的数据放在数据集中（ElasticSearch）

5.把user.query向量化

6.放到数据库中进行相似性检索（TopK = ？）

7.把检索出来的结果 和 self.query 聚合成一个新的提示词
