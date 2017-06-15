#  Affinity analysis workshop outline
1. Introduction: 
GIve a brief introduction to what affinity analysis means and then talk about the underlying concepts, through which affinity analysis can be done where  we discuss a number of advanced methods that are designed to make association pattern mining :  

**Examples**: Discuss about some examples where association rule mining is usually applied, such as affinity analysis, demographic and profile analysis,Recommendations and Collaborative Filtering, bioinformatics etc

**Business use case**: Pick some real world business use case and how this can  provide a solution to it.(market basket analysis in this case)
	

These topics are all related to the extraction of interesting summary information from item sets in different ways.

2. Prerequisites:
A general idea of what associative rule mining means, python and general machine learning ideas.

3. overview:
	1. Summarization: The output of association pattern mining is typically very large. For an end-user, a smaller set of discovered itemsets is much easier to understand and assimilate. we will introduce a number of summarization methods such as finding maximal itemsets, closed itemsets, or nonredundant rules.
	2. Querying: When a large number of itemsets are available, the users may wish to query them for smaller summaries. we will discuss a number of specialized summarization methods that are query friendly. The idea is to use a two-phase approach in which the data is preprocessed to create a summary. This summary is then queried.
	3. Constraint incorporation: In many real scenarios, one may wish to incorporate application-specific constraints into the itemset generation process. Although a constraint-based algorithm may not always provide online responses, it does allow for the use of much lower support-levels for mining, than a two-phase “preprocess-once query-many” approach.
	
4. Research design and the market basket analysis problem
  1.Introduction: explain the problem in detail
  2.Problem: 
  3.solutions :
  4.Algorithms to study
	-  **Association Pattern mining**: 

 		1. Introduction
		2. Pattern mining framework: 
		A general outline that describes the problem and various ways that one might use to solve it
		3. Pattern mining Algorithms discussion:
	Discuss some important terminologies and some algorithms such as frequent item mining, apriori, enumeration tree etc
		4. Summary
	
	-  **Advanced concepts in Association Pattern mining**: [additional, only if required]

		1. Introduction 
		2. Pattern summarization & querying
		
5. data modelling and EDA with some dataset:
6. Usecase In real world: