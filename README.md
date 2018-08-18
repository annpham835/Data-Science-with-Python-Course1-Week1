def sum(x, y):
    sum = x + y
    if sum in range(15, 20):
        return 20
    else:
        return sum

print(sum(10, 6))
print(sum(10, 2))
print(sum(10, 12))
'''Giải thích:
Định nghĩa hàm Sum là tổng của x và y.
Nếu 15<=Sum(x,y) <20, trả kết quả 20
Nếu không, trả kết quả là Sum(x,y)'''
