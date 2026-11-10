# Vedant Thaker

**Machine Learning Engineer | Applied AI and ML Systems**

I build around the decision a system has to make: which item to recommend, which orders to assign, which cases to review, and whether a model workload can run reliably.

My background spans fraud ML at **CSAA**, recommendation, search and client delivery at **Ace Infoway**, and concurrent independent work in applied AI and inference engineering. Here I make the engineering decisions inspectable through code, experiments and reports.

## Engineering portfolio

| Area | What I build and investigate |
| --- | --- |
| **Recommendation and fulfillment systems** | [Temporal Recommendations](https://github.com/VEDANT1602/DataScienceProject/tree/master/projects/temporal-recommendations) tests PyTorch ranking against popularity under a global time boundary. [Grocery Batch Planner](https://github.com/VEDANT1602/grocery-batch-planner) connects XGBoost duration estimates to verified OR-Tools assignments: 284 on-time orders versus 275 for buffered greedy across 600 fictional orders. |
| **Fraud and claims review** | [Hybrid Fraud GNN](https://github.com/VEDANT1602/hybrid-fraud-gnn) compares learned graph context with engineered graph controls; the simpler graph-statistics model wins the recorded synthetic test. [Claims Multilabel Signals](https://github.com/VEDANT1602/claims-multilabel-signals) uses family-disjoint evaluation, label-specific thresholds and support gates, keeping rare labels and distribution shift visible. |
| **Inference and training systems** | [Inference Systems Lab](https://github.com/VEDANT1602/DataScienceProject/tree/master/projects/inference-systems-lab) joins streaming contracts, quality gates and KV-cache checks, including a small real Tesla T4 attention experiment. [Checkpoint Integrity Lab](https://github.com/VEDANT1602/checkpoint-integrity-lab) restores model, Adam and CPU RNG state to reproduce a training trajectory after rejecting corrupt or incomplete snapshots. |

[Read the engineering reports](https://github.com/VEDANT1602/DataScienceProject/blob/master/docs/engineering-portfolio.md) · [Browse the repository directory](https://github.com/VEDANT1602/DataScienceProject/blob/master/docs/repository-directory.md)

## How I work

Define the decision and available evidence. Build a useful baseline. Implement the mechanism that addresses the failure. Test its boundaries. Measure the result and keep the tradeoff visible, including when the simpler approach wins.

**Core stack:** Python, SQL, PyTorch, XGBoost, scikit-learn, FastAPI, Spark, Docker and AWS. Project-specific tools include OR-Tools and CUDA.

The public implementations are independent work from 2026; each records its data, authorship, measurements and limits. Employer and customer code stays private. The T4 result concerns tiny attention arithmetic; vLLM and Nebius serving integrations have collection scripts but no recorded provider benchmark. Checkpoint recovery was measured on CPU.

## Earlier work

[FormVision](https://github.com/VEDANT1602/FormVision) · [LLM-Powered Knowledge Base](https://github.com/VEDANT1602/LLM-Powered-Knowledge-Base) · [Cryptocurrency Sentiment Analysis](https://github.com/VEDANT1602/Cryptocurrency-Sentiment-Analysis-System) · [Heart Disease Prediction](https://github.com/VEDANT1602/Heart-Disease-Prediction-System) · [Car Price Prediction](https://github.com/VEDANT1602/Sales-Prediction-of-Cars-using-ML)

These repositories retain their original history and scope. The car-price work is an ASU report co-authored by **Divyesh Rathod, Meet Shah and Vedant Thaker**.

[LinkedIn](https://www.linkedin.com/in/vedant-thaker/) · [Email](mailto:vedant.thaker1602@gmail.com)
