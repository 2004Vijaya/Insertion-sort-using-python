# Insertion-sort-using-python

#Insertiom sort
'''
8 7 6 15 16 5 10 11
7 8 6 15 16 5 10 11
6 7 8 15 16 5 10 11
6 7 8 15 16 5 10 11
6 7 8 15 5 16 10 11
6 7 8 5 15 16 10 11
6 7 5 8 15 16 10 11
6 5 7 8 15 16 10 11
5 6 7 8 15 16 10 11
5 6 7 8 15 10 16 11
5 6 7 8 10 15 16 11
5 6 7 8 10 15 11 16
5 6 7 8 10 11 15 16

*****Algorithm*****
1.start from the second element (i=1)
2.previous index vlaued element check 
3.shift larger element one position to the right
4.insert the current element in the correct position
5.repeat untill arrray sorted

#pseudocode

for i 1 to n-1
key=arr[i]
j=i-1
while j>=0 and arr[j]>key
arr[j+1]=arr[j]
j--

bestcase=o(n)
worst case=o(n**2)
'''
