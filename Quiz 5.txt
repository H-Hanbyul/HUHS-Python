from random import *
cnt = 0

for i in range(1,51):
    t = randrange(5,51)

    if 5 <= t <= 15:
        print("[0] {0}번째 손님 (소요시간 : {1}분)".format(i,t))
        cnt +=1

    else :
        print("[ ] {0}번째 손님 (소요시간 : {1}분)".format(i,t))

print("총 탑승 승객 : {0} 분".format(cnt))