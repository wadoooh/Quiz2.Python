print("Ingresa el mensaje cifrado")
mensaje = input()
print("Cuántas veces quieres mover la letra")
veces = int(input())

mensajeCifrado = ""

for i in range(0, len(mensaje), 1):
    letra = mensaje[i]
    minuscula = ('a' <= letra <= 'z')
    mayuscula = ('A' <= letra <= 'Z')
    if not (minuscula or mayuscula):
        mensajeCifrado += letra
    else:
        ascii = ord(letra)
        baseAscii = ord('a')
        if mayuscula:
            baseAscii = ord('A')
        nuevoAscii = (ascii - baseAscii - veces) % 26 + baseAscii
        nuevaLetra = chr(nuevoAscii)
        mensajeCifrado += nuevaLetra

print('el mensaje descifrado es: '+mensajeCifrado)
