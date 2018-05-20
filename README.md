# README

I wasn't able to complete all the task in time. But I will do an overview and answer the requirements for this code challenge

Created a working master and a branch called "devisecancan"

The master works as a normal blog with the ability to add post and comments

The "devisecancan" branch addressed the functionality of users and the ability to author and co author post but still has bugs to iron out

##Answers for the requirements

The way I wanted to go about the users having the ability to co author post was to use cancancan gem. This would allow users(authors) to create a post and have another user edit the post having given them the ability through cancancan

The users would be able to comment on post but not edit the comment if they aren't the original commenter.

I built the tables to reference user to coincide with author

To combat bloating in the controller we would use private methods to contain all duplicate code, keeping the controller methods DRY.


