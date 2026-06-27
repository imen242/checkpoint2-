# question1
sample_list= [2,3,6]
result=1
for item in sample_list:
    result*=item
print(result)
# question2
sample_list2=[(2,5),(1,2),(4,4),(2,3),(2,1)]
expected_result=sorted(sample_list2,key=lambda x: x[1])
print(expected_result)
# question3
d1={'a':100,'b':200, 'c':300}
d2={'a':300,'b':200, 'd':400}
expected_result2=d1.copy()
for key,value in d2.items()
    if key in expected_result2:
        expected_result2[key] +=value
    else:
        expected_result2[key]=value
print(expected_result2)
# question4
n=8
result_dict={}
for i in range(1, n+1)
    result_dict[i]=i*i
print (result_dict)
# question5
sample_list3=[('item1','12.20'),('item2','15.10'),('item3','24.5')
expected_result3=sorted(sample_list3,key=lambda x: float(x[1]),reverse=True)
print(expected_result3)
# question6
my_set={0,1,2,3,4}
for item in my_set:
    print(item)
my_set.add(5)
my_set.add(6)
my_set.discard(0)
