# Machine Learning con Oracle ADS: productividad en la creación de modelos

### Para saber más: Free Tier

Oracle ofrece la opción de crear una cuenta gratuita, en la cual el usuario tendrá USD 300 (trescientos dólares) de créditos disponibles durante 30 días para la utilización de los servicios pagos.

Para poder crear una cuenta gratuita (Free Trial) necesitarás reunir los siguientes requisitos:

Una cuenta de e-mail válida;

Permiso para recibir un SMS para la verificación por texto (en caso de que el e-mail no sea reconocido);

Y una tarjeta de crédito disponible para el registro (Atención: No habrá cobro de factura durante el período de Free Trial).

**Observación**: Las interfaces mostradas en las imágenes a continuación podrían ser diferentes de la interfaz que utilizarás cuando realices el curso.

1.  Abre tu navegador web a través de [Oracle Cloud Free](https://www.oracle.com/cloud/free/ "Oracle Cloud Free") para poder tener acceso al formulario de registro de **Oracle Cloud**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/18.jpg)

2.  Digita la información solicitada, en el formulario anterior, para proseguir con la creación de tu conta:

En el campo País/Territorio, selecciona tu país;

En los campo Nombre y Apellido, coloca tu nombre y apellido respectivamente;

En el campo E-mail, digita tu e-mail.

3. Con los campos llenos, Elige la opción **Soy humano** y, en seguida, haz clic en el botón **Verificar mi e-mail**.

4. Accede al buzón de entrada de tu e-mail y verifica si recibiste un e-mail de validación de la cuenta de Oracle, semejante al siguiente.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/19.jpg)

5. En el e-mail mostrado en el paso anterior, selecciona **Click here**. En seguida, serás redireccionado a una página donde podrás proseguir con la creación de tu cuenta.

6.  En los campos presentados en esta página, digita la siguiente información:

**Contraseña:** Escoge y digita una contraseña;

**Nombre de la Empresa**: Coloca el nombre de la empresa donde trabajas (campo opcional);

**Nombre de cuenta de Cloud:** Es generado automáticamente con base en tus respuestas al formulario. Es posible alterar este nombre borrándolo y digitando un nuevo nombre de usuario(a). Es importante guardar esta información, pues la vas a necesitar al momento de hacer login en **Oracle Cloud**;

**Región Local**: Selecciona tu región de origen.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/20.jpg)

7.  Con los campos debidamente diligenciados, haz clic en Continuar.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/21.jpg)

8. En el próximo formulario, debes digitar tu dirección, Número de identificación y número de teléfono. En seguida, haz clic en **Continuar**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/22.jpg)

9. En la siguiente pantalla de "Verificación de pago", haz clic en la opción **Añadir método de verificación de pago**.
![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/23.jpg)

10. Seguidamente, selecciona la opción **Credit Card** y digita los datos de tu tarjeta de crédito.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/24.jpg)

11. Cuando la verificación de tu tarjeta se haya concluído, podrás revisar y aceptar el contrato haciendo clic en la caja de selección localizada abajo del Contrato.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/25.jpg) 

12. Después de haber hecho esto, selecciona la opción **Iniciar mi evaluación gratuita**.

13. Recibirás un primer e-mail de Oracle notificando que la creación de tu cuenta está siendo procesada. Finalizada esta etapa, recibirás un segundo e-mail informando que el proceso fue concluído y que ya puedes acceder a tu cuenta.

### Preparando el ambiente

**Base de datos del curso**

Para que puedas realizar este curso, deberás descargar el siguiente [dataset](https://caelum-online-public.s3.amazonaws.com/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/datos_salud_final.csv "dataset")

**Observación**: La base de datos que estaremos empleando pertenece a una fuente externa. En ella, hallaremos una columna llamada sexo con los atributos *masculino* y *femenino*. Somos conscientes sobre el uso de las palabras sexo y género, y que este último no se resume tan solo a una clasificación binaria (masculino y femenino). Para el curso en cuestión, se evaluaron los factores que nos remiten a las características biológicas individuales y que marcan la diferencia para el equipo médico en el seguimiento de pacientes que pueden llegar a desarrollar la enfermedad de las arterias coronarias en la próxima década. De esta forma, resolvimos mantener la base de datos como se encuentra en su fuente original para no sesgar la información.

Ahora que accedimos al ambiente Oracle, vamos a aprender a configurarlo. Para ello, necesitamos seguir los siguientes pasos: La configuración de un *stack*, la configuración del ambiente de *Data Science* y la configuración de sesión del notebook. Entonces, te presento a continuación el paso a paso de la creación de cada etapa, recordando que es necesario que antes hayas realizado el login en tu cuenta de Oracle.

**Observación**: Las interfaces mostradas en las imágenes a continuación pueden variar con respecto a las que encontrarás cuando vayas a utilizar el ambiente Oracle.

**Configurando el Stack**

1. Haz clic en la esquina superior izquierda de la pantalla para abrir el menú. Después, selecciona al opción **Developer Services** y, en seguida, en la sección de **Resource Manager**, haz clic sobre **Stacks**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/1.jpg)

2. En **Stacks**, haz clic en la opción **Create Stack** que está localizada en la columna central de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/2.jpg)

3. Allí, selecciona la opción **Template** y, en el área de **Stack Configuration**, haz clic en **Select Template**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/3.jpg)

4. Ahora, vamos a seleccionar el **Template** que queremos utilizar. Para ello, accede a la segunda pestaña de esta pantalla, llamada **Service**. En seguida, escoge la opción **Data Science** que está localizada en la mitad de la pantalla, y para finalizar, haz clic en el botón **Select Template** que se encuentra en la parte inferior de la página.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/4.jpg)

5. Para continuar con la creación del *stack*, haz clic sobre **Next**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/5.jpg)

6. En la pantalla **Create Stack**, no es necesario marcar ninguna de las cajas de selección. Solamente debes hacer clic sobre **Next**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/6.jpg)

7. En la página de Review, puedes verificar un resumen de todo el proceso de creación realizado hasta el momento. No es necesario realizar ninguna selección en esta parte. Para continuar, basta hacer clic sobre **Create**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/7.jpg)

8. Con el *stack* creado, ahora es necesario accederlo. Para ello, haz clic sobre el nombre del *stack*. Este nombre se encuentra en la columna **Name** de la tabla presentada en el centro de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/8.jpg)

9. Ahora que el *stack* está seleccionado, es necesario aplicarle las configuraciones que se definieron hasta el momento. Para ello, debes hacer clic sobre **Apply**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/9.jpg)

