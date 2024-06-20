# CoDefeater: Using LLMs To Find Defeaters in Assurance Cases

This repo contains the datasets (assurance cases) and results for the paper submission at ASE 2023 - NIER

**Abstract:** Constructing assurance cases is a widely used, and sometimes required, process toward demonstrating that safety-critical systems will operate safely in their planned environment. %and comply with regulatory standards. However, developing assurance cases is difficult and time-consuming. To mitigate the risk of errors and missing edge cases, the concept of defeaters - arguments or evidence that challenge claims in an assurance case - has been introduced. Defeaters can provide timely detection of weaknesses in the arguments, prompting further investigation and timely mitigations. However, capturing defeaters relies on expert judgment, experience, and creativity and must be done iteratively due to evolving requirements and regulations. This new ideas paper proposes CoDefeater, an automated process to leverage Large Language Models (LLMs) for finding defeaters. Initial results on two systems show that LLMs can efficiently find known and unforeseen feasible defeaters to support safety analysts in enhancing the completeness and confidence of assurance cases.


## Index

1. Datasets (Assurace Cases) <br>
	- Large Hadron Collider (LHC)Machine Protection System (MPS). This assurance case was originally developed by Rees, Chris, et al. 2023 [1]. The [full assurance case](https://cds.cern.ch/record/2854725/files/LHC%20MPS%20-%20Original%20EA_argument%20+%20Preamble.pdf), [related paper](https://cds.cern.ch/record/2854725/files/Manuscript.pdf) and supplementary material can be found [here](https://cds.cern.ch/record/2854725) <br>
	- [sUAS Battery Case](Datasets/sUAS) <br>
