
#my_math
def factorial(n):

    """
    if n < 0:
        raise ValueError("Число не может быть отрицательным")
    
    if not isinstance(n, int):
        raise ValueError("Число должно быть целым")
    
    result = 1
    for i in range(1, n + 1):
        result *= i
    
    return result


print("Факториал 5:", factorial(5))
print("Факториал 0:", factorial(0))
