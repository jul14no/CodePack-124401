# CodePack-124401


#loop for

print("Usando for loop:")
for andar in range(20, 0, -1):
    if andar == 13:
        continue
    print(andar)


#loop while 

print("Usando while loop:")
andar = 20
while andar > 0:
    if andar != 13:
        print(andar)
    andar -= 1


#do-while loop

print("Usando do-while loop:")
andar = 20
while True:
    if andar != 13:
        print(andar)
    andar -= 1
    if andar == 0:
        break
