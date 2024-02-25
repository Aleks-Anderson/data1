def calculate_sum(numbers):
    """
    Функция принимает список чисел и возвращает их сумму.
    """
    total_sum = sum(numbers)
    return total_sum

# Пример использования скрипта
if __name__ == "__main__":
    # Задайте список чисел
    numbers_list = [1, 2, 3, 4, 5]

    # Вызов функции для расчета суммы
    result_sum = calculate_sum(numbers_list)

    # Вывод результата
    print(f"Сумма чисел в списке {numbers_list} равна: {result_sum}")
