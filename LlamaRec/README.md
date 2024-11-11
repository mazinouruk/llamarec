```bash
python train_retriever.py
```
```bash
python train_ranker.py --llm_retrieved_path PATH_TO_RETRIEVER
```

## Citation
Please consider citing the following papers if you use our methods in your research:
```
@article{yue2023linear,
  title={Linear Recurrent Units for Sequential Recommendation},
  author={Yue, Zhenrui and Wang, Yueqi and He, Zhankui and Zeng, Huimin and McAuley, Julian and Wang, Dong},
  journal={arXiv preprint arXiv:2310.02367},
  year={2023}
}

@article{yue2023llamarec,
  title={LlamaRec: Two-Stage Recommendation using Large Language Models for Ranking},
  author={Yue, Zhenrui and Rabhi, Sara and Moreira, Gabriel de Souza Pereira and Wang, Dong and Oldridge, Even},
  journal={arXiv preprint arXiv:2311.02089},
  year={2023}
}
```