**Configurando el servicio**

1. Haciendo clic sobre el menú sándwich, en la esquina superior izquierda, selecciona la opción **Analytics & AI** y, en donde aparece **Machine Learning**, haz clic en **Data Science**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/10.jpg)

2. En la pantalla **Projects**, haz clic en el botón **Create project**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/11.jpg)

3. En el área de **Create Project**, puedes llenar el campo **Name** con el nombre del proyecto y el campo **Description** con la descripción del mismo. En seguida, debes hacer clic en **Create**.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/12.jpg)

4. Con el proyecto creado, ahora es necesario accederlo. Para ello, basta hacer clic sobre el nombre del proyecto. El mismo se encuentra en la columna **Name** de la tabla presentada en la mitad de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/13.jpg)

### Configurando la sección del Notebook

**Observación**: La creación del notebook, puede demorar más de lo que se espera. En caso de ser así, no te preocupes, es completamente normal.

1. Con el proyecto seleccionado, vamos a avanzar a la última parte del proceso de configuración que es la creación de una sección del notebook. Para comenzar, debes hacer clic sobre el botón **Create notebook session**, localizado en la columna central de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/14.jpg)

2. En la pantalla de **Create notebook session**, debes seleccionar el notebook que deseas utilizar. En **Compute shape**, hacia el centro de la pantalla, nota que ya contamos con un notebook seleccionado por defecto. Pero, para visualizar las otras opciones de notebook, debes hacer clic sobre el botón gris de **Select** que se encuentra al lado derecho de la página.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/15.jpg)

3. En la página de **Select compute**, encontrarás máquinas con diferentes características pre-configuradas. Para seleccionar la misma máquina utilizada en el curso, haz clic en la opción Intel, localizada hacia la derecha de tu pantalla. En seguida, selecciona la tercera caja de selección denominada **VM Standard 2.4** y haz clic en el botón **Select**, en la esquina inferior izquierda de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/16.jpg)

4. Con la máquina seleccionada, ahora debes establecer el espacio de almacenamiento para ella. Para hacer esto, en el campo Block storage size (in GB) puedes digitar 50, que es el valor mínimo de almacenamiento que puedes utilizar. Posteriormente, en los dos campos de la sección de **Network resources** puedes hacer clic sobre las flechas localizadas en las esquinas de los campos y seleccionar las redes por defecto que aparecen (normalmente los nombres de ellas son algo semejante a **Data Science VCN** y **Data Science - Private**, respectivamente). Para finalizar la creación de la sección de notebook basta hacer clic sobre "Create" localizado en la esquina inferior izquierda de la pantalla.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/17.jpg)

### Para saber más: ¿Qué es un árbol de decisión?

Imagina que te estás sintiendo mal, pero no tienes idea de lo que podría ser. Al buscar ayuda médica, te hacen una serie de preguntas (¿Dolor de cabeza? ¿Fiebre? ¿Tos?...). Entonces, recibes un parecer informando cuál podría ser la causa de estos síntomas. En la situación presentada, se siguió el mismo principio utilizado en un estimador llamado árbol de decisión.

El árbol de decisión es uno de los modelos de previsión más sencillos, inspirado en la forma como los seres humanos tomamos las decisiones y posee una alta interpretabilidad, o sea, una comprensión fácil de los pasos que fueron realizados para lograr alcanzar el resultado final. Estos árboles pueden ser utilizados tanto para modelos de regresión, que tienen el objetivo de prever valores numéricos, como para modelos de clasificación, que tienen el objetivo de prever categorías.

Este puede ser representado gráficamente, de forma que cada una de las decisiones tomadas en el proceso puedan ser visualizadas. Los elementos principales del árbol de decisión son los nodos, las ramas y las hojas.

La estructura del árbol comienza con un nodo inicial, también llamado raíz. A partir de la raíz, se trazan ramificaciones que generan nuevos nodos y el proceso se repite para los nodos subsecuentes hasta llegar a una hoja. La hoja es un nodo especial y contiene la información de la respuesta, pudiendo tratarse de una categoría o de un valor previsto.

Cada rama representa una toma de decisión a partir de un valor o de una categoría de las variables explicativas, dividiendo el conjunto de datos en nodos que presentan datos con características cada vez más similares entre sí.

Para comprender estos conceptos, veamos un ejemplo.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/26.jpg)

En el ejemplo tenemos una orientación médica sobre covid-19 para que las personas practiquen o no el aislamiento. La raíz o el nodo inicial representa la pregunta si la persona tiene los síntomas de Covid-19, como aquellas preguntas realizadas por el(la) médico(a), mencionadas anteriormente. La pregunta es respondida a través de las ramas que parten de la raíz, separando a las personas que presentan los síntomas de quienes no los presentan. el nodo referente a las personas que tienen síntomas se trata de un nodo hoja, con la decisión final de aislamiento social. El nodo referente a las personas que no tienen síntomas se trata de un nodo interno, que pasa por una nueva pregunta, creando así nuevas ramas y nodos. El proceso se repite hasta que alcanza las decisiones finales.

Por lo tanto, el esquema consiste en un árbol de decisión, en el cual es posible detectar todas las elecciones que fueron tomadas para alcanzar las conclusiones. El algoritmo del computador seguirá estos mismos principios, tomando las decisiones con base en las variables explicativas.

### Para saber más: ¿Cómo funciona la matriz de confusión?

La **matriz de confusión** es una herramienta muy utilizada para evaluar modelos de clasificación de Machine Learning. Ella consiste en una matriz en que las filas representan los valores reales y las columnas representan los valores predichos. Cada espacio de la matriz pasa a ser un diagnóstico. La idea general es contabilizar la cantidad de veces que un determinado valor A es clasificado como valor B.

Para trabajar con un ejemplo, vamos a pensar en una lista de pacientes con síntomas de Covid-19, en la cual tú ejecutaste un modelo de predicción y obteviste la siguiente clasificación:

```python
valores_predichos = [1, 0, 0, 0, 1, 1, 0, 1, 1, 0]
```
Los valores reales de la clasificación de estos(as) mismos(as) pacientes son:
```python
valores_reales = [1, 0, 1, 0, 1, 1, 0, 1, 0, 1]
```
El valor `0` significa que el(la) paciente no está infectado(a) y `1` significa que está infectado(a) con Covid-19.

Analizando tan solo los valores de `valores_predichos` y `valores_reales`, se puede notar que el modelo presentó errores en la clasificación de algunas muestras. La matriz de confusión nos mostrará la frecuencia de clasificación para cada clase en nuestro modelo de la siguiente forma:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/27.jpg)

