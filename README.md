# Hasoc_2021 (Hate Speech and Offensive Content Identification in English and Indo-Aryan Languages)
Models developed by me and my team for the competition along with the research paper that was accepted to be published at the CEUR proceedings by the Forum for Information Retrieval Evaluation (FIRE21) organizers

# Abstract
Hate Speech classification has crucial applications in the social media domain. We describe the performance of our classifiers in the Hate Speech and Offensive Content Identification Track (HASOC) of FIRE
2021 conference. The dataset provided is for Indo-European Languages. We chose English tweets and
developed two main classifiers as part of HASOC Track 1, which had two Subtasks 1A and 1B. Subtask
1A is a binary Hate Speech identification task, and Subtask 1B is multi grained classification of hate,
profane, offensive and neutral content. Our team ”Beware Haters” studied Support Vector Machine,
Random Forest, Logistic Regression, Bidirectional Long Short Term Memory Model and an Ensemble
of the listed models for the Subtask 1A and the highest Macro F1 score we achieved was 0.7722 by our
Ensemble model which combined the advantages of SVM, Logistic Regression and Random Forest. We
used a model interpretation tool LIME, before integrating the models in a weighted Ensemble approach.
For Subtask 1B, we obtained better results using a DistilBERT model that achieved a Macro F1 score of
0.6311. We have compared the performance of the basic DistilBERT Model with a fine tuned version


# Conclusion
We classified the Hate Speech dataset provided by the HASOC Track 1 of FIRE 2021. Though
Subtask 1A is a simple binary classifier we could not achieve the expected accuracy and stood
25th out of the total 56 submissions [Fig.13]. The reason is that Subtask 1A had a limited data
and our decision to augment it with more data from Kaggle probably did not work. Meanwhile,
we observed that an Ensemble method improved our accuracy over other approaches used.
Work is under progress in this line to quantify the interpretations provided by LIME. The
multigrain classification problem was the toughest with the benchmark performance as low as
0.5 (Precision and F1 score). With respect to the fine-grained classifier developed for Subtask
1B, DistilBERT gave superior performance compared to other approaches and scored the 8th
rank among the total 37 submissions [Fig.14]. It is interesting to note that both Subtask 1A and
Subtask 1B required entirely different approaches though they were all Hate Speech classifiers.
