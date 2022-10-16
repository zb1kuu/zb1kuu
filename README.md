from math import pi
# 1
print("1. Pole szescianu")
def p_szescianu():
    a=float(input("Bok= "))
    print("Pole szescianu= ", 6*a**2)
# 2

print("2. Objetosc szescianu")
def v_szescianu():
    a=float(input("Bok= "))
    print("Objetosc szescianu= ", a**3)
# 3
print("3. Pole kuli")
def p_kuli():
    r=float(input("r= "))
    print("Pole kuli= ", 4*pi*r**2)
# 4
print("4. Objetosc kuli")
def v_kuli():
    r=float(input("r= "))
    print("Objetosc kuli= ", 4/3*pi*r**3)
# 5
print("5. Pole calkowite stozka")
def p_stozka():
    r=float(input("r= "))
    l=float(input("l= "))
    print("Pole stozka= ", pi*r**2+pi*r*l)
# 6
print("6. Objetosc stozka")
def v_stozka():
    r=float(input("r= "))
    H=float(input("H= "))
    print("Objetosc stozka= ", 1/3*pi*r**2*H)
# 7
print("7. Pole kwadratu")
def p_kwadratu(a):
    return a**2
# 8
print("8. Pole prostokata")
def p_prosto(a,b):
    return a*b
# 9
print("9. Pole walca")
def p_walca(r,H):
    return pi*r**2*H
# 10
print("10. Objetosc walca")
def v_walca(r,H):
    return 2*pi*r**2+2*pi*r*H
# 11
print("11. Pole prostopadloscianu")
def p_prostopad(a, h):
    return 2*a**2+4*a*h
# 12
print("12. Objetosc prostopadloscianu")
def v_prostopad(a, h):
    return a**2*h
# 13
print("13. Pole trójkąta")
def p_trojkata():
    a=float(input("a= "))
    h=float(input("h= "))
    return 1/2*a*h
# 14
print("14. Pole trapezu")
def p_trap():
    a=float(input("a= "))
    b=float(input("b= "))
    h=float(input("h= "))
    return 1/2*(a+b)*h
# 15
print("15. Pole rownolegloboku")
def p_rowno():
    a=float(input("a= "))
    h=float(input("h= "))
    return a*h
# 16
print("16. Delta")
def delta():
    a=float(input("a= "))
    b=float(input("b= "))
    c = float(input("c= "))
    return b**2-4*a*c
# 17
print("17. Pole okręgu")
def p_okr():
    r=float(input("r= "))
    return pi*r**2
# 18
print("18. dzielenie  dwóch wartości")
def mnoz():
    a=float(input("a= "))
    b=float(input("b= "))
    return a/b

coliczyc=input("Co Liczyc? ")
if coliczyc=="1":
    p_szescianu()
elif coliczyc=="2":
    v_szescianu()
elif coliczyc=="3":
    p_kuli()
elif coliczyc=="4":
    v_kuli()
elif coliczyc=="5":
    p_stozka()
elif coliczyc=="6":
    v_stozka()
elif coliczyc=="7":
    print("Pole = " + str(p_kwadratu(float(input("Bok= ")))))
elif coliczyc=="8":
    print("Pole = " + str(p_prosto(float(input("Bok1= ")), float(input("Bok2= ")))))
elif coliczyc=="9":
    print("Pole = " + str(p_walca(float(input("r= ")), float(input("H= ")))))
elif coliczyc=="10":
    print("Pole = " + str(v_walca(float(input("r= ")), float(input("H= ")))))
elif coliczyc=="11":
    print("Pole = " + str(p_prostopad(float(input("a= ")), float(input("h= ")))))
elif coliczyc=="12":
    print("Pole = " + str(v_prostopad(float(input("a= ")), float(input("h= ")))))
elif coliczyc=="13":
    print("Pole = ", p_trojkata())
elif coliczyc=="14":
    print("Pole = ", p_trap())
elif coliczyc=="15":
    print("Pole = ", p_rowno())
elif coliczyc=="16":
    print("Delta = ", delta())
elif coliczyc=="17":
    print("Pole = ", p_okr())
elif coliczyc=="18":
    print("Wynik = ", mnoz())

else:
    print("TO NIE LICZBA ???????")


# Kacper Gora3c
