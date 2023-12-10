---
permalink: /
# title: "DigiCall"
excerpt: "About me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<img src="images/banner.png">

# DigiCall

## A Benchmark for Measuring the Maturity of Digital Strategy through Company Earning Calls

Digital transformation reinvents companies, their vision and strategy, organizational structure, processes, capabilities, culture, and enables the development of new or enhanced products and services delivered to customers more efficiently. By formalizing their digital strategy, organizations attempt to plan for their digital transformations and accelerate their company growth. Understanding how successful a company is in its digital transformation starts with accurately measuring its digital maturity levels. However, existing approaches to measuring organizations' digital strategy have inconsistent results, and also do not provide resources (data) for future research to improve. In order to measure the digital strategy maturity of companies and provide a benchmark, we leverage the state-of-the-art NLP models on unstructured data (earning call transcripts), and reach the state-of-the-art F1 levels (94%) for this task. We release 3.691 earning call transcripts and also annotated data set labeled particularly for the digital strategy maturity by linguists.

Paper:  [DigiCall:FinNLP@EMNLP](https://aclanthology.org/2022.finnlp-1.7/)<br>

Background
====
- Digital transformation reinvents companies, their vision and strategy, organizational structure, processes, capabilities, and culture and enables the development of new or enhanced products and services delivered to customers more efficiently (Bharadwaj et al., 2013; Al-Ali et al., 2020; Jackson, 2015; Freitas Junior et al., 2016).
- Global spending on digital transformation will reach 2.8 trillion dollars by 2025 and exceed 10 trillion dollars over five years (IDC, 2021).
- Understanding how successful a company is in its digital transformation starts with accurately measuring its digital maturity levels.
- Existing approaches to measuring organizations’ digital strategy has inconsistent results and also do not provide resources (data) for future research to improve.

Prediction of Digital Maturity from Earning Call Transcripts
======
- In order to measure and evaluate the digital strategy of firms, the status quo of a company’s digital transformation and the digital maturity level are measured (Thordsen et al., 2020; Kane et al., 2017).
- We predict the maturity of the digital strategy of S&P 500 companies by leveraging transformer-based models with domain knowledge.
- The most similar work to ours (Al-Ali et al., 2020)’s that uses earning call transcripts but does not release any data.

Pipeline
======
<img src="images/pipeline.png" usemap="#image-map" alt="Map" />

<map name="image-map">
    <area target="" alt="Section 1" title="Section 1" href="#section1" coords="34,44,270,350" shape="rect">
    <area target="" alt="Section 2" title="Section 2" href="#section2" coords="280,45,500,350" shape="rect">
    <area target="" alt="Section 2" title="Section 2" href="#section2" coords="280,45,500,350" shape="rect">
</map>

Download Data
------
[Labelled Data](https://github.com/hpataci/DigiCall/raw/main/annotated_data.csv)<br>
[Raw Data (2018 A-M)](https://github.com/hpataci/DigiCall/raw/main/2018_A_M.zip)<br>
[Raw Data (2018 N-Z)](https://github.com/hpataci/DigiCall/raw/main/2018_N_Z.zip)<br>
[Raw Data (2019 A-M)](https://github.com/hpataci/DigiCall/raw/main/2019_A_M.zip)<br>
[Raw Data (2019 N-Z)](https://github.com/hpataci/DigiCall/raw/main/2019_N_Z.zip)<br>

Model Results
------
<img src="images/results.png">

An Example : IBM 2018 Q4
---
<img src="images/ibm.png">
<br><br>
<img src="images/maturity_table1.png" width="50%">
<br><br>
<img src="images/maturity_table2.png" width="50%">

Exploratory Analysis: Stock Returns and Digital Strategy Initiative Maturity
----
<img src="images/eda.png">