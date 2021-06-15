# PRÁCTICA No.2  ANÁLISIS DE MALLAS

## 1. OBJETIVOS
 
#### OBJETIVO GENERAL
 Aplicar los conocimientos anteriormente obtenidos como son La Ley de Kirchhoff y Ley de Ohm ya que será gran utilidad para el análisis de mallas.

Aplicando el metodo de mallas comprvaremos las medicones en simulacion y en calculos

Se relizara en un circuito mixto el cual se difivira en mallas para su pediones y sus calculos 
 
#### OBJETIVOS ESPECÍFICOS

- Examinar el método de análisis de mallas como herramientas en la resolución de circuitos eléctricos.
- Verificar que los valores medidos en la práctica realizada en el simulador Tinkercad coincidan con los valores calculados de las corrientes.
- Realizar comparaciones entre los datos análiticos, simulados y experimentados usando  el método de análisis de mallas.
- Comprobar la efectividad y facilidad del uso del Método de análisis de mallas.

## 2.MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/84431598/121991018-6b90af80-cd64-11eb-921f-d55528170504.png)


## 3.EXPLICACIÓN DEL PROCEDIMIENTO

#### 3.1 MATERIALES Y EQUIPOS

![image](https://user-images.githubusercontent.com/84431598/121798020-7bd04f80-cbe9-11eb-8628-5a9bead606fe.png)

#### 3.2 PROCEDIMIENTO

3.2.1 Implemente el circuito que se presenta en la figura 2.1.

![image](https://user-images.githubusercontent.com/84425276/121952618-1b90f900-cd22-11eb-931f-57f9e7eb01d9.png)

3.2.2 Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1.

![image](https://user-images.githubusercontent.com/84425276/121957209-b809ca00-cd27-11eb-961c-fdf08ddddca7.png)

   *Figura 1: Medición de corriente*

3.2.3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 2.1, obteniendo los valores de las corrientes de malla. Anote los resultados en la tabla 4.1.

![image](https://user-images.githubusercontent.com/84425276/121957542-29497d00-cd28-11eb-9116-dbd14905d205.png)

   *Figura 2: Simulación en Tinkercad*
   
  ![image](https://user-images.githubusercontent.com/84431598/121991203-d641eb00-cd64-11eb-9f46-dd6cd81f218e.png)
 
   *Figura 3: Simulación en Proteus*

![image](https://user-images.githubusercontent.com/84458025/122090305-3ff5df80-cdcd-11eb-92f2-6bf0799078d1.png)

![image](https://user-images.githubusercontent.com/84458025/122090306-3ff5df80-cdcd-11eb-9990-042c158ea247.png)


   *Figura 4: Simulación en Real*
## 4. RESPUESTA A INTERROGANTES Y CÁLCULO DEL ERROR

### 4.1  CIRCUITO PARA EL ANÁLISIS DE MALLAS

![image](https://user-images.githubusercontent.com/84425276/121957762-76c5ea00-cd28-11eb-8804-1bf1666ef45f.png)

   *Figura 4: Simulación del circuito*

#### Tabla 4.1. Resultados obtenidos para el circuito de la figura 2.1.

![image](https://user-images.githubusercontent.com/84425276/121964481-3ae35280-cd31-11eb-9fbe-612a3e8b532a.png)

### 4.2 CÁLCULOS

###  EXPLICACIÓN DE MÉTODO

El método de malla consiste en asignar a cada una de las mallas de cicuito de una corriente imaginaria, a la que se denomina malla, que circula en un sentido determinado por un grupo de ramas del circuito formado por una trayectoria cerrada.

![image](https://user-images.githubusercontent.com/84431598/121816961-486ede80-cc44-11eb-9b08-0df856f0c89e.png)

Necesitamos tener todas las resistencias en una sola unidad por lo tanto se convierte de kΩ a Ω

![image](https://user-images.githubusercontent.com/84431598/121819894-47927880-cc55-11eb-8897-e7b227ff3c1a.png)


### PLANTEAMIENTO DE LAS ECUACIONES
Una  vez definidas las corrientes  de mallas del circuito y establecidas las corrientes de las ramas y sus voltajes se plantea una ecuacion para cada malla en este caso 3 mallas .

####  MALLA 1

![image](https://user-images.githubusercontent.com/84431598/121819718-3bf28200-cc54-11eb-9dab-6b1ac748e11a.png)


#### MALLA 2

![image](https://user-images.githubusercontent.com/84431598/121819612-a9ea7980-cc53-11eb-9dd2-d016625ccc88.png)

#### MALLA 3

![image](https://user-images.githubusercontent.com/84431598/121819563-66900b00-cc53-11eb-91c1-bd9db345559c.png)


#### SISTEMA DE ECUACIONES

![image](https://user-images.githubusercontent.com/84431598/121819451-bfab6f00-cc52-11eb-9ed1-a90c050ecc3d.png)

Resolviendo el sistema se obtiene:

![image](https://user-images.githubusercontent.com/84431598/121822151-1d47b780-cc63-11eb-849b-fb2bd51833aa.png)

Realizando las conversiones de A a mA y uA se tiene:

![image](https://user-images.githubusercontent.com/84431598/121822410-94318000-cc64-11eb-888a-9bf9d072e076.png)

### 4.3 Cálculo del error

![image](https://user-images.githubusercontent.com/84425276/121963343-96acdc00-cd2f-11eb-992f-bbe0c48ba140.png)

### 4.4 Compare los valores de la tabla 2.1 y realice sus conclusiones.

- Los valores medidos y los valores calculados coinciden con un mínimo error.

## 5. VIDEO




## 6. CONCLUSIONES

- Los valores medidos y los valores calculados coinciden con un mínimo error.
- De los resultados obtenidos anteriormente se concluye que la práctica fue realizada correctamente.
- Para realizar esta práctica de laboratorio fueron necesarios concocimientos previos como son: La ley de Kirchhoff, expresa que la suma de voltajes tiene que ser igual a cero, y la Ley de Ohm  que nos dice que el voltaje es igual a la corriente por la resistencia.
- Se pudo comparar en un simulacion real que las medicones de cada intecidad  pueden variar por milecimas a dferencia de los resultados objetidosen calculos 
- Con la aplicaion del metodo de mallas comprovamos que la intesidad del circuito mas una sola direcion.

## 7. BIBLIOGRAFÍA

Ayllón Fandiño, E. (1987). *Fundamentos de la teoría de los circuitos eléctricos II.* La Habana: Pueblo y Educación.

Robbins, A y Miller, W. (2007). Análisis de circuitos teoría y práctica (4ta ed,).México DF, México: Cengage Learning.



