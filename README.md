# Learning Software Configuration Spaces: A Systematic Literature Review

* Motivation: What studies have been reported in the literature on learning software configuration spaces since the introduction of Software Product Lines to date (2019)? 
 * Based on a systematic literature review
   * we provide a framework classification of four main stages: Sampling, Measuring, Learning, and Validation
   * we identified different applications (pure prediction, optimization, specialization, interpretability, etc.)
   * we review subject systems and application domains 
   * we describe numerous sampling strategies 
   * we detail how configurations are measured 
   * we report on learning algorithms used and their assessment 
   * we identify severeal open challenges faced by the current approaches

* Data Extraction
  * see [primary studies](https://github.com/VaryVary/ML-configurable-SLR/blob/master/primary-studies.xlsx) and [results](https://github.com/VaryVary/ML-configurable-SLR/blob/master/results.xlsx).
  
Please do not hesitate to [contact us](mailto:juliana.alves-pereira@irisa.fr?subject=[GitHub:SLR]%20Learning%20Configuration%20Spaces), if you think that a certain work is classified incorrectly, or if you know any additional works that should be included.

## Bubble Charts

The bubble charts below show the metrics associated with each sampling and learning for each application.
As an example consider the first bubble chart (Applicability: Dynamic Configuration), we can notice that for the learning algorithm "CART", state-of-the-art approaches use four sampling strategies: random, STT, STT with random differences, and nearest neighbor.
They validated "CART \& random" by using precision and recall. For "CART \& STT" and "CART \& STT with random
differences", they use ranking constraints.
For "CART \& nearest neighbor", they use two different metrics: qualitative analysis and statistical significance.
The size of the bubble determines the number of papers addressing each "sampling \& learning".
Through these bubble charts is possible to have a summarized overview of the most used "sampling, learning, 
and validation metrics" for each applicability.
For dynamic configuration, the most used sampling is arbitrarily chosen and random, the learning algorithm is CART (5 studies) and linear regression (6 studies). The most used evaluation metrics are F-test, MRE, MSE, and (p-value, R2, RSE).

## Applicability: Pure Prediction (A1)

![A1-leg](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A1-leg.png)
![A1](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A1.png)

## Applicability: Interpretability of configurable systems (A2)

![A2-leg](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A2-leg.png)
![A2](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A2.png)

## Applicability: Optimization (A3)

![A3-leg_1](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A3-leg_1.png)
![A3-leg_2](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A3-leg_2.png)
![A3](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A3.png)

## Applicability: Dynamic Configuration (A4)

![A4-leg](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A4-leg.png)
![A4](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A4.png)

## Applicability: Mining Constraints (A5)

![A5-leg](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A5-leg.png)
![A5](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A5.png)

## Applicability: Evolution (A6)

![A6-leg](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A6-leg.png)
![A6](https://github.com/VaryVary/ML-configurable-SLR/blob/master/A6.png)

