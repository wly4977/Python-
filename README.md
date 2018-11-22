# Python-
一只没有编程基因的小白自学Python之路
## 排序1
```
def sort(list1):
    l=len(list1)
    while l>=1:
        for i in range(l-1):
            if list1[i]<=list1[i+1]:
                list1[i]=list1[i]
                list1[i+1]=list1[i+1]
            else:
                a=list1[i]
                list1[i]=list1[i+1]
                list1[i+1]=a
        l=l-1
    return list1
list1=[2,-4,7,0]
sort(list1)
```
