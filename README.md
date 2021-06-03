# Financial-Statement-Summarization
Applying Transformers for Summarizing Financial Statement Data

#### Abstract
Automatic financial statement summarization using machine learning is
an important task for forecasting company performance. This paper tested
4 transformer architectures to determine their effectiveness for summarizing
financial statements. Further applications of the methods presented here could
include summarization of a wider variety of corporate documents, particularly
for the private equity and venture capital markets.

Based on the results obtained for financial statement summarization, the PEGASUS-
Legal v2 model is the optimal model with the highest ROUGE scores, with ROUGE-1
precision at 0.37 precision and an F-measure of 0.33. This model outperformed the
T5, BERT2BERT and PEGASUS-Finance models for the summarization task.

Example SHAP Value for explaining how a summary was Generated:

![Pegasus_Legal_2_SHAP_Values](https://user-images.githubusercontent.com/33669038/120719515-685e0f80-c498-11eb-8a0c-2506a070d3da.PNG)

