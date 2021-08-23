# Membership Inference Attacks and Defenses on Machine Learning Models Literature
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of membership inference attacks and defenses papers on machine learning models.

Paper are sorted by their released dates in descending order.

This repository serves as a complement of the survey below.

[**Membership Inference Attacks on Machine Learning: A Survey**] (https://arxiv.org/abs/2103.07853)

````bibtex
@article{hu2021membership,
  title={Membership Inference Attacks on Machine Learning: A Survey},
  author={Hu, Hongsheng and Salcic, Zoran and Dobbie, Gillian and Zhang, Xuyun},
  journal={arXiv preprint arXiv:2103.07853},
  year={2021}
}
````

If you feel this repo is helpful, please cite the survey above.

## Membership Inference Attack

### Attack papers 2021
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **On the Difficulty of Membership Inference Attacks** | White-box | Classification Models | CVPR | [Link](https://openaccess.thecvf.com/content/CVPR2021/html/Rezaei_On_the_Difficulty_of_Membership_Inference_Attacks_CVPR_2021_paper.html) | [Link](https://github.com/shrezaei/MI-Attack) |
| 2021 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|
| 2021 | **Label-only membership inference attacks** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v139/choquette-choo21a.html) | [Link](https://github.com/cchoquette/membership-inference) |
| 2021 | **On the Privacy Risks of Model Explanations** | Black-box | Classification Models | AIES | [Link](https://dl.acm.org/doi/abs/10.1145/3461702.3462533?casa_token=N1y7W8SoFxQAAAAA:FDsVwyOBIS98rwYWsUpE2dlcmDaJXiKJnJOV1aAkiy1iE4K7Xn8cO184o5hAfQctNbxEpX2WM6XIwA) | |
| 2021 | **Systematic evaluation of privacy risks of machine learning models** | White-box; Black-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity21/presentation/song) | [Link](https://github.com/inspire-group/membership-inference-evaluation)|
| 2021 | **Practical blind membership inference attack via differential comparisons** | Black-box | Classification Models | NDSS |[Link](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_5C-2_24293_paper.pdf) | [Link](https://github.com/hyhmia/BlindMI) |
| 2021 | **On the (In) Feasibility of Attribute Inference Attacks on Machine Learning Models** | White-box; Black-box | Classification Models | EuroS&P | [Link](https://arxiv.org/abs/2103.07101) | |
| 2021 | **How Does Data Augmentation Affect Privacy in Machine Learning?** | Black-box | Classification Models | AAAI | [Link](https://www.aaai.org/AAAI21Papers/AAAI-353.YuD.pdf) | [Link](https://github.com/dayu11/MI_with_DA)|
| 2021 | **Node-Level Membership Inference Attacks Against Graph Neural Networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2102.05429) | |
| 2021 | **The Audio Auditor: User-Level Membership Inference in Internet of Things Voice Services** | Black-box | Automatic Speech Recognition Model | PoPETs | [Link](https://researchonline.jcu.edu.au/64660/) | |
| 2021 | **Reconstruction-Based Membership Inference Attacks are Easier on Difficult Problems** | Black-box | Image Translation Models; Image Segmentation Models | ICCV | [Link](https://arxiv.org/abs/2102.07762) | [Link](https://github.com/avitalsh/reconst_based_MIA)|
| 2021 | **This Person (Probably) Exists. Identity Membership Attacks Against GAN Generated Faces** | Black-box | Generative Models | Arxiv | [link](https://arxiv.org/abs/2107.06018) | |
| 2021 | **Membership Inference Attack Susceptibility of Clinical Language Models** | White-box; Black-box | Clinical Language Models | Arxiv | [Link](https://arxiv.org/abs/2104.08305) | |
| 2021 | **Killing four birds with one Gaussian process: the relation between different test-time attacks** | Black-box | Classification Models | ICPR | [Link](https://ieeexplore.ieee.org/abstract/document/9413290?casa_token=RxUKWNuCdsAAAAAA:eg4blFMRYcf9sWqjagDPFqunYNKjN1cwASboegqbvOJyC8ERxy8WOAH0MNvCA5IhAJfJUGnS8g) | |
| 2021 | **Evaluating the Vulnerability of End-to-End Automatic Speech Recognition Models To Membership Inference Attacks** | Black-box | Speech Recognition Models | Interspeech | [Link](https://assets.amazon.science/48/f3/f8d1b62c4bf8bd63cf7a069eff24/evaluating-the-vulnerability-of-end-to-end-automation-speech-recognition-models-to-membership-inference-attacks.pdf) | |
| 2021 | **Membership Inference Attacks on Knowledge Graphs** | Black-box | Knowledge Graph Embedding Models | Arxiv | [Link](https://arxiv.org/abs/2104.08273) | |
| 2021 | **Membership Leakage in Label-Only Exposures** | Black-box | Classification Models | CCS | [Link](https://arxiv.org/abs/2007.15528) | |
| 2021 | **Membership inference attack on graph neural networks** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2101.06570) | |
| 2021 | **Membership Inference Attacks on Deep Regression Models for Neuroimaging** | Black-box | Regression Models | MIDL | [Link](https://arxiv.org/abs/2105.02866) | |
| 2021 | **Membership Inference Attacks on Lottery Ticket Networks** | Black-box | Classification Models | ICML Workshop | [Link](https://openreview.net/forum?id=4lyXal2ZWB3) | |
| 2021 | **Membership Inference on Word Embedding and Beyond** | Black-box | Word Embedding Models | Arxiv | [Link](https://arxiv.org/abs/2106.11384) | | 

 
### Attack papers 2020
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **Quantifying Privacy Leakage in Graph Embedding** | White-box; Black-box | Graph Embedding Models | NeurIPS Workshop |[Link](https://arxiv.org/abs/2010.00906) | [Link](https://github.com/vasishtduddu/GraphLeaks)|
| 2020 | **GECKO: Reconciling Privacy, Accuracy and Efficiency in Embedded Deep Learning** | Black-box | Classification Models | NeurIPS Workshop | [Link](https://arxiv.org/abs/2010.00912) | |
| 2020 | **Gan-leaks: A taxonomy of membership inference attacks against generative models** | White-box; Black-box | Generative Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417238?casa_token=5npei5-D6vUAAAAA:aXjBRatnngBs0Hyd01LfDQGc60aL_XnEc93SJPPjsiWPLQzzXc4U6wRQFNmYMtZv6Y_Zgz9EaSAomQ) | [Link](https://github.com/DingfanChen/GAN-Leaks) |
| 2020 | **Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference** | White-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity20/presentation/leino) | |
| 2020 | **Information leakage in embedding models** | Black-box | Text Embedding Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3372297.3417270?casa_token=qSdKKvBuMlsAAAAA:pvtisX5ke3aHgg2xt3AuATThaogPwPUZes1s2Td2um1Zn3ZxXR5XsjNcPObf4E6gBJHkl_0zXn1qVw) | |
| 2020 | **When machine unlearning jeopardizes privacy** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2005.02205) | |
| 2020 | **Revisiting membership inference under realistic assumptions** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2005.10881) | [Link](https://github.com/bargavj/EvaluatingDPML)|
| 2020 | **Membership inference attacks on sequence-to-sequence models: Is my data in your machine translation system?** | Black-box | Text Generation Models | TACL | [Link](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00299/43536/Membership-Inference-Attacks-on-Sequence-to) | [Link](https://github.com/sorami/tacl-membership) |
| 2020 | **Segmentations-leak: Membership inference attacks and defenses in semantic image segmentation** | Black-box | Image Segmentation Models | ECCV| [Link](https://link.springer.com/chapter/10.1007/978-3-030-58592-1_31) | [Link](https://github.com/SSAW14/segmentation_membership_inference)|
| 2020 | **Performing co-membership attacks against deep generative models** | White-box | Generative Models |ICDM | [Link](https://ieeexplore.ieee.org/abstract/document/8970995?casa_token=_QVk9Y51OCYAAAAA:rZ2t3JfMxXDs-CvoR-Uvh7a8oLGHDRUXruJBWjVA0_qD7B5piJBBhuiwaVEAnFWHQspmTxrFwA) | |
| 2020 | **On the privacy risks of algorithmic fairness** | Black-box | Classification Models | EuroS&P | [Link](https://arxiv.org/abs/2011.03731) | |
| 2020 | **A Comprehensive Analysis of Information Leakage in Deep Transfer Learning** | Black-box | Classification Models | Arxiv| [Link](https://arxiv.org/abs/2009.01989) | |
| 2020 | **Gan enhanced membership inference: A passive local attack in federated learning** | White-box | Classification Models | ICC |[Link](https://ieeexplore.ieee.org/abstract/document/9148790?casa_token=TwA2PQfrAooAAAAA:TKJlyEVcg4h_Dcq29OLJz_HU29YUFwmtzAnhFCABIv7gpNEvQBbzIlYjjiH37zjILdNO5SoqqA) | |
| 2020 | **Privacy analysis of deep learning in the wild: Membership inference attacks against transfer learning** | Black-box | Classification Models | Arxiv| [Link](https://arxiv.org/abs/2009.04872) | |
| 2020 | **Data and model dependencies of membership inference attack** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2002.06856) | |
| 2020 | **A Pragmatic Approach to Membership Inferences on Machine Learning Models** | Black-box | Classification Models | EuroS&P | [Link](https://ieeexplore.ieee.org/abstract/document/9230385?casa_token=rReHm3AMDfwAAAAA:tbLfZUjLhEO368PbybwT6RVNgzAwFD9t0_Xhy9KnrZ9eX9dxJq9IunO6GH6Wm7fk7OPHfHF0AQ) | |
| 2020 | **Quantifying Membership Inference Vulnerability via Generalization Gap and Other Model Metrics** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2009.05669) | 
| 2020 | **Investigating the Impact of Pre-trained Word Embeddings on Memorization in Neural Networks** | Black-box | Word Embedding Models | TSD | [Link](https://link.springer.com/chapter/10.1007/978-3-030-58323-1_30) | |
| 2020 | **Beyond Model-Level Membership Privacy Leakage: an Adversarial Approach in Federated Learning** | White-box | Classification Models | ICCCN | [Link](https://ieeexplore.ieee.org/abstract/document/9209744?casa_token=Zd05FWW-sLQAAAAA:wP4jc9aCILSpCREa3E4Zo8zCuWetxaZrW78Yi2Q8ZI3Ztr9rer70G3bFa_sNeuHo7O8YyZ4nxQ) | |
| 2020 | **Practical Membership Inference Attack Against Collaborative Inference in Industrial IoT** | White-box | Classification Models | IEEE Trans. Industr. Inform. | [Link](https://ieeexplore.ieee.org/document/9302683?denied=) | |





### Attack papers 2019
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2019 | **Exploiting unintended feature leakage in collaborative learning**| White-box | Classification Models | S&P | [Link](https://ieeexplore.ieee.org/abstract/document/8835269?casa_token=eYvm-5MHJ5EAAAAA:jJfXg2OLofzNw4ZZgRxuoMcEu6flf1epeMeRKZkNln9W99yar_N2WFawsaohM2XRicRA0vnujw) | [Link](https://github.com/csong27/property-inference-collaborative-ml)|
| 2019 | **Comprehensive Privacy Analysis of Deep Learning: Passive and Active White-box Inference Attacks against Centralized and Federated Learning** | Black-box; White-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/8835245?casa_token=2VTmu69Ze5YAAAAA:cNBfmpyOtRzlcjC17vP_fvqWINaGcGCAA1BGWxfBzEveksH6GRAMfrmGSH7ULi4Wf_G0NzJNnw) | [Link](https://github.com/privacytrustlab/ml_privacy_meter) |
 |2019 | **ML-Leaks: Model and Data Independent Membership Inference Attacks and Defenses on Machine Learning Models** | Black-box | Classification Models | NDSS | [Link](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-1_Salem_paper.pdf) | [Link](https://github.com/AhmedSalem2/ML-Leaks) |
| 2019 | **LOGAN: Membership Inference Attacks Against Generative Models** | Black-box; White-box | Generative Models | PoPETs | [Link](https://arxiv.org/abs/1705.07663) | [Link](https://github.com/jhayes14/gen_mem_inf)|
| 2019 | **White-box vs Black-box: Bayes Optimal Strategies for Membership Inference** | Black-box | Classification Models | ICML | [Link](http://proceedings.mlr.press/v97/sablayrolles19a.html) | |
| 2019 | **Auditing data provenance in text-generation models** | Black-box | Text Generation Models | KDD | [Link](https://dl.acm.org/doi/abs/10.1145/3292500.3330885) | [Link](https://github.com/csong27/auditing-text-generation) |
| 2019 | **Socinf: Membership inference attacks on social media health data with machine learning** | Black-box | Classification Models | IEEE Trans. Comput. Soc. Syst. | [Link](https://ieeexplore.ieee.org/abstract/document/8728167?casa_token=4RgQ9tuXHiYAAAAA:RpcPcXmjOfNGr5joJQN8J0NAPsan_1aXygP4SR21qXWJuDbAzbVj-YVU6ASV_zCzPqK4fzWBCQ) | |
| 2019 | **Monte Carlo and Reconstruction Membership Inference Attacks against Generative Models.** | White-box; Black-box | Generative Models | PoPETs | [Link](https://petsymposium.org/2019/files/papers/issue4/popets-2019-0067.pdf) | [Link](https://github.com/SAP-samples/security-research-membership-inference-against-generative-networks) |
| 2019 | **Disparate Vulnerability: on the Unfairness of Privacy Attacks Against Machine Learning** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1906.00389) | |
| 2019 | **Demystifying the membership inference attack** | Black-box | Classification Models | CMI | [Link](https://ieeexplore.ieee.org/abstract/document/8962136) | |
| 2019 | **Differential Privacy Defenses and Sampling Attacks for Membership Inference** | Black-box | Classification Models | NeurIPS Workshop | [Link](https://arxiv.org/abs/2009.00395) | |
| 2019 | **Privacy Risks of Securing Machine Learning Models against Adversarial Examples** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3319535.3354211) | [Link](https://github.com/inspire-group/privacy-vs-robustness) |
| 2019 | **Membership Inference Attacks against Adversarially Robust Deep Learning Models** | Black-box | Classification Models | S&P Workshop | [Link](https://ieeexplore.ieee.org/abstract/document/8844607?casa_token=Afs5maC5j74AAAAA:JQ6Jy-Gq3N4XFZqpX35qGzbjTx5e1p9tkIVoFYc4QDdIpIsvkHl__rsawNYpQ7K5ZvyBORo86A) | |
| 2019 | **Demystifying Membership Inference Attacks in Machine Learning as a Service** | Black-box | Classification Models | IEEE Trans. Serv. Comput. | [Link](https://ieeexplore.ieee.org/abstract/document/8634878?casa_token=MC0Uw6Ni-HgAAAAA:zJ32LbWViM5adpNr6sh8tNMZI-Or50HI-QawC1hyMTjPiDxDe8kAAbtdBC0saPOz88Y0aqkLNw) | [Link] |


 
### Attack papers 2018
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Privacy Risk in Machine Learning: Analyzing the Connection to Overfitting** | Black-box | Classification Models | CSF | [Link](https://ieeexplore.ieee.org/abstract/document/8429311?casa_token=NQu6-mEb9JMAAAAA:LTU3BPSYc8ALHF89ifdWs1zl__ABgBzIr44xFoN2t8HwjTb5vm20S00VeH9JSmaBU-miBt5Ucg) | [Link](https://github.com/samuel-yeom/ml-privacy-csf18) |
| 2018 | **Understanding membership inferences on well-generalized learning models** | Black-box | Classification Models | Arxiv | [link](https://arxiv.org/abs/1802.04889) | |

### Attack papers 2017
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2017  | **Membership inference attacks against machine learning models** | Black-box | Classification Models | S&P | [link](https://ieeexplore.ieee.org/abstract/document/7958568?casa_token=YOmVjvUemFUAAAAA:gGeuARxnjASvh9gnPkijkLD7d7HD1VV1JZkooXtS6tb6LGfKqHgBbyoaI-0-X7kFeP-3bjUR2A) | [Link](https://github.com/csong27/membership-inference) |


## Membership Inference Defense
### Defense papers 2021
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **On the privacy-utility trade-off in differentially private hierarchical text classification** | White-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2103.02895) | |
| 2021 | **MLCapsule: Guarded Offline Deployment of Machine Learning as a Service** | Black-box | Classification Models | CVPR | [Link](https://openaccess.thecvf.com/content/CVPR2021W/TCV/html/Hanzlik_MLCapsule_Guarded_Offline_Deployment_of_Machine_Learning_as_a_Service_CVPRW_2021_paper.html) | |

### Defense papers 2020
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2020 | **Privacy for All: Demystify Vulnerability Disparity of Differential Privacy against Membership Inference Attack** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2001.08855) | |
| 2020 | **Privacy for All: Demystify Vulnerability Disparity of Differential Privacy against Membership Inference Attack**  | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/2001.08855) | |
| 2020 | **Differential Privacy Protection Against Membership Inference Attack on Machine Learning for Genomic Data** | Black-box | Classification Models | Biocomputing | [Link](https://www.worldscientific.com/doi/abs/10.1142/9789811232701_0003) | |

### Defense papers 2019
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2019 | **Evaluating Differentially Private Machine Learning in Practice** | Black-box | Classification Models | USENIX Security | [Link](https://www.usenix.org/conference/usenixsecurity19/presentation/jayaraman) | [Link](https://github.com/bargavj/EvaluatingDPML) |
| 2019 | **MemGuard: Defending against Black-Box Membership Inference Attacks via Adversarial Examples** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3319535.3363201) | [Link](https://github.com/jjy1994/MemGuard) |


### Defense papers 2018
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Machine Learning with Membership Privacy using Adversarial Regularization** | Black-box | Classification Models | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3243734.3243855) | [Link](https://github.com/SPIN-UMass/ML-Privacy-Regulization) |
| 2018 | **Privacy-preserving Machine Learning through Data Obfuscation** | Black-box | Classification Models | Arxiv | [Link](https://arxiv.org/abs/1807.01860) | |


### Defense papers 2017

