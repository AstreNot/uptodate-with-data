# Up to date with data

Daily learning log and notebooks on the path to **data science / AI engineering**.
Foundations come from *Learning From Data* [1]; each week adds an optimization or AI-engineering topic.
All notebooks use synthetic data and are solved, so they run top to bottom (Colab or local).

## How it works
- One **notebook per weekday** in `notebooks/WW_module/DD_topic.ipynb`: business question, from-scratch build, quantified impact, limits, references.
- Notebooks are drafted in `drafts/` (git-ignored), reviewed, then moved to `notebooks/` and published.
- One short **log** entry in `log/YYYY-MM-DD.md`: what I learned, what confused me, tomorrow's goal.

## Weekly rhythm
| Day | Type | What |
|-----|------|------|
| Mon–Wed | Book | A chapter of *Learning From Data* [1], theory plus a from-scratch simulation |
| Thu | Toolkit | Optimization (LP, MILP), NLP, transformers, RAG, evaluation |
| Fri | Apply | A small business simulation that ends in a number (cost saved, revenue protected) |

## Schedule: 2 Nov – 31 Dec 2026 (43 notebook days)

| Date | Type | Topic |
|------|------|-------|
| Mon 2 Nov | Book | Ch1: The learning problem and the perceptron |
| Tue 3 Nov | Book | Ch1: Is learning feasible? Hoeffding's inequality |
| Wed 4 Nov | Book | Ch1: Error and noise |
| Thu 5 Nov | Toolkit | pandas, exploratory data analysis and SQL basics |
| Fri 6 Nov | Apply | Retail churn flag: the cost of a wrong call |
| Mon 9 Nov | Book | Ch2: Growth function and break point |
| Tue 10 Nov | Book | Ch2: VC dimension |
| Wed 11 Nov | Book | Ch2: The VC generalization bound |
| Thu 12 Nov | Toolkit | LP: formulating and solving a linear program [4] |
| Fri 13 Nov | Apply | Production planning with LP |
| Mon 16 Nov | Book | Ch3: Linear regression |
| Tue 17 Nov | Book | Ch3: Logistic regression and gradient descent |
| Wed 18 Nov | Book | Ch3: Nonlinear transforms |
| Thu 19 Nov | Toolkit | LP duality and sensitivity: shadow prices [4] |
| Fri 20 Nov | Apply | Demand forecast with linear regression, and what its errors cost |
| Mon 23 Nov | Book | Ch4: Overfitting |
| Tue 24 Nov | Book | Ch4: Regularization |
| Wed 25 Nov | Book | Ch4: Validation and cross-validation |
| Thu 26 Nov | Toolkit | MILP: branch and bound, binary decisions [5] |
| Fri 27 Nov | Apply | An overfit forecast: how validation saves money |
| Mon 30 Nov | Book | Ch5: Occam's razor |
| Tue 1 Dec | Book | Ch5: Sampling bias |
| Wed 2 Dec | Book | Ch5: Data snooping |
| Thu 3 Dec | Toolkit | NLP basics: tokenization, TF-IDF, embeddings [9] |
| Fri 4 Dec | Apply | Support-ticket triage with honest validation |
| Mon 7 Dec | Book | e-Ch: Similarity methods (k-NN, RBF) |
| Tue 8 Dec | Book | e-Ch: Neural networks |
| Wed 9 Dec | Book | e-Ch: Support vector machines |
| Thu 10 Dec | Toolkit | Transformers and attention [7] |
| Fri 11 Dec | Apply | **Predict then optimize**: churn scores feed a MILP retention budget |
| Mon 14 Dec | Book | e-Ch: Learning aides |
| Tue 15 Dec | Extra | Decision trees [3] |
| Wed 16 Dec | Extra | Ensembles: random forests and boosting [3], [11] |
| Thu 17 Dec | Toolkit | RAG: retrieval, chunking, evaluation [8] |
| Fri 18 Dec | Apply | Question answering over a synthetic knowledge base |
| Mon 21 Dec | Extra | Model comparison: book models vs trees |
| Tue 22 Dec | Extra | Uncertainty: confidence intervals and the bootstrap [12] |
| Wed 23 Dec | Buffer | Catch-up and review |
| Thu 24 Dec | Toolkit | Evaluation metrics and cost-sensitive thresholds |
| Fri 25 Dec | Rest | Holiday |
| Mon 28 Dec | Capstone | Scope and synthetic data |
| Tue 29 Dec | Capstone | Build |
| Wed 30 Dec | Capstone | Impact and limits |
| Thu 31 Dec | Capstone | Polish and publish |

## References
1. Abu-Mostafa, Magdon-Ismail & Lin (2012). *Learning From Data*. AMLBook.
2. Hoeffding, W. (1963). Probability inequalities for sums of bounded random variables. *JASA*, 58(301), 13–30.
3. James, Witten, Hastie & Tibshirani (2021). *An Introduction to Statistical Learning* (2nd ed.). Springer.
4. Bertsimas, D. & Tsitsiklis, J. (1997). *Introduction to Linear Optimization*. Athena Scientific.
5. Wolsey, L. (1998). *Integer Programming*. Wiley.
6. Hastie, Tibshirani & Friedman (2009). *The Elements of Statistical Learning* (2nd ed.). Springer.
7. Vaswani et al. (2017). Attention is all you need. *NeurIPS*.
8. Lewis et al. (2020). Retrieval-augmented generation for knowledge-intensive NLP tasks. *NeurIPS*.
9. Jurafsky, D. & Martin, J. *Speech and Language Processing* (3rd ed. draft).
10. Rosenblatt, F. (1958). The perceptron. *Psychological Review*, 65(6), 386–408.
11. Breiman, L. (2001). Random forests. *Machine Learning*, 45(1), 5–32.
12. Efron, B. (1979). Bootstrap methods: another look at the jackknife. *Annals of Statistics*, 7(1), 1–26.
