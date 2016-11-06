# EPF
## Abstract

Our project will be focus on obtain, treat and represent data from a web forum called “Englishforum”, in an automatized way. For that we will be using the tools learned during the lectures and other new ones.
This web forum does the same paper than reddit but on Switterland. The website appeared around 2005 and has reach the number of 68,000 users, since then. With an average of 179,958 visits per day, this website has become an information exchange node. 

## Data
As any forum, a lot of information is well organized and can be easily obtain by following a reusable pattern. As an example:
Topic --> threads --> (Post + Commentaries). Where:
-	Topics (Name, viewing, last post, threads, posts)
-	Thread (Name, author, Sticky, rating, last replied, replies, views, state (open, closed, moved)
-	Post (Name, date, author, last edited and by who, text)
-	Commentaries (same structure as before)
The potential of this data are the questions that we can answer form it, here are some examples:
-	Are new users from Switzerland or others countries, what do they look for in this forum, which is the average of active members compared with new members. How do they evolve in the forum?
-	Are the most active members relevant I the forum, or just spammers.
-	Finding which are the most important topics in the forum, are they relevant topics for daily life?
-	A lot of relations taking a count the different topics (Market: is it a good place for selling? What kind of things are sold? ...)
-	Is this website growing or it is stuck and dying?
-	How the social events affect in the forum?
## Feasibility & Risks

### Feasibility	
The forum structure is well known.	
We can obtain accurate informatio.
Data sparse: after the analysis, the treated data can be interpreted in different ways. 
### Risks
Get stuck in the process of finding possible relations.
Data sparse: Some relations between the data couldn’t have enough measures.
Just focus on a way of seeing the data 
Abuse of visualization or not well organized.

##Deliverables

For our first aim, we will develop an automatically download system that follows a pattern as the one shown before. After achieving this, we will have a well-organized continuous pipeline of data. Please notice that at this phase of the project the analyze of the data structure will be already be done. We will be saving it on others several structures, so in the future we will have the possibility of create new relations in an easy way.
This could approximate our deliverables:
-	Setting up the working environment (Apache spark) and first tries downloading the data and working with it.
-	Making a continuous pipeline of data.
-	Plotting the actual data and making more advanced ways of data treatment (Machine learning tools).
-	A phase focus on plotting in the best way all the analysis made before.