Cada uno de los valores de la matriz son identificados por un diagnóstico que, siguiendo el orden de las filas, corresponde a:

- **Verdadero Negativo (true negative - TN)**: Ocurre cuando el modelo clasifica la muestra de forma correcta. Por ejemplo, la persona no está infectada con Covid-19 y el modelo lo predijo de forma correcta.

- **Falso Positivo (false positive - FP):** El modelo clasifica la muestra de forma incorrecta. Por ejemplo, el(la) paciente no está infectado(a) con Covid-19 y el modelo predijo que sí estava. También se conoce como **Error de Tipo I**.

- **Falso Negativo (false negative - FN)**: El modelo clasifica la muestra de forma incorrecta. Por ejemplo, el(la) paciente está infectado(a) con Covid-19 y el modelo predijo que no estava. También se conoce como **Error de Tipo II**.

- Verdadero Positivo (true positive - TP): La clasificación de la muestra corresponde con el conjunto de datos reales. Por ejemplo, la persona está infectada con Covid-19 y el modelo lo predijo de forma correcta.

De esta forma, para el ejemplo de pacientes con síntomas de Covid, tendríamos:

TN = 3

FP = 1

FN = 2

TP = 4

A través de la identificación de los diagnósticos, es posible extraer métricas de la matriz de confusión que son importantes para evaluar qué tan bien el modelo está clasificando los datos. Las principales métricas que pueden ser extraídas de la matriz de confusión son:

Exactitud/Accuracy: Evalúa la proporción de aciertos con relación a todas las previsiones realizadas. Esta se obtiene sumando la diagonal principal de la matriz y dividiendo entre la suma de todos los valores.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/28.jpg)

Para el ejemplo de pacientes con síntomas de Covid, tendríamos:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/29.jpg)

Sensibilidad/Recall: Evalúa la proporción de verdaderos positivos entre todos los valores positivos reales. Esta se obtiene dividiendo los verdaderos positivos entre la suma de los positivos reales.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/30.jpg)

Para el ejemplo de pacientes con síntomas de Covid, tendríamos:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/31.jpg)

Precisión/Precision: Evalúa la proporción de verdaderos positivos entre las predicciones dadas como positivas por el modelo. Esta se obtiene dividiendo los verdaderos positivos entre la suma de las previsiones positivas.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/32.jpg)

Para el ejemplo de pacientes con síntomas de Covid, tendríamos:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/33.jpg)

Especificidad/Specificity: Evalúa la proporción de verdaderos negativos entre todos los valores negativos reales. Esta se obtiene dividiendo los verdaderos negativos entre la suma de los negativos reales.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/34.jpg)

Para el ejemplo de pacientes con síntomas de Covid, tendríamos:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/35.jpg)

F1 Score: Es un equilibrio entre la sensibilidad y la precisão, siendo la media harmónica entre las dos métricas.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/36.jpg)

Para el ejemplo de pacientes con síntomas de Covid, tendríamos:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/37.jpg)

El siguiente código sirve para construir un informe con las métricas que fueron explicadas para el ejemplo de los pacientes con Covid-19:

```python
from sklearn.metrics import classification_report
valores_reales = [1, 0, 1, 0, 1, 1, 0, 1, 0, 1]
valores_predichos = [1, 0, 0, 0, 1, 1, 0, 1, 1, 0]
target_names = ['no infectado', 'infectado']
print(classification_report(valores_reales, valores_predichos, target_names=target_names))
```
Output:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/38.jpg)

Adicionalmente, puedes verificar el código que se utilizó para generar la matriz de confusión mostrada al principio de esta sección, en el siguiente [repositorio de GitHub](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/blob/main/matriz_de_confusion.ipynb "repositorio de GitHub").

### Para saber más: ¿Qué son los hiperparámetros?

Cada uno de los modelos de Machine Learning posee un comportamiento distinto para prever los resultados utilizando métodos matemáticos y computacionales. El comportamiento de un modelo dependerá de constantes, parámetros o características para que la fórmula matemática o el procedimiento computacional se comporte de una manera diferente.

Estos argumentos que controlan el comportamiento de un modelo de Machine Learning son conocidos como **hiperparámetros**. Al alterar el valor de estos parámetros, alteramos también el desempeño del modelo, una vez que, para cada conjunto de datos diferentes, es necesario un ajuste diferente de los hiperparámetros para que un modelo se pueda adaptar mejor a este conjunto.

El árbol de decisión, por ejemplo, posee una característica llamada profundidad que se refiere a la longitud del camino más largo desde la raíz hasta una hoja del árbol. Una profundidad muy grande permite que el modelo se ajuste mejor a los datos y clasifique los registros de una forma más precisa. Por otro lado, una profundidad muy pequeña puede resultar en menos ramificaciones y que, como consecuencia, los datos no sean clasificados de forma correcta, dado que el modelo no logró “decidir” cómo clasificar los datos presentados, por ejemplo.

De este modo, debe existir un equilibrio en el valor de la profundidad, una vez que si el modelo se ajusta perfectamente a los datos de entrenamiento, no será capaz de generalizar para un conjunto de datos nunca visto, quedando sobreajustado (overfitting).

