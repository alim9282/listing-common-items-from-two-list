# listing-common-items-from-two-list
a = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]
b = [1,2,3,6,7,15,17,22,23,26,]
c = len(a)
i = 0
k = []
while i<c:
    if a[i] in b:
        k.append(a[i])
    i = i+1
print(k)        
        
