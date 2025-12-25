AI PAPERS FLASH DRIVE
========================================================================
This is meant to be a fun weekend activity (or something to dig into whenever you have free time and feel like learning something new) If you end up enjoying it, maybe you will end up starting your own project because you enjoyed this so much. Do with it what you please.

In this flash drive I’ve included a curated set of AI research papers you can skim or read in full to get a strong feel for what’s happening at the cutting edge of AI right now and read for a greater understanding about the current AI industry.

I wanted to put this together because I understand that this is a very interesting topic to you. 
========================================================================

I also included links to some of my own projects and code from my GitHub so you can see what these ideas and different implementations of these different AI technologies and algorithms look like in practice, how they’re actually implemented in code, not just described in theory.  

ARGUS (personal AI assistant):
https://github.com/BJW333/ARGUS
Note: The README.md for ARGUS isn’t fully updated to the newest version of the system, but it does a good job explaining the basics of what it does.

RoMaLM:
https://github.com/BJW333/RoMaLM

Sensory System:
https://github.com/BJW333/Sensory_System


Long-term, the idea is that ARGUS + the Sensory System, once integrated, would function like one larger “world-model-style” system: the Sensory System gathers and summarizes environment context, and ARGUS uses that context to reason and act and respond to user inputs but also to respond proactively based on things it notices within the context of what is returned from the Sensory System. They aren’t integrated yet, but that’s the direction. ARGUS also can self improve itself and its knowledge already I just haven't integrated Sensory System yet due to efficiency and compute issues.


On GitHub, you can download individual Python (.py) files from the repos. If any of the code is confusing, you can drag and drop the file into ChatGPT and ask for a quick explanation or a walkthrough of what each function does. I highly recommend doing this it makes the projects much easier to understand fast as READMEs dont always cover the in depth cutting edge work done for instance with ARGUS or RoMaLM.



========================================================================

How to use this folder:
  - Each folder is a topic (LLMs, world models, self-organizing nets, etc.)
  - Open PDFs in any PDF viewer. If you want a guided order, try this:

========================================================================

=================
READING PATHS:
=================

How to read:
- Start with Abstract + Intro + Figures + Conclusion.
- Don’t get stuck on math. If it’s dense, skip ahead and come back.

-----------------------------------------------------------------------
PATH A — BIG-PICTURE / CONCEPTS 
-----------------------------------------------------------------------
1) 04_World_Models/A Path Towards Autonomous Machine Intelligence (LeCun).pdf
2) 01_LLM_Foundations/Attention Is All You Need (Transformer).pdf
3) 01_LLM_Foundations/GPT-4 Technical Report.pdf
4) 01_LLM_Foundations/A Survey of Large Language Models.pdf
5) 06_Reasoning_TestTime/The Illusion of Thinking (Apple).pdf
6) 04_World_Models/World Models (Ha & Schmidhuber).pdf
7) 04_World_Models/DreamerV3 - Mastering Diverse Domains through World Models.pdf
8) 04_World_Models/MuZero - Planning with a Learned Model.pdf
9) 07_Self_Improvement/Godel Agent - A Self-Referential Agent Framework for Recursive Self-Improvement.pdf
10) 07_Self_Improvement/Darwin Godel Machine - Open-Ended Evolution of Self-Improving Agents.pdf
11) 05_Self_Organizing_NNs/A Survey on Recent Advances in Self-Organizing Maps.pdf
12) 07_Self_Improvement/Self-Taught Optimizer (STOP) - Recursively Self-Improving Code Generation.pdf
13) 02_Alignment_Preference/Hyperparameter Optimization in Machine Learning.pdf

-----------------------------------------------------------------------
PATH B — BUILDER / SYSTEMS (Uncle)
-----------------------------------------------------------------------
1) 01_LLM_Foundations/Attention Is All You Need (Transformer).pdf
2) 01_LLM_Foundations/Training Compute-Optimal Large Language Models (Chinchilla).pdf
3) 02_Alignment_Preference/LoRA - Low-Rank Adaptation of Large Language Models.pdf
4) 02_Alignment_Preference/QLoRA - Efficient Finetuning of Quantized LLMs.pdf
5) 02_Alignment_Preference/Direct Preference Optimization (DPO).pdf
6) 03_RAG_Tools_Agents/Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (RAG).pdf
7) 03_RAG_Tools_Agents/Self-RAG - Learning to Retrieve, Generate, and Critique through Self-Reflection.pdf
8) 03_RAG_Tools_Agents/Toolformer - Language Models Can Teach Themselves to Use Tools.pdf
9) 03_RAG_Tools_Agents/ReAct - Synergizing Reasoning and Acting in Language Models.pdf
10) 08_Efficiency/FlashAttention-3 - Fast and Accurate Attention with Asynchrony and Low Precision.pdf
11) 08_Efficiency/Transformers are SSMs - Generalized Models and Efficient Algorithms.pdf
12) 07_Self_Improvement/Self-Taught Optimizer (STOP) - Recursively Self-Improving Code Generation.pdf
13) 02_Alignment_Preference/Hyperparameter Optimization in Machine Learning.pdf

