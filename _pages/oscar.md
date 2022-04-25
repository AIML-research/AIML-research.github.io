---
title: "Artificial Intelligence and Machine Learning Group - OSCAR project"
layout: textlay
excerpt: "AIML Group -- Projects"
sitemap: false
permalink: /projects/oscar/
---

### OSCAR: Opinion Stream Classification with Ensembles and Active leaRners
<div>
<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/images/logopic/logo-dfg.jpg" style="width: 250px">  
</figure>
</div>

- <b>Funding: </b> German Research Foundation (Deutsche Forschungsgemeinschaft - DFG)
- <b>Project duration: </b> 2017 - 2019
- <b>Homepage: </b> 

#### Team
<b> Leibniz University Hannover & L3S Research Center </b>

- Prof. Dr. Eirini Ntoutsi
- M.Sc. Damianos Melidis
- M.Sc. Amir Abolfazli
- M.Sc. Vasileios Iosifidis

<b> Otto von Guericke University Magdeburg </b>
- Prof. Dr. Myra Spiliopoulou
- M.Sc. Vishnu Unnikrishnan

#### Motivation
“What other people think” has always been an important piece of information for our decision-making process. But the Internet and the Web allow us now to find answers to this question beyond the circle of our personal acquaintances. Traditional sentiment mining techniques focus on static data. However, as opinions accumulate from the social streams, changes might occur like changes in the general sentiment towards a subject or towards specific facets of this subject, as well as changes in the words used to express sentiment. Subjects also change over time. In OSCAR, we develop opinion stream mining methods that deal with change and adapt the learned models continuously.

#### Challenges & Highlights
The first part of OSCAR is on leveraging stream mining methods to deal with vocabulary/ feature changes. A change in the feature space means that the model built upon the old words must be updated. We will accumulate information on the usage and sentiment of each word to highlight the long-term interplay between word polarity and document polarity. Second, we will work on reducing the need for labeled documents. To this end we will develop active learning methods that learn and adapt polarity models on an evolving feature space. Third, we will work on dealing with different types of change simultaneously. To this purpose, we will use ensembles. We will dedicate some ensemble members to the identification of topic trends, others to changes in the vocabulary and others to temporal changes, including periodical ones.

#### Potential applications & future issues
The output of OSCAR will be a complete framework, encompassing active ensemble learning methods that deal with different forms of change and learn with limited expert involvement. Such a framework can be used in other stream classification tasks, beyond sentiment analysis.


#### Related publications
- Iosifidis, V., & Ntoutsi, E. (2019, November). <a href = "https://dl.acm.org/doi/abs/10.1145/3357384.3357974"> Adafair: Cumulative fairness adaptive boosting. </a> In Proceedings of the 28th ACM International Conference on Information and Knowledge Management (pp. 781-790).
- Iosifidis, V., & Ntoutsi, E. (2020).<a href = "https://link.springer.com/article/10.1007/s10115-019-01392-9"> Sentiment analysis on big sparse data streams with limited labels. </a> Knowledge and Information Systems, 62(4), 1393-1432.
- Le Quy, T., Nejdl, W., Spiliopoulou, M., & Ntoutsi, E. (2019, September). <a href = "https://link.springer.com/chapter/10.1007/978-3-030-38081-6_8"> A neighborhood-augmented LSTM model for taxi-passenger demand prediction. </a> In International Workshop on Multiple-Aspect Analysis of Semantic Trajectories (pp. 100-116). Springer, Cham.
- Unnikrishnan, V., Beyer, C., Matuszyk, P., Niemann, U., Pryss, R., Schlee, W., ... & Spiliopoulou, M. (2020). <a href ="https://link.springer.com/article/10.1007/s41060-019-00177-1"> Entity-level stream classification: exploiting entity similarity to label the future observations referring to an entity. </a> International Journal of Data Science and Analytics, 9(1), 1-15.
- Beyer, C., Unnikrishnan, V., Niemann, U., Matuszyk, P., Ntoutsi, E., & Spiliopoulou, M. (2019, April). <a href = "https://dl.acm.org/doi/abs/10.1145/3297280.3297333"> Exploiting entity information for stream classification over a stream of reviews. </a> In Proceedings of the 34th ACM/SIGAPP Symposium on Applied Computing (pp. 564-573).
- Iosifidis, V., Tran, T. N. H., & Ntoutsi, E. (2019, August). <a href = "https://link.springer.com/chapter/10.1007/978-3-030-27615-7_20"> Fairness-enhancing interventions in stream classification. </a> In International Conference on Database and Expert Systems Applications (pp. 261-276). Springer, Cham. 
- 


