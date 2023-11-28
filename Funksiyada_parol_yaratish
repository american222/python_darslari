import random
son = []

harflar = ['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']
sonlar = ['0','1','2','3','4','5','6','7','8','9']
katta_harf = ['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']

def parol():
    for i in range(random.randint(2,5)):
        son.append(random.choice(harflar))
    for i in range(random.randint(3,5)):
        son.append(random.choice(sonlar))
    for i in range(random.randint(2,4)):
        son.append(random.choice(katta_harf))
    

    random.shuffle(son)
    return son


mening = parol()
print(mening)
