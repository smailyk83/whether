# whether one
def check_even_odd(number):
    if number % 2 == 0:
        return "Число чётное"
    else:
        return "Число нечётное"

# Getting a number from the user
try:
    user_input = int(input("Введите число: "))
    result = check_even_odd(user_input)
    print(result)
except ValueError:
    print("Пожалуйста, введите целое число.")

