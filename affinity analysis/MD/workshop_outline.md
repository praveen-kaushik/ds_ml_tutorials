“Each child is an adventure into a better life—an opportunity to change the old pattern and make it new.”—H.H.H

# Affinity analysis outline

-  **Introduction**
GIve a brief introduction to what affinity analysis means and then talk about the underlying concepts, through which affinity analysis can be done where  we discuss a number of advanced methods that are designed to make association pattern mining :  
	
	1. Summarization: The output of association pattern mining is typically very large. For an end-user, a smaller set of discovered itemsets is much easier to understand and assimilate. we will introduce a number of summarization methods such as finding maximal itemsets, closed itemsets, or nonredundant rules.
	2. Querying: When a large number of itemsets are available, the users may wish to query them for smaller summaries. we will discuss a number of specialized summarization methods that are query friendly. The idea is to use a two-phase approach in which the data is preprocessed to create a summary. This summary is then queried.
	3. Constraint incorporation: In many real scenarios, one may wish to incorporate application-specific constraints into the itemset generation process. Although a constraint-based algorithm may not always provide online responses, it does allow for the use of much lower support-levels for mining, than a two-phase “preprocess-once query-many” approach.

These topics are all related to the extraction of interesting summary information from item sets in different ways.

- **Examples**:
 
Discuss about some examples where association rule mining is usually applied, such as affinity analysis, demographic and profile analysis,Recommendations and Collaborative Filtering, bioinformatics etc

- **Business use case**:

Pick some real world business use case and how this can  provide a solution to it.(market basket analysis in this case)

- **Association Pattern mining**: 

 	1. Introduction
	2. Pattern mining framework: 
	A general outline that describes the problem and various ways that one might use to solve it
	3. Pattern mining Algorithms discussion:
	Discuss some important terminologies and some algorithms such as frequent item mining, apriori, enumeration tree etc
	4. Summary
	
-  **Advanced concepts in Association Pattern mining**: [additional, only if required]

	1. Introduction 
	2. Pattern summarization & querying
	
-  **Tutorial: Market basket analysis**:

The prototypical problem for which the association rule mining problem was first proposed is that of market basket analysis. In this problem, it is desired to determine rules relating buying behavior of customers. The knowledge of such rules can be very useful for a retailer. For example, if an association rule reveals that the sale of beer implies a sale of diapers, then a merchant may use this information to optimize his or her shelf placement and promotion decisions. In particular, rules that are interesting or unexpected are the most informative for market basket analysis. Many of the traditional and alternative models for market basket analysis are focused on such decisions.

The goal is to present the student with a guided example and work it along in python with some real world dataset
