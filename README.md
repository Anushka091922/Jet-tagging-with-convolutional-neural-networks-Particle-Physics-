# Jet-tagging-with-convolutional-neural-networks-Particle-Physics-
## Jet Tagging with Neural Networks
![jets](https://github.com/Anushka091922/Jet-tagging-with-convolutional-neural-networks-Particle-Physics-/assets/114327511/d1a5cdb2-ac75-46ba-ada0-5c617e7e2044)


### Overview
This repository serves as a resource for learning about jet tagging using deep neural networks in the context of high-energy physics, particularly proton-proton collisions. The project includes code, and datasets aimed at providing a comprehensive understanding of the process of training and evaluating neural networks for jet classification tasks.
Machine learning, particularly deep learning, has sparked a revolution in the analysis of large-scale data samples within the field of particle physics, significantly enhancing the potential for discovering new fundamental laws of nature (Radovic et al., 2018). In particular, deep learning techniques have revolutionized the approach to jet tagging, a crucial classification task conducted at high-energy particle colliders like the CERN Large Hadron Collider (LHC), resulting in a remarkable enhancement in performance (Kogler et al., 2019; Larkoski et al., 2020).
![Screenshot 2024-03-31 123555](https://github.com/Anushka091922/Jet-tagging-with-convolutional-neural-networks-Particle-Physics-/assets/114327511/f3016aa4-c44e-45a8-bd9b-82766895d859)
 
At the CERN Large Hadron Collider (LHC), high-energy proton beams collide at an astounding frequency of 40 million times per second (40 MHz), producing sprays of outgoing particles. To analyze the resulting collision data, complex detector systems like ATLAS and CMS are employed, consisting of over 100 million individual sensors. These detectors measure various properties of the outgoing particles, allowing researchers to reconstruct collision events and identify novel physics processes, such as the discovery of the Higgs boson.
A crucial step in the analysis process is jet tagging, which involves identifying the type of particle that initiates a jet. Jets are collimated sprays of outgoing particles, and tagging them correctly is essential for distinguishing particles of interest, like the Higgs boson or the top quark, from other types of jets. However, jet tagging is challenging due to the radiation and subsequent particle production within jets, leading to a cascade of particles and smearing of the initial particle's characteristics.

Traditional jet tagging approaches rely on hand-crafted features based on the principles of quantum chromodynamics (QCD). However, the emergence of deep learning has introduced new methods that represent jets as unordered sets of outgoing particles. ParticleNet, for instance, adapts the Dynamic Graph CNN architecture and has shown substantial performance improvements on jet tagging benchmarks. Despite subsequent model proposals, no significant performance gains have been achieved, largely due to the lack of large public datasets.

### References:
### Particle physics
•	The Particle Data Group [(https://pdg.lbl.gov/2021/reviews/contents_sports.html)] has a wonderfully concise review on machine learning. You can find it under Mathematical Tools > Machine Learning.

•	Jet Substructure at the Large Hadron Collider by A. Larkowski et al (2017). Although ancient by deep learning standards (most papers are outdated the moment they land on the arXiv 🙃), this review covers all the concepts we’ll need when looking at jets and how to tag them with neural networks.

•	HEPML-LivingReview. A remarkable project that catalogues loads of papers about machine learning and particles physics in a useful set of categories.

•	Physics Meets ML. A regular online seminar series that brings together researchers from the machine learning and physics communities.

•	Machine Learning and the Physical Sciences. A recent workshop at the NeurIPS conference that covers the whole gamut of machine learning and physics

•	Graph Neural Networks in Particle Physics by J. Shlomi et al (2020). A concise summary of applying graph networks to experimental particle physics

### Deep learning
•	Deep Learning for Coders with Fastai and PyTorch by Jeremy Howard and Sylvain Gugger. 

•	Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurélien Géron. 