El modelo de árbol de decisión utilizado para la clasificación, que está disponible en la biblioteca [scikit-learn](https://scikit-learn.org/stable/ "scikit-learn"), posee el parámetro que controla la característica mencionada anteriormente, es decir, la profundidad máxima o `max_depth`, que es el hiperparámetro que controla la profundidad del árbol. A través de la [documentación del DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html "documentación del DecisionTreeClassifier"), podemos verificar, dentro de los argumentos de la función, los hiperparámetros de el siguiente modelo:

```python
class sklearn.tree.DecisionTreeClassifier(*, criterion='gini', splitter='best', max_depth=None, min_samples_split=2, min_samples_leaf=1, min_weight_fraction_leaf=0.0, max_features=None, random_state=None, max_leaf_nodes=None, min_impurity_decrease=0.0, class_weight=None, ccp_alpha=0.0)
```
Otro hiperparámetro que puede ser controlado en el árbol de decisión es `min_samples_leaf`, que está relacionado con la cantidad mínima de muestras de los datos de entrenamiento para cada hoja. Esto significa que, si hay un nodo en el árbol con la cantidad de registros definida en `min_samples_leaf,` este nodo no puede ser dividido en otros nodos.

Al emplear un modelo sin definir un valor para los hiperparámetros, los valores por defecto serán utilizados. Cabe destacar que, la mayoría de las veces, estos hiperparámetros configurados por defecto no son la mejor opción para los datos que están siendo usados.

### Haga lo que hicimos

Llegó la hora de poner manos a la obra. Tú vas a hacer parte del equipo de científicos de datos que va a construir un modelo de clasificación de pacientes que desarrollarán, o no, EAC (Enfermedad de las Arterias Coronarias) en la próxima década. Para ello, te invito a entrenar algunas variaciones de modelo y comparar los resultados para encontrar tu mejor combinación.

Si lo deseas, puedes usar algunas de las siguientes estrategias:

- Cambiar el algoritmo;
- Seleccionar features;
- Optimizar los hiperparámetros.

### Lo que aprendimos

En esta aula, aprendimos a:

- Crear un Jupyter notebook en el ambiente **Oracle Cloud**;
- Cargar la base de datos utilizando **Oracle ADS;**
- Crear un modelo utilizando **Sklearn;**
- Evaluar el modelo con las métricas de exactitud y la matriz de confusión;
- Mejorar el modelo explorando la optimización de hiperparámetros y selección de features;
- Identificar las dificultades de una exploración manual de modelos.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior.

[Descargue los archivos en Github](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/blob/aula-2/aula-2.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/archive/refs/heads/aula-2.zip "aquí") para descargarlos directamente.

### Para saber más: Grid Search y Random Search

Cada modelo posee diversos hiperparámetros que controlan su comportamiento y que afectan directamente el desempeño. La elección de cada uno de estos parámetros, de forma manual, demanda mucho tiempo y casi nunca traerá el mejor resultado posible. Siempre que ejecutamos un modelo sin informar los parámetros, los valores default (por defecto) son utilizados, y a veces, no es nuestra mejor alternativa.

Entonces, encontrar los parámetros que convierten al modelo en la mejor opción posible es una etapa crucial en el desarrollo de una aplicación de Machine Learning. Para que este trabajo no sea realizado de forma manual, existen dos soluciones que pueden ser utilizadas para probar diversos valores para los hiperparámetros y comparar los resultados, volviendo la elección del modelo un proceso más simple.

La primera solución es **Grid Search** (búsqueda en cuadrícula). Esta consiste en recorrer todos los valores de hiperparámetros dentro de las opciones que son escogidas por la persona científica de datos. Las combinaciones de los hiperparámetros son probadas en el entrenamiento del modelo y los resultados son comparados, siendo posible encontrar la mejor combinación dentro de todas las que se encuentran disponibles.

El primer paso es seleccionar los valores probables de los parámetros y almacenarlos en un diccionario, donde las llaves son los nomebres de los parámetros y los valores son las posibilidades que serán exploradas.

```python
espacio_de_parametros = {
  "max_depth" : [3, 5],
  "min_samples_leaf" : [32, 64, 128]
}
```

Es necesario importar `GridSearchCV` de la biblioteca **sklearn**. Ahora bien, los argumentos de la función que necesitamos digitar son: El modelo, en este caso, el árbol de decisión; y el `param_grid`, que es el diccionario con los valores que serán probados.

```python
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import GridSearchCV
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer(as_frame=True)
x = data['data']
y = data['target']

modelo = DecisionTreeClassifier()
busqueda = GridSearchCV(modelo, param_grid=espacio_de_parametros)
busqueda.fit(x, y)
busqueda.best_params_
```

La segunda solución es **Randomized Search** (búsqueda aleatoria), que selecciona aleatoriamente algunas combinaciones de hiperparámetros, diferente de Grid Search que realiza la búsqueda con todas ellas. Las combinaciones escogidas por Randomized Search son, entonces, probadas en el entrenamiento del modelo y los resultados son comparados, siendo posible encontrar la mejor combinación dentro de aquellas aleatoriamente escogidas. El número de iteraciones `n_iter` define cuántas combinaciones deben ser escogidas por el método.

```python
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import GridSearchCV
from sklearn.datasets import load_breast_cancer

data = load_breast_cancer(as_frame=True)
x = data['data']
y = data['target']

modelo = DecisionTreeClassifier()
n_iter = 3

busqueda = RandomizedSearchCV(modelo, param_distributions=espacio_de_parametros, n_iter = n_iter)

búsqueda.fit(x, y)
busqueda.best_params_
```
¿Cuál de las soluciones debemos escoger?

Consideración	GridSearch	RandomSearch
- Punto Positivo	Explora todas las combinaciones escogidas, generando el mejor resultado posible dentro de las posibilidades	Al explorar algunas posibilidades de forma aleatoria, demanda de menos tiempo y es más viable en este punto que Grid Search, obteniendo un resultado satisfactorio
- Punto Negativo	Al explorar todas las combinaciones, demanda de mucho tiempo y puede que no sea viable computacionalmente	No existe la certeza de que el resultado obtenido sea el mejor posible, por no explorar todas las posibilidades

### Para saber más: Random Forest

Los árboles de decisión poseen una característica que les impide ser considerados la herramienta ideal: La imprecisión. Esto quiere decir que ellos funcionan muy bien con los datos utilizados para crearlos, pero no tan bien para realizar la clasificación de nuevas muestras. El bosque aleatorio (random forest) busca resolver este problema de overfitting (sobreajuste) que ya conocemos.

El algoritmo Random Forest se basa en la utilización de diversos árboles de decisión para encontrar el resultado. Como el árbol de decisión puede ser usado para la regresión y la clasificación, el Random Forest también puede ser utilizado para los dos tipos de problema. Vamos a concentrarnos aquí en los problemas de clasificación. Para realizar la previsión, el algoritmo crea diversos árboles de decisión en el conjunto de datos y realiza la predicción para cada uno de ellos. Internamente, hace una “votación” para analizar cual predicción es la más frecuente y, entonces, esta predicción se convierte en la respuesta final.

Si se utilizara la misma base de datos en la creación de todos los árboles de decisión del Random Forest, las respuestas de cada uno de los árboles serían iguales y el resultado de la votación sería idéntico al realizar un único modelo de árbol de decisión. Para evitar este problema, se emplea una técnica conocida como **bootstrapping**.

Esta técnica consiste en tomar muestras con reposición del conjunto de datos original, y cada uno de estos muestreos será utilizado para un árbol de decisión diferente. El muestreo con reposición significa que, al sortear un elemento, eso no nos impide que el mismo aparezca en sorteos futuros. De esta forma, los árboles tendrán resultados distintos, una vez que son entrenados con conjuntos de datos diferentes. En el muestreo con repetición, las observaciones de la tabla podrán quedar por fuera y otras estarán duplicadas.

Para recapitular los pasos:

- Al utilizar el modelo Random Forest, podemos escoger la cantidad de árboles de decisión que serán creados. En Scikit Learn, podemos controlar la cantidad de los mismos a través del parámetro `n_estimators`.

- El modelo creará un conjunto de datos para cada árbol a partir del método bootstrapping en la base de datos original, resultando en un resultado distinto para cada uno de los árboles.
- Finalmente, será realizada una votación entre los resultados de los árboles y la clase predicha en la mayoría de los árboles será escogida como la clasificación del modelo Random Forest.

### Haga lo que hicimos

¡Hola, científico de datos! Ahora llegó el momento de que explores la herramienta **AutoML** a través de sus parámetros y tratando de comprender cómo podemos leer los resultados que ella encontró.

Los pasos son:

- Transformar nuestros datos en `ADSData`;
- Definir los modelos que van a ser explorados por `AutoML`;
- Ejecutar los experimentos de `AutoML`.

### Haga lo que hicimos

¡Hola, científico de datos! Ahora llegó el momento de que explores la herramienta **AutoML** a través de sus parámetros y tratando de comprender cómo podemos leer los resultados que ella encontró.

Los pasos son:

- Transformar nuestros datos en `ADSData`;
- Definir los modelos que van a ser explorados por `AutoML`;
- Ejecutar los experimentos de `AutoML`.

### Opinión del instructor

¡Te felicito por seguir los pasos del aula! Ahora que **AutoML** encontró el mejor modelo, el papel de la persona científica de datos es el de reflexionar en los análisis realizados y entender cuál es el mejor modelo. Te invito a explorar las diversas funcionalidades para entender los experimentos hechos por **AutoML**.

Los comandos para explorar los experimentos son:

- `print_trials()`
- `visualize_algorithm_selection_trials()`
- `visualize_feature_selection_trials()`
- `visualize_tuning_trials()`

### Lo que aprendimos

En esta aula, aprendimos a:

- Utilizar **AutoML** de Oracle ADS;
- Transformar los datos en tipo `ADSData`;
- Entender de qué manera **AutoML** realiza la exploración de modelos y leer la tabla de resultados de **AutoML**;
- Leer la tabla de resultados del modelo seleccionado por **AutoML** y leer el gráfico de selección de features;
- Comparar los planteamientos entre la exploración manual de modelos y la exploración con **AutoML**, entendiendo los beneficios del abordaje de **AutoML**.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior.

[Descargue los archivos en Github](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/blob/aula-3/aula-3.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/archive/refs/heads/aula-3.zip "aquí") para descargarlos directamente.


### Para saber más: Precision Recall x Curva ROC

Para evaluar los modelos de clasificación, además de las métricas que se obtienen a partir de la matriz de confusión, podemos utilizar curvas que consideran el desempeño del modelo en diferentes puntos de corte, conocidos como “thresholds”. Vamos a entender mejor en qué consisten estos puntos de corte.

En la construcción de un modelo de clasificación, la predicción de una clase está unida a una probabilidad. Imagina que tenemos una variable target con dos posibilidades (0 o 1). Si un modelo clasifica una observación como 1, significa que hay una probabilidad de x% de que aquella observación sea de la clase 1.

El punto de corte es un valor de probabilidad en el cual, si la probabilidad de predicción es mayor que este valor, se atribuye dicha observación a la clase 1. Si fuere menor, se atribuye dicha observación a la clase 0. A medida que el punto de corte varía, los resultados obtenidos en la clasificación se tornan diferentes, haciendo que el modelo acierte más de una clase a cambio de errar más otra.

A través de un ejemplo, quedará evidente cómo los puntos de corte modifican las métricas de la matriz de confusión. En la siguiente imagen están representadas la precisión y la sensibilidad. En ella están definidos 3 puntos de corte en 25%, 50% y 75%, representados por las flechas verticales. Los ceros y unos son los valores reales de las clases y la clasificación será realizada a través de los puntos de corte. Los valores a la izquierda de la flecha serán clasificados como 0 y los valores a la derecha serán clasificados como 1 por el modelo.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/39.jpg)

