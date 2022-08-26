# Python-Filter-Range-Length-Tuples

lst = [(4, ), (5, 6), (2, 3, 5), (5, 6, 8, 2), (5, 9)]
res = list(filter(lambda n : len(n)>=2 and len(n)<=3,lst))
print(res)
