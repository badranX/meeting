# RL for Student data. 
"MOReL: Model-Based Offline Reinforcement Learning" by Rahul et al.

The main algorithm of the paper:

Algorithm 1 MOReL: Model Based Offline Reinforcement Learning
- 1: Require Dataset D
- 2: Learn approximate dynamics model P̂ : S × A → S using D.
- 3: Construct α-USAD, U α : S × A → {TRUE, FALSE} using D (see Definition 1).
- 4: Construct the pessimistic MDP M̂p = {S ∪ HALT, A, rp , P̂p , ρ̂0 , γ} (see Definition 2).
- 5: (OPTIONAL) Use a behavior cloning approach to estimate the behavior policy π̂b .
- 6: πout ← PLANNER(M̂p , πinit = π̂b )
- 7: Return πout ..

# KT evaluation
EduStudio a new github repo for KT models and KT datasets
[Link](https://edustudio.readthedocs.io/en/latest/)

# KT based recommender evaluation
"ADAPTIVE LEARNING PATH NAVIGATION BASED ON
KNOWLEDGE TRACING AND REINFORCEMENT LEARNING" 2023 by Chen et al.

evaluates the model by "the average pass rate (APR) for all exercises" as measured by a KT model at time t.
