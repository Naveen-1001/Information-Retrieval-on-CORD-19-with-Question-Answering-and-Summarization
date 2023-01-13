## Information-Retrieval-on-CORD-19-with-Question-Answering-and-Summarization

Many research articles on COVID-19 have been
published over the last few years. More than 400,000 such articles
have been collected and are available through the COVID-19
Open Research Dataset (CORD). Effective information retrieval
over the dataset can help health workers and scientific re-
searchers. 

We present a COVID-19 information
retrieval system with question-answering and summarization.
Various keyword-based and neural-network-based models are
used to efficiently reduce the search space and find relevant
sentences from the vast corpus. These sentences are further
shortlisted using a combination of various scoring metrics. The
retrieved sentences are then used for abstractive summarization.
Finally, the summary and the query are used for question
answering. 

### Methodology

<p align = "center">
<img src="https://user-images.githubusercontent.com/71968107/212251601-aa5d729b-d0bf-4003-94e0-65a9a7298485.png" width=75%>
</p>
                                                                                                                
### Results
We evaluate the proposed model using various metrics
on the CovidQA dataset for both natural language and keyword
queries. The proposed approach achieves 0.177 P@1, 0.244 R@3
and 0.268 MRR for natural language queries, 0.162 P@1, 0.236
R@3 and 0.258 MRR for keyword queries. The proposed model
outperforms various unsupervised model baselines in both types
of queries for most of the metrics.

#### Contributors
* Pratham Nayak
* Naveen Shenoy
* Sarthak Jain

