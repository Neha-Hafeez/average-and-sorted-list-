# average-and-sorted-list-
#find average #sort list in ascending order without using builtin function
list=[90,80,90,40,50,60]
sum=0
for x in list:
    sum=x+sum
s_avg=sum/len(list)
print('average = ',s_avg)
x=0

my_list = [-15, -26, 15, 1, 23, -64, 23, 76]
new_list = []

while list:
    min = list[0]
    for x in list:
        if x < min:
            min = x
    new_list.append(min)
    list.remove(min)
print(new_list)
