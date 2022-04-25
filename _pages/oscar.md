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
- Fafalios, P., Iosifidis, V., Stefanidis, K., & Ntoutsi, E. (2020). <a href ="https://link.springer.com/article/10.1007/s00799-018-0257-7"> Tracking the history and evolution of entities: entity-centric temporal analysis of large social media archives. </a> International Journal on Digital Libraries, 21(1), 5-17.
- Fafalios, P., Iosifidis, V., Ntoutsi, E., & Dietze, S. (2018, June). <a href ="https://link.springer.com/chapter/10.1007/978-3-319-93417-4_12"> Tweetskb: A public and large-scale rdf corpus of annotated tweets. </a> In European Semantic Web Conference (pp. 177-190). Springer, Cham.
- Melidis, D. P., Spiliopoulou, M., & Ntoutsi, E. (2018, October). <a href ="https://dl.acm.org/doi/abs/10.1145/3269206.3271717"> Learning under feature drifts in textual streams. </a> In Proceedings of the 27th ACM International Conference on Information and Knowledge Management (pp. 527-536).
- Blake, C., & Ntoutsi, E. (2018, November). <a href = "https://ieeexplore.ieee.org/abstract/document/8588810/"> Reinforcement learning based decision tree induction over data streams with concept drifts. </a> In 2018 IEEE International Conference on Big Knowledge (ICBK) (pp. 328-335). IEEE. <b>Best Student Paper Award </b>
- Unnikrishnan, V., Beyer, C., Matuszyk, P., Niemann, U., Pryss, R., Schlee, W., ... & Spiliopoulou, M. (2020). <a href = "https://link.springer.com/article/10.1007/s41060-019-00177-1"> Entity-level stream classification: exploiting entity similarity to label the future observations referring to an entity. </a> International Journal of Data Science and Analytics, 9(1), 1-15.
- Melidis, D. P., Campero, A. V., Iosifidis, V., Ntoutsi, E., & Spiliopoulou, M. (2018, June). <a href = "https://dl.acm.org/doi/abs/10.1145/3227609.3227664">  Enriching lexicons with ephemeral words for sentiment analysis in social streams. </a> In Proceedings of the 8th international conference on web intelligence, mining and semantics (pp. 1-8).
- Beyer, C., Niemann, U., Unnikrishnan, V., Ntoutsi, E., & Spiliopoulou, M. (2018). <a href ="https://www.cs.waikato.ac.nz/~abifet/SAC2018/"> Predicting document polarities on a stream without reading their contents. </a> In Proceedings of the Symposium on Applied Computing (SAC).
- Iosifidis, V., & Ntoutsi, E. (2017, August). <a href ="https://dl.acm.org/doi/abs/10.1145/3097983.3098159"> Large scale sentiment learning with limited labels. </a>In Proceedings of the 23rd ACM SIGKDD international conference on knowledge discovery and data mining (pp. 1823-1832).
- Iosifidis, V., Oelschlager, A., & Ntoutsi, E. (2017, September). <a href = "https://link.springer.com/chapter/10.1007/978-3-319-67008-9_29"> Sentiment classification over opinionated data streams through informed model adaptation. </a>In International conference on theory and practice of digital libraries (pp. 369-381). Springer, Cham.
