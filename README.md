# Python_lists_-_tuples
#Create an empty list called my_list.
#Append the following elements to my_list: 10,20,30,40.
my_list = []
my_list.append(10)
my_list.insert(2, 15) #Insert the value 15 at the second position in the list
my_list.append(20)
my_list.append(30)
my_list.append(40)

#Extend my_list with another list
list2 = [50,60,70]
my_list.extend(list2)
my_list.remove(70) #Remove the last element from my_list

print(my_list[3]) #Find and print the index of the value 30 in my_list