Extras (optional):
- 04_World_Models/V-JEPA 2 - Self-Supervised Video Models Enable Understanding, Prediction, and Planning.pdf
- 09_Multimodal/SAM 2 - Segment Anything in Images and Videos.pdf

========================================================================


Folder map:
  01_LLM_Foundations      - What modern LLMs are & how they scale
  02_Alignment_Preference - Aligning models with human preferences
  03_RAG_Tools_Agents     - Tool use, retrieval, and agents
  04_World_Models         - Predictive models of environments + planning
  05_Self_Organizing_NNs  - Self-organization: SOMs, plasticity, growth
  06_Reasoning_TestTime   - Test-time compute & reasoning limits
  07_Self_Improvement     - Self-improving/self-modifying systems
  08_Efficiency           - Speedups / alternatives to vanilla attention
  09_Multimodal           - Vision + language + segmentation


Included papers:

  - [01_LLM_Foundations] A Survey of Large Language Models
  - [01_LLM_Foundations] Attention Is All You Need (Transformer)
  - [01_LLM_Foundations] GPT-4 Technical Report
  - [01_LLM_Foundations] Qwen2.5 Technical Report
  - [01_LLM_Foundations] The Llama 3 Herd of Models
  - [01_LLM_Foundations] Training Compute-Optimal Large Language Models (Chinchilla)
  - [02_Alignment_Preference] Direct Preference Optimization (DPO)
  - [02_Alignment_Preference] Hyperparameter Optimization in Machine Learning
  - [02_Alignment_Preference] LoRA - Low-Rank Adaptation of Large Language Models
  - [02_Alignment_Preference] QLoRA - Efficient Finetuning of Quantized LLMs
  - [03_RAG_Tools_Agents] A Survey on Large Language Model based Autonomous Agents
  - [03_RAG_Tools_Agents] Large Language Model based Multi-Agents - A Survey of Progress and Challenges
  - [03_RAG_Tools_Agents] ReAct - Synergizing Reasoning and Acting in Language Models
  - [03_RAG_Tools_Agents] Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (RAG)
  - [03_RAG_Tools_Agents] Self-RAG - Learning to Retrieve, Generate, and Critique through Self-Reflection
  - [03_RAG_Tools_Agents] Toolformer - Language Models Can Teach Themselves to Use Tools
  - [04_World_Models] A Path Towards Autonomous Machine Intelligence (LeCun)
  - [04_World_Models] DreamerV3 - Mastering Diverse Domains through World Models
  - [04_World_Models] MuZero - Planning with a Learned Model
  - [04_World_Models] PlaNet - Learning Latent Dynamics for Planning from Pixels
  - [04_World_Models] V-JEPA 2 - Self-Supervised Video Models Enable Understanding, Prediction, and Planning
  - [04_World_Models] World Models (Ha & Schmidhuber)
  - [05_Self_Organizing_NNs] A Survey on Recent Advances in Self-Organizing Maps
  - [05_Self_Organizing_NNs] Evolving Self-Assembling Neural Networks (LNDP)
  - [05_Self_Organizing_NNs] SONGs - Self-Organizing Neural Graphs
  - [05_Self_Organizing_NNs] SORN - a self-organizing recurrent neural network
  - [06_Reasoning_TestTime] The Illusion of Thinking (Apple)
  - [06_Reasoning_TestTime] s1 - Simple test-time scaling
  - [07_Self_Improvement] Darwin Godel Machine - Open-Ended Evolution of Self-Improving Agents
  - [07_Self_Improvement] Godel Agent - A Self-Referential Agent Framework for Recursive Self-Improvement
  - [07_Self_Improvement] Self-Programming Artificial Intelligence Using Code-Generating Language Models
  - [07_Self_Improvement] Self-Taught Optimizer (STOP) - Recursively Self-Improving Code Generation
  - [08_Efficiency] FlashAttention-3 - Fast and Accurate Attention with Asynchrony and Low Precision
  - [08_Efficiency] Transformers are SSMs - Generalized Models and Efficient Algorithms
  - [09_Multimodal] LLaVA - Visual Instruction Tuning
  - [09_Multimodal] LLaVA-1.5 - Improved Baselines with Visual Instruction Tuning
  - [09_Multimodal] LLaVA-OneVision-1.5
  - [09_Multimodal] SAM 2 - Segment Anything in Images and Videos

