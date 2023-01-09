Ejercicio que calcula el tiempo que tardariamos en leer los nombres de determinado numero de poblacion.
# Algoritmo

1.INICIO

   2.Declaracion(poblacion_float,tienpo_a_leer=2,segundos_float,minutos_float,horas_float,dias_float,meses_float,años_float)
   
   3."Ingresa el número de población que quieres evaluar"
   
   4.Asignar(poblacion)

   5.segundos=(poblacion*tiempo_a_leer)
   
   6.minutos=(segundos/60)

   7.horas=(minutos/60)

   8.dias=(horas/24)

   9.meses=(dias/30)

   10.años=(meses/12)

   11.Mostrar("te tardarías",años,meses,dias,"en leer los nombres de los habitantes del planeta")
 
12.FIN

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


