
first_number = int(input("введите первое число:"))
second_number = int(input("введите второе число:"))



print ( "Сложение: " )
print ( first_number + second_number )
print ( "Вычитание: " )
print ( first_number - second_number )
print ( "Деление:" )
print ( first_number / second_number )
print ( "Умножение: " )
print ( first_number * second_number )

if second_number != 0:
    print ( "Деление:", first_number / second_number )
else:
    print ( "Деление на ноль невозможно!!!")
