# day.1
mark = [56,78,73,92,87,98,28,91,85,70,66,45,93]
num=1
min=mark[0]
max=mark[0]
while num<13:
    if min>mark[num]:
        min=mark[num]
    if max<mark[num]:
        max=mark[num]
    num=num+1
print(f"本班最高分为{max}，最低分为{min}")  
