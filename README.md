# Data-Science-Experiment-Handbook
📚 Data Science Experiment Handbook: 一个致力于实现《数据科学与工程导论》课程中的各个单元的实验的实验手册。本仓库包括从数据获取、预处理、特征工程到模型构建与评估的完整流程。欢迎各位数据科学爱好者、研究者和开发者共同参与与贡献!

## 描述
本仓库目标是用“开源生态数据分析”中的各种任务作为《数据科学与工程导论》课程中的各个单元的实验；内容可参照[开源生态分析挖掘任务 - 数据科学系列课程规划](https://xlab2017.yuque.com/msdpvs/me6vqg/pffx1f7lrqkbcegl?singleDoc#)

数据分析流程：
1. 问题定义：明确需要解决的问题或目标，并确定分析的范围和目标指标。
2. 数据收集：收集相关数据，可以是从内部数据库、外部数据源、传感器等获取。确保数据的准确性和完整性。
3. 数据预处理：对收集到的数据进行清洗、去除异常值、处理缺失值等，使数据达到可用状态。
4. 数据探索：对数据进行可视化和统计分析，探索数据之间的关系、趋势和规律。可以使用统计图表、描述性统计和数据挖掘技术。
5. 特征工程：根据问题的需求和数据的特点，选择合适的特征变量，并进行特征提取、转换和选择，以提高模型的预测性能。
6. 数据建模：根据问题的性质选择适当的数据建模技术，如机器学习、统计建模等，构建预测模型或分类模型。
7. 结果评估：对建立的模型进行评估和验证，使用合适的指标评估模型的性能和准确度，如精确度、召回率、F1值等。
8. 结果解释与展示：将分析结果通过可视化方式展示，解释模型的预测结果，给出结论和建议，帮助决策者理解和应用分析结果。可以使用报告、图表、数据可视化工具等方式呈现。

## 什么是GitHub机器人？
开源软件的开发是一个合作过程，涉及到一个由地理位置分散的开发者社区，通常在GitHub这样的平台上协同工作。为了接受外部贡献，仓库通过“fork”被分享，并通过拉取请求进行修改。

机器人已经在GitHub社区中被广泛采用，用于自动化与拉取请求相关的预定义任务，从而减轻维护者的工作负担。在GitHub开源软件社区中，这些机器人表现得就像人类用户。例如，他们可以开放、关闭或评论拉取请求和问题。

GitHub机器人不仅拥有自己的用户资料，还可以像开发者一样参与各种任务。它们还扮演着开发者和外部服务之间的桥梁，如报告持续集成（CI）工具的结果。

我们定义的GitHub机器人是在GitHub环境中行为与人类用户相似的任务导向机器人。它们是一种与其他工具交互的新形式的应用程序，可以自动执行预定义任务，并将不同的服务紧密集成。

## 研究目标
通过本仓库，我们的目标是设计和实现一个模型，以准确地分类和识别GitHub上的机器人账户。这是一个分类问题，我们的数据集位于`data/github_bot_label_data.csv`，其中仅包含标签。

## 仓库内容 & 实验流程

目前实验的问题是：

| 题目                     | 任务         | 目录  |
| ------------------------ | ------------ |  -------------  |
| 机器人账号识别           | 分类任务     |  bot_detection |
| 开源社区发现             | 聚类任务     | community_discovery |
| 预测项目star数           | 回归预测任务     | predict_star |
| 开源社区评论情感分析     | NLP/分类任务 | emotion_analysis   |
| 对开发者推荐感兴趣的项目 | 推荐任务     | recommend_project |

实验流程如下：

数据收集 - 01data_collection.ipynb  
数据预处理 - 02data_preprocessing.ipynb  
数据探索 - 03data_exploration.ipynb  
特征工程 - 04feature_engineering.ipynb  
数据建模 - 05data_modeling.ipynb  
结果评估 - 06result_evaluation.ipynb  
结果解释与展示 - 07result_interpretation_presentation.ipynb  

## 贡献与参与
我们诚挚地欢迎所有对此研究感兴趣的研究者、开发者和数据科学家加入我们。无论是通过提供数据、优化模型还是提供新的见解，您的每一份贡献都对我们非常重要。

联系方式
如有任何疑问或建议，请通过 issue 提交或直接联系我们。

感谢您对 Data Science Experiment Handbook 的关注和支持！🌟
