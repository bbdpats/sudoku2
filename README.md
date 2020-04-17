import random
dat=random.sample(range(1,4),3)
d=[]
for f in range(1,4):
    if dat not in d:
        d.append(dat)
        dat=random.sample(range(1,4),3)
    if d[1][0] != d[0][0]:
        dat=random.sample(range(1,4),3)
        print('valid') 
    if d[1][1] != d[0][1]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[1][2] != d[0][2]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][0] != d[0][0]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][1] != d[0][1]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][2] != d[0][2]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][0] != d[1][0]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][1] != d[1][1]:
        dat=random.sample(range(1,4),3)
        print('valid')
    if d[2][2] != d[1][2]:
        dat=random.sample(range(1,4),3)
        print('valid')
