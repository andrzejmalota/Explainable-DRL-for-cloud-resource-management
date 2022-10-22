# Master Thesis: System for explaining actions of cloud resource management policies trained with use of Deep Reinforcement Learning

Abstract

Cloud computing resources management is a critical component of the modern cloud
computing platform, which is one of the most important IT services developed in recent
years as most online applications are dependent upon its resources. The objective of cloud
resource management is to optimally manage computing resources for the application in a
way that minimizes the cost of the infrastructure for the user while maintaining the high
Quality-of-Service (QoS). This task is often solved using rule-based policies but more robust
and complex solutions such as Deep Reinforcement Learning (DRL) agents are being heavily researched or already used in production. As the agent’s decisions have a huge financial
impact on both the user and the Cloud Services Provider (CSP) it is very important to understand the reasoning behind the policy decisions to achieve higher trust, transparency, and
dependability of the system. This thesis provides global and local interpretability by applying the eXplainable Artificial Intelligence (XAI) algorithm - Integrated Gradients (IG) to the
deep learning model upon which the DRL agent is built to produce feature s that show the
magnitude and the direction of the feature’s influence on the agent’s decision. Thanks to the
statistical analysis of the DRL agents, we were able to differentiate between the proactive
and reactive agents. A reactive agent reacted with delay to the increase in the workload. On
the other hand, proactive agents were able to predict the spikes and provide the necessary
computing resources ahead of time. The main analysis based on the feature attributions was
very fruitful, firstly, we were able to create agent policy summarization, by calculating the
absolute mean attributions or positive/negative mean attributions we could showcase the most
important features for each agent. Secondly, feature attributions empowered us to analyze the
learning process of the agents by looking at the feature attributions changes between the consecutive iterations of the agent. Local interpretability meant that we could debug the agent’s
prediction, analyze why the agent made the wrong decisions, or even find examples where
the agent made the right decision but based it on the wrong reasons. In the last step of the
analysis, we successfully performed feature selection by removing from the environment the
feature, that had a small impact on the agent’s decision and showed that there was no performance drop in the agent trained without that feature while making the training faster and the
agent simpler and easier to interpret.
