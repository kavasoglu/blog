---
layout: post
categories:
  - data science
permalink: /data_science/ml/
summary:
order: 0
---
To start with, let's answer to this question: Why do we need machine learning at all?  

Statisticians and developers have been trying to guess the outcome of an event based on observations of already existing ones. Statisticians have been using mathematical operations on the data they have and, they have been trying to explain the outcome with the probabilities. And, developers have been implementing rule-based systems to predict the outcome of a new event. When we have a huge number of events, it becomes really difficult to do mathematical calculations or implement these rule-based systems, and because a computer is good at numerical values and computation, we have started to make machines learn to do these operations somehow with the numerous methods called "machine learning".

We can investigate machine learning methods in 3 sub-categories:
- Supervised learning
- Unsupervised learning
- Reinforcement learning

Supervised learning is used when we have labeled data. We have many observed entities with their real outcomes, and we are trying to guess the outcome of a new entity based on the data we have already. Supervised learning can be divided into 2 categories: classification and regression. Classification methods have categorical outcomes, we are identifying entities as categories like an email is spam or not. Whereas, regression methods have numerical outcomes and can be used eg. when we try to find out price of a house.  

Unsupervised learning is used when we have data but no outcomes of the entities. We try to group the entities according to their similarities based on some features that we identify. An example application could be document clustering: we have a bunch of documents, and we try to group them according to their subjects, they can be related to politics, technology or cooking. In that case, unsupervised methods are used. Also, these methods are also widely used to reduce data set to a smaller subset.  

Reinforcement learning applies penalty or reward to improve the method progress. When a correct outcome is produced, a reward is given to follow up in that path and vice versa for the penalty case. It is used in gaming agents, software in cars etc.  

Deep learning can be applied to all these 3 sub-categories. The initial idea behind deep learning was we care about the accuracy of an outcome not how we find it out, and due to this, we rarely understand the reasonings of the outcome predicted by deep learning models. To use deep learning we need huge volume of data and unfortunately high computing power, so right now it is not feasible to use these models for everyday jobs.  

As we have already mentioned, machine learning methods are applied on the data we have. Due to this fact, we need to validate our data to avoid bias as much as possible. It seems inevitable not to produce biased data since we are all human beings, and it is difficult to catch if we carry any bias in ourselves. But, it is always a good practice to check if we have a meaningful real world data before applying machine learning methods.  
