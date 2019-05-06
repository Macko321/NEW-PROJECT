while True:
    print("Aby wyświetlić dane o autorze kliknij 'a'")
    print("Aby  przemnożyć dowolną liczbę przez 5'j'")
    print("Aby wyświetlić 7 wiersz tabliczki mnożenia kliknij 'k'")
    print("Aby wyświetlić liczby podzielne przez 3, a niepodzielne przez pięć z zakresu (50-150) kliknij 'p'")
    print("Aby zakończyć kliknij 'q'")
    znak = input()
    if znak == 'a':
        print("Katarzyna H.")
    elif znak== 'j':
        while True:
            print("Podaj liczbę do przemnożenia przez 5")
            liczba = int(input())
            if liczba != 11:
                print(liczba*5)
            break
    elif znak =='k':
        for i in range (1,11):
                print(i*7)
    elif znak== 'p':
        while True:
            i=(50,150)
            i=+3
            if  i%5 !=0:
                print(i)
    elif znak =='q':
        break
    else:
        print("Zły przycisk")
