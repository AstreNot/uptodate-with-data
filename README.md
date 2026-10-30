# Up to date with data

Daily learning log and module notebooks on the path to **data science / AI engineering**.
All notebooks use synthetic data and are solved, so they run top to bottom (Colab or local).

## How it works
- One **notebook per day** (Mon–Fri) in `notebooks/WW_module/DD_topic.ipynb`: business question, from-scratch build, quantified impact, limits, references. Each week is one module (table below).
- Notebooks are drafted in `drafts/` (git-ignored), reviewed, then moved to `notebooks/` and published.
- One short **log** entry in `log/YYYY-MM-DD.md`: what I learned, what confused me, tomorrow's goal.

## Track: 2 Nov – 31 Dec 2026

| Wk | Starts | Module | Business simulation | Core reference |
|----|--------|--------|---------------------|----------------|
| 1 | 2 Nov | The learning problem: perceptron, feasibility, Hoeffding | Retail churn flag | [1], [2] |
| 2 | 9 Nov | Linear models, error and noise, train/test split | Demand and churn scoring | [1], [3] |
| 3 | 16 Nov | Overfitting, regularization, validation | Forecast that fails in production | [1], [3] |
| 4 | 23 Nov | SQL, data modeling, data quality tests | Clean pipeline vs dirty data | [4] |
| 5 | 30 Nov | Trees, ensembles, metrics and cost-sensitive decisions | Fraud / churn with action cost | [3], [5] |
| 6 | 7 Dec | Neural networks and deep learning basics | Image or tabular classifier | [6] |
| 7 | 14 Dec | Transformers, embeddings | Semantic search over documents | [7], [8] |
| 8 | 21 Dec | RAG, evaluation, data governance | Support-answer assistant | [9] |
| – | 28–31 Dec | Capstone polish, README, portfolio link | End-to-end project | – |

## References
1. Abu-Mostafa, Magdon-Ismail & Lin (2012). *Learning From Data*. AMLBook.
2. Hoeffding, W. (1963). Probability inequalities for sums of bounded random variables. *JASA*, 58(301), 13–30.
3. James, Witten, Hastie & Tibshirani (2021). *An Introduction to Statistical Learning* (2nd ed.). Springer.
4. Kleppmann, M. (2017). *Designing Data-Intensive Applications*. O'Reilly.
5. Hastie, Tibshirani & Friedman (2009). *The Elements of Statistical Learning* (2nd ed.). Springer.
6. Goodfellow, Bengio & Courville (2016). *Deep Learning*. MIT Press.
7. Vaswani et al. (2017). Attention is all you need. *NeurIPS*.
8. Rosenblatt, F. (1958). The perceptron. *Psychological Review*, 65(6), 386–408.
9. Lewis et al. (2020). Retrieval-augmented generation for knowledge-intensive NLP tasks. *NeurIPS*.