En el primer punto de corte tenemos 3 valores, a la izquierda, clasificados como 0 y 9 valores, a la derecha, como 1. La precisión es dada por 5/(5+4) = 55,5%, mostrando que 5 valores fueron clasificados correctamente como 1, entre 9 valores totales clasificados como 1. La sensibilidad está dada por 5/(5+1) = 83%, indicando que 5 valores fueron clasificados correctamente como 1, entre 6 valores reales 1 en el conjunto de datos.

En el segundo punto de corte tenemos 6 valores, a la izquierda, clasificados como 0 y 6 valores, a la derecha, clasificados como 1. La precisión está dada por 4/(4+2) = 66,6%, apuntando que 4 valores fueron clasificados correctamente como 1, entre 6 valores totales clasificados como 1. La sensibilidad está dada por 4/(4+2) = 66,6%, demostrando que 4 valores fueron clasificados correctamente como 1, entre 6 valores reales 1 en el conjunto de datos. El mismo raciocínio se puede aplicar para el último punto de corte, resultando en valores diferentes para las métricas.

Para cada punto de corte, una matriz de confusión puede ser creada y las métricas pueden ser extraídas en una tabla, en la cual cada fila representa un punto de corte con sus respectivas métricas. De esta tabla, pueden ser construídos gráficos para el análisis del modelo.

#### Curva Precision x Recall

La curva de precision (precisión) por recall (sensibilidad) es una de las formas de evaluar que tan bien el modelo está. Esta curva es preferible cuando los datos están desbalanceados o cuando los falsos positivos sean más importantes que los falsos negativos. Para construir la curva, se necesita utilizar las métricas Precision y Recall que se obtienen a partir de la matriz de confusión, utilizando diferentes puntos de corte.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/40.jpg)

El gráfico del ejemplo anterior muestra dos curvas de Precision x Recall, una para el modelo Random Forest y otra para el Decision Tree. Podemos identificar que, con el aumento del Recall en el modelo Random Forest, la Precisión se mantiene igual, presentando una caída en un valor alto de Recall. O sea, en cuanto el modelo aumenta la cantidad de aciertos de valores positivos, no presenta ningún error de previsión para previsiones positivas hasta que llegue a una cantidad de aciertos muy grande, en el cual atribuye algunas previsiones que debían ser positivas para resultados negativos.

Para el modelo Decision Tree, a medida que el Recall aumenta, la Precisión disminuye. En otras palabras, a medida que el modelo aumenta la cantidad de aciertos de valores positivos, la tasa de error de previsión para previsiones positivas comienza a caer, hasta llegar a un punto en que el error de previsión aumenta drásticamente.

