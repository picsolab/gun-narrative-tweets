# Gun Narrative Across Major Mass Shooting Events

The datasets released here was used in our paper "The Dynamics of Twitter Users' Gun Narratives Across Major Mass Shooting Events."

This study reveals the shift of gun-related narratives from two ideological groups during three high-profile mass shootings across the years from 2016 to 2018. 

We collected longitudinal digital traces on Twitter from over 155,000 ideology-identifiable users. This study tracked the shift of gun-related narratives from the two ideological groups during three high-profile mass shootings across the years from 2016 to 2018.

The inclusion criteria of users and mass shooting events was detailed in our paper. For this study, we compiled tweets from the two groups of users for the selected three mass shooting events. Each event set includes users' tweets within a four-week time window centered on the time of incidence, referred as the __Event__ period. To examine whether any measured differences in users' tweeting language are attributable to the incidents, we identify an equivalent period of four weeks for each event during one of its preceding or succeeding years, referred as __Control__ period. Please refer to our paper for details of the study design.

To distinguish tweets relevant to gun violence or policy issues among others in our data collection, we adopt the list of keywords, phrases, and hashtags used in prior work, including several keywords likely to be associated with guns or gun control in the US, and a set of hashtags indicative of support for or opposition to gun control (e.g., 2nd amendment, #guncontrolnow, #gunrights, #protect2a, etc.). We used them as independent seed sets and iteratively extended the list by adding keywords and hashtags mostly likely to co-occur with the chosen words, to capture the related tweets on either side to a great extent while avoiding the bias toward a particular stance. See details about relevance filtering and bot prevention in our paper.

The released datasets includes (1) all tweet IDs of the relevant tweets within a four-week period for the three __Event__ and three __Control__ sets, and (2) the human coding results of the 480 sample tweets. 

(1) tweetIDs
This include 6 files: ```contrl_*_tweetIDs.txt``` and ```event_*_tweetIDs.txt```.
This dataset corresponds to Table 1 and Fig 6 in the paper -- the number of relevant non-retweet tweets (i.e., #Relevant) extracted from our collection for the corresponding event and control periods.
(2) human coding results: ```human_coding.csv```
Each row has 12 columns: 
* "tweetID"
* "event": correspond to one of the mass shooting events
* "time": one of the four stages in an event
* "Relevancy": whether the tweet is related to gun policy; all the following columns will be 'N/A' if not relevant
* "Moral": whether the tweet mentions call-for-action
* "Stand": stance of the tweet
* "Rhetoric scheme": corresponds to the scheme in Table 4 in the paper
* "Victim": whether the tweet mentions a victim 
* "Villain": whether the tweet mentions a villain
* "Hero": whether the tweet mentions a hero
* "Problem nature": whether the tweet is about problem nature 
* "Blame target": whether the tweet mentions a blame target 
(The last 5 columns correspond to Table 3 in the paper.)


## Publication
If you make use of these data sets and code, please cite:

Lin, Y.-R., Chung, W.-T. (2020). #The Dynamics of Twitter Users' Gun Narratives Across Major Mass Shooting Events (In Press) 
