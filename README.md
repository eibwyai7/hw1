from itertools import permutations 


def areAnagram(str1, str2):
#Get lengths of both strings
n1 = len(str1)
n2 = len(str2)

#If legth of both strings is not the same, then 
#they cannot be anagram
if n1 != n2:
    return 0
    
    
#Sort both strings
str1 = sorted(str1)
str2 = sprted(str2)

# Compare sorted strings
for i in range (0, n1):
  if str1[i] != str2[i]:
    return 0
   
return 1

print(areAnagram('CAT', "ATC'))
str_=[]
s = ['I', 'D', 'S', 'D', 'A', 'A', 'B', 'I', 'H', 'C', 'V', 'Qu', 'P', 'M', 'G', 'O']
perm = list( permutations9s, 1600

def convertTuple (tup):
  str = '', join(tup)
  return str
words =[ convertTuple(tuple_) for tuple_ in perm]

def findAllAnagram (arr, n):
  for i in range(n):
    for j in range (i+1,n):
      if areAnagram(arr[i], arr[j]):
        str_. append(arr[i])
    retuen str




