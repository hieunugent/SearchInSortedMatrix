# SearchInSortedMatrix
- Write a function that returns an array of the row and column indices of the target integer if contained in the maxtrix, otherwise [-1,-1]
- given 2D array of distinct integers and a target integer
- each row in the matrix is sorted; 
- the matric doesn't necessatily have the same height and width
# solution
- go the  right corner of the array, check it if it value is target or not
- if less than target, increase the row by one
- if greater than target, decrease the col by one
- else return the result at row col
- if there is no result return [-1-1]
- why it work: because the array is 2D sorted at each row and the element above smaller than the bottom

