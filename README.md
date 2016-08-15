# fb15k-237-akbc

A set of Jupyter notebooks capturing an effort to apply Keras to the
problem of automatic knowledge based completion, using the universal
schema [[1]] approach. We use the FB215-237 dataset [[2]] developed by
Toutanova and her collaborators [[3]],[[4]] at Microsoft Research to
evaluate the implementation's performance.

The notebooks provide the following workflows:

* FB215-237 ETL: loads and processes triples from the dataset, augmenting them with data useful as inputs to the Keras model.
* FB215-237 Training: trains an instance of CFModel using the prepared data.
* FB215-237 Evaluation: evaluates the trained model using the protocol described in Toutanova and Chen [[3]].

## Requirements

* Python 2.7
* A copy of the FB215-237 dataset, downloaded from [[2]].

## Dependencies

* pandas 0.18.1
* keras 1.0.6
* numpy 1.11.1
* h5py 2.6.0  
* hdf5 1.8.17

## License

MIT. See the LICENSE file for the copyright notice.

## References

[[1]] S. Riedel, L. Yao, B. M. Marlin, and A. McCallum, “Relation Extraction with Matrix Factorization and Universal Schemas,” in Joint Human Language Technology Conference/Annual Meeting of the North American Chapter of the Association for Computational Linguistics (HLT-NAACL ’13), Jun. 2013.

[[2]] K. Toutanova, "FB215-237 Knowledge Base Completion Dataset," Web page https://www.microsoft.com/en-us/download/details.aspx?id=52312, May 2016. Last accessed 2016-08-14.

[[3]] K. Toutanova and D. Chen, “Observed versus latent features for knowledge base and text inference,” in 3rd Workshop on Continuous Vector Space Models and Their Compositionality, Jul. 2015.

[[4]] K. Toutanova, D. Chen, P. Pantel, H. Poon, P. Choudhury, and M. Gamon, “Representing text for joint embedding of text and knowledge bases,” in Empirical Methods in Natural Language Processing (EMNLP), Sep. 2015.

[1] http://www.riedelcastro.org//publications/papers/riedel13relation.pdf
[2] https://www.microsoft.com/en-us/download/details.aspx?id=52312
[3] https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/main_cvsc2015.pdf
[4] https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/emnlp2015kgtext.pdf