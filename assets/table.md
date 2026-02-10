| Version | Architecture                | Action Precision | Action Recall | Action F1 | Action Accuracy | Intent Accuracy | Key Trade-off                       |
| ------: | --------------------------- | ---------------- | ------------- | --------- | --------------- | --------------- | ----------------------------------- |
|      v1 | Single-stage classification | 0.66             | 0.89          | 0.76      | 0.77            | 0.40            | High recall, weak intent separation |
|      v2 | Stricter prompt rules       | 0.82             | 0.39          | 0.53      | 0.72            | 0.48            | Conservative action detection       |
|      v3 | Two-stage pipeline          | 0.44             | 0.98          | 0.61      | 0.48            | 0.28            | Over-triggers actions               |
|      v4 | Confidence-gated routing    | 0.65             | 0.61          | 0.63      | 0.71            | 0.37            | Balanced precision and recall       |
