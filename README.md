# advent-Jimmy
s=input() #input the data from the problem when running the program
arr=list(s)
arr2 = []
sum=0
for i in arr:
    arr2.append(int(i))
for i in range(0,len(arr2)):
    if arr2[i]==arr2[(i+1)%len(arr2)]:
        sum+=arr2[i]
print(sum)
