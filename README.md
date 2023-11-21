# Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents

![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/teasing_figure.png)


👉🏻This repository contains the paper list for the paper: **Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents**

👀Please check out our paper for more information！[[paper]](https://arxiv.org/pdf/2311.11797.pdf)🫡

## Contents

- [Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents](#igniting-language-intelligence-the-hitchhikers-guide-from-chain-of-thought-reasoning-to-language-agents)
  - [Contents](#contents)
  - [Paradigm Shifts of CoT](#paradigm-shifts-of-cot)
    - [1. Prompting Paradigm](#1-prompting-paradigm)
      - [1.1 Instruction Generation](#11-instruction-generation)
      - [1.2 Exemplar Generation](#12-exemplar-generation)
    - [2. CoT Reasoning](#2-cot-reasoning)
      - [2.1 CoT Formulation](#21-cot-formulation)
      - [2.2 Reasoning Aggregation](#22-reasoning-aggregation)
      - [2.3 CoT Verification](#23-cot-verification)
    - [3. CoT Application](#3-cot-application)
      - [3.1 CoT Extension 🖼️](#31-cot-extension-️)
      - [3.2 CoT for Classic NLP Task 📖](#32-cot-for-classic-nlp-task-)
      - [3.3 CoT for Agent🤖](#33-cot-for-agent)
      - [3.4 CoT for Science 🧪](#34-cot-for-science-)
    - [4. CoT Explanation](#4-cot-explanation)
    - [5. CoT Safety](#5-cot-safety)
  - [CoT Agent](#cot-agent)
    - [Communicative Agent](#communicative-agent)
    - [Autonomous Agent](#autonomous-agent)
  - [Citation](#citation)


## Paradigm Shifts of CoT

![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/CoT_overview.png)

### 1. Prompting Paradigm

#### 1.1 Instruction Generation

- **Zero-Shot-CoT**

  [2022.05]  Large language models are zero-shot reasoners [[paper]](https://arxiv.org/abs/2205.11916)

  Kojima T, Gu S S, Reid M, et al. NIPS 2022.

- **Plan-and-solve prompting**

  [2023.05] Plan-and-solve prompting: Improving zero-shot chain-of-thought reasoning by large language models [[paper]](https://arxiv.org/abs/2305.04091)

  Wang L, Xu W, Lan Y, et al. arXiv. 

- **Automatic Prompt Engineer**

  [2022.11] Large language models are human-level prompt engineers [[paper]](https://arxiv.org/abs/2211.01910)
  
  Zhou Y, Muresanu A I, Han Z, et al.  arXiv. 

- **OPRO**

  [2023.09] Large language models as optimizers [[paper]](https://arxiv.org/abs/2309.03409)

  Yang C, Wang X, Lu Y, et al. arXiv. 

#### 1.2 Exemplar Generation

- **Manual-CoT**

  [2022.01] Chain-of-thought prompting elicits reasoning in large language models [[paper]](https://arxiv.org/abs/2201.11903)

  Wei J, Wang X, Schuurmans D, et al.  NIPS 2022.

- **Active-Prompt**

  [2023.02] Active prompting with chain-of-thought for large language models [[paper]](https://arxiv.org/abs/2302.12246)

  Diao S, Wang P, Lin Y, et al.  arXiv.

- **Auto-CoT**

  [2022.10] Automatic chain of thought prompting in large language models [[paper]](https://arxiv.org/abs/2210.03493)

  Zhang Z, Zhang A, Li M, et al. arXiv.

- **Automate-CoT**

  [2023.02] Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data [[paper]](https://arxiv.org/abs/2302.12822)
  
  Shum K S, Diao S, Zhang T. arXiv.

### 2. CoT Reasoning

#### 2.1 CoT Formulation

![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/CoT_formulation.png)

- **Program-of-thoughts**

  [2022.11] Program of thoughts prompting: Disentangling computation from reasoning for numerical reasoning tasks [[paper]](https://arxiv.org/abs/2211.12588)

  Chen W, Ma X, Wang X, et al. arXiv.

- **Tab-CoT**

  [2023.05] Tab-CoT: Zero-shot Tabular Chain of Thought [[paper]](https://aclanthology.org/2023.findings-acl.651/)

  Jin Z, Lu W.  ACL 2023 findings

- **Tree-of-Thoughts**

  [2023.05]  Tree of thoughts: Deliberate problem solving with large language models [[paper]](https://arxiv.org/abs/2305.10601)

  Yao S, Yu D, Zhao J, et al. arXiv.

- **Graph-of-Thought (Rationale)**

  [2023.08] Graph of thoughts: Solving elaborate problems with large language models [[paper]](https://arxiv.org/abs/2308.09687)

  Besta M, Blach N, Kubicek A, et al. arXiv.

- **Skeleton-of-thought**

  [2023.07] Skeleton-of-thought: Large language models can do parallel decoding [[paper]](https://arxiv.org/abs/2307.15337)

  Ning X, Lin Z, Zhou Z, et al. arXiv.

- **Recursion of Thought**

  [2023.06] Recursion of Thought: A Divide-and-Conquer Approach to Multi-Context Reasoning with Language Models [[paper]](https://aclanthology.org/2023.findings-acl.40.pdf)

  Lee S, Kim G. ACL 2023 findings.

#### 2.2 Reasoning Aggregation

- **Rationale-Augmented Ensembles**

  [2022.07] Rationale-augmented ensembles in language models [[paper]](https://arxiv.org/abs/2207.00747)

  Wang X, Wei J, Schuurmans D, et al. arXiv.

- **Self-consistency** **CoT**

  [2022.03] Self-consistency improves chain of thought reasoning in language models [[paper]](https://arxiv.org/abs/2203.11171)

  Wang X, Wei J, Schuurmans D, et al.  ICLR 2023.

#### 2.3 CoT Verification

- **Natural Program**

  [2023.06] Deductive Verification of Chain-of-Thought Reasoning [[paper]]()

  Ling Z, Fang Y, Li X, et al. arXiv.

-  **PRM**

  [2023.05] Let's Verify Step by Step [[paper]](https://arxiv.org/abs/2305.20050)

  Lightman H, Kosaraju V, Burda Y, et al. arXiv.

- **Self-Verification**

  [2022.12] Large language models are better reasoners with self-verification [[paper]](https://arxiv.org/abs/2212.09561)

  Weng Y, Zhu M, Xia F, et al. arXiv.

- **CRITIC**

  [2022.12] Critic: Large language models can self-correct with tool-interactive critiquing [[paper]](https://arxiv.org/abs/2305.11738)

  Gou Z, Shao Z, Gong Y, et al. arXiv.

- **Verify-and-Edit** 🛠️

  [2023.05] Verify-and-edit: A knowledge-enhanced chain-of-thought framework [[paper]](https://aclanthology.org/2023.acl-long.320/)

  Zhao R, Li X, Joty S, et al. ACL 2023.

- **AuRoRA**

  [2023.08] AuRoRA: Augmented Reasoning and Refining with Task-Adaptive Chain-of-Thought Prompting [[website]]({https://anni-zou.github.io/aurora-en.github.io/)

  Zou A, Zhang Z, Zhao H

### 3. CoT Application

#### 3.1 CoT Extension 🖼️

![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/CoT_extension.png)

- **Multilingual-CoT**

  [2022.10] Language models are multilingual chain-of-thought reasoners [[paper]](https://arxiv.org/abs/2210.03057)

  Shi F, Suzgun M, Freitag M, et al. ICLR 2023.

- **Multimodal-CoT**

  [2023.02] Multimodal chain-of-thought reasoning in language models [[paper]](https://arxiv.org/abs/2302.00923)
  
  Zhang Z, Zhang A, Li M, et al. arXiv.
  
- **Graph-of-Thought (Input)**

  [2023.05] Beyond Chain-of-Thought, Effective Graph-of-Thought Reasoning in Large Language Models [[paper]](https://arxiv.org/abs/2305.16582)
  
  Yao Y, Li Z, Zhao H. arXiv.

#### 3.2 CoT for Classic NLP Task 📖

- **SumCoT**

  [2023.05] Element-aware Summarization with Large Language Models: Expert-aligned Evaluation and Chain-of-Thought Method [[paper]](https://aclanthology.org/2023.acl-long.482/)

  Wang Y, Zhang Z, Wang R.  ACL 2023.

- **Self-Prompting**

  [2022.12] Self-prompting large language models for open-domain qa [[paper]](https://arxiv.org/abs/2212.08635)
  
  Li J, Zhang Z, Zhao H. arXiv.

#### 3.3 CoT for Agent🤖

![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/CoT_agent.png)


- **ReAcT**

  [2022.10] React: Synergizing reasoning and acting in language models [[paper]]()

  Yao S, Zhao J, Yu D, et al. ICLR 2023。

- **Android in the Wild**

  [2023.07] Android in the Wild: A Large-Scale Dataset for Android Device Control [[paper]](https://arxiv.org/abs/2307.10088)

  Rawles C, Li A, Rodriguez D, et al. arXiv.

- **ToolLLM**

  [2023.07] Toolllm: Facilitating large language models to master 16000+ real-world apis [[paper]](https://arxiv.org/abs/2307.16789)

  Qin Y, Liang S, Ye Y, et al. arXiv.

- **MM-ReAcT**

  [2023.03] Mm-react: Prompting chatgpt for multimodal reasoning and action [[paper]](https://arxiv.org/abs/2303.11381)
  
  Yang Z, Li L, Wang J, et al. arXiv.

#### 3.4 CoT for Science 🧪

- **ChemCrow**

  [2023.04] ChemCrow: Augmenting large-language models with chemistry tools[[paper]](https://arxiv.org/abs/2304.05376)

  Bran A M, Cox S, White A D, et al. arXiv.

- **Med-PaLM**

  [2022.12] Large language models encode clinical knowledge [[paper]](https://www.nature.com/articles/s41586-023-06291-2)
  
  Singhal K, Azizi S, Tu T, et al.  Nature, 2023.

### 4. CoT Explanation

- **Implicit Bayesian Inference**

  [2021.11] An explanation of in-context learning as implicit bayesian inference [[paper]](https://arxiv.org/abs/2111.02080)

  Xie S M, Raghunathan A, Liang P, et al. arXiv.

- **Locality of Experience**

  [2023.04] Why think step-by-step? Reasoning emerges from the locality of experience [[paper]](https://arxiv.org/abs/2304.03843)
  
  Prystawski B, Goodman N D. arXiv.

### 5. CoT Safety

- **Faithful** **CoT**

  [2023.01] Faithful chain-of-thought reasoning [[paper]](https://arxiv.org/abs/2301.13379)

  Lyu Q, Havaldar S, Stein A, et al. IJCNLP-AACL 2023

- **Bias** **and Toxicity**

  [2023.01] On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning [[paper]](https://aclanthology.org/2023.acl-long.244/)
  
  Shaikh O, Zhang H, Held W, et al. ACL 2023


## CoT Agent
![image](https://github.com/Zoeyyao27/CoT2Agent/blob/main/fig/representative_agents.png)
### Communicative Agent
- **CAMEL**
  
  [2023.03] CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society [[paper]](https://arxiv.org/abs/2303.17760)
  
  Li G, Hammoud H A A K, Itani H, et al. NIPS 2023.

- **Generative Agents**
  
  [2023.04] Generative agents: Interactive simulacra of human behavior [[paper]](https://arxiv.org/abs/2304.03442)
  
  Park J S, O'Brien J C, Cai C J, et al. arXiv.

- **Voyager**
  
  [2023.05] Voyager: An open-ended embodied agent with large language models [[paper]](https://arxiv.org/abs/2305.16291) 

  Wang G, Xie Y, Jiang Y, et al. arXiv.

- **GITM**
  
  [2023.05] Ghost in the Minecraft: Generally Capable Agents for Open-World Enviroments via Large Language Models with Text-based Knowledge and Memory [[paper]](https://arxiv.org/abs/2305.17144)

  Zhu X, Chen Y, Tian H, et al. arXiv.

- **MetaGPT**
  
  [2023.08] Metagpt: Meta programming for multi-agent collaborative framework [[paper]](https://arxiv.org/abs/2308.00352)

  Hong S, Zheng X, Chen J, et al. arXiv.

- **ChatDev**

  Communicative agents for software development [[paper]](https://arxiv.org/abs/2307.07924)

  Qian C, Cong X, Yang C, et al. arXiv.

- **MAD**

  [2023.05] Encouraging Divergent Thinking in Large Language Models through Multi-Agent Debate [[paper]](https://arxiv.org/abs/2305.19118)

  Liang T, He Z, Jiao W, et al. arXiv.

- **Multiagent Debate**

  [2023.05] Improving Factuality and Reasoning in Language Models through Multiagent Debate [[paper]](https://arxiv.org/abs/2305.14325)

  Du Y, Li S, Torralba A, et al. arXiv.

- **FORD**
  
   [2023.05] Examining the Inter-Consistency of Large Language Models: An In-depth Analysis via Debate [[paper]](https://arxiv.org/abs/2305.11595)

   Xiong K, Ding X, Cao Y, et al. arXiv.


- **TE**

  [2022.08] Using large language models to simulate multiple humans and replicate human subject studies [[paper]](https://proceedings.mlr.press/v202/aher23a.html)

  Aher G V, Arriaga R I, Kalai A T. ICML 2023.

- **VIMA**

  [2022.10] Vima: General robot manipulation with multimodal prompts [[paper]](https://arxiv.org/abs/2210.03094)

  Jiang Y, Gupta A, Zhang Z, et al. arXiv.

- **React**

  [2022.10] React: Synergizing reasoning and acting in language models [[paper]](https://arxiv.org/abs/2210.03629)

  Yao S, Zhao J, Yu D, et al. ICLR 2023.


- **Reflexion**

  [2023.03] Reflexion: Language agents with verbal reinforcement learning [[paper]](https://arxiv.org/abs/2303.11366)

  Shinn N, Cassano F, Gopinath A, et al. NIPS 2023.

### Autonomous Agent
- **AutoGPT**
  
  [2023.03] Auto-gpt: An autonomous gpt-4 experiment [[code]](https://github.com/Significant-Gravitas/Auto-GPT)

  Richards, Toran Bruce.

- **BabyAGI**

  [2023.04] BabyAGI [[code]](https://github.com/yoheinakajima/babyagi)

  Nakajima, Yohei

- **AgentGPT**
  
  [2023.09] AgentGPT [[code]](https://github.com/reworkd/AgentGPT)

  Reworkd

- **Auto-UI**

  [2023.09] You Only Look at Screens: Multimodal Chain-of-Action Agents [[paper]](https://arxiv.org/abs/2309.11436)

  Zhan Z, Zhang A. arXiv.

- **AITW**
  
  [2023.09] Android in the wild: A large-scale dataset for android device control [[paper]](https://arxiv.org/abs/2307.10088)

  Rawles C, Li A, Rodriguez D, et al. arXiv.


- **DCACQ**

  [2023.04] Improving grounded language understanding in a collaborative environment by interacting with agents through help feedback [[paper]](https://arxiv.org/abs/2304.10750) 

  Mehta N, Teruel M, Sanz P F, et al. arXiv.


- **ChemCrow**

  [2023.04] ChemCrow: Augmenting large-language models with chemistry tools [[paper]](https://arxiv.org/abs/2304.05376)

  Bran A M, Cox S, White A D, et al. arXiv.

- **Chatmof**

  [2023.08] Chatmof: An autonomous ai system for predicting and generating metal-organic frameworks [[paper]](https://arxiv.org/abs/2308.01423)

  Kang Y, Kim J. arXiv.

- **IASSE**

  [2023.04] Emergent autonomous scientific research capabilities of large language models [[paper]](https://arxiv.org/abs/2304.05332)

  Boiko D A, MacKnight R, Gomes G. arXiv.

- **CodePlan**

  [2023.09] CodePlan: Repository-level Coding using LLMs and Planning [[paper]](https://sci-hub.ru/https://arxiv.org/abs/2309.12499)

  Bairi R, Sonwane A, Kanade A, et al. arXiv.

- **ToRA**

  [2023.09] ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving [[paper]](https://arxiv.org/abs/2309.17452)

  Gou Z, Shao Z, Gong Y, et al. arXiv.

- **Toolformer**

  [2023.02] Toolformer: Language models can teach themselves to use tools [[paper]](https://arxiv.org/abs/2302.04761)

  Schick T, Dwivedi-Yu J, Dessì R, et al. arXiv.

- **Fireact**

  [2023.10] FireAct: Toward Language Agent Fine-tuning [[paper]](https://arxiv.org/abs/2310.05915)
  Chen B, Shu C, Shareghi E, et al. 
## Citation
```
@misc{zhang2023igniting,
      title={Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents}, 
      author={Zhuosheng Zhang and Yao Yao and Aston Zhang and Xiangru Tang and Xinbei Ma and Zhiwei He and Yiming Wang and Mark Gerstein and Rui Wang and Gongshen Liu and Hai Zhao},
      year={2023},
      eprint={2311.11797},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