#### Curva ROC

La curva ROC (Receiver Operating Characteristic) es una de las herramientas utilizadas para evaluar a un clasificador de forma muy semejante a la curva precision x recall. Sin embargo, muestra la relación entre la tasa de los valores realmente positivos y la tasa de los falsos positivos para varios puntos de corte diferentes. La tasa de los valores realmente positivos representa la tasa de muestras positivas que son correctamente clasificadas, recibiendo el nombre de recall, o sensibilidad, y es calculada de acuerdo con la siguiente expresión:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/30.jpg)

Ya la tasa de falsos positivos representa la tasa de muestras positivas que son clasificadas erróneamente y es calculada de acuerdo con la expresión:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/41.jpg)

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/42.jpg)

Existe una línea de referencia en la diagonal del gráfico que corresponde a una línea de base y representa el caso en el cual el clasificador identifica aleatoriamente las clases. A través de cada una de las curvas, es posible extraer una métrica conocida como AUC (Area Under the Curve) o el área bajo la curva. Esta métrica varía de 0 a 1 y cuanto mayor sea su valor, el modelo será mejor evaluado.

Pero, ¿Cómo podemos interpretar este gráfico? Se percibe que la línea representando el clasificador **RandomForestClassifier** crece más rápidamente hasta alcanzar el valor máximo de True Positive Rate (o recall). Esto significa que el modelo alcanza 100% de clasificación correcta de los positivos y permanece hasta alcanzar el punto (1, 1) del gráfico. Este punto nos dice que el modelo tiene 100% de True Positive Rate y 100% de False Positive Rate (tasa de verdaderos positivos y de falsos negativos, respectivamente), indicando que el modelo clasifica todas las muestras positivas correctamente y todas las muestras que no son positivas fueron incorrectamente clasificadas.

Entonces, cuando el modelo llega al 100% de True Positive Rate y permanece allí hasta alcanzar el 100% de False Positive Rate, el modelo logra clasificar todas las muestras positivas de forma correcta independientemente del threshold adoptado. Por otro lado, la línea representando el clasificador **DecisionTreeClassifier** demora más para llegar al 100% de True Positive Rate. Pero, cuando llega al valor máximo, permanece igual a la del clasificador anterior.

Este pequeño atraso del **DecisionTreeClassifier** con respecto al **RandomForestClassifier** resulta en áreas diferentes, que son las AUCs para cada clasificador. El primero tuvo una AUC de 0.914 y el segundo, 0.979. Por lo tanto, este último es el mejor clasificador.

### Para saber más: Gráfico de Gain x Lift

Además de los gráficos de las curvas ROC y de Precision x Recall, es posible evaluar los modelos de clasificación a través del gráfico de Ganancia (Cumulative Gain Chart) y del gráfico de Elevación (Lift Chart). Mientras que la curva ROC y Precision x Recall trabajan con el conjunto entero de datos de una sola vez, los gráficos de Gain o Lift evalúan el desempeño del modelo en cada porcentual del conjunto de datos y lo compara con la recta de base, que representa el desempeño si no se utiliza ningún modelo de previsión.

#### Gráfico de Ganancia (Gain Chart)

En la construcción de un modelo de clasificación, la predicción de una clase está unida a una probabilidad. Imagina que tenemos una variable target con dos posibilidades (0 o 1). Si un modelo clasifica una observación como 1, significa que hay una probabilidad de x% de que aquella observación sea de la clase 1. La probabilidad de cada uno de los registros es importante para la construcción del gráfico de Ganancia.

Los pasos para la construcción de este tipo de gráfico son:

1. Encontrar la probabilidad de clasificación de las clases para todos los registros utilizando el modelo de clasificación.
2. Ordenar el conjunto de datos de forma descendiente de acuerdo con la probabilidad de ser de la clase 1.
3. Dividir el conjunto de datos que está ordenado en secciones iguales.
4. Realizar el conteo de valores reales de la clase 1 en cada una de las partes, haciendo la suma cumulativa hasta el último grupo, que tendrá la cantidad total de valores reales de la clase 1.
5. Dividir el resultado cumulativo de cada sección por el valor total de valores reales de la clase 1.
Vamos a entender estos pasos a través de un ejemplo. Supon que tenemos un conjunto de datos de 20 pacientes y construimos un modelo para prever si el(la) paciente tiene covid (clase 1) o no (clase 0). La siguiente tabla muestra: la probabilidad de que los pacientes tengan covid (clase 1) según la previsión del modelo; y la clase verdadera representa la situación real del paciente.

Paciente | Probabilidad | Clase verdadera
---------|-----------------
A | 61% | 0
B | 79% | 1
C | 75% | 1
D | 70% | 1
E | 81% | 1
F | 52% | 0
G | 88% | 1
H | 49% | 0
I | 35% | 1
J | 58% | 0
K | 80% | 1
L | 77% | 0
M | 87% | 0
N | 65% | 1
O | 45% | 0
P | 75% | 0
Q | 24% | 0
R | 76% | 1
S | 69% | 0
T | 71% | 1

Ahora ordenamos el conjunto de datos, en orden decreciente, de acuerdo con la probabilidad de ser de la clase 1, resultando en la siguiente tabla:

Paciente | Probabilidade | Clase verdadera
------------------------|-----------------------
G | 88% | 1
M | 87% | 0
E | 81% | 1
K | 80% | 1
B | 79% | 1
L | 77% | 0
R | 76% | 1
C | 75% | 1
P | 75% | 0
T | 71% | 1
D | 70% | 1
S | 69% | 0
N | 65% | 1
A | 61% | 0
J | 58% | 0
F | 52% | 0
H | 49% | 0
O | 45% | 0
I | 35% | 1
Q | 24% | 0


Con la tabla ordenada, vamos a dividir el conjunto de datos en 10 partes iguales. Como la tabla posee 20 filas, cada una de las partes tendrá 2 filas. La frecuencia de valores 1 verdaderos será contada en cada una de las partes, siendo posible extraer la frecuencia acumulada. A través de esta, es posible dividir cada uno de los resultados acumulados por el valor total de valores reales 1, que en el caso del ejemplo es 10.

Los resultados pueden ser sumarizados en una tabla:

Total de pacientes | Frecuencia acumulada de valores 1 | Tasa de la clase verdadera
----------------|-------------------------
2 | 1 | 10%
4 | 3 | 30%
6 | 4 | 40%
8 | 6 | 60%
10 | 7 | 70%
11 | 8 | 80%
14 | 9 | 90%
16 | 9 | 90%
18 | 9 | 90%
20 | 10 | 100%

