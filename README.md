# Frome-Memory-to-Experience
Paper list for "From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms".

## 📖 Introduction
While memory mechanisms have emerged as the architectural cornerstone of LLM agents, current research remains fragmented, oscillating between operating system engineering and cognitive science. This theoretical divide prevents a unified view of technological synthesis and a coherent evolutionary perspective. To bridge this gap, this repository maintains the paper list for our survey: [**"From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms"**](https://www.preprints.org/manuscript/202601.0618). We propose a novel **Evolutionary Framework** that formalizes the development of LLM agent memory into three distinct stages:
1. 💾 **Storage** (Trajectory Preservation): Focusing on the complete preservation and basic retrieval of raw interaction traces.
2. 🧠 **Reflection** (Trajectory Refinement): Introducing analysis mechanisms to refine and correct original memories through reflection.
3. 🌟 **Experience** (Trajectory Abstraction)：Transforming trajectory clusters into experience through cross-trajectory abstraction techniques.

By focusing on these pivotal technologies and their positions within the evolution path, this project aims to offer a unified roadmap to help the community research and design next-generation LLM Agent Memory systems.

## 🛤️ Evolution Path
![Evolution Path](./figures/figure1.PNG)
<p align="center"><i>Figure 1: The Evolutionary path of LLM Agent Memory.</i></p>

Before diving into the evolution of memory mechanisms, we first establish the standard workflow for an LLM Agent integrated with memory. Taking the classic ReAct paradigm as an example, the Agent's decision-making process forms a dynamic closed loop enabled by memory.
During each task execution cycle, the Agent leverages two core capabilities:
1. **Memory Read**: The Agent actively retrieves relevant knowledge from the memory bank to supplement the current context.
2. **Memory Write**: As the task progresses, the generated interaction sequences are recorded as historical trajectories and are written into the memory system in real-time.
## 📜 PaperList
### 💾 Storage
### 🧠 Reflection
### 🌟 Experience

##
