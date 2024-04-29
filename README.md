# sfDLN
This repository includes the implementation of structure-function discrepancy learning which is proposed in "Graph Neural Networks Identify An Increased Discrepancy Between Structural and Functional Brain Connectomes Over the Cognitive Decline Continuum"


# Hyperparameter Experiments on ADD-SCI Classification

ChebyNet(snet-lnet) sfDLN is used for experiments given below.

1 ) Impact of the k for the k-NN Classifier

| k    | Accuracy | F1 Score |
| :--- |:-------: | :-------:|
| 3    | 0.853 ± 0.011     |  0.832 ± 0.007    |
| 5    | 0.872 ± 0.009     |  0.836 ± 0.007    |
| 7    | 0.879 ± 0.007     |  0.845 ± 0.009    |
| 9    | 0.879 ± 0.010     |  0.844 ± 0.013    |

2 ) Impact of the K for the ChebyNet

| K    | Accuracy | F1 Score |
| :--- |:-------: | :-------:|
| 0    | 0.512 ± 0.045     |  0.465 ± 0.086 |
| 1    | 0.879 ± 0.007     |  0.845 ± 0.009 |
| 2    | 0.834 ± 0.018     |  0.792 ± 0.020 |

# sfDLN on ADD-MCI and MCI-SCI Classification

ChebyNet(snet-lnet)-sfDLN is used for experiments given below. ChebyNet- sfDLN - I refers to the sfDLN trained using inverted (alternative) hypothesis of decreasing discrepancy.

1 ) ADD-MCI Classification

| Model    | Accuracy | F1 Score |
| :--- |:-------: | :-------:|
| ChebyNet-sfDLN-I | 0.655 ± 0.023     |  0.510 ± 0.046 |
| ChebyNet-sfDLN   | 0.712 ± 0.027     |  0.636 ± 0.040 |

2 ) MCI-SCI Classification

| Model    | Accuracy | F1 Score |
| :--- |:-------: | :-------:|
| ChebyNet-sfDLN-I | 0.520 ± 0.036     |  0.458 ± 0.040 |
| ChebyNet-sfDLN   | 0.545 ± 0.029     |  0.478 ± 0.027 |




