# nwo-nlp-challenge

# Challenge: Semantic Search Algorithm  
Design and implement a semantic search algorithm that is able to score and rank a  set of keywords (trends) by how strongly associated they are to a given query term.  The algorithmic approach could borrow techniques from association rule mining to  analyze the co-occurrence of terms within a corpora of tweets and reddit posts, and should take into consideration the uniqueness of the trend and the recency of the  association. For example, the algorithm should be able to determine that the query  ‘iPhone’ is more strongly associated to trends like ‘MagSafe’, ‘5G’, and ‘pacific blue'  then it is to “Biden” or “perfume”.  

## Details:  
- The expected input to the method should be a query term, and the output should  be an ordered set of trends. The method should be implemented in Python (v3.7).  
- You can explore the dataset via the GCP BigQuery WebIDE and you can connect to  the database from python using the provided JSON key.  
- The sample twitter and reddit datasets can found in the tables `nwo-sample.graph.tweets` and `nwo-sample.graph.reddit` respectively   
