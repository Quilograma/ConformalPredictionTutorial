### Code of INDUCTIVE CONFORMAL PREDICTION: A STRAIGHTFORWARD INTRODUCTION WITH EXAMPLES IN PYTHON

Inductive Conformal Prediction (ICP) is a set of distribution-free and model agnostic algorithms
devised to predict with a user-defined confidence with coverage guarantee. Instead of having point
predictions, i.e., a real number in the case of regression or a single class in multi class classification,
models calibrated using ICP output an interval or a set of classes, respectively. ICP takes special
importance in high-risk settings where we want the true output to belong to the prediction set with
high probability. As an example, a classification model might output that given a magnetic resonance
image a patient has no latent diseases to report. However, this model output was based on the most
likely class, the second most likely class might tell that the patient has a 15% chance of brain tumor
or other severe disease and therefore further exams should be conducted. Using ICP is therefore way
more informative and we believe that should be the standard way of producing forecasts. This paper
is a hands-on introduction, this means that we will provide examples as we introduce the theory.

```
Please cite as (Bibtex citation)

- @misc{https://doi.org/10.48550/arxiv.2206.11810,
  doi = {10.48550/ARXIV.2206.11810},
  
  url = {https://arxiv.org/abs/2206.11810},
  
  author = {Sousa, Martim},
  
  keywords = {Machine Learning (stat.ML), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {Inductive Conformal Prediction: A Straightforward Introduction with Examples in Python},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
