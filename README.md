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