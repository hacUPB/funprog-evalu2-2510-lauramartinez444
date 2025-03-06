# 1. DISTANCIA ENTRE DOS PUNTOS 🚏
    Inicio
    Escribir "Ingrese las coordenadas (x1, y1) del primer punto
    Leer x1, y1
    Escribir "Ingrese las coordenadas (x2, y2) del segundo punto

    Distancia = SQRT(X2-X1)²+(Y2-Y1)²

    Imprimir Distancia
    Fin

![alt text](../images/1retodrawio.png)

# 2. TELAS 🧶🧵👔
    Inicio
    Escribir "Ingrese la cantidad de metros que desea pedir"
    Leer cantidad

    Pulgadas = cantidad * 39.37

    Imprimir Pulgadas
    Fin

![alt text](<../images/2.Retodrawio.png>)

# 3. TRIÁNGULO RECTÁNGULO 🔺📐📐
    Inicio
    Escribir "Ingrese el cateto opuesto"
    Leer cateto opuesto
    Escribir "Ingrese el cateto adyacente"
    Leer cateto adyacente

    Hipotenusa² = cateto opuesto² + cateto adyacente²

    Hipotenusa = SQRT(Hipotenusa²)  

    Imprimir Hipotenusa
    Fin

![alt text](<../images/3.retodrawio.png>)

# 4. ¡CUMPLEAÑOS! 🎊🎉🍰🥧
    Inicio
    Escribir "Ingrese su fecha de nacimiento dn/mn/an"
    Leer dn, mn, an
    Leer da, ma, aa

    Sí dn > da y mn > ma entonces 
    Edad = aa-an

        Si no
        Sí dn < da y mn < ma entonces 
        Edad = (aa-an)-1 
    

            Si no
            Si dn = da y mn = ma entonces 
            Edad = aa-an   
            Escribir "Feliz Cumpleaños 🎉🎊"
            Fin Si
    Fin Si 
        Fin Si

    Imprimir Edad 
    Fin

# 5. SUELDO DE UN TRABAJADOR 👷‍♂️👷‍♀️👷‍♂️👷‍♀️
    Inicio
    Escribir "Ingrese el sueldo por hora del trabajador" 
    Leer vh
    Escribir "Ingrese horas trabajadas"
    Leer ht

    Si ht > 50
    Escribir "valor no permitido 50 es el máximo de horas"
    Si no  
    Si ht < 40 
        Vt = ht*vh

    Si no 
        Si ht > 40 y ht < 45
            Vt = (40*vh)+((40-ht)*2)

        Si no 
            Si ht > 45 y ht < 50
            Vt = (40*vh)+((5)*2)+((45-ht)*3)
    Fin Si
        Fin Si
            Fin Si

    Imprimir "El sueldo total es igual a: Vt"
    Fin

# 6. N CANTIDADES 🦺🦺
    Inicio

    Escribir "Ingrese N cantidades" 
    Leer N
    Leer Numeros negativos, Ceros, Numeros positivos 

    Si N < 0 Numeros negativos = +1

        Si no 
        Si N = 0 Ceros = +1 

            Si no 
                Si N > 0 Numeros = +1 
    Fin Si
        Fin Si 
            Fin Si
            Imprimir "Numeros negativos =, Ceros =, Numeros positivos =,"
    Fin

# 7. AHORRANDO EXPONENCIALMENTE 💷💸💰
    Inicio
    Definir ahorro_diario = 0.03
    Definir ahorro_total = 0

    Desde día = 1 hasta día = 365 
    ahorro_diario = ahorro_diario * 3
    ahorro_total = ahorro_total + ahorro_diario
        
    Fin Desde

    Imprimir "Ahorro total en un año: ", ahorro_total, ahorro_diario" pesos"
    Fin 


# 8. DESCUENTO EN N ARTÍCULOS 🎟🎫💎
    Inicio
    Escribir "Ingrese el precio de los artículos comprados"
    Leer precio

    Si precio >= $200
    Precio total: precio - (precio*15%)

        Si no
            Si $200 > precio > $100
             Precio total :  precio - (precio*12%)

                Si no 
                    Si precio < $100
                    Precio total : precio - (precio*10%)
    Fin Si            
         Fin Si
                Fin Si

                    Imprimir "Tu precio total es:",  Precio total
    Fin

# 9. FUNCIÓN EXPONENCIAL 📕📖✏🖋🖌🖍📈
    Inicio
    Escribir "Ingrese el valor de x"
    Leer x
    Escribir "Ingrese el número de términos que desea imprimir"
    Leer n 

    e^x = 1
    término = 1 
    i = 1 

        Mientras i < n hacer: 
        término = término * x / i 
        e^x = e^x + termino  
        i = i + 1  

        Fin Mientras 

    Imprimir "El valor aproximado de e^x es:", e^x

    Fin

# 10. FUNCIÓN SENO 🧩⚙🗃📇📚
    Inicio
    Escribir "Ingrese el valor de x en radianes"
    Leer x 
    Escribir "Ingrese el número de términos que desea imprimir"
    Leer n

    Sen(x) = x  
    termino = x  
    i = 1  

         Mientras i < n hacer
        termino = termino * (-1) * x * x / ((2 * i) * (2 * i + 1))  
        Sen(x) = Sen(x) + termino  
        i = i + 1  
        Fin Mientras

        Imprimir "El valor aproximado de Sen(x) es: ", Sen(x)
    Fin 