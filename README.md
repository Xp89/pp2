# pp2
p two
def fibonacci(n):
    fib_list = [0, 1]
    for i in range(2, n):
        fib_list.append(fib_list[i - 1] + fib_list[i - 2])
    return fib_list

n = int(input("请输入要计算的斐波那契数列的前n个数字："))
result = fibonacci(n)
print(f"斐波那契数列的前{n}个数字为：{result}")
