============
Publications
============

`Self-Organizing Map Oversampling (SOMO) for imbalanced data set learning  <https://www.sciencedirect.com/science/article/pii/S0957417417302324>`_
==================================================================================================================================================

Learning from imbalanced datasets is challenging for standard algorithms, as
they are designed to work with balanced class distributions. Although there are
different strategies to tackle this problem, methods that address the problem
through the generation of artificial data constitute a more general approach
compared to algorithmic modifications. Specifically, they generate artificial
data that can be used by any algorithm, not constraining the options of the
user. In this paper, we present a new oversampling method, Self-Organizing
Map-based Oversampling (SOMO), which through the application of a
Self-Organizing Map produces a two dimensional representation of the input
space, allowing for an effective generation of artificial data points. SOMO
comprises three major stages: Initially a Self-Organizing Map produces a
two-dimensional representation of the original, usually high-dimensional, space.
Next it generates within-cluster synthetic samples and finally it generates
between cluster synthetic samples. Additionally we present empirical results
that show the improvement in the performance of algorithms, when artificial data
generated by SOMO are used, and also show that our method outperforms various
oversampling methods.

`Effective data generation for imbalanced learning using conditional generative adversarial networks <https://www.sciencedirect.com/science/article/pii/S0957417417306346>`_
============================================================================================================================================================================

Learning from imbalanced datasets is a frequent but challenging task for
standard classification algorithms. Although there are different strategies to
address this problem, methods that generate artificial data for the minority
class constitute a more general approach compared to algorithmic modifications.
Standard oversampling methods are variations of the SMOTE algorithm, which
generates synthetic samples along the line segment that joins minority class
samples. Therefore, these approaches are based on local information, rather on
the overall minority class distribution. Contrary to these algorithms, in this
paper the conditional version of Generative Adversarial Networks (cGAN) is used
to approximate the true data distribution and generate data for the minority
class of various imbalanced datasets. The performance of cGAN is compared
against multiple standard oversampling algorithms. We present empirical results
that show a significant improvement in the quality of the generated data when
cGAN is used as an oversampling algorithm.

`Improving imbalanced learning through a heuristic oversampling method based on k-means and SMOTE   <https://www.sciencedirect.com/science/article/pii/S0020025518304997>`_
===========================================================================================================================================================================

Learning from class-imbalanced data continues to be a common and challenging
problem in supervised learning as standard classification algorithms are
designed to handle balanced class distributions. While different strategies
exist to tackle this problem, methods which generate artificial data to achieve
a balanced class distribution are more versatile than modifications to the
classification algorithm. Such techniques, called oversamplers, modify the
training data, allowing any classifier to the proposed method improves
classification results. Moreover, k-means SMOTE consistently outperforms other
popular oversampling methods. An implementation is made available in the Python
programming language.

`Geometric SMOTE: A geometrically enhanced drop-in replacement for SMOTE <https://www.sciencedirect.com/science/article/pii/S0020025519305353?via%3Dihub>`_
===========================================================================================================================================================

Classification of imbalanced datasets is a challenging task for standard
algorithms. Although many methods exist to address this problem in different
ways, generating artificial data for the minority class is a more general
approach compared to algorithmic modifications. SMOTE algorithm, as well as any
other oversampling method based on the SMOTE mechanism, generates synthetic
samples along line segments that join minority class instances. In this paper we
propose Geometric SMOTE (G-SMOTE) as a enhancement of the SMOTE data generation
mechanism. G-SMOTE generates synthetic samples in a geometric region of the
input space, around each selected minority instance. While in the basic
configuration this region is a hyper-sphere, G-SMOTE allows its deformation to a
hyper-spheroid. The performance of G-SMOTE is compared against SMOTE as well as
baseline methods. We present empirical results that show a significant
improvement in the quality of the generated data when G-SMOTE is used as an
oversampling algorithm. An implementation of G-SMOTE is made available in the
Python programming language.

`Oversampling for Imbalanced Learning Based on K-Means and SMOTE <https://arxiv.org/abs/1711.00837>`_
=====================================================================================================

Learning from class-imbalanced data continues to be a common and challenging
problem in supervised learning as standard classification algorithms are
designed to handle balanced class distributions. While different strategies
exist to tackle this problem, methods which generate artificial data to achieve
a balanced class distribution are more versatile than modifications to the
classification algorithm. Such techniques, called oversamplers, modify the
training data, allowing any classifier to be used with class-imbalanced
datasets. Many algorithms have been proposed for this task, but most are complex
and tend to generate unnecessary noise. This work presents a simple and
effective oversampling method based on k-means clustering and SMOTE
oversampling, which avoids the generation of noise and effectively overcomes
imbalances between and within classes. Empirical results of extensive
experiments with 71 datasets show that training data oversampled with the
proposed method improves classification results. Moreover, k-means SMOTE
consistently outperforms other popular oversampling methods. An implementation
is made available in the python programming language.

`Geometric SMOTE: Effective oversampling for imbalanced learning through a geometric extension of SMOTE <https://arxiv.org/abs/1709.07377>`_
============================================================================================================================================

Classification of imbalanced datasets is a challenging task for standard
algorithms. Although many methods exist to address this problem in different
ways, generating artificial data for the minority class is a more general
approach compared to algorithmic modifications. SMOTE algorithm and its
variations generate synthetic samples along a line segment that joins minority
class instances. In this paper we propose Geometric SMOTE (G-SMOTE) as a
generalization of the SMOTE data generation mechanism. G-SMOTE generates
synthetic samples in a geometric region of the input space, around each selected
minority instance. While in the basic configuration this region is a
hyper-sphere, G-SMOTE allows its deformation to a hyper-spheroid and finally to
a line segment, emulating, in the last case, the SMOTE mechanism. The
performance of G-SMOTE is compared against multiple standard oversampling
algorithms. We present empirical results that show a significant improvement in
the quality of the generated data when G-SMOTE is used as an oversampling
algorithm.

================
Research roadmap
================

- Theoretical analysis of over-sampling.

- Theoretical analysis of G-SMOTE.

- Theoretical analysis of clustering over-sampling.

- Application of regression over-sampling.

- Over-sampling for categorical variables.

- Application of clustering over-sampling to credit scoring and anomaly
  detection.

- Application of CGANs variations and generative models to over-sampling.

- Publication of papers to describe various open-source software tools and
  algorithms.
