def func_evalg(a:int,
               b:int) -> int:
    while a != 0 and b != 0:
        if a < b:
            a, b = b, a
        a = a % b
    return a + b


test_data = {
    (10, 6): 2,
    (24, 5): 1,
    (27, 9): 9,
    (105, 30): 15,
    (240, 44): 4
}

for i in test_data:
    a, b = i
    c = func_evalg(a, b)
    print('НОД({0}, {1})-{2}:{3}'.format(i[0], i[1], c, c == test_data[i]))
