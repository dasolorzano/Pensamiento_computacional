Ejercicio que calcula el tiempo que tardariamos en leer los nombres de determinado numero de poblacion.
# Algoritmo
# Diagrama de Flujo
![image](https://user-images.githubusercontent.com/119319898/208264017-0250b925-08c9-4a4d-b749-aa7b20080048.png)

# Seudo_codigo

        Algoritmo sin_titulo
          poblacion=0
          tiempo_de_leer=2
          seg=0
          minutos=0
          horas=0
          dias=0
          meses=0
          anos=0
          Escribir "ingresa el numero de poblacion que quieres validar"
          Leer poblacion
          Escribir poblacion
          seg=(poblacion*tiempo_de_leer)
          Escribir seg
          minutos=(seg/60)
          horas=(minutos/60)
          dias=(horas/24)
          anos=(dias/365)
          escribir "te tardarias" " segundos ",seg," seg ",minutos," minutos ",horas," horas ",dias," dias ",anos," anos "
        FinAlgoritmo


