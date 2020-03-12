# Reto Semana Tec

# Herramientas computacionales: maestros de la analítica
---

##### Integrantes:
1. *[Poner aquí Nombre y Apellidos del integrante 1]* - *[Poner aquí su Matrícula]* 
2. *[Poner aquí Nombre y Apellidos del integrante 2]* - *[Poner aquí su Matrícula]* 
3. *[Poner aquí Nombre y Apellidos del integrante 3]* - *[Poner aquí su Matrícula]* 
4. *[Poner aquí Nombre y Apellidos del integrante 4]* - *[Poner aquí su Matrícula]*
5. *[Poner aquí Nombre y Apellidos del integrante 4]* - *[Poner aquí su Matrícula]*

---
## Bienvenida

De acuerdo a DOMO (empresa de software en la nube con sede en American Fork, Utah, Estados Unidos.), en 2017 se generaban por día 2.5 quintillones de bytes en datos. Aunque no todos estos datos son relevantes, existe mucha información que se puede extraer de estos. Debido a la cantidad, un analista humano no es capaz de hacer el análisis de estos datos, por lo que tiene que recurrir a herramientas computacionales.

En esta semana Tec aprenderás los fundamentos del análisis de datos, incluyendo algunas herramientas básicas que te permitirán obtener una idea rápida de cómo están compuestos los datos y resolver algunas preguntas acerca de ellos.

Te invitamos a explotar al máximo las actividades a desarrollar, así como a preguntar todas las dudas que tengas, para que puedas obtener las habilidades fundamentales que seguro te serán de mucha ayuda en tu vida profesional.

Este documento es una guía sobre los entregables del reto y la estructura que debe seguir para organizar su entrega.

### Estructura del repositorio

Debe respetar la siguiente estructura de carpetas:
```
- / 			        # Raíz de todo el reto
    - README.md			# Archivo con la información del reto (este archivo)
    - entregables		# Carpeta con los entregables del reto
    - datasets		        # Carpeta con los datasets y recursos a utilizar
```

## Actividades y Entregables 

### Actividad 1. Repositorio

#### ¿Qué tengo que hacer?

1. Si aún no tienes una cuenta en Github, créala con el correo electrónico de tu preferencia.
2. Utilizando el comando `git clone`, clona este repositorio a tu computadora local. En este repositorio, dentro de la carpeta *datasets* encontrarás los conjuntos de datos a utilizar durante el reto.
3. Utilizando un editor de texto como `nano`, edita este archivo y agrega en la sección correspondiente que se encuentra al inicio, los nombres y matrículas de los miembros del equipo.
5. Utilizando los comandos `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.
6. Captura una pantalla por cada uno de los pasos anteriores, donde se aprecien los comandos utilizados y las operaciones realizadas.

#### Entregables 

1. Confecciona un documento con las capturas de pantalla de los pasos realizados.
2. Nombra el documento [Actividad_1.pdf](entregables/Actividad_1.pdf) y adiciónalo a la carpeta *entregables* de este repositorio.
3. Utilizando los comandos `git add`, `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.

### Actividad 2. Obtención de estadísticas descriptivas

#### ¿Qué tengo que hacer?

En esta actividad trabajarás con el conjunto de datos asignado para el reto, el cual puedes encontrar en la carpeta *entregables* de este repositorio. Tienes que replicar los pasos vistos durante las horas de salón.

1. Crea un archivo de Jupyter Notebook y nómbralo [Actividad_2.ipynb](entregables/Actividad_2.ipynb) y adiciónalo a la carpeta *entregables* de este repositorio. Adiciona al archivo el código necesario para realizar las siguientes acciones.
2. Carga el *dataset* usando tu lector de CSV o con Pandas. Es recomendable hacerlo con Pandas.
3. Verifica la cantidad de datos que se tienen, las variables que contiene cada vector de datos e identifica el tipo de variables.
4. Analiza las variables para saber qué representa cada una y en qué rangos se encuentran. Si la descripción del problema no te lo indica, utiliza el máximo y el mínimo para encontrarlo.
5. Basándose en la media, mediana y desviación estándar de cada variable, ¿qué conclusiones puedes entregar de los datos?.
6. Incorpora dentro del archivo de Jupyter Notebook los bloques de texto necesarios para dar respuesta a las preguntas planteadas.
7. Utilizando los comandos  `git add`, `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.

#### Entregables 

1. En GitHub debe quedar actualizado el archivo [Actividad_2.ipynb](entregables/Actividad_2.ipynb), incluyendo en el mismo todo el código programado, así como los bloques de texto explicando en cada paso como ejecutarlos, su interpretación de los resultados y las respuestas a las preguntas.

### Actividad 3. Mapas de calor y boxplots

#### ¿Qué tengo que hacer?

En esta actividad trabajarás con el conjunto de datos asignado para el reto, el cual puedes encontrar en la carpeta *entregables* de este repositorio. Tienes que replicar los pasos vistos durante las horas de salón.

1. Abre una Terminal.
2. Utilizando el comando `cd` cámbiate a la carpeta *entregables* del repositorio local.
3. Utilizando el comando `cp` crea una copia del archivo [Actividad_2.ipynb](entregables/Actividad_2.ipynb) y nómbralo [Actividad_3.ipynb](entregables/Actividad_3.ipynb).
4. Adiciona al archivo de esta actividad el código necesario para realizar el análisis de las variables usando diagramas de cajas y bigotes, histogramas y mapas de calor.
5. Incorpora dentro del archivo de Jupyter Notebook los bloques de texto necesarios para documentar cada bloque de código.
6. Adiciona un bloque de texto en el cuál respondas las siguientes preguntas:
    - ¿Hay alguna variable que no aporta información?
    - Si tuvieras que eliminar variables, ¿cuáles quitarías y por qué?
    - ¿Existen variables que tengan datos extraños?
    - Si comparas las variables, ¿todas están en rangos similares? ¿Crees que esto afecte?
    - ¿Puedes encontrar grupos que se parezcan? ¿Qué grupos son estos?
7. Utilizando los comandos  `git add`, `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.

