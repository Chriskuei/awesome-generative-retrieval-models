# awesome-generative-retrieval-models

> A curated list of awesome papers related to generative retrieval models. If I missed any papers, feel free to open a PR to include them! And any feedback and contribuitons are welcome!

Generative retrieval is meant to replace the long-lived "retrieve-then-rank" paradigm by collapsing the indexing, retrieval, and ranking components of traditional Information Retrieval (IR) systems into a single unified model.
With generative retrieval, indexing is replaced with model training, while retrieval and ranking are replaced with model inference.

## Table of Contents
- [Opinion Papers](#opinion-papers)
- [Analysis](#analysis)
- [Indexing Strategy](#indexing-strategy)
- [Identifier Design](#identifier-design)
- [Dynamic Corpora](#dynamic-corpora)
- [Applications](#applications)

***

## Opinion Papers
- [Rethinking Search: Making Domain Experts out of Dilettantes](https://arxiv.org/pdf/2105.02274.pdf). *Metzler et al.*, SIGIR Forum 2021.

## Analysis
- [Understanding Differential Search Index for Text Retrieval](https://arxiv.org/abs/2305.02073). *Chen et al.*, ACL 2023 Findings.
- [How Does Generative Retrieval Scale to Millions of Passages?](https://arxiv.org/abs/2305.11841). *Pradeep et al.*, Arxiv 2023.

## Indexing Strategy
- [Transformer Memory as a Differentiable Search Index](https://arxiv.org/abs/2202.06991). *Tay et al.*, NeurIPS 2022. [[Video](https://www.youtube.com/watch?v=qlB0TPBQ7YY)] (**DSI**)
- [CorpusBrain: Pre-train a Generative Retrieval Model for Knowledge-Intensive Language Tasks](https://arxiv.org/abs/2208.07652). *Chen et al.*, CIKM 2022. [[Code](https://github.com/ict-bigdatalab/CorpusBrain)] (**CorpusBrain**)
- [A Neural Corpus Indexer for Document Retrieval](https://arxiv.org/abs/2206.02743). *Wang et al.*, NeurIPS 2022. (**NCI**)
- [Bridging the Gap Between Indexing and Retrieval for Differentiable Search Index with Query Generation](https://arxiv.org/abs/2206.10128). *Zhuang et al.*, Arxiv 2022. [[Code](https://github.com/ArvinZhuang/DSI-transformers)] (**DSI-QG**)

## Identifier Design
- [Autoregressive Entity Retrieval](https://arxiv.org/pdf/2010.00904.pdf). *Cao et al*, ICLR 2021. [[Code](https://github.com/facebookresearch/GENRE)] (**GENRE**)
- [Autoregressive Search Engines: Generating Substrings as Document Identifiers](https://arxiv.org/pdf/2204.10628.pdf). *Bevilacqua et al.*, NeurIPS 2022. [[Code](https://github.com/facebookresearch/SEAL)] (**SEAL**)
- [DynamicRetriever: A Pre-training Model-based IR System with Neither Sparse nor Dense Index](https://arxiv.org/pdf/2203.00537.pdf). *Zhou et al*, Arxiv 2022. (**DynamicRetriever**)
- [Ultron: An Ultimate Retriever on Corpus with a Model-based Indexer](https://arxiv.org/pdf/2208.09257.pdf). *Zhou et al*, Arxiv 2022. (**Ultron**)
- [Learning to Tokenize for Generative Retrieval](https://arxiv.org/abs/2304.04171). *Sun et al*, Arxiv 2023. (**GenRet**)
- [TOME: A Two-stage Approach for Model-based Retrieval](https://arxiv.org/abs/2305.11161). *Ren et al*, ACL 2023. (**TOME**)
- [Term-Sets Can Be Strong Document Identifiers For Auto-Regressive Search Engines](https://arxiv.org/abs/2305.13859). *Zhang et al*, Arxiv 2023. (**AutoTSG**)
- [Multiview Identifiers Enhanced Generative Retrieval](https://arxiv.org/abs/2305.16675). *Li et al*, ACL 2023.

## Dynamic Corpora
- [DSI++: Updating Transformer Memory with New Documents](https://arxiv.org/pdf/2212.09744.pdf). *Mehta et al*, Arxiv 2022. (**DSI++**)
- [Continually Updating Generative Retrieval on Dynamic Corpora](https://arxiv.org/pdf/2305.18952.pdf). *Yoon et al*, Arxiv 2022. (**StreamingIR**)

## Applications
- [GERE: Generative Evidence Retrieval for Fact Verification](https://dl.acm.org/doi/pdf/10.1145/3477495.3531827). *Chen et al*, SIGIR 2022. [[Code](https://github.com/Chriskuei/GERE)] (**GERE**)
- [Generative Multi-hop Retrieval](https://arxiv.org/pdf/2204.13596.pdf). *Lee et al*, Arxiv 2022. (**GMR**)
- [Data-Efﬁcient Autoregressive Document Retrieval for Fact Veriﬁcation](https://arxiv.org/pdf/2211.09388). **Thorne**, Arxiv 2023. (**DearDR**)
- [Contextualized Generative Retrieval](https://arxiv.org/pdf/2210.02068.pdf). *Lee et al*, Arxiv 2022. (**CGR**)
- [A Unified Generative Retriever for Knowledge-Intensive Language Tasks via Prompt Learning](https://arxiv.org/abs/2304.14856). *Chen et al*, SIGIR 2023. (**UGR**)
- [Recommender Systems with Generative Retrieval](https://arxiv.org/abs/2305.05065). *Rajput et al*, Arxiv 2023. (**RQ-VAE**)
- [IRGen: Generative Modeling for Image Retrieval](https://arxiv.org/abs/2303.10126). *Zhang et al*, Arxiv 2023. (**IRGen**)
