# List
#Normal list program in python

friends = ["Adarsh","Raj","shivam","Radhey","Vishal",5,67.7]
print(friends)
friends.append("Anurag")
print(friends)
friends.reverse()
print(friends)
friends.insert(2,"Tripathi")
print(friends)          

l1 = [1,2,34,3,56,4,5] #increasing order
l1.sort()
print(l1)
l1.reverse()
print(l1)
value = l1.pop(2) #pop removes the element at the given index and returns it
print(value)
print(l1)
