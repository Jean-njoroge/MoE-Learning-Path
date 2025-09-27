# Foundations of AI and the Role of Mixture of Experts (MoE)

## 🎯 Purpose
This document introduces the **big picture of AI** before the week-by-week modules.  
It explains:
1. What AI is at a high level.
2. The main **building blocks of AI systems**.
3. Where **Mixture of Experts (MoE)** fits in this landscape.

---

## 1. What is AI?
Artificial Intelligence (AI) is the field of creating systems that can:
- **Perceive** (see, hear, read)
- **Reason** (draw conclusions, plan)
- **Learn** (improve from data/experience)
- **Act** (take decisions in the world)

---

## 2. Elements of AI Systems
Every AI system can be thought of as layers:

1. **Algorithm layer** → architectures (CNNs, RNNs, Transformers, MoE).  
2. **Data layer** → datasets, embeddings, knowledge graphs.  
3. **Optimization layer** → training methods, reinforcement learning, scaling.  
4. **Infrastructure layer** → hardware (GPUs/TPUs), distributed compute.  
5. **Application layer** → APIs, apps, products.  
6. **Governance layer** → ethics, safety, regulations.

> These layers stack together like a system — MoE lives mainly in the **algorithm layer** but impacts training and infrastructure as well.

---

## 3. Where MoE Fits
- **Past:** Symbolic AI tried “experts” via rules.  
- **Now:** MoE brings the idea of “experts” into deep learning, where *parts of the model activate only when needed*.  
- **Why important:** MoE enables **scalability** (bigger models without proportional compute cost).  
- **Relevance:** MoE sits inside the *transformer family*, extending foundation models with sparse expert routing.

---

## 4. Roadmap for this Learning Path
- **Week 1** → Fundamentals of AI & system elements.  
- **Week 2** → Implementation of MoE in modern architectures.  
- **Week 3** → Reasoning, symbolic MoE, composition.  
- **Week 4** → Applications, deployment, and future directions.  

---

## ✅ Takeaway
Before diving into code and architectures, it’s crucial to see the **system as a whole**.  
This foundation ensures that as we learn MoE, we understand:
- Where it lives in AI’s ecosystem.  
- How it connects to data, training, infrastructure, and applications. 
