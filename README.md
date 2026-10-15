# fundoc

本仓库讨论并沉淀"如何构建 AI 能用的知识库"的方法论——不是某个工具的使用手册，而是在
把文档交给 RAG / Agent 消费之前，内容本身该怎么组织、怎么结构化、怎么维护。

## 文档

| 文档 | 内容 |
| --- | --- |
| [如何构建 AI 能用的知识库](docs/ai-knowledge-base-guide.md) | "给人看"和"给 AI 用"的差别、内容原子化与目录组织、分类体系 / 本体论 / 知识图谱三层工具、文档格式规范、面向检索的分块策略、向量检索与 GraphRAG 的取舍、内容治理闭环、常见误区、落地检查清单 |

核心判断：AI 知识库的瓶颈不在模型和工具，而在内容本身的结构化程度和持续维护机制。

## 使用

本仓库只有 Markdown 文档，没有需要安装的代码。在线阅读直接点上面的链接；想在本地检索或
拿去喂给自己的知识库，克隆下来即可：

```bash
git clone https://github.com/farfarfun/fundoc.git
cd fundoc
```

落地时建议的用法：拿 [`docs/ai-knowledge-base-guide.md`](docs/ai-knowledge-base-guide.md)
末尾的检查清单逐条过一遍自己现有的文档库，先修内容，再挑工具。

## 关于组织

[farfarfun](https://github.com/farfarfun) 是一个专注于实用工具库的开源组织，涵盖云存储、
数据处理、AI、多媒体与开发工具链等方向。本仓库在其中承担的是方法论文档的角色：面向
知识库 / RAG 的内容侧规范，与面向代码仓库的开发规范文档
[fundev-doc](https://github.com/farfarfun/fundev-doc) 分工互补。

- 🏠 组织主页：<https://github.com/farfarfun>
- 📦 PyPI：<https://pypi.org/user/niuliangtao/>
- 📧 联系：farfarfun@qq.com
