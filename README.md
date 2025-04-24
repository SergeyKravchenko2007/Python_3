# Python_3
Tusk1
num = input("Введіть число: ")
result = float(num) * 2
print(f"Результат: {result}")
Tusk2
a = float(input("Перше число: "))
b = float(input("Друге число: "))
print(f"Сума: {a + b}")
print(f"Різниця: {a - b}")
print(f"Добуток: {a * b}")
print(f"Частка: {a / b}" if b != 0 else "Помилка: ділення на 0")
Tusk3
nums = input("Введіть числа через кому: ").split(',')
numbers = [float(n.strip()) for n in nums]
print(f"Сума: {sum(numbers)}")
print(f"Середнє: {sum(numbers) / len(numbers)}")
Tusk4
num = float(input("Введіть число: "))
decimals = int(input("Скільки знаків після коми? "))
print(f"Результат: {num:.{decimals}f}")
