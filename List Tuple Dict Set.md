
############################### List 列表 list=[]
#pop是删除列表的最后一个
list=[1,2,3,4,5]
list.pop()
print(list)

#pop（i）里面加入元素，则是删除指定位置的元素
list=['小明',"小红",3,4,5]
list.pop(1)
print(list)

#append是在列表中的最后一位增加一个元素

#直接在列表中的位置赋值，则可以更新该对应位置的元素
list=['小明',"小红",3,4,5]
list[1] = 'sb'
print(list)
print(list[1])

########################### Tuple 元组（元组内指向不可更改）Tuple=（，）

########################## Dict 字典（每一个元素都是一个数列 Dict={'a':1,'b':2,'c':3}

dict={'seele':100, 'emma':200, 'joe':400}
print('seele is', dict['seele'])
if 'seele' in dict:
    print('True')
if 'wang' not in dict:
    print('True')
#可以用get()获取字典里面的对应数列 如果没有则返回None，或则赋值
dict={'seele':100, 'emma':200, 'joe':400}
print(dict.get('emma'))
print(dict.get('sb'))
print(dict.get('sb',88888))

########################### Set 集合 （没有重复的键） Set={}
s = set([1, 1, 2, 2, 3, 3])
print(s)


#add()增加一个元素
s.add(5)
print(s)


##############################  str是不变对象，而list是可变对象
list=['a','c','k','b']
list.sort()
print(list) # list内部元素会被重新排列

str = 'ABC'
print(str.replace("A", "fuck"))
print(str) ### str字符是不可以改变的
