# odd-num-from-1-to-max
maxnum=int(input())
if maxnum%2 ==0:
    c= [i for i in range(1,maxnum,2)]
else:
     c=[i for i in range(1,maxnum+1,2)]
print(c)
