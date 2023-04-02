Machine Learning for Theorem Proving
====================================

This is a list of papers broadly related to machine learning for theorem proving. PRs are welcome.


## Theorem Proving in Proof Assistants (a.k.a. Interactive Theorem Provers)

### Coq

* [GamePad](https://arxiv.org/abs/1806.00608)
* [CoqGym](https://arxiv.org/abs/1905.09381)
* [TacticToe: Learning to Prove with Tactics](https://arxiv.org/abs/1804.00596)
* [TacTok: Semantics-Aware Proof Synthesis](https://dl.acm.org/doi/abs/10.1145/3428299)
* [Generating Correctness Proofs with Neural Networks](https://dl.acm.org/doi/abs/10.1145/3394450.3397466)
* [Passport: Improving Automated Formal Verification Using Identifiers](https://arxiv.org/abs/2204.10370)
* [The Tactician: A Seamless, Interactive Tactic Learner and Prover for Coq](https://link.springer.com/chapter/10.1007/978-3-030-53518-6_17)
* [Hammer for Coq: Automation for Dependent Type Theory](https://link.springer.com/article/10.1007/s10817-018-9458-4)
* 

### HOL Light

* [HoList](https://arxiv.org/abs/1904.03241)
* [Graph Representations for Higher-Order Logic and Theorem Proving](https://arxiv.org/abs/1905.10006)
* [Mathematical Reasoning via Self-supervised Skip-tree Training](https://arxiv.org/abs/2006.04757)
* [Learning to Reason in Large Theories without Imitation](https://arxiv.org/abs/1905.10501)
* [Retrieval-Augmented Proof Step Synthesis](http://aitp-conference.org/2021/abstract/paper_18.pdf), Szeged et al., AITP 2021:
* [LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning](https://arxiv.org/abs/2101.06223)
* [Mathematical Reasoning in Latent Space](https://arxiv.org/abs/1909.11851)
* [HOL(y)Hammer: Online ATP Service for HOL Light](https://arxiv.org/abs/1309.4962)
* [HolStep: A Machine Learning Dataset for Higher-order Logic Theorem Proving](https://arxiv.org/abs/1703.00426)


### Isabelle

* [IsarStep: a Benchmark for High-level Mathematical Reasoning](https://arxiv.org/abs/2006.09265)
* [Thor: Wielding Hammers to Integrate Language Models and Automated Theorem Provers](https://arxiv.org/abs/2205.10893)
* [Magnushammer: A Transformer-based Approach to Premise Selection](https://arxiv.org/abs/2303.04488)
* [Baldur: Whole-Proof Generation and Repair with Large Language Models](https://arxiv.org/abs/2303.04910)
* [LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning](https://arxiv.org/abs/2101.06223)
* [Hammering towards QED](https://pure.mpg.de/rest/items/item_2381986/component/file_2381985/content)
* [LISA: Language Models of Isabelle Proofs](http://aitp-conference.org/2021/abstract/paper_17.pdf), Jiang et al., AITP 2021:


### Lean

* [Formal Mathematics Statement Curriculum Learning](https://arxiv.org/abs/2202.01344)
* [Proof Artifact Co-Training](https://arxiv.org/abs/2102.06203)
* [LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning](https://arxiv.org/abs/2101.06223)
* [HyperTree Proof Search for Neural Theorem Proving](https://arxiv.org/abs/2205.11491)


### Metamath

* [Learning to Prove Theorems by Learning to Generate Theorems](https://arxiv.org/abs/2002.07019)
* [HyperTree Proof Search for Neural Theorem Proving](https://arxiv.org/abs/2205.11491)
* [Generative Language Modeling for Automated Theorem Proving](https://arxiv.org/abs/2009.03393)
* [LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning](https://arxiv.org/abs/2101.06223)


### Others

* [INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving](https://arxiv.org/abs/2007.02924)
* [MiniF2F: a cross-system benchmark for formal Olympiad-level mathematics](https://arxiv.org/abs/2109.00110)
* [TacticZero: Learning to Prove Theorems from Scratch with Deep Reinforcement Learning](https://arxiv.org/abs/2102.09756)


## Autoformalization

* [Autoformalization with Large Language Models](https://arxiv.org/abs/2205.12615)
* [Towards a Mathematics Formalisation Assistant using Large Language Models](https://arxiv.org/abs/2211.07524)
* [Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs](https://arxiv.org/abs/2210.12283)
* [Data-Efficient Learning of Natural Language to Linear Temporal Logic Translators for Robot Task Specification](https://arxiv.org/abs/2303.08006)
* [nl2spec: Interactively Translating Unstructured Natural Language to Temporal Logics with Large Language Models](https://arxiv.org/abs/2303.04864)
* [ProofNet: Autoformalizing and Formally Proving Undergraduate-Level Mathematics](https://arxiv.org/abs/2302.12433)
* [Towards a Mathematics Formalisation Assistant using Large Language Models](https://arxiv.org/abs/2211.07524)
* [Formal Specifications from Natural Language](https://arxiv.org/abs/2206.01962)
* [Towards Autoformalization of Mathematics and Code Correctness: Experiments with Elementary Proofs](https://arxiv.org/abs/2301.02195)


## Premise Selection

* [DeepMath - Deep Sequence Models for Premise Selection](https://arxiv.org/abs/1606.04442)
* [Machine-Learned Premise Selection for Lean](https://bartoszpiotrowski.pl/p/lean-premise-selection-paper.pdf)
* [Premise Selection for Theorem Proving by Deep Graph Embedding](https://arxiv.org/abs/1709.09994)


## Theorem Proving in First-Order Logic

* [Training a First-Order Theorem Prover from Synthetic Data](https://arxiv.org/abs/2103.03798)
* [Proving Theorems using Incremental Learning and Hindsight Experience Replay](https://proceedings.mlr.press/v162/aygun22a.html)
* [Machine Learning for First-Order Theorem Proving: Learning to Select a Good Heuristic](https://link.springer.com/article/10.1007/s10817-014-9301-5)
* [Deep Network Guided Proof Search](https://arxiv.org/abs/1701.06972)
* [MaLeCoP Machine Learning Connection Prover](https://link.springer.com/chapter/10.1007/978-3-642-22119-4_21)


## Machine Learning for Other Symbolic Tasks Related to Theorem Proving

* [FastSMT](http://fastsmt.ethz.ch/)
* [Learning Loop Invariants for Program Verification](https://papers.nips.cc/paper_files/paper/2018/hash/65b1e92c585fd4c2159d5f33b5030ff2-Abstract.html)
* [Learning to Find Proofs and Theorems by Learning to Refine Search Strategies: The Case of Loop Invariant Synthesis](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1f14ac136d55c34a18a04ce3db083599-Abstract-Conference.html), Laurent and Platzer, NeurIPS 2022:
* [Learning Heuristics for Quantified Boolean Formulas through Deep Reinforcement Learning](https://arxiv.org/abs/1807.08058)
* [Teaching Temporal Logics to Neural Networks](https://arxiv.org/abs/2003.04218)
* [Learning a SAT Solver from Single-Bit Supervision](https://arxiv.org/abs/1802.03685)
* [Guiding High-Performance SAT Solvers with Unsat-Core Predictions](https://link.springer.com/chapter/10.1007/978-3-030-24258-9_24)


## Theorem Proving and Mathematical Reasoning in Natural Language

* [NaturalProofs: Mathematical Theorem Proving in Natural Language](https://arxiv.org/abs/2104.01112)
* [NaturalProver: Grounded Mathematical Proof Generation with Language Models](https://arxiv.org/abs/2205.12910)
* [A Survey of Deep Learning for Mathematical Reasoning](https://arxiv.org/abs/2212.10535)
* [LILA: A Unified Benchmark for Mathematical Reasoning](https://aclanthology.org/2022.emnlp-main.392/)
* [Measuring Mathematical Problem Solving With the MATH Dataset](https://arxiv.org/abs/2103.03874)
* [Solving Quantitative Reasoning Problems with Language Models](https://arxiv.org/abs/2206.14858)
* [A Survey in Mathematical Language Processing](https://arxiv.org/abs/2205.15231)
