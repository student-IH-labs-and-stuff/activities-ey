# 6_02 Activity 1 

Following the method you saw in the lesson lets examine another business problem without a straightforward solution : 
How does the number of reviews relate to the number of checkouts per author?
For example, if an author is more popular at the checkout, will they receive more reviews overall ? 
Or is there something else involved in popularity such as the marketing spend by the publisher, no of books / series that author has published, price of the edition etc   

1. Attempt to create a report (table) which shows the Author First_Name, Last_Name, with the sum of checkouts and count of reviews 
2. Consider what the syntax should be to create a ratio between checkout sum and count of reviews 
3. Try creating said ratio as a new column on the Author table the syntax could look like: **ratio_reviews_checkouts = count(Ratings[ReviewID]) / sum(Checkouts[Checkouts])**
4. Use this new column in the report - notice that the same value is repeated multiple times 
5. Think about or research PowerBI methods to resolve this - there are others than the Merge queries shown in class - so that you can reach a point where you have an accurate ratio of reviews to checkouts against each author
6. Update the report to demonstrate your solution working or note down your ideas to share with the class 
