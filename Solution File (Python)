res = []
for i in range(int(input())):
    string = input()
    row = int(string.split()[0])
    col = int(string.split()[1])

    shape = []

    for i in range(row):
        a = []
        string = input()
        for j in range(col):
            a.append(string[j])
        shape.append(a)

    result = []

    for i in  range(0, row):
        max_in_row = []
        ctr = 0
        for j in range(0, col):
            if (shape[i][j] == "#"):
                ctr += 1
            elif (shape[i][j] != "#" and ctr != 0):
                max_in_row.append(ctr)
                ctr = 0
        if(max_in_row):
            result.append(max(max_in_row))
    res.append(max(result))

for i in range(len(res)):
    print(res[i])