El gráfico de ganancia tendrá, en el eje x, el porcentual del conjunto de datos ordenados y, en el eje y, la tasa de la clase verdadera obtenida a través de los pasos anteriormente explicados. La línea de base es una recta que tiene el mismo valor para x y y y representa el caso en el cual no es utilizado ningún modelo.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/43.jpg)

#### Gráfico de Elevación (Lift Chart)

Al dividir los valores de la curva del modelo por los valores de la línea de base del gráfico de ganancia, podemos construir una tabla que sirve de referencia para el gráfico de elevación. Para los datos del ejemplo mostrados anteriormente, tendremos la siguiente tabla:

Curva del modelo (Gain chart) | Línea de base (Gain chart) | Elevación
------------------------|-------------------
0% | 0% | -
10% | 10% | 1
30% | 20% | 1,5
40% | 30% | 1,333333
60% | 40% | 1,5
70% | 50% | 1,4
80% | 60% | 1,333333
90% | 70% | 1,285714
90% | 80% | 1,125
90% | 90% | 1
100% | 100% | 1

El gráfico de elevación tiene en el eje x el porcentual del conjunto de datos ordenados. En el eje y, presenta la elevación y el cálculo de la división de la curva del modelo por la línea de base del gráfico de ganancia. La línea de base del gráfico de elevación es una recta constante con valor igual a 1.

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/44.jpg)

De forma semejante a el AUC en la curva ROC, en los gráficos de ganancia y elevación cuanto mayor sea el área entre la curva del modelo y la línea de base, es mejor evaluado el modelo. Ello indica que el modelo logró un desempeño mucho superior en relación a la no utilización de modelos de clasificación. En el mismo gráfico, es posible realizar la visualización de diferentes modelos y compararlos, facilitando su elección.

### Para saber más: Overfitting

El objetivo de los modelos supervisados de Machine Learning es realizar la previsión de valores o clases con base en algunas características. Para que esto sea posible, se emplea una base de datos con sus características y la variable target para el entrenamiento de dicho modelo. El **Overfitting** va a ocurrir cuando el modelo se adecúa demasiado a las particularidades del conjunto de entrenamiento por ser muy complejo, pero no es capaz de generalizar cuando posee nuevos datos. En caso de que sea muy sencillo, el modelo puede no lograr capturar la variedad en los datos ni ajustarse al conjunto de datos utilizado para entrenamiento.

Existen algunas posibles soluciones para tratar el overfitting, como:

- Simplificar el modelo, escogiendo un algoritmo más simple que posea menos parámetros para ajustar.
- Recolectar más datos para realizar el entrenamiento del modelo.
- Remover los ruidos en los datos, como valores extremos, outliers, valores incorrectos y los valores nulos. El modelo puede utilizar estos datos para realizar el ajuste y, con ello, provocar el overfitting.

Para analizar como este *sobreajuste* se presenta en un modelo de clasificación, vamos a observar el siguiente gráfico:

