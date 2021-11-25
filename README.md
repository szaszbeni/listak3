def feladat1():
    lista=[]
    for i in range(20,41):
        lista.append(i*i)
    print(lista)

def feladat2():
    szöveg=["Az ősz annyira szereti a naplementéket, hogy minden egyes levélre egyet fest."]
    print(len(szöveg))
    szoszam=szöveg.count(" ") + 1
    print("A szövegben enyyi szó van:", szoszam)
    e= szöveg.count("e")
    print("A szövegben enyi E betü van", e)

def feladat3():
    i=0
    szamok=[]
    for i in range(16):
        a=randint(1,100)
        szamok.append(a)
        i=i+a
    print(i)
    print(i/15)
    print(max(szamok)-min(szamok))
    print(szamok)

#feladat1()
#feladat2()
#feladat3()
