# La modalidad que elegi fue la modalidad Jr. 
#Tome como archivo original el que nos dio la catedra
#Sobre ese archivo aplique cambios en FE Historico, aplique reduccion de la dimensionalidad con canaritos asesinos, el undersampling del 1 lo cambie a 0.5, en la optimizacion bayesiana puse un learning rate de 0.005, eraly stopping de 1000 y num iterations de 9999
#Esto lo hice con 6 semillas. 
#Para seleccionar el submit en kaggle lo que hice fue para cada experimento de 6 semillas cada uno, me arme una tabla, donde en las filas iban los resultados que iba obteniendo con cada semilla y en las columnas los numeros de envios
#calcule el promedio y el desvio para cada valor de envio, y me quede para cada experimento con el envio que tenia menor desvio y una ganancia razonable. 
#Para definir con que script/experimento quedarme lo que hice fue comparar entre experimentos esas ganancias promedio (de menor devio), y me quede con el experimento que tenia mayor ganancia.
#Luego para definir con que semilla publicar el script, lo que hice fue ver para esa columna de envios que semilla tenia su valor de ganancia mas cercano al promedio de ganancia para ese envio. 
#Adjunto el excel con los resultados. 

