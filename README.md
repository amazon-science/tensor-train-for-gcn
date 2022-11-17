## Tensor Train Decomposition for GCN

In this project, we use tensor-train decomposition to compress the learnable embedding tables
for graph neural network models (GNN) on featureless graphs.

By compressing the large learnable embedding
table, we can significantly accelerate GNN training speed on large graphs whose training cannot
fit in a single GPU.

In addition to faster training speed, our techniques can also improve the GNN model performance.
After compressing the learnable embedding table, our method can still achieve model performance
comparable or even outperform the GNN model with the full embedding table.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## Cite

We would appreciate citations to the following paper:

```
@inproceedings{yin2022ttgcn,
	title = {Nimble GNN Embedding with Tensor-Train Decomposition},
	author = {Yin, Chunxing and Zheng, Da and Nisa, Israt and Faloutsos, Christos and Karypis, George and Vuduc, Richard},
	year = {2022},
	booktitle = {Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
}
```

## License

This project is licensed under the Apache-2.0 License.

