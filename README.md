# Data Structures and Algorithms Final Project
Final Project for the Data Structures and Algorithms course at Hertie. 

## Preaching the Gospel 
### Do politicians tweet what is written in their party programme?

* Carlo Greß 
* Lukas Warode  
* Johannes Halkenhaeusser



# Agenda
* Wir muessen vor jedem code chuck im Markdown documenten (sagt Hannah).
    * nicht zu viele sachen printen und inline comments sind nur fuer uns. 
* Which politician(s) do we want?
--> person with most followers. 
--> Annalena Baerbock 
* which similarity measure should we use?
--> Johannes sucht sich ein oder zwei aus.  
* What's the targeted code architecture?
* Who does what? (Johannes' suggestion)
    * Write an Email to Simon to discusss project generally
    * Lukas: get twitter data, save and process it, for one MP from each party?
    * Johannes: Code functions for similarity (maybe not all of them haha)
        - zusammengehoerende Woerter
        - remove stopwords
        - lemmatize
        - remove stopwords again
        - find similarity metrics
    * Carlo: Documentation and explanation of the similarity measures
        - was kann man wie plotten (an tweets und an similarity metrics.)

Aufbau
    - Party programm --> txt.type
    - Tweets --> csv-file
    - controller: accesses the files from data and preps them for viewer
    - Viewer gets the files passed from controller and does the nlp part 
        * tfitf
        * cosine similarity 