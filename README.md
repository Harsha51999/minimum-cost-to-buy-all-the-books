# minimum-cost-to-buy-all-the-books
To Find the minimum cost to buy all the books. 

Problem Description: We have to find the minimum cost that is required to buy all the 
books according to their ratings 

Constraint: 
1. Cost of each book should be atleast one dollar.
2. A book has higher cost than the adjacent one ( either left or right ) if it's rating is more than the 
adjacent.

Algorithm:
1. We have to create a function to get minimum cost and in that we have to declare 
two arrays named as left to right and right to left .
2. First,we have to fill all elements in both the arrays with 1 .
3. Now we have to traverse from left to right and then fill LtoR, and we have to update 
it by seeing the previous rating of the given array .
4. In LtoR we don't care about the next rating of given array .
5. Now we have to traverse from right to left and then fill RtoL, and we have to update 
it by seeing the previous rating of the given array .
6. In RtoL we don't care about the next rating of given array.
7. We have to declare and initialise the variable result as 0.
8. Now we have to find the maximum of LtoR and RtoL for every ith element and add it 
to the result 
9. Finally we have to print the result value as the minimum cost 