#### Entregables 

1. En GitHub debe quedar actualizado el archivo [Actividad_3.ipynb](entregables/Actividad_3.ipynb), incluyendo en el mismo todo el código programado, así como los bloques de texto explicando en cada paso como ejecutarlos, su interpretación de los resultados y las respuestas a las preguntas planteadas.

### Actividad 4. Modelos de *Machine Learning*

#### ¿Qué tengo que hacer?

En esta actividad trabajarás con diferentes modelos de *Machine Learning* para clasificación, predicciones y/o encontrar patrones con los datos. Tienes que replicar los pasos vistos durante las horas de salón.

1. Abre una Terminal.
2. Utilizando el comando `cd` cámbiate a la carpeta *entregables* del repositorio local.
3. Utilizando el comando `cp` crea una copia del archivo [Actividad_3.ipynb](entregables/Actividad_3.ipynb) y nómbralo [Actividad_4.ipynb](entregables/Actividad_4.ipynb).
4. Adiciona al archivo de esta actividad el código necesario para realizar una regresión lineal, una clasificación y/o un análisis de patrones con K-means.
5. Incorpora dentro del archivo de Jupyter Notebook los bloques de texto necesarios para documentar cada bloque de código.
6. Adiciona un bloque de texto en el cuál respondas las siguientes preguntas:
    - Regresión
        * ¿Cuáles son las variables significativas?
        * ¿Cuál es la variable objetivo a predecir?
        * ¿Cuántas variables categóricas tienes? ¿Qué conversión realizas para poder utilizar las variables categóricas?
        * ¿Qué otras variables propones para mejorar la predicción? Justifica cada una de ellas
        * ¿Qué tasa de error obtuviste?
        * ¿Tu modelo es bueno o es malo? ¿Por qué?
    - Clasificación
        * ¿Cuáles son las variables significativas?
        * ¿Cuál es la variable objetivo a clasificar? ¿Cuáles son las clases de salida?
        * Interprete su matriz de confusión y escriba sus apreciaciones
        * ¿El modelo está sobrecargado a alguna clase? ¿De ser así, cuál es la mejor medida a utilizar: accuracy, precision o recall? Justifique su respuesta
        * ¿Qué valores obtuviste para accuracy, precision o recall?
        * ¿Tu modelo es bueno o es malo? ¿Por qué?
    - K-means
        * ¿Crees que estos centros puedan ser representativos de los datos? ¿Por qué?
        * ¿Cómo obtuviste el valor de k a usar?
        * ¿Los centros serían más representativos si usaras un valor más alto? ¿Más bajo?
        * ¿Qué distancia tienen los centros entre sí? ¿Hay alguno que esté muy cercano a otros?
        * ¿Qué pasaría con los centros si tuviéramos muchos outliers en el análisis de cajas y bigotes?
        * ¿Qué puedes decir de los datos basándose en los centros?

7. Utilizando los comandos  `git add`, `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.

#### Entregables 

1. En GitHub debe quedar actualizado el archivo [Actividad_4.ipynb](entregables/Actividad_4.ipynb), incluyendo en el mismo todo el código programado, así como los bloques de texto explicando en cada paso como ejecutarlos, su interpretación de los resultados y las respuestas a las preguntas planteadas.

### Actividad 5. Presentación y video

#### ¿Qué tengo que hacer?

1. Prepara una presentación en PowerPoint para exponer frente al grupo, donde muestres tus datos, los análisis ejecutados y los resultados obtenidos. 
2. Nombra la presentación [Actividad_5.pptx](entregables/Actividad_5.pptx) y adiciónala a la carpeta *entregables* de este repositorio.
3. Graba un video de máximo 4 minutos, donde cada integrante debe hablar de la parte que realizó, así como describir los resultados y cambios hechos. Sube el video a la carpeta *entregables* de este repositorio con el nombre [Actividad_5.mp4](entregables/Actividad_5.mp4).
4. Utilizando los comandos `git add`, `git commit` y `git push`, actualiza los cambios en el repositorio de GitHub.

#### Entregables 

1. En GitHub deben quedar actualizados los archivos de la [presentación](entregables/Actividad_5.pptx) y el [video](entregables/Actividad_5.mp4). 
2. Con las preguntas y retroalimentaciones obtenidas, haz los cambios pertinentes en tus entregables del reto.
3. Utilizando los comandos `git commit` y `git push`, actualiza los archivos modificados, en el repositorio de GitHub.

## 6. Referencias

*[Incluya aquí las referencias a sitios de interés, datasets y cualquier otra información que haya utilizado para realizar el reto y que le puedan ser de utilidad a otras personas que quieran usarlo como referencia]*