![](https://caelum-online-public.s3.amazonaws.com/ESP+-+1903+-+Machine+Learning+con+Oracle+ADS%3A+productividad+en+la+creaci%C3%B3n+de+modelos/45.jpg)

Percibimos, al inicio del gráfico, una baja complejidad del modelo: La exactitud del entrenamiento y de prueba son bajas. Conforme la complejidad aumenta, al evaluar la exactitud en el conjunto de datos de entrenamiento, obtenemos un valor cada vez mayor, indicando aciertos cada vez mayores. Esta misma observación aplica para el conjunto de datos de prueba: Al aumentar la complejidad del modelo, la exactitud aumenta para los datos nuevos no utilizados en el entrenamiento. Sin embargo, a partir de cierto punto, la exactitud en los datos de prueba comienza a disminuir y la exactitud de los datos de entrenamiento continúa aumentando, pero de una forma menos significativa.

Esta caída en el rendimiento del modelo para los datos de prueba indica el sobreajuste del modelo a los datos de entrenamiento. Esto significa que el modelo aprendió de forma minuciosa los patrones de datos utilizados en el aprendizaje y, al aplicar este conocimiento a los datos de prueba, acaba realizando una previsión incorrecta de los nuevos registros, porque estos no poseen características idénticas a las de los datos de entrenamiento.

### Desafío: explorando parámetros de AutoML

Podemos cambiar algunos parámetros de AutoML para encontrar un modelo diferente del propuesto en el aula. Te desafío a visitar la [documentación](https://docs.oracle.com/en-us/iaas/tools/ads-sdk/latest/ads.automl.html?highlight=automl#ads.automl.provider.OracleAutoMLProvider.train "documentación") del método `train` de Oracle AutoML y explorar más a fondo parámetros.

Aquí te dejo algunas sugerencias:

- `model_list`: Utilizar la lista completa de algoritmos de clasificación soportados por Oracle AutoML;
- `score_metric`: Utilizar la métrica F1 score, explicada en la sección **Para saber más: Matriz de confusión**.
- `time_budget`: Utilizar el valor 0 en este parámetro para que AutoML explore más posibilidades.

### Haga lo que hicimos

Llegó el momento de comparar el modelo creado manualmente y el que fue creado por **Auto ML**. Para ello, debemos crear diversas métricas, seguir las buenas prácticas y emplear [ADSEvaluator](https://docs.oracle.com/en-us/iaas/tools/ads-sdk/latest/ads.evaluations.html?highlight=adsevaluator#ads.evaluations.evaluator.ADSEvaluator "ADSEvaluator").

Para garantizar una comparación de calidad, entrenamos nuevamente los dos modelos y también necesitamos transformarlos en un **ADS Mode**l, la clase que representa el modelo en el contexto de **Oracle ADS**.

### Opinión del instructor

Luego de crear el **ADSEvaluator**, vamos a utilizar los métodos `show_in_notebook()` y el atributo `metrics`, para tener acceso a diversas métricas:

- Precisión X Sensibilidad;
- Curva ROC, Ganancia;
- Elevación y Matriz de confusión;
- Exactitud;
- Precisión;
- Sensibilidad;
- AUC; y
- Hamming Distance.

Utilizando estas métricas, podemos analizar, entre los modelos creados, cuál es el mejor modelo y cómo este se desempeña para resolver el problema de clasificación de EAC.

### Lo que aprendimos

En esta aula, aprendimos a:

- Crear el objeto **ADSEvaluator**, responsable por generar métricas de comparación entre los modelos;
- Explorar las métricas gráficas para comparar los modelos, Precisión X Sensibilidad, Curva ROC, Ganancia, Elevación y Matriz de confusión;
- Explorar las métricas numéricas para comparar los modelos, Exactitud, Precisión, Sensibilidad, AUC, Hamming Distance;
- Evaluar la calidad del modelo en los datos de entrenamiento y de prueba;
- Utilizar las métricas para identificar y tratar las posibles causas de overfitting;

#### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior.

[Descargue los archivos en Github](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/blob/aula-4/aula-4.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/archive/refs/heads/aula-4.zip "aquí") para descargarlos directamente.

### Haga lo que hicimos 

Después de que seleccionamos el mejor modelo para colocarlo en producción, necesitamos, antes de ir más allá, garantizar que podemos explicar su funcionamiento y sus decisiones. Para ello, vamos a utilizar la herramienta [ADSExplainer](https://docs.oracle.com/en-us/iaas/tools/ads-sdk/latest/ads.explanations.html?highlight=adsexplainer#ads.explanations.explainer.ADSExplainer "ADSExplainer"). Ahora, introduce en esta herramienta tu modelo final y tus datos de entrenamiento y prueba.

#### Opinión del instructor

Una vez creado el modelo **ADSExplainer**, es importante analizar, en las decisiones de tu modelo: El contexto global y el impacto de cada una de las features. Aún en el contexto global, trata de entender la distribución de los datos de una feature y el efecto que tiene con relación a la probabilidad de clasificación del modelo. También, puedes analizar el contexto local y comprender cómo fue realizada la clasificación de un(a) paciente individual, observando cómo cada una de las características de esa persona determinó su clasificación.

Los principales métodos para acceder a esta información son:

- `global_explanation.compute_partial_dependence()`
- `global_explanation.compute_feature_importance()`
- `local_explanation.explain()`

### Lo que aprendimos

En esta aula, aprendimos a:

- Crear el objeto **ADSExplainer**, responsable por generar las explicaciones del modelo.
- Construir e interpretar el gráfico PDP para analizar la relación entre las variables.
- Explicar cómo una determinada muestra es clasificada por el modelo, a través del método `local_explanation()`.
- Reflexionar sobre la importancia de la gobernanza de datos y la Ley General de Protección de Datos.

### Proyecto del aula anterior

¿Comenzando en esta etapa? Aquí puedes descargar los archivos del proyecto que hemos avanzado hasta el aula anterior.

[Descargue los archivos en Github](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/blob/aula-5/aula-5.ipynb "Descargue los archivos en Github") o haga clic [aquí](https://github.com/alura-es-cursos/1903-machine-learning-con-oracle-ads-productividad-en-la-creacion-de-modelos/archive/refs/heads/aula-5.zip "aquí") para descargarlos directamente.

### Para saber más: explorando los archivos del Artefacto

Cuando utilizamos el comando `prepare`, este genera diversos archivos que son la representación de nuestro modelo fuera del notebook.

Vamos a entender el propósito de cada uno de ellos:

**'input_schema.json'**

El archivo de input guarda el esquema de datos de entrada que son utilizados para llamar el método predict de nuestro modelo. Con este archivo, logramos identificar el nombre de las características utilizadas por el modelo, el orden en que ellas aparecen y el tipo de ellas. Toda esta información es esencial para crear un software que pueda interactuar con nuestro modelo, por ejemplo una API.

**'output_schema.json'**

Es un archivo que guarda el esquema de datos de salida, o sea, el nombre de la variable de salida, la clasificación de su modelo. También es muy útil en una integración con una API.

**model.onnx**

Este es el archivo que, de hecho, es el objeto en nuestro modelo serializado. El ONNX es una representación de modelos de código abierto.

**score.py**

Es un script Python que realiza toda la parte de cargar y utilizar el modelo para hacer las previsiones y la transformación de los datos. Logramos realizar todas las operaciones manualmente, pero este script facilita este proceso, pues vamos a necesitar solamente llamar algunas funciones para poder volver a utilizar nuestro modelo.

**´onnx_data_transformer.json´**

Este carga toda la información para crear un transformador responsable por convertir los objetos de los datos de entrada y salida del modelo en el formato ONNX utilizado también para guardar el modelo.

**‘runtime.yaml’**

Es el archivo que guarda toda la información sobre las configuraciones y versiones del ambiente que generaron este artefacto. Dicha información es muy importante para construir un nuevo ambiente que sea capaz de ejecutar el modelo sin ningún problema de versión o falta de alguna dependencia.

Cuando utilizamos herramientas que facilitan nuestro trabajo, siempre es importante entender como estas funcionan. De esta manera, te recomiendo que continúes explorando estos archivos y trates de entender mejor su contenido para que puedas identificar y solucionar cualquier problema que se te pueda presentar.

### Para saber más: utilizando las variables de entorno

Cuando guardamos el artefacto en el catálogo, omitimos algunos parámetros para, así, utilizarlos por defecto. Pero es importante saber cómo obtener esta información.

El método `save` de **ADSModel**, por ejemplo, utiliza la información de los ID del proyecto y de compartimiento. Por defecto, este utiliza los valores de tu archivo `config`, pero tú podrías, por ejemplo, necesitar colocar tu modelo en un proyecto diferente. Una de las maneras de descubrir la información que necesitas para realizar este cambio es utilizando las variables de entorno.

Las variables de entorno son una funcionalidad del sistema operativo que nos permite guardar la información tal como los números de identificación, los caminos de los archivos e incluso contraseñas. Este recurso es muy interesante, pues cualquier programa que necesite de alguna información y tenga conocimiento de la llave o nombre de la variable puede hacer esta solicitud para el sistema operativo y este va a retornar el valor.

Observemos algunos ejemplos:

Podemos encontrar el ID de nuestro proyecto a través de la llave “PROJECT_OCID”, o también el ID del compartimiento a través de la llave “NB_SESSION_COMPARTMENT_OCID”. Para solicitar esta información del OS debemos importar la biblioteca os:

```python
import os
```

Posteriormente, podemos acceder al método `environ` e informar como parámetro la llave de la información.

```python
os.environ["NB_SESSION_COMPARTMENT_OCID"]
```
Podemos imprimir estos valores:

```python
print(os.environ["NB_SESSION_COMPARTMENT_OCID"])
print(os.environ["PROJECT_OCID"])
```

¡Estás listo!, ahora puedes acceder a la información del ambiente cloud y utilizar los parámetros de configuración de diversas funciones.

