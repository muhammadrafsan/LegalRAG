<h1 align="center">
LegalRAG: A Hybrid RAG System for Multilingual Legal Information Retrieval
</h1>
<p align="center">
  <strong>Official implementation of the paper [IJCNN 2025]</strong>
</p>
<p align="center">
  <a href="https://arxiv.org/abs/2504.16121">📄 Read the Paper on arXiv</a>
</p>


## Contributions
<strong>The major contributions are as follows:</strong>

✅ Introduction of an advanced multilingual RAG framework specialized for low-resource languages, specifically Bangla, to improve question-answering on complex bilingual legal documents.

✅ Unlike the conventional RAG pipeline, our approach incorporates an additional LLM for relevance checking and query refinement, ensuring that only the most relevant texts are passed to the generative model, thereby improving accuracy.

✅ A diverse Q&A test set is curated based on Bangladesh Police Gazettes to assess the performance of the system. The evaluation, conducted using human judgment and semantic similarity metrics, demonstrates that the proposed framework outperforms the conventional RAG pipeline in handling bilingual regulatory texts.

## Proposed Method
<img width="1428" height="476" alt="image" src="https://github.com/user-attachments/assets/c200e9a3-f56c-4b4e-ae89-b411bc61dce4" />
<strong>FIGURE:</strong> Proposed RAG pipeline for multilingual legal document question-answering. The yellow box highlights the RelevanceCheck and Query Refinement processes, which are introduced in our proposed novel framework to enhance the existing vanilla RAG pipeline.

## Results
<strong>TABLE:</strong> Comparison of evaluation results on the test set using two metrics: the average human evaluation score (1–5) and mean cosine similarity (µ) ± standard deviation (σ). These metrics capture both the central tendency and variability in semantic similarity. The Advanced RAG (Ours) achieves superior performance compared to the Vanilla RAG.
<img width="1365" height="281" alt="image" src="https://github.com/user-attachments/assets/de3965c8-1a8f-4ed1-9da5-4e21c631bf10" />

<br>

<strong>TABLE:</strong> Domain-wise mean cosine similarity of the employed LLMs: Mixtral8×7B, Llama 3.1 (8B), and Gemma 2 (9B). For all models, our proposed Advanced RAG method outperforms the Vanilla RAG pipeline. The gray-highlighted rows refer to the results of our proposed approach, while the bold text indicates the best result for each domain.
<img width="1539" height="337" alt="image" src="https://github.com/user-attachments/assets/832477ee-e674-4c49-984b-e8a55b025c3a" />


## Citation

If you wish to cite this work, feel free to use this [BibTeX](http://www.bibtex.org/) reference:

```bibtex
@article{kabir2025legalrag,
  title={LegalRAG: A Hybrid RAG System for Multilingual Legal Information Retrieval},
  author={Kabir, Muhammad Rafsan and Sultan, Rafeed Mohammad and Rahman, Fuad and Amin, Mohammad Ruhul and Momen, Sifat and Mohammed, Nabeel and Rahman, Shafin},
  journal={arXiv preprint arXiv:2504.16121},
  year={2025}
}
```
