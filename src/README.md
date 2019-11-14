This is the directory where your source code would reside

I wrote four functions to solve this problem.

The first function is round_values. The built in round function does not round values properly. So I decided to wrote the function my own.

The second function is sum_values, which builds a dictionary that has a tuple (border, measure, date) as key. So I am able to aggregate values with the same border, measure and date. The final step of this function involves sort the dictionary by key. 

The third function is moving_avg. The idea is iterating through the sorted dictionary. The dictionary is sorted by time in increasing order,  so I am able to calculate the moving average through each iteration.

The fourth function is final_output. The function sorts rows and appends column names to the list. 