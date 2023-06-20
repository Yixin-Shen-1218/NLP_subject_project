### Environment

All the code are runnable in the GOOGLE colab.

I use GOOGLE colab pro+, the GPU type is **A100**.

The default python environment of GOOGLE colab is **python 3.10**.

You can uncommand the the code in the top cell and change the **python version to 3.8**.

Before running the code,  please upload the data files into one 'data' folder that is on the same level as jupyter files.

```python
!pip install torch torchvision transformers
!pip install wandb
!pip install nltk
```



### Jupyter Files

1. ass3_text_classification      Code for the BERT+Classifier model
2. ass3_evidence_retrieval_v1       Code for the single_encoder DPR
3. ass3_evidence_retrieval_v2       Code for the double_encoder DPR
4. ass3_evidence_retrieval_v3 (you can ignore this)    Code for the single_encoder DPR that only encodes the evidences once 
5. ass3_evidence_retrieval_v4        Code for the single_encoder DPR with stopword deletion
6. ass3_data_analysis               Code for data analysis



Note that: Due to my old laptop is flooded, the BM25 model in the report is not in this code submission...But I think it has essentially no effect on the experimental REPORT.