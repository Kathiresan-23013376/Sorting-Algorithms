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
i)	#Selection Sort
```
###Program to sort the elements in list using Selection sort
###Devoloped by:KATHIRESAN K
###reg.no:212223110021
```
```
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if(num[j]<num[low]):
            low=j
    num[i],num[low]=num[low],num[i]
print(num)
```
ii)	#Insertion Sort
```###Program to sort the elements in list using Insertion sort
###Devoloped by:KATHIRESAN K
###reg.no:212223110021
```
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
![image](https://github.com/Kathiresan-23013376/Sorting-Algorithms/assets/150008375/fc9f1272-d7c3-407b-8bf0-8152ac821e73)

## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
