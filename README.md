6# -https://video.weibo.com/show?fid=1034:4923198807146593
供游戏玩家玩，以及教他们玩。
c
import random

temp = [i + 1 for i in range(35)]
random.shuffle(temp)
i = 0
list = []
while i < 7:
    list.append(temp[i])
    i = i + 1
list.sort()
print('\033[0;31;;1m')
print(*list[0:6], end="")
print('\033[0;34;;1m', end=" ")
print(list[-1])
