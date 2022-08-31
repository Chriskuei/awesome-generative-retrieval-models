# awesome-generative-retrieval-models

> A curated list of awesome papers related to generative retrieval models. If I missed any papers, feel free to open a PR to include them! And any feedback and contribuitons are welcome!

Generative retrieval is meant to replace the long-lived "retrieve-then-rank" paradigm by collapsing the indexing, retrieval, and ranking components of traditional Information Retrieval (IR) systems into a single unified model.
With generative retrieval, indexing is replaced with model training, while retrieval and ranking are replaced with model inference.

## Table of Contents
- [Opinion Papers](#opinion-papers)
- [Indexing Startegy](#indexing-startegy)
- [Identifier Design](#identifier-design)
- [Application](#application)

***

## Opinion Papers

- [Rethinking Search: Making Domain Experts out of Dilettantes](https://arxiv.org/pdf/2105.02274.pdf) *Metzler et al.*, SIGIR Forum 2021.

## Indexing Strategy
- [Transformer Memory as a Differentiable Search Index](https://arxiv.org/abs/2202.06991) *Tay et al.*, Arxiv 2022. [[Video](https://www.youtube.com/watch?v=qlB0TPBQ7YY)] (**DSI**)
- [CorpusBrain: Pre-train a Generative Retrieval Model for Knowledge-Intensive Language Tasks](https://arxiv.org/abs/2208.07652) *Chen et al.*, CIKM 2022. [[Code](https://github.com/ict-bigdatalab/CorpusBrain)] (**CorpusBrain**)
- [A Neural Corpus Indexer for Document Retrieval](https://arxiv.org/abs/2206.02743) *Wang et al.*, Arxiv 2022. (**NCI**)
- [Bridging the Gap Between Indexing and Retrieval for Differentiable Search Index with Query Generation](https://arxiv.org/abs/2206.10128) *Zhuang et al.*, Arxiv 2022. [[Code](https://github.com/ArvinZhuang/DSI-transformers)] (**DSI-QG**)

## Identifier Design
- [Autoregressive Entity Retrieval](https://arxiv.org/pdf/2010.00904.pdf) *Cao et al*, ICLR 2021. [[Code](https://github.com/facebookresearch/GENRE)] (**GENRE**)
- [Autoregressive Search Engines: Generating Substrings as Document Identifiers](https://arxiv.org/pdf/2204.10628.pdf) *Bevilacqua et al.*, Arxiv 2022. [[Code](https://github.com/facebookresearch/SEAL)] (**SEAL**)
- [DynamicRetriever: A Pre-training Model-based IR System with Neither Sparse nor Dense Index](https://arxiv.org/pdf/2203.00537.pdf) *Zhou et al*, Arxiv 2022. (**DynamicRetriever**)
- [Ultron: An Ultimate Retriever on Corpus with a Model-based Indexer](https://arxiv.org/pdf/2208.09257.pdf) *Zhou et al*, Arxiv 2022. (**Ultron**)

## Applications
- [GERE: Generative Evidence Retrieval for Fact Verification](https://dl.acm.org/doi/pdf/10.1145/3477495.3531827) *Chen et al*, SIGIR 2022. [[Code](https://github.com/Chriskuei/GERE)] (**GERE**)
- [Generative Multi-hop Retrieval](https://arxiv.org/pdf/2204.13596.pdf) *Lee et al*, Arxiv 2022. (**GMR**)
