# Tuesday Servers/Node/Express > MongoDb Relationships
_Journal Entry_

## What are the three types of relationships?

 One-To-One (1:1) - This is a relationship between two entitties. In the example provided it seems like Author and Address are only able to belong to one another, rather than be maleable. This can be modeled in two ways. THe first is to emeb the relationship as a document, and the second is to link to a document in a separate collection. 
 One-To-Many (1:N) - This is a relationship where one side is only related to one thing, and the other side is many things related to the other side. The example used is a blog post vs the blog comments. 
 Many-To-Many (N:N) - This is a relationship where they might have many relationships between eachother. 

 In the example used, there might be a book that has many authors, but that author has also worked on many books. So both sides are going to have multiple correlations 

 ## What are the benefits of the traditional linking of relationships instead of Embedding?

Embedding - You would be able to easily retrieve all of the blog comments in the example used above. However, it seems like if you are having a high traffic site, that eventually if there are enough comments you could max the file size. It also seems like there are problems with MongoDb knowing how to add padding and making it look nice when it gets to a certain point. 

Linking - The advantage to linking in the case of the blog is that the comments will make it less liekly to hit the maximum document size of 16mb. The application can slice and dice the data more easily. However the downside is that in order to get all of the comments we would have to cause a lot of reads from the database 
 

 ## What are some of the challenges faced when deciding how to manage a many--to-mnany relationship that ultimately drive your deciion on how to create it? 
There are a lot of thigns to consider but the first is that is does one side have more categories than the other. In the instance of hte books, there are more books in the Sci-Fi category than there are categories of books. So you have to really think about which strategy is going to be the best. 




## Afternoon Challenge

https://github.com/Vincent-Girard/gregslist





