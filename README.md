# d4g2025-factualitydetection-public
An ensemble solution incorporating a fine-tuned MNLI model and a LLM-as-a-judge approach, built for the Data 4 Good competition 2025.

We were tasked to develop an analytical solution to evaluate the factuality of a set of responses with respect to the given questions and contexts in the test.json file. In particular, each response will be labelled with a type according to the following classification rules:

+ Factual: the answer is correct
+ Contradiction: the answer is incorrect
+ Irrelevant: the answer has nothing to do with the question

The code in this repository should be viewed in conjunction with the accompanying competition DataCamp notebook.
