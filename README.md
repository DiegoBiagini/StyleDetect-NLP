# StyleDetect-NLP
This repository contains all the work done for the Natural Language Processing course A.Y. 2022-2023 at the university of Bologna, Master degree in Artificial Intelligence.  
The content of this repository was developed by: Biagini Diego (me), Donati Matteo, Simeoni Ildebrando.  
This repository contains the solution to 2 fixed assignments for the course and the final course project, which has been the bulk of our work thus it gives the name to the repository in its entirety.  
Each problem folder also contains a paper-like report explaining in detail how it was solved.  

## Style Change Detection
This project and paper describes two simple but effective approaches for the three Style Change Detection (SCD) tasks for PAN at CLEF 2022.  
The first approach we propose is based on fine-tuning the BERT transformer and training different classification heads to solve all three
tasks in an end-to-end fashion.  
The second approach is instead based on sentence transformers (i.e. SBERT-based architectures) and the principles of metric learning, and works by computing distances directly in the embedding space implied by the chosen transformer-based encoder.  
We show how, using both approaches, we are able to achieve adequate results and also outperform existing state-of-the-art methods in a particular task.

## Part of Speech tagging
In this project and paper, a well defined and structured pipeline to asses the Part-Of-Speech (POS) Tagging problem is proposed. 
After a careful analysis of the given Penn Treebank dataset, a variety of simple but yet powerful RNN-based models, alongside GloVe embeddings, have been used
to tackle the problem at hand.  
After having tuned the hyperparameters of the proposed architectures using a grid-search approach, the two best models have been selected and evaluated on the test split of the original dataset, obtaining overall good results despite the simplicity of the architectures at hand.

## Generative Question Answering
Conversational generative Question Answering (also called Abstractive Question Answering) is a challenging task that requires understanding of conversational history as well as the ability to generate meaningful answers rather than
extracting text from a given context as is.  
In this paper and project we tried to implement various types
of encoder-decoder transformer-based models
to solve the problem on a particular dataset,
CoQA.  
Despite discouraging results we came up with possible reasons for such insuccesses and they mostly lie in the model choice.
