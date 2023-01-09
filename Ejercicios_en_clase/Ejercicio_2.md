Ejercicio que indica si eres mayor o menor de edad en un rango de 0 a 120 años.
# Algoritmo

1.INICIO

 2. Declaracion(Edad(int))
 
  3. MOSTRAR "ingresa tu edad"
  
  4. Asignar edad
  
  5. SI edad> = 18
   
   5.1 MOSTRAR "Eres mayor de edad"
   
   5.2 SINO
   
   5.3 MOSTRAR "eres menor de edad"
   
6.FIN

# Diagrama de Flujo
![image](https://user-images.githubusercontent.com/119319898/211169395-6ca11d23-fbd4-4937-bf8f-635e75ed20f9.png)

# Seudo_codigo

    Algoritmo de_acuerdo_a_tu_edad_eres
	edad <- 0
	Escribir 'Ingresa tu edad'
	Leer edad
	Si edad>=0 Y edad<=120 Entonces
		Si edad>=18 Entonces
			Escribir 'Eres mayor de edad'
		SiNo
			Escribir 'Eres menorde edad'
		FinSi
	SiNo
		Escribir 'error en la edad, reingresa tu edad'
	FinSi
    FinAlgoritmo       
