# list with-in a list
nest=[[1,2,3],[4,5,6,],[7,8,9]]
print(nest)
print(nest[0])
print(nest[2][2])
print("modify:")
nest[0][2]=23
print(nest)
nest[1]=200
print(nest)

[[1, 2, 3], [4, 5, 6], [7, 8, 9]]
[1, 2, 3]
9
modify:
[[1, 2, 23], [4, 5, 6], [7, 8, 9]]
[[1, 2, 23], 200, [7, 8, 9]]
