Ejercicio que indica si eres mayor o menor de edad en un rango de 0 a 120 años.
# Algoritmo

INICIO
  Declaracion(Edad(int))
  MOSTRAR "ingresa tu edad"
  Asignar edad
  SI edad> = 18
   MOSTRAR "Eres mayor de edad"
   SINO
   MOSTRAR "eres menor de edad"
12.FIN

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
