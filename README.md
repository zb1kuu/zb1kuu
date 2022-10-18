
import random2
#gr 1/2
  # zad 1
def srednia_harmoniczna():
    suma=0
    i=0
    while True:
        inp=input()
        suma+= 1/float(inp)
        i+=1
        if inp=="stop":
            break

        print(i/float(suma))


#zad 2

A=[3,5,6,7,8]
def sprawdzanie():
    i=0
    inp=float(input())
    while i<len(A):
        if inp==A[i]:
            print(i)
        i+=1
#zad 3
def zadanie3():
    max=int(input("podaj największą liczbę"))
    min=int(input("podaj najmniejszą liczbę"))
    n=int(input("podaj długość tabeli"))
    i=2
    A=[min,max]
    while i<n:
        rand=random2.randint(min,max)
        i+=1
        A.append(rand)
    print(A)
#zad 4



#zad 5
def zadanie5():
    n=int(input())
    i=1
    while i<=n:
        print(3**i)
        i+=1
