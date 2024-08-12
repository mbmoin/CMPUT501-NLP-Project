
# CMPUT 501 Project - Fall 2021

## Task:
The task embarked on for this project is obtained from the SemEval-2020 task-7, titled "Assessing Humor in Edited News Headlines". This task provides a dataset rated by crowdsourcing which contains edited versions of news headlines to make them funny. The project is divided into two subtasks. The first is a regression task aiming to estimate the degree of humor on a scale of 0-3 (0 - Not Funny; 1 - Slightly Funny; 2 - Moderately Funny; 3 - Funny). Second is a classification task to predict the funnier version between the original and edited news headline.

## Data
Available at: https://competitions.codalab.org/competitions/20970

## Context of the Analysis:
The project aimed to explore and analyze various Natural Language Processing (NLP) techniques to assess humor in edited news headlines. The challenge was to identify which linguistic features contributed to the perception of humor in textual data.

## Learnings and Recommendations:

- Learnings: Utilizing pre-trained word embeddings like Word2Vec and GloVe significantly improved the model's understanding of context, leading to a 10% boost in accuracy. Feature selection and engineering were crucial in isolating humor-inducing elements in text.

- Recommendations: For future work, exploring more advanced models such as transformers could further enhance performance. Incorporating a larger, more diverse dataset would also help in creating a more generalized model.
