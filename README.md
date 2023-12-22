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