### Ejercicio 1
#### 1.1 Análisis.
Se introduce un símbolo de proceso que Ae[100] As[100], luego se pone una salida de datos que te pide el "Numero de estudiantes", de hay se pone una entrada de datos que n, luego una condición que ne>0 and ne<100, si la condición es no se introduce una salida de datos que "no esta dentro de los límites" y se regresa al símbolo de salida de datos que "Número de estudiantes" si la condición es fue si se introduce un ciclo for que i=0; i<ne; i++, luego se introduce un símbolo de salida de datos que te pide "Dame la edad" de hay introduces la edad en una entrada de datos, luego una condición que ed>0 and ed<130, si la condición es no se introduce una salida de datos que te dice "no esta dentro de los límites" y se regresa a la salida de datos donde te pides que que introduzcas tu edad, si la condición fue si se introduce una salida de datos que te pide el "Semestre", de ahí una entrada de datos que te pide que introduzcas e semestre, luego una condición que se>0 and se<130, si la condición es no se introduce una salida de datos que "no esta dentro de los limites" y se regresa a la salida de datos que te pide "Semestre", si la condición fue si se pone un símbolo de proceso que Ae[i]=ed, se pone otro símbolo de proceso que As[i]=se, luego se regresa al ciclo for, si el ciclo for ya no se repite se introduce una salida de datos que que imprime Ae, As.
#### 1.2 Diagrama de flujo.
[![1.jpg](https://i.postimg.cc/6QM4FPKb/1.jpg)](https://postimg.cc/DWbzXB81)
#### 1.3 Prueba de escritorio.
corrida|valor i|V E|V S|i=n?|
|-|-|-|-|-|
|1|0|VE[0]=16|VS[0]=3|no|
|2|1|VE[1]=17|VS[1]=5|no|
|3|2|VE[2]=18|VS[2]=7|no|
|4|3|VE[3]=17|VS[3]=5|Si, impr VE y VS|

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|18|7|
|17|5|

#### 1.4 Entradas.
3, una para pedir numero de estudiantes, otra para pedir la edad y la ultima para pedir el semestre.
#### 1.5 Salidas.
6, una sale con "Numero de estudiantes", la segunda "No esta dentro de los límites", la tercera "Dame la edad", la cuarta "No esta dentro de los límites", la quinta "Semestre", la sexta "No esta dentro de los límites"

### Ejercicio 2
#### 2.1 Análisis.
Se pide un símbolo de proceso que pide M[100,2], de ahí una salida de datos que "Numero de estudiantes", luego una entrada de datos que pide ne, después un símbolo de decisión que ne>0 and ne<100, si la condición es no se pone una salida de datos que "no esta dentro de los límites" y se regresa a la salida de datos que dice "Número de estudiantes", si la condición es si se ingresa un ciclo for que i=0; i<ne; i++, si el ciclo se repite luego se pone una salida de datos que pide "Dame la edad", de ahí una entrada de datos que ed, luego una condición que ed>0 and ed<130, si la condición es no se pone una salida de datos que "No esta dentro de los límites" y se regresa a la salida de datos de "Dame tu edad", si la condición es si se pone una salida de datos que pide "Semestre", luego una entrada de datos que se, de ahí una condición que se>0 and se<130, si la condición es no se pone una salida de daos que "No esta dentro de los límites" y se regresa a la salida de datos que te pide el "Semestre", si la condición es si se introduce un símbolo de proceso que M[i,1], de ahí se regresa al ciclo for, y si el ciclo ya no se repite se pone una salida de datos que imprime "M".
#### 2.2 Diagrama de Flujo. 
[![2.jpg](https://i.postimg.cc/KvdmpRWq/2.jpg)](https://postimg.cc/7fnvfYw0)
#### 2.3 Prueba de Escritorio.
|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,0]=16|no|
|2|1|0|M[1,0]=17|no|
|3|2|0|M[2,0]=17|no|
|4|3|0|M[3,0]=16|Si, entonces sig contador|

|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,1]=3|no|
|2|1|0|M[1,1]=5|no|
|3|2|0|M[2,1]=5|no|
|4|3|0|M[3,1]=3|Si, entonces impr [M]|

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|17|5|
|16|3|
#### 2.4 Entradas.
3, la primera pide ne, la segunda ed, y la tercera se
#### 2.5 Salidas.
6, la primera "Numero de estudiantes", la segunda "No esta dentro de los límites", la tercera "Dame la edad", la cuarta "No esta dentro de los límites", la quinta "Semestre" y la ultima "No esta dentro de los límites".

### Ejercicio 3.
#### 3.1 Análisis.
Se ingresa un símbolo de proceso que M[50,50], de ahí una salida de datos que "Ingresa el tamaño de la matriz", después una entrada de datos que n, luego una condición que n>1 and n<50, si la condición es no se ingresa una salida de datos que "No esta dentro de los límites" y se regresa a la salida de datos que "Ingresa el tamaño de la matriz", si la condición es si se ingresa una salida de datos que "Numero leído del teclado", de ahí una entrada de datos que num, después una condición que num>0 and num<50, si la condición es no se pone una salida de datos que "No esta dentro de los límites" y se regresa a la salida de datos que "Numero leído del teclado", si la condición fue si se pone un ciclo for que i=0; i<n; i++, si el ciclo for se repite se pone otro ciclo for que j=0; j<i; j++, si ese ciclo for se repite se pone un símbolo de proceso que M[i,j]=num, y se regresa al ciclo for, si ese ciclo for ya no se repite se va al otro ciclo for i=0; i<n; i++, si ese ciclo for ya no se repite se termina.
#### 3.2 Diagrama de flujo.
[![3.jpg](https://i.postimg.cc/Zq1wNzsM/3.jpg)](https://postimg.cc/qtxcfSTs)
#### 3.3 Prueba de Escritorio.
|i|j|Matriz|num|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|5|no|
|0|1|M[0,1]|7|no|
|0|2|M[0,2]|8|si, entonces J+1 y vuelve a empezar|

|5|7|8|
|-|-|-|
|5|7|8|
|5|7|8|

#### 3.4 Entradas.
2
#### 3.5 Salidas.
4

### Ejercicio 4
#### 4.1 Análisis.
Se ingresa con un símbolo de proceso que M[50,50] C=0, luego una salida de datos que "Ingresa el tamaño de la matriz", después una entrada de datos que n, luego una condición que n>1 and n<50, si la condición es no se pone una salida de datos que "No esta dentro de los límites" y se regresa a la salida de datos de "Ingresa el tamaño de la matriz", si la condición fue si se pone un ciclo for que i=0; i<n; i++, si el ciclo for se repite se pone otro ciclo for que j=0; j<i; j++, de ahí un símbolo de proceso que M[i,j]=c, después otro símbolo de proceso que c=c++, y se regresa al ciclo for, si el ciclo for ya no se repite se regresa al ciclo for j=0; j<i; j++, después se regresa al otro ciclo for i=0; i<n; i++, si ese ciclo for ya no se repite se termina.
#### 4.2 Diagrama de Flujo.
[![4.jpg](https://i.postimg.cc/pdWmBsyY/4.jpg)](https://postimg.cc/rDHyVC1K)
#### 4.3 Prueba de Escritorio.
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|0|no|
|0|1|M[0,1]|0|no|
|0|2|M[0,2]|0|si, entonces vuelve a empezar|

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|
#### 4.4 Entradas.
1
#### 4.5 Salidas.
2

### Ejercicio 5
#### 5.1 Análisis.
Se ingresa con un proceso de datos que M[100,100], de ahí una salida de datos que "Ingresa el tamaño de una matriz", luego una entrada de datos que n, después una condición que n>1 and n<100, si la condición es no se pone una salida de datos que "No esta dentro de los límites" y se regresa a la salida de datos que "Ingresa el tamaño de la matriz", si la condición fue si se ingresa un ciclo for que i=0; i<n; i++, si el ciclo for se repite se pone otro ciclo for que j=0; j<i; j++, de ahí se pone un símbolo de proceso que M[i,j]=j+1, y se regresa al ciclo for, si el ciclo for ya no se repite se va al otro ciclo for de i=0; i<n; i++, si ese ciclo for ya no se repite se termina.
#### 5.2 Diagrama de Flujo.
[![5.jpg](https://i.postimg.cc/MH9ChbSB/5.jpg)](https://postimg.cc/RJnpttqC)
#### 5.3 Prueba de Escritorio.
|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|1|no|
|0|1|M[0,1]|1|no|
|0|2|M[0,2]|1|si, entonces C+1 y vuelve a empezar|

|1|1|1|
|-|-|-|
|2|2|2|
|3|3|3|
#### 5.4 Entradas.
1
#### 5.5 Salidas.
2

### Ejercicio 6.
#### 6.1 Análisis.
Se inicia con un símbolo de proceso que M[100,100], luego una salida de datos que "Tamaño de la matriz", de hay una entrada de datos que n, después una condición que n>0 and n<=100, si la condición fue no se introduce una salida de datos que "e" de ahí se regresa a la salida de datos que "tamaño de la matriz", si la condición fue si se pone un ciclo for que i=0; i<n; i++, si el ciclo se repite se pone otro ciclo for que j=0; j<n; j++, de ahí se pone una condición que j=i, si la condición es no se pone un símbolo de proceso que M[i,j]=0 y si la condición fue si M[i,j]=i+1, ambas condiciones se regresan al ciclo for de j=0; j<n; j++, si ese ciclo ya no se repite se va al otro ciclo for de i=0; i<n; i++.
#### 6.2 Diagrama de Flujo.
[![6.png](https://i.postimg.cc/sfTzvSB8/6.png)](https://postimg.cc/vDxkK4tL)
#### 6.3 Prueba de Escritorio.
|corridas|i|j|M|j=m?|
|-|-|-|-|-|
|1|0|1|M[0,0]=0|no|
|2|0|2|M[0,0]=0|no|
|3|0|3|M[0,0]=0|no|
|4|0|4|0|0|M[0,0]=0|si, entonces i+1 y j=0|

|0|0|0|0|
|-|-|-|-|
|0|0|0|0|
|0|0|0|0|
|0|0|0|0|

Ahora hacemos la secuencia y en cada ciclo acabado le sumamos 1 a j

|Corridas|i|M|
|-|-|-|
|1|0|M[i,i=i+1|
|2|1|M[i,i=i+1|
|3|2|M[i,i=i+1|
|4|3|M[i,i=i+1|


Ejemplo

|1|0|0|0|
|-|-|-|-|
|0|2|0|0|
|0|0|3|0|
|0|0|0|4|

#### 6.4 Entradas.
1
#### 6.5 Salidas.
2

### Ejercicio 7.
#### 7.1 Análisis.
Se inicia con un símbolo de proceso que M[50,50], después una entrada de datos que A[2500], luego una salida de datos que "Numero de matriz" de ahí una entrada de datos que num, después una condición que num>0 and num<=50, si la condición es no se pone una salida de datos que "e" y se regresa a la salia de datos que te pide "Numero de matriz" si la condición fue si se pone un ciclo for que i=0; i<num; i++, después se pone otro ciclo for que j=0; i<num; j++, después un símbolo de proceso que M[i,j]=n de ahí se regresa al ciclo for de j=0; i<num; j++, si ese ciclo ya no se repite se va al otro ciclo for de i=0; i<num; i++, luego se pone un símbolo de proceso que num=num*num, después otro ciclo for que i=0; i<num; i++, si el ciclo se repite se pone otro ciclo for que j=0; j<num; j++, después se pone un simbolo de proceso que A[c]=M[i,j], de ahí se pone otro símbolo de proceso que c++, se regresa al ciclo for de j=0; j<num; j++, si ese ciclo for ya no se repite se regresa al ciclo for de i=0; i<num; i++.
#### 7.2 Diagrama de Flujo.
[![7.png](https://i.postimg.cc/vmQm9yzH/7.png)](https://postimg.cc/k2p93kzk)
#### 7.3 Prueba de Escritorio.
|corridas|Matriz|Vector|j+1|
|-|-|-|-|
|1|M 0,0|M 0,0=V 0|j+1|
|2|M 0,1|M 0,1=V 1|j+1|
|3|M 0,2|M 0,2=V 2|j+1|

If j=M, i+1 and j=0 y regresa el ciclo hasta que i=M


|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|
#### 7.4 Entradas.
1
#### 7.5 Salidas.
3

### Ejercicio 8.
#### 8.1 Análisis.
Se inicia con un símbolo de proceso que CR=0 MM=0 CM=0 R1=0 AR=0, luego se pone un símbolo de proceso que CA[50,70], otro símbolo de proceso que NM[7], otro símbolo de proceso que PM[7], otro símbolo de proceso que PA[50], después una salida de datos que "Num alumnos", de hay una entrada de datos que na, después una condición que na>=5 and na<=50, si la condición es no se pone una salida de datos que "e", y se regresa a una salida de datos que "Num alumnos", si la condición fue si se pone un ciclo for que i=0; i<7; i++, después una salida de datos que "Nombre de materia", luego una entrada e datos que nma, después un símbolo de proceso que NM[i]=nma, y se regresa al ciclo for, mas tarde un símbolo de proceso que NM, se pone una salida de datos que "Si todo esta bien escribe 0, si no introduce el numero de la materia para corregir", después se pone una entrada de datos que RE, luego se pone una condición que RE==0, si la condición es no se pone una entrada de datos que nma, luego se pone un símbolo de proceso que NM[RE]=nma, y se regresa al símbolo de proceso que NM, si esa condición es si se pone un ciclo for que i=0; i<na; i++, si el ciclo for se repite se pone otro ciclo for que j=0; j<7; j++, si ese ciclo se repite se pone una salida de datos que "introduce la cal del alumno", luego una entrada de datos que cal, de ahí un símbolo de proceso que M[i,j]=cal, y se regresa al ciclo for de j=0; j<7; j++, si ese ciclo for ya no se repite se regresa al ciclo for de i=0; i<na, i++, de ahí se pone un ciclo for de i=0; i<na; i++, si el ciclo se repite se pone otro ciclo for que j=0; j<7; j++, después se pone un  símbolo de proceso que PA=PA+C[i,j], luego se pone otro símbolo de proceso que PA[i]=PA[i]+c[i,j], se regresa de nuevo al ciclo for de j=0; j<7; j++, si ese ciclo for ya no se repite se regresa al otro ciclo for de i=0; i<na; i++, si ese ciclo for ya no se repite se va a otro ciclo for de i=0; i<7; i++, si ese ciclo for se repite se va a otro ciclo for de j=0; j<na; j++, de ahí se pone un símbolo de proceso que SM=SM+C[i,j], se regresa al símbolo for de j=0; j<na; j++, si ese ciclo ya no se repite se pone un símbolo de proceso que PM[i]=SM/na, y se va al ciclo for de i=0; i<7; i++, si ese ciclo for ya no se repite se va a un símbolo de proceso que AM[0]CA=0, de ahí se pone una condición que CA>PA[i], si la condición es no se pone un símbolo de proceso que CA=PA[i] AM=i, y se va para el ciclo for igual que si la condición fue si se va al ciclo for, después se pone un ciclo for que i=0; i<7; i++, si ese ciclo for se repite se va a una condición que CM>PM[i], si la condición fue no se pone un símbolo de proceso que CM=PM[i]  MM=[i], si la condición fue si se regresa al ciclo for i=0; i<7; i++, y si ese ciclo for ya no se repite se termina.
#### 8.2 Diagrama de Flujo.
[![8.png](https://i.postimg.cc/Hs7Q0zBK/8.png)](https://postimg.cc/WhTFTGR6)
#### 8.3 Prueba de Escritorio.
|corridas|i|j|M|j+1|
|-|-|-|-|-|
|1|0|0|M 0,0=Materia|j+1|
|2|0|1|M 0,1=Materia|j+1|
|3|0|2|M 0,2=Materia|j+1|
|4|0|3|M 0,3=Materia|j+1|

|Español|Matematicas|Historia|Geografia|
|-|-|-|-|
|5|4|3|9|
|8|6|4|7|
|9|7|7|6|
|7|9|8|7|
#### 8.4 Entradas.
5
#### 8.5 Salidas.
5

### Ejercicio 9.
#### 9.1 Análisis.
Se inicia con un símbolo de proceso de A[100], de ahí una salida de datos que "Límite", después una entrada de datos que n, luego una condición que n>1, si la condición es no se pone una salida de datos que "e" de ahí se regresa a una salida de datos que "Límite" si la condición fue si se pone un ciclo for que i=1; i<=n; i++, si el ciclo se repite se va a otro ciclo for que j=1; j<=i; j++, después se va a un símbolo de proceso que A[i-1]=A[i-1]+j, se regresa al ciclo for, si ese ciclo for ya no se repite se va al otro ciclo for de i=1; i<=n; i++, si ese ciclo for ya no se repite se imprime una salida de datos que "A".
#### 9.2 Diagrama de Flujo.
[![9.png](https://i.postimg.cc/5ypKJ3Fb/9.png)](https://postimg.cc/GT8xJvQ5)
#### 9.3 Prueba de Escritorio.
|i|vector|i=V?|
|-|-|-|
|1|0|V[i]=V[i-1]+i+1|
|2|1|V[i]=V[i-1]+i+1|
|3|2|V[i]=V[i-1]+i+1|

|1|
|-|
|3|
|6|

#### 9.4 Entradas.
1
#### 9.5 Salidas.
3

### Ejercicio 10.
#### 10.1 Análisis.
Se inicia con un símbolo de proceso que M[10,10] A[100], de ahí se pone una salida de datos que "Dar el tamaño de la matriz", luego se pone una entrada de datos que n, después una condición que n>0 and n<=10, si la condición es no se pone una salida de datos que "e", y se regresa a la salida de datos que "Dar el tamaño de la matriz", si la condición fue si se pone una entrada de datos que m, luego otra condición que m>1 and m<=10, si la condición fue no se pone una salida de datos que "e" y se regresa a la salida de dato de "Dar tamaño de la matriz", si la condición fue si se pone un ciclo for que i=0; i<n; i++, si el ciclo se repite se pone otro ciclo for que j=0; j<m; j++, si el ciclo se repite se pone una salida de datos que "Ingresa el numero", de ahí se pone un símbolo de proceso que M[i,j], de ahí se regresa al ciclo for, si ese ciclo for ya no se repite se regresa al otro ciclo for de i=0; i<n; i++.
#### 10.2 Diagrama de Flujo.
[![10.png](https://i.postimg.cc/YCxvpb6L/10.png)](https://postimg.cc/w17q25b9)
#### 10.3 Prueba de escritorio.
|i|j|M|Suma|
|-|-|-|-|
|0|0|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|1|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|2|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|3|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|

If J=M, J=0 and I+1 y vuelve a iniciar
#### 10.4 Entradas.
2
#### 10.5 Salidas.
3
