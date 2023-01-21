costo de lapices 





Algoritmo costo_total_lapices
	cantidad_lapices<-0
	costo <-0
	precio_a_pagar<-0
	Escribir " ingresa el numero de cada lapices "
	leer cantidad_de_lapices;
	Si cantidad_de_lapices >= 1000 Entonces
		costo<-85
	SiNo
		costo<-90
	Fin Si
	precio_a_pagar<-costo* cantidad_de_lapices;
	Escribir " valor de costo ", costo;
	Escribir " valor de pago ", precio_a_pagar;
FinAlgoritmo






suma de numeros 

Algoritmo sin_titulo
	num <- 0 
	Escribir "ingresa un numero"
	leer num
	
	Si num>0 Entonces
		Escribir "es positivo"
	SiNo
		Escribir "es negativo"
	Fin Si
	
FinAlgoritmo


suma de 3 numeros Algoritmo Suma_de_numeros
	num_1 <- 0
	num_2 <- 0
	res <- 0 
	Escribir "Ingresa primero numero"
	leer num_1
	
	Escribir "Ingresa seundo numero"
	leer num_2
	
	res<-num_1 + num_2
	
	Escribir "La suma de tus numeros es ",res
	
	
FinAlgoritmo




Algoritmo sin_titulo
	num<-0
	sum<-0
	i<-1

	Mientras i<=10 Hacer
		
		Escribir "escribe un numero"
		leer num
		sum<- sum+num
		i<-i+1
	Fin Mientras
	Escribir "las suma de tusd 10 numeros es ", sum
FinAlgoritmo





aprovado p re´rovao 

Algoritmo sin_titulo
	cal<-0
	Escribir "ingresa calificacion"
	leer cal
	Si cal>1 y cal<7 Entonces 
		Si cal>4 Entonces
			Escribir " APROBADO "
		SiNo
			Escribir "REPROBADO "
		Fin Si
	SiNo
		Escribir "calificacion invalida"
	Fin Si
	
FinAlgoritmo







promedio de alumnos

Algoritmo sin_titulo
	Definir total,edad,suma Como Entero
	Definir promedio como real
	Escribir "Ingresa el total de alumnos"
	leer total
	x = 1
	suma = 0
	Mientras x <= total Hacer
		Escribir "Ingresa tu edad"
		leer edad
		suma = suma + edad
		x = x + 1
	FinMientras
	Escribir "El promedio de edades de todo el grupo es: ",suma / total
FinAlgoritmo
