# Parcial-Final

#Ejercisio numero 1 

# Copia este código y ejecútalo en Python
# ─── Serie de Fibonacci ───────────────────────────────────
 
n = int(input("¿Cuántos términos deseas ver? "))
 
a = 0   # Primer término
b = 1   # Segundo término
 
for i in range(n):
    print(a)
    siguiente = a + b   # Calcula el siguiente término
    a = b              # El anterior pasa a ser el actual
    b = siguiente      # El nuevo pasa a ser el siguiente



# Ejercisio numero 2 

# Copia este código y ejecútalo en Python
# ─── Pirámide de Números ──────────────────────────────────
 
n = int(input("¿Cuántas filas quieres? "))
 
for fila in range(1, n + 1):         # Ciclo externo: cada fila
    for j in range(1, fila + 1):     # Ciclo interno: números de la fila
        print(j, end=" ")            # Imprime sin salto de línea
    print()                          # Salta de línea al terminar la fila
