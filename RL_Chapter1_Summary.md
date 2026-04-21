**What is Reinforcement Learning (RL)?**

*   RL is a subfield of machine learning that focuses on automatic learning of optimal decisions over time.
*   It inherently incorporates a time dimension into its learning equations, unlike typical supervised learning problems.
*   RL is often described as being closer to how people understand artificial intelligence.

**Comparison with Other ML Disciplines:**

*   **Supervised Learning:**
    *   Involves building a function to map inputs to outputs based on labeled example pairs ("ground truth").
    *   Examples: Text classification (spam/not spam), image classification (cat/dog), regression (weather prediction), sentiment analysis.
*   **Unsupervised Learning:**
    *   Assumes no predefined labels and aims to learn hidden structures in datasets.
    *   Examples: Clustering data (finding similar items/clients), Generative Adversarial Networks (GANs) for generating fake data.
*   **Reinforcement Learning:**
    *   Falls between full supervision and no predefined labels.
    *   Uses methods from supervised learning (e.g., deep neural networks, stochastic gradient descent) but applies them differently.

**Core Concepts in RL:**

*   **Agent:** The entity that takes actions in an environment, observes the environment, and receives rewards. (e.g., robot mouse, chess program, human brain).
*   **Environment:** Everything outside the agent with which the agent interacts. It provides rewards and observations.
*   **Actions:** Things an agent can do in the environment. Can be discrete (e.g., move left/right) or continuous (e.g., steering angle).
*   **Reward:** A scalar value obtained periodically from the environment, indicating how well the agent has behaved (positive for good, negative for bad, neutral for nothing special). The agent's goal is to maximize accumulated reward.
    *   Examples of rewards: Financial profit, win/lose/draw in chess, dopamine release in the brain, game scores.
*   **Observations:** Pieces of information the environment provides the agent, indicating what's happening around it. These differ from the environment's full internal state, which is usually too vast or impossible to fully know.

**Complications in RL:**

*   **Dependency on Agent Behavior:** Observations are influenced by the agent's actions; inefficient actions can lead to misleading feedback.
*   **Non-IID Data:** Observations are not independent and identically distributed, which is a requirement for many supervised learning methods.
*   **Exploration/Exploitation Dilemma:** Agents must balance using known successful actions (exploitation) with trying new actions to discover better rewards (exploration).
*   **Delayed Reward:** The consequences (rewards) of actions can be significantly delayed, making it challenging to attribute causality.

**RL Formalisms:**

*   RL has specific assumptions and limitations that define its applicability.
*   Key entities are the **agent** and **environment**, communicating through **actions**, **reward**, and **observations**. 