# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
# Deveolped by:K.Ligneshwar
# Register no:212223230113
i)	# Selection Sort

````
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)
````
# Deveolped by:K.Ligneshwar
# Register no:212223230113
ii)	# Insertion Sort
```
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)
```

## Output:
![Screenshot 2024-05-14 181316](https://github.com/drgbhuvaneswari/Sorting-Algorithms/assets/149365037/390ea961-49a9-49b4-b2a6-f3ec1b976589)
![Screenshot 2024-05-14 181329](https://github.com/drgbhuvaneswari/Sorting-Algorithms/assets/149365037/5205ed78-eaac-4a18-91ae-7415e2b30d30)
## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
