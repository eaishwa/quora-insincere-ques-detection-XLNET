# quora-insincere-ques-detection-XLNET

This problem was hosted by Quora on Kaggle in Feb, 2019. Quora is on a mission to improve their platform by removing toxic content from its platform. So they made a labelled dataset available to the public by hosting it as a kaggle competition. The data consists of questions and a target column which marks if the question is sincere or not. Any question that is non-neutral and inflammatory/ not truly intended to ask a question is marked insincere. The goal is to develop a model that can identify if the incoming new question is sincere or not.

For more information on the dataset, plese refer https://www.kaggle.com/c/quora-insincere-questions-classification/data.

This notebook gives step by step implementation of using the XLNET model developed by google, to fine tune on the Quora Insincere Questions Identification dataset. This is a guide to implement the fine tuning of the XLENT model for a sentence classification problem. This guide shall be followed for similar downstream tasks provided you have the task specific labelled dataset. This notebook uses the pytorch hugging face package namely PyTorch-Transformers.

For more information on XLNET, please refer to my article https://towardsdatascience.com/xlnet-explained-in-simple-terms-255b9fb2c97c

To know more about pytorch transformers, please refer https://huggingface.co/pytorch-transformers/model_doc/xlnet.html#
