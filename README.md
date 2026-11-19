# Vedant Thaker

Machine learning engineer working on fraud review, recommendation systems and applied AI. My background includes fraud ML at CSAA, search and recommendations at Ace Infoway, and independent work on retrieval and inference.

Three results from my independent projects explain what I look for in a model.

- **Fraud review.** Given 80 reviews, a tree with seven days of graph statistics found 19 positives. A trained graph encoder found 10. These are synthetic transactions, but the comparison poses a practical question: what does the extra training stage buy the review team? [Held-out comparison](https://github.com/VEDANT1602/hybrid-fraud-gnn/blob/main/results/case-study.md)
- **Fulfillment.** Across 600 fictional grocery orders, the buffered batch planner delivered 284 on time against 275 for buffered greedy. Each wave records which orders went to which shopper, so the comparison can be traced back to a particular assignment. [Assignments by wave](https://github.com/VEDANT1602/grocery-batch-planner/blob/main/results/wave-results.json)
- **Inference.** Seven timed trials on a free Tesla T4 checked whether two implementations of one attention layer agreed. The recorded medians were 25.626 ms for full recomputation and 20.790 ms with KV reuse. The vLLM and Nebius guides cover a separate serving experiment that still needs measurements. [Device, timing procedure and raw repetitions](https://github.com/VEDANT1602/inference-systems-lab/tree/main/results/colab-t4)

For recommendation work, the [MovieLens evaluation](https://github.com/VEDANT1602/temporal-recommendations/blob/main/reports/case-study.md) shows how a popularity fallback changed which held-out ratings could be scored. For applied AI, [Knowledge Ledger](https://github.com/VEDANT1602/knowledge-ledger-hackathon) shows what happens when a fresh crawl contains an expired offer.

I use Python, SQL, PyTorch and XGBoost across these projects. The [portfolio directory](https://github.com/VEDANT1602/DataScienceProject/blob/master/docs/repository-directory.md) includes the earlier notebooks and the ASU used-car price report I co-authored with Divyesh Rathod and Meet Shah.

[LinkedIn](https://www.linkedin.com/in/vedant-thaker/) · [Email](mailto:vedant.thaker1602@gmail.com)
