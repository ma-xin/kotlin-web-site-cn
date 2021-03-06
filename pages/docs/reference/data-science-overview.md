---
type: doc
layout: reference
category: "Introduction"
title: "Kotlin 用于数据科学"
---

# Kotlin 用于数据科学

From building data pipelines to productionizing machine learning models, Kotlin can be a great choice for 
working with data:
* Kotlin is concise, readable and easy to learn.
* Static typing and null safety help create reliable, maintainable code that is easy to troubleshoot. 
* Being a JVM language, Kotlin gives you great performance and an ability to leverage an entire ecosystem 
of tried and true Java libraries. 

## Interactive editors

Notebooks such as [Jupyter Notebook](https://jupyter.org/) and [Apache Zeppelin](https://zeppelin.apache.org/) provide convenient tools for data visualization and 
exploratory research. Kotlin integrates with these tools to help you explore data, share your findings with 
colleagues, or build up your data science and machine learning skills.

### Jupyter Kotlin kernel

The Jupyter Notebook is an open-source web application that allows you to create and share documents 
(aka "notebooks") that can contain code, visualizations, and markdown text. 
[Kotlin-jupyter](https://github.com/Kotlin/kotlin-jupyter) is an open source project that brings Kotlin 
support to Jupyter Notebook. 

![Kotlin in Jupyter notebook]({{ url_for('asset', path='images/landing/data-science/kotlin-jupyter-kernel.png')}})

Check out Kotlin kernel's [GitHub repo](https://github.com/Kotlin/kotlin-jupyter) for installation 
instructions, documentation, and examples.

### Zeppelin Kotlin interpreter

Apache Zeppelin is a popular web-based solution for interactive data analytics. It provides strong support 
for the Apache Spark cluster computing system, which is particularly useful for data engineering. 
Starting from [version 0.9.0](https://zeppelin.apache.org/docs/0.9.0-preview1/), Apache Zeppelin comes with 
bundled Kotlin interpreter. 

![Kotlin in Zeppelin notebook]({{ url_for('asset', path='images/landing/data-science/kotlin-zeppelin-interpreter.png')}})

## Libraries

The ecosystem of libraries for data-related tasks created by the Kotlin community is rapidly expanding. 
Here are some libraries that you may find useful:

### Kotlin 库
* [kotlin-statistics](https://github.com/thomasnield/kotlin-statistics) 是一个为<!--
-->探索性统计与生产统计中提供扩展函数的库。它支持基本的数字列表/序列/数组函数（从 `sum` 到 `skewness`）、
切片操作符（诸如 `countBy`、 `simpleRegressionBy`）、分箱（binning）操作符、离散 PDF 采样、
朴素贝叶斯分类器、聚类、线性回归等等。

* [kmath](https://github.com/mipt-npm/kmath) 是一个受 [NumPy](https://numpy.org/) 启发的库。
这个库支持代数结构与运算、类数组结构、数学表达式、直方图、
流运算、[commons-math](http://commons.apache.org/proper/commons-math/) 与
[koma](https://github.com/kyonifer/koma) 的包装等等。

* [krangl](https://github.com/holgerbrandl/krangl) 是一个受 R 语言的 [dplyr](https://dplyr.tidyverse.org/)
与 Python 的 [pandas](https://pandas.pydata.org/) 启发的库。这个库提供了采用函数式风格 API
进行数据操作的功能；它还包括过滤、转换、聚合与重塑表格数据的函数。

* [lets-plot](https://github.com/JetBrains/lets-plot) 是一个用 Kotlin 编写的统计数据绘图库。
Lets-Plot 是多平台的，不仅可以用于 JVM，还可以用于 JS 与 Python。

* [kravis](https://github.com/holgerbrandl/kravis) 是另一个用于表格数据可视化的库，其灵感来自于
Python 的 [ggplot](https://ggplot2.tidyverse.org/)。

### Java 库

因为 Kotlin 提供了与 Java 互操作的头等支持，所以也可以在用于数据科学的 Kotlin 代码中使用 Java 库。
以下是这些库的一些示例：

* [DeepLearning4J](https://deeplearning4j.org/)——一个 Java 深度学习库

* [ND4J](http://nd4j.org/)——用于 JVM 的高效矩阵数学库

* [Dex](https://github.com/PatMartin/Dex)——一个基于 Java 的数据可视化工具

* [Smile](https://github.com/haifengl/smile)——一个全面的机器学习、自然语言处理、线性代数、图、插值与可视化系统。除了 Java API，Smile 还提供了函数式的 [Kotlin API](http://haifengl.github.io/api/kotlin/smile-kotlin/index.html) 以及 Scala 与 Clojure API。
   * [Smile-NLP-kt](https://github.com/londogard/smile-nlp-kt)——以 Kotlin 扩展函数与接口格式重写了 Smile 的自然语言处理部分的 Scala 隐式内容。

* [Apache Commons Math](http://commons.apache.org/proper/commons-math/)——一个 Java 通用数学、统计与机器学习库

* [OptaPlanner](https://www.optaplanner.org/)——一个用于优化规划问题的求解器实用程序

* [Charts](https://github.com/HanSolo/charts)——一个正在开发中的科学 JavaFX 图表库

* [CoreNLP](https://stanfordnlp.github.io/CoreNLP/)——一个自然语言处理工具包

* [Apache Mahout](https://mahout.apache.org/)——一个回归、聚类与推荐的分布式框架

* [Weka](https://www.cs.waikato.ac.nz/ml/index.html)——一组用于数据挖掘任务的机器学习算法

如果这个列表还不能满足需求，可以在 Thomas Nield 的
[**Kotlin 数据科学资源**](https://github.com/thomasnield/kotlin-data-science-resources)摘要中找到更多选项。
