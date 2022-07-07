# Pythontemelfinal



l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
l2 = []
def flatten(n):
    for x in n:
        if isinstance(x, list):
            flatten(x)
        else:
            l2.append(i)

flatten(l)
print(l2)
