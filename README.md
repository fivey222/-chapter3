# -
![对话过程](GIFhuaxiangdou.gif)
以上为导入数据库后与茴香豆助手的对话过程。
使用体验：
优点：可以快速创建属于自己的数据库，然后快速导入信息。使用非常方便，能导入ppt之类的文件来总结信息。
一些需要改进的地方：可能是网络问题，导入20MB以上的文件后，对话速度较慢，更新高精度llm后，有时反而不能识别到是否为询问问题。
学习感想：
rag是一种新的大模型训练方法，得益于检索增强生成（RAG）技术，使得茴香豆在处理特定知识领域的复杂查询时，能够给出高效且准确的回应。这种能力尤其适合在群聊环境中，快速定位问题并提供解决方案，极大地提升了沟通效率。在尝试了第四章的微调后，明显感觉到了两者速度存在不小差距。不知道为什么，在引入了一定大小的数据库后，茴香豆可能降低识别无关对话的能力，会对无关问题做出相对不符合情景的回答。
而学习课程时，虽然由于资源和时间问题没法实践，也了解了一些茴香豆的部署过程，理解了向量数据库这一概念。将已有的数据库转换成向量数据后，只要问题与库中的问题相似，即可按照外部数据库给出答案，这点免去了大量重新训练的时间
