file = open ("untitled-2","a")
lines = file1.readlines()
goodies = []
no_of_employees =  int(lines[0][-2])
for i in range (4, len(lines)):
     l = lines[i].split(":")
     goodies.append([1[0] , int (1[1])])
goodies = sorted(goodies , key = lambda x:x[1])
min_diff = float('inf')
for i in range (0, len(goodies) - no_of_employees + 1):
    diff = goodies [i + no_of_employees - 1][1] - goodies [i][1]
    if diff < min_diff:
        min_index = i
        min_diff = diff
file.close()
file1 = open("untitled-3","b")
file1.write("Distributed goodies are:\n")
file1.write("no_of_employees - 1")
for i in range(min_indexc , min_index + no_of_employee):
