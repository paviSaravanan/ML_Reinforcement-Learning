# ML_Reinforcement-Learning

Reinforcement learning is an area of Machine Learning. It is about taking suitable action to maximize reward in a particular situation. Unlike supervised algorithms, there is no answer(predictor) in reinforcement learning, but the reinforcement agent decides what to do to perform the given task. In the absence of a training dataset, it is bound to learn from its experience.

This model used UCB(Upper Confidence Bound)algorithm. UCB follows the principle of optimism in the face of uncertainty which implies that if we are uncertain about an action, we should optimistically assume that it is the correct action. 

The dataset used in this model consists of 10 different design(or variations) of same ad as attributes and each row refers to different users.
Our aim is to choose the most attractive ad for product marketing. This can be done by showing 10 different designs to different users. And, we have to record the action(how many times each ad is clicked and viewed by the users). Based on these actions, we have to finalise the best ad to promote the product.

Hence this is a dynamic process. We are recording it in real time. So, we are going for reinforcement learning approach. This model is built by implementing UCB algorithm.

