# Duplicate Pull Request Detection using an Attention-based Pre-trained Neural Language Model
### Context: 
Open source software community brings together users with common interests to create a healthy open-source project, which can be modified and improved by anyone inside or outside the community via the Pull-Request (PR). However, the PR process is usually uncoordinated and distributed, which could cause massive duplication. Such duplication represents a waste of time and energy for both contributors and reviewers.
### Objective: 
In this paper, we propose an approach based on a pre-trained language model named BERT (Bidirectional Encoder Representations from Transformers) to automatically detect duplicate PRs in GitHub based on textual information.
### Method:
We used a balanced dataset of 3,328 labeled PRs collected from 26 popular GitHub projects. This data is fed into the BERT model in order to learn the contextual relationships between the words used in the PR pairs. Then, the BERT's outputs are fed into a  Multilayer Perceptron (MLP) classifier, which represents our base duplicate PRs detector.
### Results:
The evaluation showed that BERT model provided the best performance and achieved an accuracy of 92% with MLP classifier. Results have proven that BERT’s word representation features achieved  13% (resp., 17% and 23%) better compared to Siamese-BERT model (resp., Dual-Channel Convolutional Neural Network and Word2Vec) in term of accuracy...
