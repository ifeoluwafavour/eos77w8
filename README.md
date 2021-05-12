# Side Effects

This model has been trained using the SIDER benchmark from MoleculeNet. Molecular properties of this dataset are predicted and encoded using GROVER, a novel molecular representation encompassing detailed structural information.

## Summary
* Predicts **Side Effects** for small molecules
* Takes **compound structures** as input
* Trained with the benchmark **SIDER MoleculeNet** dataset (2039 molecules)
* Results validated **in-silico** against baseline methods for the same dataset
* Published in [*Rong et al, Advances in Neural Information Processing Systems 2020*](https://papers.nips.cc/paper/2020/hash/94aef38441efa3380a3bed3faf1f9d5d-Abstract.html)
* Processed data can be found [here](https://github.com/tencent-ailab/grover)

## Specifications
* Input: SMILES string (also accepts an InChIKey string or a molecule name string, and converts them to SMILES)
* Endpoint:

## History
1. Model was downloaded on 12.05.21 from [TencentAILab](https://github.com/tencent-ailab/grover)
2. We duplicated task/predict.py and scripts/save_features.py from Tencent GitHub repository
3. Model was incorporated to Ersilia on 12/05/2021
