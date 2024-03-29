---
title: "Understanding Recurrent Neural Architectures by Analyzing and Synthesizing Long Distance Dependencies in Benchmark Sequential Datasets"
date: 2018-10-01
publishDate: 2021-07-08T08:18:23.906192Z
authors: ["Abhijit Mahalunkar", "John D. Kelleher"]
publication_types: ["2"]
abstract: "In order to build efficient deep recurrent neural architectures, it isessential to analyze the complexity of long distance dependencies(LDDs) of the dataset being modeled. In this context, in this pa-per, we present detailed analysis of the complexity and the degreeof LDDs (orLDD characteristics) exhibited by various sequentialbenchmark datasets. We observe that the datasets sampled from asimilar process or task (e.g. natural language, or sequential MNIST,etc) display similar LDD characteristics. Upon analysing the LDDcharacteristics, we were able to analyze the factors influencingthem; such as (i) number of unique symbols in a dataset, (ii) sizeof the dataset, (iii) number of interacting symbols within a givenLDD, and (iv) the distance between the interacting symbols. Wedemonstrate that analysing LDD characteristics can inform theselection of optimal hyper-parameters for SOTA deep recurrentneural architectures. This analysis can directly contribute to thedevelopment of more accurate and efficient sequential models. Wealso introduce the use of Strictlyk-Piecewise languages as a pro-cess to generate synthesized datasets for language modelling. Theadvantage of these synthesized datasets is that they enable targetedtesting of deep recurrent neural architectures in terms of their abil- ity to model LDDs with different characteristics. Moreover, usinga variety of Strictlyk-Piecewise languages we generate a numberof new benchmarking datasets, and analyse the performance of anumber of SOTA recurrent architectures on these new benchmarks."
featured: false
publication: "*arXiv e-prints*"
tags: ["Computer Science - Machine Learning", "Statistics - Machine Learning"]
url_pdf: "https://arxiv.org/pdf/1810.02966.pdf"
---

