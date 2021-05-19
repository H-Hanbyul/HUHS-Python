def std_weight(h,g):
    if g == "남자":
        return h * h * 22

    else :
        return h * h * 21

h = 175
g = "남자"
w = std_weight(h/100, g)

print("키 {0}cm {1}의 표준 체중은 {2}kg 입니다.".format(h,g,w))