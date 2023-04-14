сохраните ваши собственные файлы
#from math import sqrt, pi

print("1-прямоугольник, 2-треугольник, 3-круг, 4-трапеция, 5-эллипс, 6-ромб")
figure = input("Выберите фигуру: ")

if figure == '1':
    print("Длины сторон прямоугольника:")
    a = float(input("a = "))
    b = float(input("b = "))
    print("Площадь: %.2f" % (a * b))
elif figure == '2':
    print("Длины сторон треугольника:")
    a = float(input("a = "))
    b = float(input("b = "))
    c = float(input("c = "))
    p = (a + b + c) / 2
    s = (p * (p - a) * (p - b) * (p - c))** 0.5
    print("Площадь: %.2f" % s)
elif figure == '3':
    r = float(input("Радиус круга R = "))
    print("Площадь: %.2f" % (3.14 * r ** 2))
elif figure == '4':
    print("Длины сторон трапеции:")
    a = float(input("a = "))
    b = float(input("b = "))
    h = float(input("h = "))
    s = (a + b) * h * 0.5
    print("Площадь: %.2f" % s)
elif figure == '5':
    r  = float(input("Радиус круга r = "))
    R = float(input("Радиус круга R = "))
    s = (3.14 * r  * R)
    print("Площадь: %.2f" % s)
elif figure == '6':
        d = float(input("d = "))
        D = float(input("D = "))
        s = (D * d) * 0.5
        print("Площадь: %.2f" % s)
else:
    print("Ошибка ввода")

    
