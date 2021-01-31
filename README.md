# Awesome Explanatory Supervision

Overview of literature on learning from supervision on the model's explanations.


**Warning**: early draft, permanent WIP.


Did we miss a relevant paper?  Please submit a new entry in the following format:


```markdown
- **An Artificially-intelligent Means to Escape Discreetly from the Departmental Holiday Party; guide for the socially awkward**
  Eve Armstrong; arXiv 2020 [paper](https://arxiv.org/abs/2003.14169)
  Notes: it is a joke;  a pretty good joke actually.
```


### Table of Contents
- [Explanatory Passive Learning](#explanatory-passive-learning)
- [Explanatory Interactive Learning](#explanatory-interactive-learning)
- [Background](#background)



### [Explanatory Passive Learning](#content)

Approaches that somehow regularize or supervise the model's explanations.

- **Tangent Prop - A formalism for specifying selected invariances in an adaptive network**
  Patrice Simard, Bernard Victorri, Yann Le Cun, John Denker; NeurIPS 1992 [paper](https://papers.nips.cc/paper/536-tangent-prop-a-formalism-for-specifying-selected-invariances-in-an-adaptive-network.pdf)
  Notes: injects invariances into a neural net by regularizing its gradient;  precursor to learning from gradient-based explanations.

- **Right for the right reasons: training differentiable models by constraining their explanations**
  Andrew Slavin Ross, Michael C. Hughes, and Finale Doshi-Velez; IJCAI 2017 [paper](https://www.ijcai.org/Proceedings/2017/0371.pdf)

- **Deriving Machine Attention from Human Rationales**
  Yujia Bao, Shiyu Chang, Mo Yu, and Regina Barzilay; ACL 2019 [pdf](https://www.aclweb.org/anthology/D18-1216.pdf)

- **Concept bottleneck models**
  Pang Wei Koh, Thao Nguyen, Yew Siang Tang, Stephen Mussmann, Emma Pierson, Been Kim, and Percy Liang; ICML 2020 [paper](http://proceedings.mlr.press/v119/koh20a/koh20a.pdf)

- **Debiasing Concept Bottleneck Models with Instrumental Variables**
  Mohammad Taha Bahadori, and David E. Heckerman; arXiv 2020 [paper](https://arxiv.org/pdf/2007.11500.pdf)

- **Evaluating Explanations: How much do explanations from the teacher aid students?**
  Danish Pruthi, Bhuwan Dhingra, Livio Baldini Soares, Michael Collins, Zachary C. Lipton, Graham Neubig, and William W. Cohen; 2020 arXiv [paper](https://arxiv.org/pdf/2012.00893)
  Notes: defines importance of different kinds of explanations by measuring their impact when used as supervision.

- **Reflective-Net: Learning from Explanations**
  Johannes Schneider, Michalis Vlachos; arXiv 2020 [paper](https://arxiv.org/pdf/2011.13986.pdf)

- **Teaching with Commentaries**
  Aniruddh Raghu, Maithra Raghu, Simon Kornblith, David Duvenaud, and Geoffrey Hinton; arXiv 2020 [paper](https://arxiv.org/pdf/2011.03037)

- **Improving performance of deep learning models with axiomatic attribution priors and expected gradients** 
  Gabriel Erion, Joseph D. Janizek, Pascal Sturmfels, Scott Lundberg, Su-In Lee; arXiv 2020 [paper](https://arxiv.org/pdf/1906.10670)

- **Interpretations are useful: penalizing explanations to align neural networks with prior knowledge**
  Laura Rieger, Chandan Singh, William Murdoch, Bin Yu; ICML 2020 [paper](http://proceedings.mlr.press/v119/rieger20a/rieger20a.pdf)




### [Explanatory Interactive Learning](#content)

Approaches that combine explanatory supervision with interactive machine learning:

- **Principles of Explanatory Debugging to Personalize Interactive Machine Learning**
  Todd Kulesza, Margaret Burnett, Weng-Keen Wong, Simone Stumpf; IUI 2015 [paper](https://openaccess.city.ac.uk/id/eprint/13819/1/paper326.pdf)

- **Explanatory Interactive Machine Learning**
  Stefano Teso, Kristian Kersting; AIES 2019 [paper](https://www.aiml.informatik.tu-darmstadt.de/papers/teso2019aies_XIML.pdf)
  Note: introduces explanatory interactive learning, focuses on active learning setup.

- **Taking a hint: Leveraging explanations to make vision and language models more grounded**
  Ramprasaath R. Selvaraju, Stefan Lee, Yilin Shen, Hongxia Jin, Shalini Ghosh, Larry Heck, Dhruv Batra, and Devi Parikh; ICCV, 2019 [pdf](https://openaccess.thecvf.com/content_ICCV_2019/papers/Selvaraju_Taking_a_HINT_Leveraging_Explanations_to_Make_Vision_and_Language_ICCV_2019_paper.pdf)

- **Toward Faithful Explanatory Active Learning with Self-explainable Neural Nets**
  Stefano Teso; IAL Workshop 2019. [paper](https://lirias.kuleuven.be/retrieve/578884)
  Note: explanatory active learning with self-explainable neural networks.

- **Making deep neural networks right for the right scientific reasons by interacting with their explanations**
  Patrick Schramowski, Wolfgang Stammer, Stefano Teso, Anna Brugger, Franziska Herbert, Xiaoting Shao, Hans-Georg Luigs, Anne-Katrin Mahlein, Kristian Kersting; Nature Machine Intelligence 2020 [paper](https://www.nature.com/articles/s42256-020-0212-3)
  Note: introduces end-to-end explanatory interactive learning, fixes clever Hans deep neural nets.

- **Human-driven FOL explanations of deep learning**
  Gabriele Ciravegna, Francesco Giannini, Marco Gori, Marco Maggini, Stefano Melacci; IJCAI 2020 [paper](https://www.ijcai.org/Proceedings/2020/0309.pdf)
  Notes: first-order logic.

- **Machine Guides, Human Supervises: Interactive Learning with Global Explanations**
  Teodora Popordanoska, Mohit Kumar, Stefano Teso; arXiv 2020 [paper](https://arxiv.org/pdf/2009.09723.pdf)
  Note: introduces narrative bias and explanatory guided learning, focuses on human-initiated interaction and global explanations.

- **Right for the Right Concept: Revising Neuro-Symbolic Concepts by Interacting with their Explanations**
  Wolfgang Stammer, Patrick Schramowski, and Kristian Kersting; arXiv 2020 [paper](https://arxiv.org/pdf/2011.12854)
  Notes: first-order logic, attention.



### [Background](#content)

A selection of general resources on Explainable AI focusing on overviews, surveys, societal implications, and critiques:

- **The Mythos of Model Interpretability**
  Zachary Lipton, CACM, 2016 [paper](https://dl.acm.org/doi/pdf/10.1145/3236386.3241340)

- **A survey of methods for explaining black box models**
  Riccardo Guidotti, Anna Monreale, Salvatore Ruggieri, Franco Turini, Fosca Giannotti, and Dino Pedreschi; ACM Computing Surveys, 2018 [paper](https://dl.acm.org/doi/pdf/10.1145/3236009)

- **Explanation in Artificial Intelligence: Insights from the Social Sciences**
  Tim Miller; Artificial Intelligence, 2019 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0004370218305988)

- **Unmasking clever hans predictors and assessing what machines really learn**
  Sebastian Lapuschkin, Stephan Wäldchen, Alexander Binder, Grégoire Montavon, Wojciech Samek, Klaus-Robert Müller; Nature Communications 2019 [paper](https://www.nature.com/articles/s41467-019-08987-4)

- **Interpretation of neural networks is fragile**
  Amirata Ghorbani, Abubakar Abid, James Zou; 2019 AAAI [paper](https://ojs.aaai.org/index.php/AAAI/article/view/4252/4130)

- **Is Attention Interpretable?**
  Sofia Serrano, Noah A. Smith; 2019 ACL [paper](https://www.aclweb.org/anthology/P19-1282.pdf)

- **Attention is not Explanation**
  Sarthak Jain, and Byron C. Wallace; ACL 2019 [paper](https://www.aclweb.org/anthology/N19-1357.pdf)

- **Attention is not not Explanation**
  Sarah Wiegreffe, and Yuval Pinter; 2019, EMNLP-IJCNLP [paper](https://www.aclweb.org/anthology/D19-1002.pdf)

- **The (un)reliability of saliency methods**
  Pieter-Jan Kindermans, Sara Hooker, Julius Adebayo, Maximilian Alber, Kristof T. Schütt, Sven Dähne, Dumitru Erhan, and Been Kim; 2019 Explainable AI: Interpreting, Explaining and Visualizing Deep Learning [paper](http://interpretable-ml.org/nips2017workshop/papers/10.pdf)

- **Explanations can be manipulated and geometry is to blame**
  Ann-Kathrin Dombrowski, Maximillian Alber, Christopher Anders, Marcel Ackermann, Klaus-Robert Müller, and Pan Kessel; 2019 NeurIPS [paper](https://papers.nips.cc/paper/2019/file/bb836c01cdc9120a9c984c525e4b1a4a-Paper.pdf)

- **Fooling Neural Network Interpretations via Adversarial Model Manipulation**
  Juyeon Heo, Sunghwan Joo, and Taesup Moon; 2019 NeurIPS [paper](https://proceedings.neurips.cc/paper/2019/file/7fea637fd6d02b8f0adf6f7dc36aed93-Paper.pdf)



### Comments

This list is directly inspired by all the awesome awesome lists out there!