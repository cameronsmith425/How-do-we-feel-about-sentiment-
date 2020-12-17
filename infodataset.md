---
layout: page
title: The Twitter Dataset
subtitle: The data we used to base our conclusions
---

The results you are seeing are based on a follow up of a paper from [Hai Liang and King-wa Fu](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0134270). These scientists had the double aim of generalizing and testing ten propositions made in previous Twitter studies and developing an adequate and replicable sampling method to study computational social sciences. We used the same tweeter user IDs and we extracted tweets text using Twitter APIs. We took the dataset used in the mentioned paper containing the IDs for each tweet and extracted these IDs to a text file; only tweet IDs associated with english were kept. Then, we ran the tweet IDs through [Hydrator](https://github.com/DocNow/hydrator) to extract the text from each tweet. The output of the Hydrator was a JSON file containing most of the same information as in the timelines data used by the paper, but with the text of each tweet as well. After the hydrator, we kept around 66% of the tweets which amounted to 1.6 million tweets. Once we had the text of the tweets, there were still tweets that were still not in english, so we eliminated those tweets and ended with 1.1 millions tweets. 

The tweets collected have been cleaned up and preprocessed with complex and annoying natural language python toolkits, but dont't we will not annoy you with those. Everything went well though trust us.


** some fancy plot about the original dataset? 

** show some tweets from some users?




