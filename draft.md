#  Introduction

S: Increasing amount of published scientific article in Indonesia  
P: Published paper is not highly reproducible  
Q: How to tackle this issue?  
R: Graph database to centralize and integrate research findings  

## Research in Indonesia

* Show data on how much Indonesia progresses within the last decade

## Medical Informatics

* define information in medicine
* intricate nature on how one information relate with the other
* how graph database can help

## Database

* define database
* type of database
* excerpt on positives and negatives
* graph db: implies underlying relationship as part of db
* relational db: treats relationship as joint of tables

# Method

Graph database is constructed using `Neo4j` and `cypher` querying
language.

* Create schema: constraints and indices
* Use periodic commit: free up memory when reaching certain threshold. Good for
  dealing with data with numerous entries
* Load file as a query object
* Set entity and relationship

# Result

Constructed database is able to return answer to queries requiring with complex
relationship, where otherwise in relational database it may require multiple
joints to achieve the same answers.

* Show query example
* Show how many db-hits on a query
* Show figures describing query processing (require `Neo4j` browser)

# Discussion

* Intro: reproducibility problem faced by researchers
* Body: graph db as a possible solution, considering the intricate
  relationships of medical information
* Premises on how graph db can be further utilized, maintained and developed
* Conclude the usability of graph db

# Conclusion

Graph database is quite performant to integrate medical health record generated
for 5,000 subjects using `synthea` program.

# Reference {-}
