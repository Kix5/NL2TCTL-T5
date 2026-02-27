NLT2CTL — Natural Language to Timed Continuous Temporal Logic

An extension of NL2TL by Yongchao Chen et al.

Overview
NLT2CTL extends the NL2TL framework to support Timed Continuous Temporal Logic (CTL). While the original NL2TL project focuses on translating natural language instructions into temporal logic formulas, this repository pushes that further by handling the timed and continuous aspects of system behavior — enabling richer and more expressive specifications for real-world, time-sensitive systems.

Original Work
This project builds on top of:

Repository: https://github.com/yongchao98/NL2TL
Authors: Yongchao Chen et al.

Please refer to the original repository for the foundational methodology 
NLT2CTL extends NL2TL with the following:

Timed Temporal Logic: Support for time-bounded operators, allowing specifications such as "within 5 seconds" or "always after time T".
Continuous Dynamics: Handling of continuous-time system behaviors, going beyond discrete event-based temporal logic.
Natural Language to CTL Translation: A pipeline that maps natural language descriptions of timed, continuous system requirements directly into CTL formulas.

Dataset
The dataset used in this project was constructed manually combined with few-shot LLM generation to produce labeled natural language to Timed Continuous Temporal Logic formula pairs. The dataset is not included in this repository — please contact the authors if you require access to it.



@article{NL2TL,
  author    = {Yongchao Chen et al.},
  title     = {NL2TL: Transforming Natural Languages to Temporal Logics using Large Language Models},
  year      = {2023},
  url       = {https://github.com/yongchao98/NL2TL}
}
