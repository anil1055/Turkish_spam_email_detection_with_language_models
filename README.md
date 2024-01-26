# Turkish Spam Email Detection with Language Models

Recently, with the development of technology and social networks, online interaction, sharing ideas on any subject has gained importance. 
While there are positive aspects to these interactions, there are also many negative aspects. Obtaining users' information and impersonating 
users in social networks is a big problem in terms of security. Thus, fraud etc. can be done by under cover of users. The most common way to
impersonate users is by sending spam messages, emails, etc. In order to overcome the security problem, processes such as spam filtering and 
spam detection method development are applied. In this study, Random Forest, Logistic Regression, Naive Bayes, Artificial Neural Networks 
machine learning methods and BERT, ELECTRA, ALBERT, DistilBERT language models were analyzed to detect e-mails containing spam in Turkish e-mails. 
Thus, it is aimed to show the effect of language models in classifying spam e-mails for Turkish. As a result of experimental studies, all 
language models were more successful than machine learning methods in classifying spam emails. While artificial neural networks from machine 
learning methods achieved 90.15% accuracy, the most successful language models were BERT and ELECTRA with 94.08% accuracy.
All model was uploaded in https://huggingface.co/anilguven

(![image](https://github.com/anil1055/Turkish_spam_email_detection_with_language_models/assets/17703776/cbf20f00-3894-4721-a748-59eaf64c3c1f)



Dataset link: https://huggingface.co/datasets/anilguven/turkish_spam_email 
!Stemming has been applied to the uploaded dataset files. Real dataset https://www.kaggle.com/datasets/emrahaydemr/turkish-mail-datasetnormalspam

!!! Please citation this paper: 
```
@INPROCEEDINGS{9559007,
  @article{article_1234079, title={Türkçe E-postalarda Spam Tespiti için Makine Öğrenme Yöntemlerinin ve Dil Modellerinin Analizi},
journal={Avrupa Bilim ve Teknoloji Dergisi},
pages={1–6},
year={2023},
DOI={10.31590/ejosat.1234079},
author={GÜVEN, Zekeriya Anıl},
keywords={Siber Güvenlik, Spam Tespiti, Dil Modeli, Makine Öğrenmesi, Doğal Dil İşleme, Metin Sınıflandırma, Cyber Security, Spam Detection, Language Model, Machine Learning, Natural Language Processing, Text Classification},
number={47},
publisher={Osman SAĞDIÇ} }
```

```
GÜVEN, Z. A. (2023). Türkçe E-postalarda Spam Tespiti için Makine Öğrenme Yöntemlerinin ve Dil Modellerinin Analizi. Avrupa Bilim ve Teknoloji Dergisi, (47), 1-6.
```
