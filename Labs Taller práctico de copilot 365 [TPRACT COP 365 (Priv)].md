# Taller práctico de Copilot 365 - Guía de Laboratorios

### Laboratorio 1: Outlook: Resumir correos y priorización

**Duración:** 20 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot en Outlook para clasificar correos importantes y generar un resumen con acciones clave.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
- Elaborar resúmenes de correos
- Solicitar sugerencias de respuestas a correos
- Editar respuestas posibles: extensión, tono, uso de redacciones alternativas

## Prerrequisitos

### Conocimientos Requeridos
- Conocimiento básico de Microsoft Outlook (envío, respuesta, organización de carpetas)

## Instrucciones Paso a Paso

### Ejercicio 1: Generar resumen con Copilot
**Objetivo:** Usar Copilot para crear un resumen básico de un correo prioritario.

**Instrucciones:**
1. Abrir Outlook.
2. Seleccionar un correo importante y de cierta extensión.
3. En la zona superior, seleccionar **"Resumen por Copilot"** y luego **"Pregúntale a Copilot"**.

![Imagen 1.](/images/Imagen1.png "Imagen 1")

![Imagen 2.](/images/Imagen2.png "Imagen 2")

4. Escribe el siguiente prompt y luego haz clic en el botón **Enviar** o pulsa **ENTER**:
```
¿Cuáles son las acciones sugeridas para continuar?

```
5. Revisa la respuesta obtenida.
6. Retorna al correo seleccionado y selecciona el botón **Responder**.

7. En el cuerpo del correo, haz clic en el ícono de la zona **Borrador con Copilot**  
   *(Atajo: Alt + i)*.

   ![Imagen 3.](/images/Imagen1.png "Imagen 3")

8. Aparecerá una lista de opciones.

   ![Imagen 4.](/images/Imagen1.png "Imagen 4")
9. En el cuadro de texto, escribe el siguiente prompt y envíalo:
```
    Sugiere una respuesta para este correo.
```
10. Revisa la sugerencia generada. En el mismo cuadro de texto, escribe ahora el siguiente prompt y envíalo:

```
Resume este correo en 1 oración ultra-concisa para un ejecutivo ocupado.  Luego lista solo los accionables críticos que requieren decisión de liderazgo.Usa lenguaje directo y sin detalles técnicos.
```

11. Esto debe generar una segunda alternativa de respuesta.  
    Se puede navegar entre las opciones utilizando los botones de navegación.

    ![Imagen 5.](/images/Imagen1.png "Imagen 5")

12. Agrega un prompt adicional y envíalo:

   ```
    Resume este correo con todos los detalles técnicos relevantes.  Incluye números específicos, nombres de sistemas o proyectos, y dependencias técnicas. Lista accionables con contexto técnico completo.
   ```
13. Finalmente, agrega una cuarta alternativa de prompt y envíalo:

   ```
    Resume este correo en tono colaborativo para compartir con el equipo. Enfatiza cómo cada accionable contribuye al objetivo común. Usa lenguaje inclusivo ("necesitamos", "podemos").
```

14. Deberías contar con hasta **cuatro alternativas de respuesta** para elegir.

15. Itera entre las opciones. Usa las herramientas de la sección **"Modificar contenido"** para realizar ajustes si lo deseas.

     ![Imagen 6.](/images/Imagen1.png "Imagen 6")

16. Elige la opción de respuesta que prefieras y haz clic en **Conservar**.

17. Para mejorar el tono o la consistencia de las respuestas, puedes cambiar la configuración base:
    - Selecciona **Configuración** en Outlook (ícono de tuerca en la esquina superior derecha).
    - Luego selecciona **Copilot**.
    - Finalmente, elige **Instrucciones de borrador**.

     ![Imagen 7.](/images/Imagen1.png "Imagen 7")


18. Usa la zona de instrucciones personalizadas para cambiar el tono. Por ejemplo:
```
    - Usar un tono muy casual
    - La longitud debe ser amplia
    - Debe ser como un poema
    - Iniciar de manera formal, cerrar con "Muchas gracias."
```

    **Importante:** Esta configuración redefine el prompt base (contexto) con el que Copilot creará respuestas. Edita con cuidado según tus necesidades laborales o personales.

19. Cierra la ventana de **Configuración**.

20. Selecciona el mismo correo con el que venías trabajando y presiona **Responder**.

21. Usando el ícono flotante de Copilot, repite los pasos **7** y **8** y solicita una nueva sugerencia con el prompt:
```
Sugiere una respuesta para este correo

```

22. Compara la respuesta obtenida con la respuesta anterior.

23. Selecciona **Descartar**.

![Imagen 8.](/images/Imagen1.png "Imagen 8")

24. Selecciona otro correo importante a tu elección.

25. Abre el panel lateral de Copilot (puedes usar el botón flotante de la esquina inferior derecha).

![Imagen 9.](/images/Imagen1.png "Imagen 9")

26. Espera a que el panel lateral de Copilot abra correctamente.

![Imagen 10.](/images/Imagen1.png "Imagen 10")

27. Escribe y aplica el siguiente prompt:
```
 Resume este correo en máximo 3 oraciones. Luego, lista todos los accionables en formato de viñetas con esta estructura: [VERBO DE ACCIÓN] + [QUÉ HACER] + [PLAZO si existe]. Identifica quién es responsable de cada acción.
```

28. Revisa el resultado generado.

29. Ahora escribe y aplica el siguiente prompt:
```
Extrae solo los accionables de este correo. Para cada uno, indica: 1) Acción específica con verbo, 2) Responsable, 3) Fecha límite. Si no hay fecha explícita, indica "No especificada".
```

30. Revisa el resultado generado.

31. Ahora escribe y aplica el siguiente prompt:
```
Examina toda mi bandeja de entrada para hoy y muéstrame lo que merece mi atención primero. Identifica los cinco correos electrónicos más importantes en función de su importancia, urgencia, remitente y relevancia para mis objetivos. Resume de qué trata cada uno, qué acción se requiere y qué puedo ignorar o delegar con seguridad.
```

32. Revisa el resultado generado.

33. Escribe y aplica este prompt para integrar accionables:
```
Examina toda mi bandeja de entrada para hoy y muéstrame lo que merece mi atención primero. Identifica los <<N>> correos electrónicos más importantes en función de:   para mis objetivos  
Criterio 1. Importancia del contenido del correo, solicitudes directas, relevancia para mis objetivos
Criterio 2. Palabras clave urgentes: Asunto contiene "urgente", "hoy", "fecha límite", "aprobación requerida"
Criterio 3. Menciones directas: Mi nombre aparece en el cuerpo del correo con una solicitud específica
Criterio 4. Hilos largos sin resolver: Conversaciones con 5+ respuestas que esperan mi respuesta
Criterio N: Remitente VIP: Correos de mi supervisor directo supervisor@demo.com

Estructura la respuesta de esta forma:
A. RESUMEN: Resume de qué trata cada correo en una o dos lineas como máximo
B. SELECCIONADO POR: Indica por cual de los 4 criterios has seleccionado este correo
C. ACCIONABLES: Determina los accionables. Para cada uno, indica: 1) Acción específica con verbo, 2) Responsable, 3) Fecha límite. Si no hay fecha explícita, indica "No especificada".
D. RESPUESTA SUGERIDA: Sugiere una respuesta para el correo.
```

   > Nota: las zonas sombreadas de amarillo pueden ser modificadas acorde a sus preferencias

34. Puedes copiar alguna respuesta sugerida usando el botón **Copiar respuesta**.

![Imagen 11.](/images/Imagen1.png "Imagen 11")


35. Luego, abre el correo y responde: pega la respuesta sugerida y edítala con Copilot usando las técnicas de los pasos previos, si lo deseas.

**Nota final:** Tómate el tiempo de revisar recomendaciones y acciones sugeridas (por ejemplo, proponer agendar una reunión). Las opciones que aparecen dependen del tipo de correo y del prompt utilizado.

## Módulo 2: Teams: Resumen de reuniones a las que no asistí

**Duración:** 20 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot en **Microsoft Teams** para obtener un resumen de reuniones realizadas.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
- Elaborar resúmenes de reuniones con acciones clave
- Programar un prompt recurrente

## Prerrequisitos

### Conocimientos Requeridos
- Conocimiento básico de Microsoft Teams
- Familiaridad con el manejo de reuniones

## Instrucciones paso a paso

### Ejercicio 1: Generar resumen de reuniones realizadas vía Teams
**Objetivo:** Usar Copilot para crear un resumen básico de una reunión realizada.

**Instrucciones:**
1. Abrir Teams.
2. Seleccionar la opción **Copilot** del menú lateral.

   ![Imagen 12.](/images/Imagen1.png "Imagen 12")
3. Espera a que cargue correctamente la ventana integrada de **Copilot Chat** en Teams.

   ![Imagen 13.](/images/Imagen1.png "Imagen 13")
4. En el cuadro de texto, escribe el siguiente prompt y envíalo:

```
Lista las reuniones en las que participó usuario@demo.com las últimas 2 semanas
```

   **Nota:** Las zonas sombreadas de amarillo pueden ser modificadas según tus preferencias. En este caso, puede ser otro correo/usuario de tu organización. También puedes usar un período diferente para la búsqueda.

5. Revisa el resultado. Deben aparecer las reuniones encontradas, indicando el nombre de la reunión, la fecha, hora, organizador, entre otros datos. También debería existir la opción de abrir la reunión desde cada ítem del resultado.
6. Ahora aplica el siguiente prompt:
```
 Elabora un resumen de cada reunión con la siguiente estructura:  
    1. ASISTENTES: lista de participantes  
    2. RESUMEN EJECUTIVO: máximo 1 párrafo  
    3. TEMAS ABORDADOS  
    4. PREGUNTAS ATENDIDAS: en una tabla indicar quién hizo la pregunta, quién la respondió y cuál fue la respuesta  
    5. CONCLUSIONES
   ```

7. Revisa el resultado. Puedes pedir que se genere en un documento Word usando un prompt como el siguiente:

```
 Convierte el resumen a un documento Word con formato corporativo
 ```

8. Obtendrás un resultado similar al siguiente (imagen referencial).

   ![Imagen 14.](/images/Imagen1.png "Imagen 14")

9. Descarga el Word y revísalo.

### Ejercicio 2: Revisar resumen de reunión generado por Teams Copilot
**Objetivo:** Usar Copilot de Teams para revisar y trabajar con el resumen de una reunión grabada.

**Instrucciones:**

1. Abrir Teams.

2. Desde el menú lateral izquierdo, abrir la aplicación **Reunirse**.

![Imagen 15.](/images/Imagen1.png "Imagen 15")


3. Esperar a que cargue la aplicación. Debe poder visualizar la aplicación de reuniones (imagen referencial).

   ![Imagen 16.](/images/Imagen1.png "Imagen 16")

4. Buscar alguna reunión grabada que sea de su interés y abrirla (imagen referencial).

   ![Imagen 17.](/images/Imagen1.png "Imagen 17")

5. Esperar unos momentos hasta que aparezca el detalle de la reunión.

6. En la zona derecha de la pantalla, seleccionar la opción **“Resumen por IA”**.
   ![Imagen 18.](/images/Imagen1.png "Imagen 18")

7. Revisar el resumen de la reunión.

8. Seleccionar **“Resumen personalizado”**. Aquí se pueden explorar otras opciones como **“Resumen del orador”**.

9. Seleccionar el botón **Copilot**. Esto abrirá la barra lateral de Copilot. Esperar a que cargue completamente (imagen referencial).

   ![Imagen 19.](/images/Imagen1.png "Imagen 19")

10. Escribir y enviar el siguiente prompt para resumir la reunión:

```
Recapitular la reunión, resumir las conclusiones clave y los elementos de acción como secciones independientes, incluidas las responsables de cada una.
```

11. Revisar el resultado obtenido.

12. Sobre la misma u otra reunión, escribir y aplicar el siguiente prompt:

```
Resume esta reunión incluyendo:  
     1) Los temas principales discutidos  
     2) Puntos clave de la transcripción  
     3) Mensajes importantes del chat  
     4) Archivos compartidos y su relevancia  
     Usa formato de lista con viñetas.
 ```
    


13. Revisar el resultado obtenido.

14. Sobre la misma u otra reunión, escribir y aplicar el siguiente prompt:

 ```
 Identifica todas las decisiones tomadas en esta reunión. Para cada decisión, proporciona:  
    **DECISIÓN:** qué se decidió  
    **CONTEXTO:** por qué se tomó esta decisión  
    **RESPONSABLE:** quién es el owner  
    **FECHA LÍMITE:** cuándo debe implementarse  
    Usa formato de tabla para mayor claridad.
 ```
15. Revisar el resultado obtenido.

16. Cerrar la reunión.

17. Seleccionar el botón lateral de **Copilot**.

18. Esperar a que cargue correctamente la ventana integrada de **Copilot Chat** en Teams.

19. Escribir y aplicar el siguiente prompt:

 ```
 Genera un resumen ejecutivo de la reunión /BUSCAR REUNION de no más de 2 párrafos.
```


Al escribir el carácter **“/”**, se podrá buscar alguna de sus reuniones y seleccionar el ítem correspondiente como parte del prompt. La experiencia de búsqueda será similar a la mostrada en la imagen referencial.

 ![Imagen 20.](/images/Imagen1.png "Imagen 20")

20. Luego de seleccionar la reunión, deberá ver su prompt completado. Envíelo (imagen referencial).

![Imagen 21.](/images/Imagen1.png "Imagen 21")

21. Revise el resumen generado.

22. Aplique ahora el siguiente prompt:

```
Crea una reunión de seguimiento para la reunión /BUSCAR REUNION para preguntas para la fecha a las hora
```

   **Nota:** Busque una reunión igual que en el paso 19 (puede ser la misma u otra). Modifique la fecha y la hora según sea necesario para su caso.

23. **Opcional**  
   a. Debajo de la respuesta obtenida, si aparece la opción **“Continuar en Outlook”**, selecciónela (imagen referencial).

![Imagen 22.](/images/Imagen1.png "Imagen 22")

24. Puede retornar a la respuesta del prompt, copiarla y pegarla en el cuerpo de la reunión, y terminar de configurar el evento según su conveniencia.

---

### Ejercicio 3: Programar instrucción recurrente
**Objetivo:** Usar Copilot Chat para crear un prompt con recurrencia (diaria, interdiaria, semanal, etc.) que resuma reuniones de los últimos *X* días o *Y* semanas.

**Instrucciones:**

1. Abrir Teams.
2. Seleccionar la opción **Copilot** del menú lateral.
3. Esperar a que cargue correctamente la ventana integrada de **Copilot Chat** en Teams.

![Imagen 23.](/images/Imagen1.png "Imagen 23")

4. Escribir y aplicar el siguiente prompt:

```
 Busca las reuniones grabadas que tuve ayer / la semana pasada / en la fecha.  
Crea un resumen indicando los siguientes puntos:  
 1. Resumen de la reunión  
 2. Participantes  
 3. Temas tratados  
 4. Siguientes acciones indicando:  
    a) Responsable  
    b) Acción  
    c) Fecha
```

   **Prompt alternativo:**
```
 Busca mis reuniones de los últimos 10 días.  
   > Recapitula cada reunión, resume las conclusiones clave y los elementos de acción como secciones independientes, incluidas las responsables de cada una.
   ```


5. En los botones que aparecen debajo del resultado, seleccione el botón de **tres puntos ( … )** y luego la opción ```**“Programar esta consulta”** ``` (imagen referencial).

6. Aparecerá la ventana **“Programar una consulta”** (imagen referencial).

![Imagen 24.](/images/Imagen1.png "Imagen 24")

7. Configure la recurrencia según se requiera (**Comienza**, **Cada**, etc.).  
   También puede definir el número de veces que se ejecutará la consulta.  
   Verifique que la opción **“Recibir un correo electrónico cuando las respuestas estén listas”** esté marcada.  
   Finalmente, haga clic en **Guardar**.

8. Aparecerá la ventana **“Consultas programadas”**, indicando que la consulta ha sido creada y se encuentra en estado **“Activo”** (imagen referencial).

**Nota:** Cada vez que se ejecute la consulta programada, recibirá un correo informativo con un enlace que lo llevará directamente al resultado desde la ventana de Copilot.

## Módulo 3: Word: Resumen de documentos extensos

## Laboratorio: Resumen de Documentos con Microsoft 365 Copilot en Word

**Duración:** 20 minutos  


## Descripción General

En este laboratorio aprenderás a utilizar **Microsoft 365 Copilot en Word** para:
- Resumir documentos extensos.
- Explorar opciones de redacción.
- Ajustar tono y extensión del contenido generado.


## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:

- Solicitar resúmenes automáticos de documentos en Word.
- Editar documentos usando diferentes configuraciones de redacción, tono y extensión.
- Emplear marcos de trabajo para crear *prompts* de resumen más eficientes.



## Prerrequisitos

### Conocimientos Requeridos
- Conocimiento básico de **Microsoft Word** para redacción y edición de documentos.



## Documentos Base

Los siguientes documentos estarán disponibles en el **OneDrive de la máquina virtual de prácticas**:

- **1Exportacion.docx** – 75 páginas  
- **2FullReportResumido.pdf** – 42 páginas  
- **3ContratoLeasing.pdf** – 33 páginas  
- **4BaseEstandarObras.pdf** – 61 páginas  

---

## Ejercicio 1: Generar un Resumen con Copilot

### Objetivo
Usar Copilot para crear un resumen automático de un documento.

---

### Instrucciones Paso a Paso

1. Abra **Microsoft Word**.

2. Desde **OneDrive** o desde su disco local, abra el documento **1Exportacion.docx**.  
   > **Nota:** Si aparece la opción *Habilitar edición*, selecciónela.

3. En la parte superior del documento, ubique la sección **“Resumen de Copilot”** y haga clic en **Generar**.

![Imagen 25.](/images/Imagen1.png "Imagen 25")

4. Espere a que Copilot genere el resumen y revise el contenido obtenido.

5. En la parte inferior del resumen, ajuste la **extensión del resumen**.

![Imagen 26.](/images/Imagen1.png "Imagen 26")

6. Cambie la opción de extensión de **Detallado** a **Breve** o **Estándar** y compare los resultados generados.

7. Regrese a la parte superior del documento y revise la pestaña **Información**, donde podrá ver:
   - **Cifras clave del documento**
   - **Preguntas y respuestas sugeridas**

   ![Imagen 27.](/images/Imagen1.png "Imagen 27")

8. Abra el **panel lateral de Copilot** haciendo clic en el botón de Copilot.

9. Espere a que el panel lateral cargue correctamente.

![Imagen 28.](/images/Imagen1.png "Imagen 28")

10. En el panel de Copilot, escriba y aplique el siguiente *prompt* general de resumen:

    ```
    Analiza la estructura de este documento e identifica:
    - Las secciones principales y su propósito
    - Los 5 datos cuantitativos más importantes
    - Las 3 conclusiones o recomendaciones clave
    Presenta la información en formato de lista.
    ```

11. Revise el resultado del resumen generado por Copilot.



**Resultado esperado:**  
Un resumen estructurado que permita comprender rápidamente el contenido, los datos clave y las conclusiones principales del documento.

12. A continuación, se presenta un set de prompts enfocados en qué hay que hacer, cómo, con qué entregables y bajo qué normas.  
Aplique los que más hagan sentido para su escenario (también puede probar los prompts con algunos documentos propios).  
Tómese su tiempo para revisar los resultados y encontrar los prompts que mejor respuesta le ofrecen acorde al contenido.

| Nº | Objetivo del resumen | Prompt sugerido |
|----|----------------------|-----------------|
| 1 | Resumen operativo general | ```Resume este documento destacando el alcance del servicio, las actividades principales del consultor y los entregables esperados, usando un enfoque operativo y técnico.``` |
| 2 | Responsabilidades del consultor | ```Resume los Términos de Referencia indicando claramente qué debe hacer el consultor en cada etapa del servicio y qué documentos debe entregar.``` |
| 3 | Visión técnica por componentes | ```Elabora un resumen técnico del documento agrupando la información por componentes: estudios de ingeniería, expediente técnico, presupuesto, cronograma y planos. ```|
| 4 | Cumplimiento normativo | ```Resume este documento indicando las principales normas, directivas y marcos legales que el consultor debe cumplir durante la reformulación del expediente técnico.``` |
| 5 | Checklist de trabajo |``` Genera un resumen del documento en forma de checklist de actividades y entregables que el consultor debe cumplir para la reformulación del expediente técnico.``` |



13. Pruebe ahora prompts de resumen de nivel ejecutivo (igualmente los puede probar con otros documentos si desea):

| Nº | Objetivo del resumen | Prompt sugerido |
|----|----------------------|-----------------|
| 1 | Resumen estratégico | ```Elabora un resumen ejecutivo de este documento explicando el objetivo de la contratación, su importancia para el proyecto y los principales resultados esperados.``` |
| 2 | Apoyo a la toma de decisiones |``` Resume este documento para un directivo, destacando qué se va a contratar, para qué sirve, qué se espera obtener y qué riesgos existen si no se ejecuta correctamente.``` |
| 3 | Enfoque en inversión pública |```Resume los Términos de Referencia desde la perspectiva de inversión pública, explicando cómo la consultoría contribuye al cierre de brechas y al financiamiento del proyecto.``` |
| 4 | One-pager ejecutivo | ```Genera un resumen de máximo una página dirigido a la alta dirección, priorizando objetivo, alcance general, productos finales y entidades involucradas. ```|
| 5 | Control y gobernanza | ```Resume este documento resaltando los mecanismos de supervisión, control, responsabilidades de la entidad y puntos críticos de gestión. ```|



14. Luego de alguna de las respuestas, puede pedir a Copilot que genere un archivo Word editable con el resumen, descargarlo y revisarlo.



## Ejercicio 2: Uso de CO-STAR (Context-Objective-Style-Tone-Audience-Response)

### Objetivo
Usar Copilot para crear un resumen de un documento utilizando el framework CO-STAR.


### Instrucciones

1. Abra Word.

2. Abra el documento **2FullReportResumido.docx**.

3. En la zona de Copilot, escriba y aplique el siguiente prompt:

```
**CONTEXTO (C):**  
Estás analizando un informe corporativo anual resumido que presenta resultados financieros, desempeño por unidades de negocio, mensajes de liderazgo y perspectivas estratégicas de la organización.

**OBJETIVO (O):**  
Generar un resumen ejecutivo claro y accionable que permita comprender rápidamente el desempeño general, los principales logros, riesgos y prioridades estratégicas del período.

**ESTILO (S):**  
Ejecutivo y estructurado, utilizando encabezados claros y viñetas cuando sea apropiado. Evita lenguaje técnico excesivo y cifras innecesarias que no aporten a la decisión.

**TONO (T):**  
Profesional, formal y orientado a la toma de decisiones de alta dirección.

**AUDIENCIA (A):**  
Alta gerencia, directores y tomadores de decisión que no disponen de tiempo para leer el informe completo.

**RESPUESTA (R):**  
Elabora un resumen ejecutivo que incluya:  
1. Visión general del desempeño del año.  
2. Principales resultados financieros y operativos.  
3. Mensajes clave de la dirección (Chairman / CEO).  
4. Riesgos y desafíos relevantes identificados.  
5. Prioridades estratégicas y perspectivas a corto y mediano plazo.

No inventes información. Si algún dato no está explícito en el documento, indícalo de forma clara.

```

4. Revise el resultado del resumen.

5. Abra el panel de navegación de Copilot (imagen referencial).

![Imagen 29.](/images/Imagen1.png "Imagen 29")

6. Busque la conversación más reciente (ubicada al inicio) y cambie su nombre por **“Resumen CO-STAR”** (imagen referencial).

![Imagen 30.](/images/Imagen1.png "Imagen 30")

7. Cree un nuevo documento de Word en una ventana aparte.

8. Abra el panel lateral de Copilot y, en el menú de navegación, busque el chat **“Resumen CO-STAR”**.

9. Al final de la respuesta obtenida, haga clic en **(+) Agregar al documento nuevo**.

![Imagen 31.](/images/Imagen1.png "Imagen 31")

10. Seleccione el texto del documento.

11. Usando Copilot sobre el texto insertado para cambiar la redacción, ingrese por ejemplo el prompt:  
``` *Cambia el tono a casual y reduce el contenido un 15%.* ```

![Imagen 32.](/images/Imagen1.png "Imagen 32")

![Imagen 33.](/images/Imagen1.png "Imagen 33")

![Imagen 34.](/images/Imagen1.png "Imagen 34")

12. Decida si desea conservar, reemplazar, regenerar o descartar el texto generado usando la botonera inferior.

![Imagen 35.](/images/Imagen1.png "Imagen 35")

13. Si lo desea, puede probar otros prompts como:  
```*Cambia el tono a más comercial y ejecutivo.*```

14. Descarte el texto generado.

15. Nuevamente, usando Copilot sobre el texto, seleccione la opción **Estructurar y mejorar**.

16. Espere el resultado y aplique los cambios que considere necesarios.

17. Opcional: Puede abrir otro documento y aplicar el siguiente prompt CO-STAR con placeholders (reemplace los valores según corresponda a sus necesidades):

``` **CONTEXTO (C):**  
Estás analizando el siguiente documento:  
{{DESCRIPCION_DEL_DOCUMENTO}}

Ejemplos:  
- Informe anual corporativo  
- Contrato de leasing financiero  
- Términos de referencia de un proyecto  
- Reporte técnico de avance  

**OBJETIVO (O):**  
El objetivo del resumen es:  
{{OBJETIVO_DEL_RESUMEN}}

Ejemplos:  
- Apoyar la toma de decisiones  
- Informar a la alta dirección  
- Facilitar la ejecución operativa  
- Identificar riesgos y responsabilidades  

**ESTILO (S):**  
El resumen debe presentarse con el siguiente estilo:  
{{ESTILO_DESEADO}}

Ejemplos:  
- Ejecutivo  
- Técnico  
- Legal  
- Operativo  
- Académico  

**TONO (T):**  
Utiliza un tono:  
{{TONO_DESEADO}}

Ejemplos:  
- Formal  
- Profesional  
- Neutro  
- Directo  
- Estratégico  

**AUDIENCIA (A):**  
El resumen está dirigido a:  
{{AUDIENCIA_OBJETIVO}}

Ejemplos:  
- Alta dirección  
- Mando medio  
- Equipo técnico  
- Área legal  
- Comité de evaluación  

**RESPUESTA (R):**  
Genera un resumen que incluya como mínimo los siguientes elementos:  
{{ESTRUCTURA_DE_SALIDA}}

Ejemplos de estructura:  
- Objetivo del documento  
- Alcance y puntos clave  
- Resultados o decisiones relevantes  
- Riesgos, limitaciones o advertencias  
- Próximos pasos o recomendaciones  

**REGLAS ADICIONALES:**  
- No inventes información.  
- Si algún dato no está explícito en el documento, indícalo como “No especificado”.  
- Prioriza claridad y síntesis sobre extensión.  
- Usa viñetas o tablas si mejora la comprensión.  
- El resultado debe ser directamente utilizable en {{FORMATO_FINAL_DESEADO}}.

Ejemplos:  
- correo electrónico  
- informe ejecutivo  
- presentación  
- acta de reunión
```
## Ejercicio 3: Uso de framework IRAC (Issue – Rule – Application – Conclusion)

### Objetivo
Usar Copilot para crear un resumen de un documento utilizando el framework IRAC.



### Instrucciones

1. Abra Word.

2. Abra el documento **3ContratoLeasing.docx**.

3. En la zona lateral de Copilot, escriba y aplique el siguiente prompt:
```
**ISSUE (I):**  
Identifica y resume los principales problemas jurídicos y contractuales abordados en este contrato de arrendamiento financiero, tales como:  
- derechos y obligaciones de las partes,  
- asignación de riesgos,  
- condiciones de pago,  
- causales de resolución,  
- opción de compra y seguros.  

**RULE (R):**  
Resume las reglas contractuales y legales aplicables que rigen el contrato, incluyendo:  
- las cláusulas clave del contrato,  
- la normativa legal mencionada (por ejemplo, Decreto Legislativo 299 y Código Civil),  
- las obligaciones financieras, operativas y de cumplimiento impuestas a la arrendataria.  

**APPLICATION (A):**  
Explica cómo dichas reglas se aplican en la práctica dentro del contrato, detallando:  
- cómo se ejecuta el arrendamiento financiero,  
- cómo se distribuyen los riesgos entre el banco y la arrendataria,  
- qué ocurre ante incumplimientos, siniestros, demoras o resolución contractual,  
- cómo operan los pagos, seguros y la opción de compra a lo largo de la vigencia del contrato.  

**CONCLUSION (C):**  
Elabora una conclusión clara que sintetice:  
- el impacto del contrato para la arrendataria,  
- los principales riesgos contractuales asumidos,  
- los puntos críticos que deben ser monitoreados durante la ejecución,  
- y las implicancias finales al término del contrato (ejercicio o no de la opción de compra).  

**REGLAS ADICIONALES:**  
- No inventes información ni interpretaciones no sustentadas en el texto.  
- Usa lenguaje claro, preciso y profesional.  
- Presenta cada sección (I, R, A, C) con encabezados visibles.  
- El resumen debe ser comprensible para un lector no abogado pero con responsabilidad de gestión.
```
4. Revise el resultado del resumen.

## Módulo 4: PowerPoint: Crear presentación automática
## Descripción General

En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot en PowerPoint para crear presentaciones profesionales usando documentos y desde cero, incorporando secciones, estilos e imágenes.

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:
- Generar presentaciones profesionales usando Copilot empleando un documento como input.
- Generar presentaciones profesionales usando Copilot desde cero, usando un prompt como input.
- Usar Copilot para crear secciones, diapositivas y aplicar estilos.


## Prerrequisitos

### Conocimientos Requeridos
- Conocimiento básico de Microsoft PowerPoint para crear presentaciones.


## Instrucciones Paso a Paso

En estos ejercicios se emplearán una serie de documentos base, que estarán disponibles en el OneDrive de su máquina virtual de prácticas.  
Los documentos a disposición son los siguientes:
- **5Ciberseguridad** – 5 páginas


## Ejercicio 1: Crear presentación a partir de un documento existente

### Objetivo
Usar Copilot para crear una presentación a partir de un documento Word existente.


### Instrucciones

1. Abra PowerPoint.

2. Seleccione **Crear con Copilot**.

![Imagen 36.](/images/Imagen1.png "Imagen 36")

3. Aparecerá la ventana **Crear una presentación con Copilot**.

![Imagen 37.](/images/Imagen1.png "Imagen 37")

4. En el cuadro de texto, complete lo siguiente:

Crea una presentación acerca de ```
/5Ciberseguridad.docx.
Cada slide debe tener como máximo 4 bullets.
Mantén un tono profesional y simplifica las ideas complejas.```


markdown
Copy code

5. Ajuste **Longitud** a **Corta**, no cambie el **Modelo** (Default) y haga clic en **Enviar** (flecha direccional a la derecha)  
(ver imagen referencial).

![Imagen 38.](/images/Imagen1.png "Imagen 38")


6. Revise el **Esquema**, modifique el **Tono** (Sugerencias, Conversación, Profesional, Persuasivo, Motivador) por el que desee y haga clic en **Regenerar**.

![Imagen 39.](/images/Imagen1.png "Imagen 39")

7. Agregue un nuevo tema (clic en el **+** ubicado en la zona inferior de la lista de diapositivas).

![Imagen 40.](/images/Imagen1.png "Imagen 40")

8. Agregue un tema sobre ```
los retos de la ciberseguridad con posibles ataques orquestados usando IA.  
Cite la fuente de información utilizada.```


9. Seleccione un **Estilo de presentación**.

![Imagen 41.](/images/Imagen1.png "Imagen 41")

10. Seleccione una **Preferencia de imagen**: Imágenes de archivo.

![Imagen 42.](/images/Imagen1.png "Imagen 42")

11. Haga clic en **Generar diapositivas**.

12. Espere a que se genere la presentación.

13. Seleccione la opción **Conversarlo**.

![Imagen 43.](/images/Imagen1.png "Imagen 43")

14. Cambie a la vista **Normal**.

15. Con la presentación generada, cree una nueva diapositiva con Copilot.  
   En la pestaña **Inicio**, seleccione **Nueva diapositiva con Copilot**.

![Imagen 44](/images/Imagen1.png "Imagen 44")

![Imagen 45.](/images/Imagen1.png "Imagen 45")

16. Escriba el siguiente prompt:

Agregar una diapositiva acerca de ```
cómo usar la IA para mejorar las operaciones de Seguridad.```


markdown
Copy code

17. Seleccione la opción **Conversarlo**.

18. Guarde la presentación con el nombre que desee.

19. Cierre la presentación.

## Ejercicio 3: Crear presentación desde cero (tema libre)

##Objetivo:

 Usar Copilot para crear una presentación desde cero, solo empleando un prompt con un tema libre  

Instrucciones:

1.	Abrir Power Point

2.	Seleccione Crear con Copilot

3.	Escriba y aplique el siguiente prompt:  
Crea una presentacion acerca de ``` la invasión del rock británico. Añade fotos o imagenes en cada slide acorde al contenido. Usa un formato atractivo y moderno, acorde al tema de la presentacion.```

4.	Ajustar Lontigitud a Media, cambiar el Modelo a Creative y Generar (flecha direccional a la derecha)

5.	Revisar el contenido generado

6.	Cambie el Estilo de presentación y Preferencias de imagen según desee. Luego haga clic en Generar diapositivas  

![Imagen 46.](/images/Imagen1.png "Imagen 46")

Nota: en este ejemplo se esta usando Estilo Standard: Serenidad moderna y en Preferencias de imagen, Origen: Imágenes generadas por IA, Fotorealista.

7.	Esperar generacion y ver el resultado.  
Nota: el tiempo de generación puede variar en función a las configuraciones aplicadas.

8.	Revise el contenido generado.

9.	Guarde la presentación

10.	Seleccione el slide final de la presentación

11.	Abra el panel lateral de Copilot

12.	Escriba y aplique el siguiente prompt:  
```Haz un collage tres fotos de bandas britanicas actuando en vivo```

13.	Espere la creación de la imagen

14.	Revise la imagen, si se desea seguir las sugerencias de prompts para agregar un titulo o marco llamativo

15.	Posicionarse encima y seleccionar + Insertar

![Imagen 47.](/images/Imagen1.png "Imagen 47")


16.	Hacer las modificaciones requeridas finales en el slide

17.	Guarde la presentación

18.	Cierre la presentacion

## Módulo 5: Copilot Chat: Plan semanal de actividades

Duration: 20 minutos

## Descripción General

En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot Chat para planificar tareas derivadas de correos y de reuniones.

## Objetivos de Aprendizaje

Al completar este laboratorio, serás capaz de:
• Planificar una agenda de tareas con prompts desde Microsoft 365 Copilot Chat en función a correos recibidos.  
• Planificar una agenda de tareas con prompts desde Microsoft 365 Copilot Chat en función a reuniones realizadas.

## Prerrequisitos

### Conocimientos Requeridos

- Conocimiento básico de Microsoft Outlook para manejo de correos  
- Conocimiento básico de Microsoft Teams para atención de reuniones  



## Instrucciones Paso a Paso

### Ejercicio 1: Atención de correos / reuniones recientes

Objetivo: Usar Copilot Chat para atender correos y reuniones recientes  

Instrucciones:

1. Abrir Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2. Aparecerá la página de Microsoft 365 Copilot Chat, similar a la siguiente (imagen referencial)

![Imagen 48.](/images/Imagen1.png "Imagen 48")

3. En el cuadro de texto escriba y envie el siguiente prompt para poder conocer los correos que se han recibido:

```
Lista los correos recibidos en los últimos {{X}} días de {{user@demo.com
}}.
Prioriza cuáles son más importantes de atender según el contenido y explica por qué.

Presenta el resultado en una tabla.
```

Nota: reemplace los datos de las zonas de amarillo por otros que hagan sentido para su escenario.

4. Copilot generará una respuesta, espere un momento.

![Imagen 49.](/images/Imagen1.png "Imagen 49")

5. Revise la respuesta. Es posible que tenga ítems de correo que pueda abrir, puede probar abriéndolos en Outlook si desea.

6. Repitiendo los pasos previos, puede ahora probar con otros prompts sugeridos, enfocados en correos que he recibido:

| Nº | Objetivo | Prompt para M365 Chat |
|----|---------|-----------------------|
| 1 | Correos sin responder |```Lista los correos que he recibido en los últimos 3 días y que aún no he respondido. Indica remitente, asunto, fecha y nivel de urgencia. Presenta el resultado en formato tabla.``` |
| 2 | Correos críticos | ``` De los correos recibidos esta semana, identifica aquellos que contienen solicitudes, aprobaciones o plazos. Resume brevemente cada uno y preséntalo en una tabla. ``` |
| 3 | Correos de un cliente | ```Resume los correos recibidos de {{Cliente / Dominio}} en los últimos {{X}} días, indicando temas tratados y si requieren acción. Presenta el resultado en tabla.``` |
| 4 | Correos largos |```Identifica los correos más extensos recibidos en los últimos {{X}} días y genera un resumen de máximo 3 líneas por correo. Presenta el resultado en una tabla.``` |
| 5 | Correos con adjuntos |```Lista los correos recibidos con archivos adjuntos esta semana, indicando remitente, tipo de archivo y para qué sirve el adjunto según el contenido del correo.``` |
| 6 | Seguimiento de compromisos | ```A partir de mis correos recientes, identifica compromisos o tareas asignadas a mí y preséntalas en una tabla con responsable y estado.``` |
| 7 | Correos ignorables | ```Analiza mis correos recibidos en los últimos {{X}} días e identifica cuáles pueden ignorarse o postergarse sin impacto. Explica brevemente por qué. ``` |
| 8 | Correos ejecutivos | ```Resume los correos más relevantes para la gestión ejecutiva recibidos esta semana, destacando decisiones, riesgos o bloqueos. Presenta el resultado en tabla.``` |
| 9 | Preparación para respuesta | ```Selecciona los correos más importantes que debo responder hoy y sugiere el enfoque de respuesta (informar, aprobar, solicitar información). Presenta el resultado en tabla.``` |

7. En el cuadro de texto escriba y envie el siguiente prompt para obtener información sobre reuniones sostenidas:
```
Lista las reuniones que sostuve ayer, con quién fueron, de qué trató cada una (máx. 1 párrafo), acuerdos y accionables.
Presenta el resultado en una tabla.
```

8. Revise el resultado. Puede probar abrir las reuniones desde los ítems obtenidos en Teams, haciendo clic en el item correspondiente.

9. Repitiendo los pasos previos, puede ahora probar con otros prompts sugeridos, enfocados en reuniones sostenidas:

| Nº | Objetivo | Prompt para M365 Chat |
|----|---------|-----------------------|
| 1 | Seguimiento de acciones | ```A partir de mis reuniones de esta semana, identifica las acciones asignadas a mí, indicando reunión de origen, acción y fecha si aplica. Presenta el resultado en tabla. ``` |
| 2 | Reuniones clave | ```Identifica las reuniones más relevantes que tuve en los últimos {{X}} días y resume las decisiones tomadas en cada una. Presenta el resultado en tabla.``` |
| 3 | Reuniones con un contacto |``` Resume las reuniones que tuve con {{Persona / Equipo}} en los últimos {{X}} días, indicando temas tratados y próximos pasos. ```|
| 4 | Reuniones sin acuerdos | ```Identifica las reuniones recientes donde no se definieron acuerdos claros y sugiere qué acciones de seguimiento serían necesarias.```|
| 5 | Preparación de reporte | ``` Genera un resumen ejecutivo de las reuniones que sostuve esta semana para reportarlo a mi jefe, destacando avances, riesgos y bloqueos.``` |
| 6 | Reuniones repetitivas |```Analiza mis reuniones recurrentes y resume los temas que se repiten y los acuerdos pendientes no cerrados. ```|
| 7 | Impacto del tiempo | ```Resume en qué se invirtió mi tiempo en reuniones la semana pasada, agrupando por tipo de reunión y principales temas tratados.```  |
| 8 | Reuniones técnicas | ```Resume las reuniones técnicas que sostuve recientemente, destacando decisiones técnicas, pendientes y responsables.``` |
| 9 | Preparación para siguiente reunión | ``` A partir de la última reunión con {{Equipo / Persona}}, resume lo acordado y sugiere una agenda para la próxima reunión.``` |



## Ejercicio 2: Planificación semanal

Objetivo: Usar Copilot Chat para planificar las actividades de la semana  

Instrucciones:

1. Abra Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2. Escriba y aplique el siguiente prompt:
``` 
Resume mi actividad de la última semana: ¿cuántos correos he recibido, cuántas reuniones tuve y qué documentos he editado?
``` 
3. Revise el resultado entregado. Si desea puede abrir los correos, reuniones y archivos encontrados.

4. Cree un nuevo chat. En la parte superior derecha seleccione el botón **Start a new chat**.

![Imagen 49.](/images/Imagen1.png "Imagen 49")

5. Escriba y aplique el siguiente prompt:
``` 
Analiza mis correos, reuniones, documentos y chats de los últimos 7 días y extrae TODAS las tareas pendientes, compromisos y accionables que requieren mi atención.

Para cada tarea, proporciona:
Tarea: [descripción clara y accionable]
Fuente: [correo de X, reunión Y, documento Z]
Contexto: [por qué es importante, quién está involucrado]
Plazo: [fecha límite si está mencionada, o "sin plazo definido"
Formato de salida: tabla con columnas [#, Tarea, Fuente, Contexto, Plazo
Excluye: tareas ya completadas, FYI sin acción requerida, spam.
``` 

6. Revise el resultado entregado. Se pueden usar los enlaces proporcionados para abrir los ítems correspondientes.

7. Opcional: si se quiere generar un correo con el resultado  
   a. Abra Outlook  
   b. Abra el panel lateral de Copilot  
   c. Abra el menú lateral y seleccione el último chat  
   d. Ubíquese al final de la respuesta y haga clic en el botón **Copiar respuesta**  
   e. Cree un nuevo correo y pegue la respuesta en el correo  

8. Retorne a Microsoft 365 Chat.

9. Escriba y aplique el siguiente prompt de matriz de Eisenhower para hacer priorización en base a 4 cuadrantes: HACER PRIMERO, PLANIFICAR, DELEGAR, ELIMINAR
``` 
Toma la lista de tareas anterior y clasifícalas usando la Matriz de Eisenhower:
Criterios:
URGENTE: tiene plazo en los próximos 3 días o alguien está esperando
IMPORTANTE: impacta objetivos estratégicos, relaciones clave o resultados críticos del negocio

Cuadrantes:
Urgente E Importante (HACER PRIMERO)
Importante pero NO Urgente (PLANIFICAR)
Urgente pero NO Importante (DELEGAR si es posible)
Ni Urgente ni Importante (ELIMINAR o hacer después)

Formato: muestra las tareas agrupadas por cuadrante con justificación breve de la clasificación.
``` 

10. Revise el resultado y ajuste el prompt si es requerido.

11. Ahora escriba y aplique el siguiente prompt para afinar el resultado de los primeros 2 cuadrantes:
``` 
Para las tareas de Cuadrante 1 (Urgente e Importante) y Cuadrante 2 (Importante no Urgente), aplica análisis de IMPACTO vs ESFUERZO:

IMPACTO (Alto/Medio/Bajo):
Alto: afecta significativamente objetivos clave, ingresos o relaciones estratégicas
Medio: contribuye a objetivos pero no es crítico
Bajo: valor limitado o impacto indirecto

ESFUERZO (Alto/Medio/Bajo):
Alto: requiere >2 horas o múltiples sesiones
Medio: 30 min - 2 horas
Bajo: < 30 minutos

Prioridad final: Alto Impacto + Bajo Esfuerzo = máxima prioridad

Muestra cada tarea con [Impacto/Esfuerzo] y ordena por prioridad óptima.
``` 

12. Revise el resultado y ajuste el prompt si es requerido.

13. Finalmente, escriba y aplique el siguiente prompt para crear un plan semanal de atención de tareas:
``` 
Crea un plan semanal (lunes a viernes) distribuyendo las tareas priorizadas en mi calendario.

RESTRICCIONES:
Respeta mis reuniones ya programadas (verifica mi calendario)
Horario laboral: 9:00 AM - 6:00 PM
Incluye bloques de enfoque de 90-120 min para tareas de alto esfuerzo
Agrupa tareas similares (batch processing)
Deja 30 min buffer entre bloques para descansos
Reserva viernes tarde para tareas de Cuadrante 2 (planificación)

DISTRIBUCIÓN:
Cuadrante 1: primeras horas del día (máxima energía)
Tareas rápidas (bajo esfuerzo): entre reuniones
Tareas creativas: mañanas
Tareas administrativas: tardes

Formato: tabla por día con [Hora, Actividad, Duración, Cuadrante]
``` 
14. Revise el resultado y ajuste el prompt si es requerido.

## Módulo 6: Outlook: Crear correos desde notas y minutas

Duration: 20 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot en Outlook para generar correos de resumen y accionables luego de una reunion.

Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
•	Elaborar correos de resumen apoyándose de Microsoft Outlook Copilot

## Prerrequisitos

Conocimientos Requeridos

-	Conocimiento básico de Microsoft Outlook (envío, respuesta, organización de carpetas)
-	Familiaridad con conceptos de gestión de correo electrónico (reglas, banderas, categorías)



## Instrucciones Paso a Paso

Ejercicio 1: Generar resumen luego de una reunion
Objetivo: Usar Copilot para crear un resumen y accionables luego de una reunion
Instrucciones:

1.	Abra Outlook

2.	Abra la barra lateral de Copilot

3.	Cree un nuevo correo.

4.	Escriba y envie el siguiente prompt
``` 
Genera un correo de seguimiento para la reunión /BUSCAR REUNION con la siguiente estructura: Temas tratados, Acuerdos y Accionables, indicando responsables cuando sea posible.



Adiciona en la respuesta un resumen de 3 parrafos del documento /{{Documento a referenciar}}
``` 

Nota: para cada zona de amarillo use los ítems que hagan sentido para su escenario, en el primer caso una reunion sostenida, en el segundo un documento (es opcional el uso del documento).


Es posible que para su facilidad sea mejor expandir las opciones inferiores de búsqueda de reuniones (imagen referencial)

![Imagen 50.](/images/Imagen1.png "Imagen 50") 


5.	Revise el resultado, ajuste el prompt según requiera.

6.	Repitiendo los pasos previos, puede ahora probar con otros prompts sugeridos, enfocados en resumen y accionables luego de una reunion

| Nº | Objetivo | Prompt |
|----|----------|--------|
| 1 | Resumen ejecutivo por correo | ``` Redacta un correo ejecutivo resumiendo la reunión {{Nombre de la reunión}}, enfocado en decisiones tomadas y próximos pasos. Máximo 5 párrafos.```  |
| 2 | Correo de pendientes | ``` Genera un correo dirigido a los asistentes de la reunión {{Nombre de la reunión}} recordando los accionables acordados y sus responsables. ``` |
| 3 | Minuta formal |```  Elabora una minuta de la reunión {{Nombre de la reunión}} con: objetivo, temas tratados, acuerdos y acciones. Usa un tono profesional.```  |
| 4 | Correo para ausentes | ``` Redacta un correo para quienes no asistieron a la reunión {{Nombre de la reunión}}, explicando brevemente de qué trató y qué se acordó. ``` |
| 5 | Seguimiento personalizado |```  Genera un correo dirigido a {{Persona}} resumiendo los acuerdos de la reunión {{Nombre de la reunión}} que requieren su acción.```  |
| 6 | Confirmación de acuerdos |```  Redacta un correo solicitando confirmación de los acuerdos tomados en la reunión {{Nombre de la reunión}} y validación de fechas. ``` |
| 7 | Preparación de reporte | ``` Resume la reunión {{Nombre de la reunión}} en un formato adecuado para enviarlo por correo a la gerencia, destacando avances, riesgos y pendientes.```  |
| 8 | Correo con agenda futura | ``` Genera un correo de seguimiento de la reunión {{Nombre de la reunión}} incluyendo una propuesta de agenda para la siguiente sesión.```  |
| 9 | Recordatorio previo | ``` A partir de la reunión {{Nombre de la reunión}}, genera un correo recordatorio con los compromisos pendientes antes de la próxima reunión.```  |


7.	Seleccione una de las respuestas. Si desea, afine y aplique nuevamente el prompt hasta tener la respuesta con el formato que desea.

8.	Hacer clic en el botón Copiar respuesta

![Imagen 51.](/images/Imagen1.png "Imagen 51")



9.	Pegarla en el cuerpo de un correo nuevo (si no había creado uno hagalo previamente).

10.	Abrir opción de Copilot sobre el texto pegado. Si desea disponer de mas espacio puede contraer temporalmente el panel lateral de Copilot

![Imagen 52.](/images/Imagen1.png "Imagen 52")



11.	Seleccionar diferentes partes del correo, repasar las opciones ya vistas en anterior ejercicio como Reescritura automática, Hacer que sea más corto, Hacer que sea mas largo, Cambiar tono,  y opciones de la sección Indicaciones sugeridas (imagen referencial)

![Imagen 53.](/images/Imagen1.png "Imagen 53")


12.	Revisar cada opción con calma, notando el cambio que opera sobre el contenido.

## Ejercicio 2: Pedir asesoramiento a Copilot

## Objetivo:
 Usar Copilot para pedir asesoramiento sobre una redacción  

## Instrucciones:

1.	Abra Outlook

2.	Abra la barra lateral de Copilot

3.	Escriba y aplique el siguiente prompt  
 ```Resume la reunión /BUSCAR REUNION para aquellos que no pudieron asistir, explicando brevemente de qué trató y qué se acordó.
  ```

Nota: busque la reunion que usted desee para el ejemplo

4.	Observe el resultado.

5.	Copie la respuesta.

![Imagen 54.](/images/Imagen1.png "Imagen 54")

6.	Cree un nuevo correo.

7.	Pegue la respuesta copiada en el cuerpo del correo.

8.	Abrir opción de Copilot sobre el texto pegado

9.	Utilizar la opción Obtener asesoramiento (imagen referencial)

![Imagen 54.](/images/Imagen1.png "Imagen 54")

10.	Revisar el cuadro de sugerencias sobre Tono, Opinión del lector, Claridad

![Imagen 55.](/images/Imagen1.png "Imagen 55")

11.	Seleccione Aplicar todas las sugerencias

12.	Revisar contenido generado, si esta conforme Reemplazar o también puede Insertar debajo o Reintentar según sea el caso de su preferencia

---

## Ejercicio 3: Creación de minuta mas detallada

Objetivo: Usar Copilot para crear un resumen mas detallado después de una reunion  

Instrucciones:

1.	Abra Outlook

2.	Abra la barra lateral de Copilot

3.	Escriba y aplique el siguiente prompt  

 ```
 Actúa como un asistente ejecutivo experto en documentación profesional.  
A partir del contenido de esta reunión /BUSCAR REUNION (transcripción, chat, audio y archivos compartidos), genera una MINUTA DE REUNIÓN en español, clara, profesional y orientada a la acción.

Sigue EXACTAMENTE esta estructura y formato:

1. **ENCABEZADO**
   - Título de la reunión
   - Fecha
   - Hora de inicio y fin
   - Modalidad (Presencial / Teams / Híbrida)
   - Organizador
   - Responsable de la minuta
 
2. **PARTICIPANTES**
   - Asistentes
   - Invitados
   - Ausentes

3. **OBJETIVO DE LA REUNIÓN**  
   Redacta un párrafo breve (máximo 3 líneas) que explique el propósito principal de la reunión.

4. **AGENDA / TEMAS TRATADOS**  
   Enumera los temas abordados durante la reunión en formato de lista numerada.

5. **RESUMEN POR TEMA**  
   Para cada tema de la agenda:
   - Resume lo discutido en lenguaje claro
   - No transcribas literalmente
   - Enfócate en hechos relevantes, acuerdos y puntos clave

6. **DECISIONES TOMADAS**  
   Presenta las decisiones en una tabla con las siguientes columnas:
   - N°
   - Decisión
   - Responsable
   - Fecha (si aplica)

   Si alguna decisión no tiene responsable o fecha clara, indica "Por definir".

7. **ACCIONES / PENDIENTES**  
   Lista todas las acciones acordadas en una tabla con:
   - Acción (verbo + qué hacer)
   - Responsable
   - Fecha límite

8. **ACUERDOS ADICIONALES**  
   Incluye lineamientos, compromisos generales o reglas acordadas que no sean tareas específicas.

9. **PRÓXIMA REUNIÓN**  
   Indica:
   - Fecha
   - Hora
   - Objetivo preliminar  
   Si no se definió, indica "Por definir".

10. **CIERRE**
    - Hora de cierre
    - Observaciones finales (si las hubiera)

**REGLAS IMPORTANTES:**
- Usa un tono profesional y neutro.
- Sé conciso pero completo.
- No inventes información.
- Si algo no fue mencionado explícitamente, indica "No definido" o "No mencionado".
- Prioriza decisiones y acciones sobre opiniones.
- Usa tablas donde se indique.
 ```

4.	Haga clic en boton inferior para "Copiar respuesta"

5.	Pegue la respuesta en el cuerpo del correo, realice los ajustes que considere necesario usando las opciones de edición de Copilot vistas en ejercicios anteriores.

## Módulo 7: Microsoft 365 Chat: Generación de contenido textual y
Duration: 20 minutos

## Descripción General
En este laboratorio, aprenderás a utilizar Microsoft 365 Copilot Chat para generar contenido de texto y gráfico, empleando diferentes técnicas de prompting engineering como Zero-shot, Few-shot, Chain-of-though y frameworks como RCTFR o SOP.

## Objetivos de Aprendizaje
Al completar este laboratorio, serás capaz de:
•	Generar diferentes contenidos de tipo texto y gráfico  
•	Mejorar la estructura de sus prompts y calidad de respuestas empleando técnicas de prompt engineering y framworks  

## Prerrequisitos

## Conocimientos Requeridos
-	Conocimiento básico en el uso de documentos de Office  

## Instrucciones Paso a Paso

## Ejercicio 1: Mejoramiento de prompts
Objetivo: Emplear diferentes técnicas para mejoramiento de prompts y obtener respuestas de mas calidad  

Instrucciones:

1.	Abra Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2.	Escriba y aplique el siguiente prompt sin dar mucho contexto sobre lo que se quiere obtener como respuesta (a esto se le conoce como Zero-shot):  
 ```
 Escribe un correo profesional agradeciendo a un cliente por su compra.
 ```
3.	Observa la respuesta, es algo genérica.

4.	Ahora puede aplicar alguno de los siguientes prompts, que siguen una idea similar (sin dar ejemplos de uso previo o Zero-Shot):

| Nº | Objetivo del prompt | Ejemplo de Zero-Shot Prompt |
|----|---------------------|-----------------------------|
| 1 | Evaluar comprensión y capacidad de síntesis. |  ```Resume este texto en tres frases. ``` |
| 2 | Realizar una traducción directa. |  ```Traduce este párrafo al inglés. ``` |
| 3 | Evaluar habilidad de adaptación de tono. |  ```Explica qué es la computación en la nube como si hablaras con un estudiante. ``` |
| 4 | Ejercicio de análisis de sentimiento. |  ```Clasifica este comentario como positivo, negativo o neutro. ``` |
| 5 | Pedir razonamiento comparativo sin contexto previo. | ``` Crea una lista de ventajas y desventajas del trabajo remoto.  ```|
| 6 | Medir creatividad espontánea. | ``` Genera una idea de campaña publicitaria para una marca de café. ``` |
| 7 | Comprobar conocimiento procedimental. | ``` Indica los pasos para instalar Visual Studio Code en Windows.  ```|
| 8 | Recuperar conocimiento general. | ``` Dame tres ejemplos de inteligencia artificial en la vida cotidiana. ``` |
| 9 | Pedir formato estructurado sin muestra previa. | ``` Resume los principios éticos de la IA en formato de tabla.  ```|


5.	Revise las respuestas obtenidas.

6.	Escriba y aplique el siguiente prompt, que es una versión mejorada de los prompts del set anterior (usando la técnica Role-Based Prompting):
```Actúa como un consultor senior de transformación digital con 15 años de experiencia en gestión de proyectos ágiles y adopción de IA empresarial. Escribe un artículo de 500 palabras sobre los beneficios de la inteligencia artificial en la gestión de proyectos empresariales. Incluye métricas específicas, casos de uso reales y recomendaciones prácticas para CTOs y PMOs.```

7.	Revise la respuesta obtenida. Se obtiene un resultado mas preciso, dado el contexto proporcionado en el prompt.

8.	Ahora puede aplicar alguno de los siguientes prompts, que siguen Role-Based Prompting:
| Nº | Objetivo del prompt | Ejemplo de Zero-Shot Prompt | Ejemplo de Role-Based Prompting |
|----|---------------------|-----------------------------|--------------------------------|
| 1 | Evaluar comprensión y capacidad de síntesis. | Resume este texto en tres frases. | ```Actúa como un editor académico con experiencia en divulgación científica. Resume el siguiente texto en tres frases claras, manteniendo las ideas principales y eliminando redundancias. ```|
| 2 | Realizar una traducción directa. | Traduce este párrafo al inglés. |``` Actúa como un traductor profesional especializado en documentos corporativos. Traduce el siguiente párrafo al inglés manteniendo el tono formal y la precisión terminológica.``` |
| 3 | Generar texto formal sin ejemplos previos. |Escribe un correo profesional agradeciendo a un cliente por su compra. | ```Actúa como un gerente de cuentas senior en una empresa B2B. Redacta un correo profesional de agradecimiento a un cliente por su compra, usando un tono formal, cercano y orientado a fidelización. ```|
| 4 | Evaluar habilidad de adaptación de tono. | Explica qué es la computación en la nube como si hablaras con un estudiante. | ```Actúa como un profesor universitario de ingeniería de sistemas. Explica qué es la computación en la nube a un estudiante de primeros ciclos, usando un lenguaje sencillo y ejemplos cotidianos.``` |
| 5 | Ejercicio de análisis de sentimiento. | Clasifica este comentario como positivo, negativo o neutro. | ```Actúa como un analista de experiencia del cliente (CX). Analiza el siguiente comentario y clasifícalo como positivo, negativo o neutro, justificando brevemente tu decisión.``` |
| 6 | Pedir razonamiento comparativo sin contexto previo. | Crea una lista de ventajas y desventajas del trabajo remoto. | ```Actúa como un consultor de recursos humanos especializado en modelos de trabajo híbrido. Elabora una lista comparativa de ventajas y desventajas del trabajo remoto desde una perspectiva organizacional y del colaborador.``` |
| 7 | Medir creatividad espontánea. | Genera una idea de campaña publicitaria para una marca de café. |``` Actúa como un director creativo de una agencia de marketing digital. Propón una idea innovadora de campaña publicitaria para una marca de café, incluyendo concepto central y mensaje clave.``` |
| 8 | Comprobar conocimiento procedimental. | Indica los pasos para instalar Visual Studio Code en Windows. | ```Actúa como un ingeniero de soporte técnico nivel senior. Describe paso a paso cómo instalar Visual Studio Code en Windows, considerando a un usuario sin experiencia técnica.``` |
| 9 | Recuperar conocimiento general. | Dame tres ejemplos de inteligencia artificial en la vida cotidiana. | ```Actúa como un divulgador tecnológico especializado en IA. Menciona tres ejemplos claros de cómo se aplica la inteligencia artificial en la vida cotidiana, explicando brevemente cada uno.``` |
| 10 | Pedir formato estructurado sin muestra previa. | Resume los principios éticos de la IA en formato de tabla. |``` Actúa como un consultor en ética y gobernanza de inteligencia artificial. Resume los principales principios éticos de la IA en una tabla clara que incluya principio y breve descripción.``` |


9.	Para varios de los casos previamente mostrados tomese el tiempo en comparar el resultado obtenido al emplear Zero-shot versus Role-Based prompting.

10.	Escriba y aplique el siguiente prompt de tipo One-Shot (da un ejemplo previo del resultado que se quiere obtener):
```
Necesito escribir reportes ejecutivos concisos para el CEO. Aquí un ejemplo del estilo que busco:

[EJEMPLO]
Título: Resultados Q3 - Migración Cloud
Resumen: La migración de 47 aplicaciones a Azure se completó con 12 días de adelanto.
Reducción de costos operativos del 23% vs. proyección inicial del 18%.
Impacto: 3,200 usuarios activos diarios sin incidentes críticos. Tiempo de respuesta mejorado en 34%.
Siguiente paso: Iniciar Fase 2 (migración de bases de datos) en Q4.
[FIN EJEMPLO]

Ahora, escribe un reporte ejecutivo de 300 palabras sobre la implementación de Microsoft
365 Copilot en nuestra organización durante el último trimestre. Usa el mismo formato estructurado, conciso y orientado a métricas del ejemplo.
```
11.	Revise el resultado

12.	Escriba y aplique el siguiente prompt de tipo Few-Shot (da varios ejemplos previos del resultado que se quiere obtener):
```
Necesito escribir emails de prospección comercial efectivos. Aquí tres ejemplos del estilo que funciona en nuestra empresa:

[EJEMPLO 1]
Asunto: 3 formas en que [Empresa] puede reducir costos IT en 30 días Hola [Nombre],
Noté que [Empresa] está expandiendo operaciones en LATAM. Empresas similares reducen costos IT un 28% implementando [solución específica].
¿15 minutos esta semana para explorar si aplica a su contexto? [Firma]
[FIN EJEMPLO 1]

[EJEMPLO 2]
Asunto: Caso de éxito: [CompetidorIndirecto] optimizó procesos en 45 días Hola [Nombre],
Vi su presentación en [Evento]. [CompetidorIndirecto] enfrentaba desafíos similares y logró [resultadoespecífico] con nuestra metodología.
¿Conversamos 10 minutos sobre su roadmap de transformación digital? [Firma]
[FIN EJEMPLO 2]

[EJEMPLO 3]
Asunto: Pregunta rápida sobre su estrategia de IA Hola [Nombre],
Felicitaciones por [logro reciente de la empresa]. ¿Han evaluado cómo IA generativa puede acelerar [proceso específico de su industria]?
Tenemos un benchmark de su sector que podría interesarle. [Firma]
[FIN EJEMPLO 3]

Ahora escribe un email de prospección de 150 palabras para un CTO de una empresa de manufactura, ofreciendo servicios de implementación de Copilot. Sigue el estilo de los ejemplos: personalizado, específico, con valor inmediato y call-to-action claro.
```

13.	Revise el resultado

14.	Como ejercicio adicional, aplique la técnica de One-Shot o Few-Shot para algun prompt que ya tenia y luego compare el resultado.

15.	Escriba y aplique el siguiente prompt de tipo Chain-of-Thought (útil para conocer el razonamiento o paso a paso que realiza la IA para generar una respuesta)
```
Diseña un plan paso a paso para implementar Microsoft 365 Copilot en una empresa de 200 empleados.
```

16.	Revise el resultado.

17.	Para practicar, puede aplicar alguno de los siguientes prompts, de tipo Chain-of-Thought:

| Nº | Objetivo / Contexto | Ejemplo de Prompt con razonamiento paso a paso |
|----|---------------------|-----------------------------------------------|
| 1 | Matemática básica |``` Si un tren viaja 60 km en una hora y otro viaja 90 km en el mismo tiempo, ¿cuál es su velocidad promedio? Razona paso a paso antes de responder.``` |
| 2 | Análisis de negocio |``` Una empresa aumentó sus ventas de 80K a 120K en tres meses. Explica paso a paso cómo calcular el porcentaje de crecimiento.``` |
| 3 | Educación / enseñanza | ``` Explica paso a paso cómo funciona el aprendizaje supervisado en inteligencia artificial. ``` |
| 4 | Análisis financiero | ``` Una inversión inicial de $10,000 crece un 8% anual durante 3 años. Calcula el valor final mostrando los pasos del cálculo.``` |
| 5 | Toma de decisiones empresariales |``` Un cliente quiere migrar su sistema a la nube. Evalúa paso a paso las ventajas y riesgos antes de recomendar una opción.``` |
| 6 | Redacción profesional (mejorar texto) |``` Mejora el siguiente párrafo explicando paso a paso los cambios que harás y por qué: [texto]. ```|
| 7 | Ciberseguridad | ``` Analiza paso a paso los riesgos de compartir contraseñas por correo electrónico y propón medidas de mitigación. ``` |
| 8 | IA y razonamiento ético | ``` Evalúa paso a paso las implicaciones éticas de usar IA para decisiones de contratación de personal.``` |

18. Como ejercicio adicional, aplique Chain-of-Thought para algun prompt que ya tenia, compare el resultado mejorado.  
CoT se puede aplicar para estos casos:  
a. Problemas de razonamiento lógico y matemático (Cálculos financieros, Problemas matemáticos, Lógica proposicional, Optimización)  
b. Análisis comparativo complejo (Comparar arquitecturas, Decisiones técnicas, Trade-offs)  
c. Diagnóstico y troubleshooting (Fallas técnicas, Incidentes de seguridad, Análisis de errores)  
d. Planeamiento estratégico y toma de decisiones (Roadmaps, Estrategias de adopción, Evaluación de riesgos)  
e. Problemas multi-etapa (Preguntas técnicas avanzadas, Arquitecturas híbridas, Casos de uso empresariales complejos)  



## Ejercicio 2: Uso de frameworks como RCTFR o SOP

Objetivo: Emplear diferentes técnicas para mejoramiento de prompts y obtener respuestas de mas calidad  

Instrucciones:

1. Abra Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2. Escriba y aplique el siguiente prompt  
``` 
Explica qué es blockchain con ejemplos del mundo real
``` 

3. Mejore el prompt anterior aplicando el marco RCTFR (Role-Context-Task-Format-Restrictions).  
Escriba y aplique el siguiente prompt:

``` 
**Rol:**  
Actúa como un especialista senior en tecnologías emergentes con experiencia en explicar conceptos complejos a audiencias no técnicas, manteniendo rigor conceptual y claridad pedagógica.

**Contexto:**  
La organización [Nombre de la empresa] desea capacitar a [Tipo de audiencia: por ejemplo, “equipo comercial”, “gerencia”, “clientes corporativos”, “estudiantes”] sobre fundamentos de blockchain.  
La explicación debe ser clara, práctica y alineada a aplicaciones reales dentro de sectores como [Sector relevante: finanzas, logística, salud, retail, etc.].  
El contenido se utilizará para [Uso previsto: capacitación interna, presentación ejecutiva, documento educativo].

**Tarea:**  
Explicar qué es blockchain de manera accesible pero precisa, describiendo sus características principales y presentando múltiples ejemplos reales que demuestren su aplicabilidad en situaciones del día a día y en escenarios corporativos.  
Los ejemplos deben estar contextualizados al sector [sector elegido].

**Formato:**  
Entrega la información en la siguiente estructura:  
- Definición clara y concisa de blockchain  
- Explicación de cómo funciona (paso a paso)  
- Características clave (descentralización, inmutabilidad, consenso, etc.)  
- Ejemplos del mundo real (mínimo 4), relacionados con [sector]  
- Un cuadro comparativo entre usos tradicionales vs. usos habilitados por blockchain  
- Un cierre con un resumen ejecutivo de no más de 5 líneas  

**Restricciones:**  
- Evita tecnicismos innecesarios a menos que estén explicados.  
- No menciones criptomonedas a menos que sea estrictamente necesario para un ejemplo.  
- Mantén un tono profesional y pedagógico.  
- No incluir código ni fórmulas matemáticas.
``` 

4. Revise el resultado.

5. Como ejercicio adicional, aplique RCTFR para algun prompt que ya tenia, compare el resultado mejorado.  
RCTFR se puede aplicar para estos casos:  
a. Prompts empresariales y profesionales (Correos ejecutivos, Informes para gerencia, Propuestas comerciales, Comunicaciones legales o contractuales)  
b. Generación de documentos estructurados (Tablas comparativas, Informes técnicos, Actas de reunión, Resúmenes ejecutivos)  
c. Automatización y plantillas reutilizables (Prompts para RRHH, Prompts para soporte TI, Prompts para marketing recurrente)  
d. Evaluación de habilidades específicas (Evaluar redacción técnica, Evaluar comprensión lectora, Simular escenarios laborales)

6. Ahora escriba y aplique el siguiente prompt  
``` 
Diseña un proceso paso a paso para aprobar gastos de viaje dentro de la empresa
``` 
7. Mejore y aplique el prompt anterior aplicando el marco SOP (Standard Operating Procedure), escriba el siguiente prompt:

``` 
Actúa como un consultor senior en gestión administrativa y control financiero corporativo.  
Diseña un Standard Operating Procedure (SOP) detallado para el proceso de aprobación de gastos de viaje dentro de una empresa.  

El SOP debe incluir claramente:  
a. Objetivo del proceso (qué se busca controlar o asegurar).  
b. Alcance (áreas, tipos de viaje y colaboradores involucrados).  
c. Roles y responsabilidades (colaborador solicitante, jefe inmediato, finanzas, contabilidad, gerencia, etc.).  
d. Requisitos previos (políticas internas, topes de gasto, documentación obligatoria).  
e. Procedimiento paso a paso, numerado y secuencial, desde la solicitud del viaje hasta la liquidación final de gastos.  
f. Controles y puntos de aprobación (criterios de validación, niveles de autorización, excepciones).  
g. Entradas y salidas del proceso (formularios, comprobantes, reportes).  
h. Indicadores clave (KPIs) para medir eficiencia y cumplimiento del proceso.  
i. Riesgos comunes y medidas de mitigación.  
j. Frecuencia de revisión y mejora del SOP.
``` 
8. Como ejercicio adicional, aplique SOP para algun prompt que ya tenia, compara el resultado mejorado.  
SOP se puede aplicar para estos casos:  
a. Prompts operativos y procedimentales (Instrucciones técnicas, Procedimientos de TI, Operaciones de soporte, Checklists)  
b. Automatización y flujos repetitivos (Procesamiento de tickets, Validación de documentos, Revisión de configuraciones, Generación de reportes periódicos)  
c. Prompts para IT Operations, DevOps y SecOps (Respuesta a incidentes, Hardening de sistemas, Onboarding / offboarding técnico, Ejecución de tareas de mantenimiento)  
d. Prompts de cumplimiento y auditoría (Auditorías de seguridad, Controles regulatorios, Evaluaciones ISO / NIST / CIS, Revisión de evidencias)  
e. Prompts para capacitación basada en procesos (Manuales operativos, Guías paso a paso, Entrenamiento de personal)

## Ejercicio 3: Creación de contenido gráfico diverso

**Objetivo:** Emplear diferentes técnicas para mejoramiento de prompts y obtener respuestas de mas calidad  

**Instrucciones:**

1.	Abra Microsoft 365 Chat (https://m365.cloud.microsoft/chat)

2.	Selecciona la opción **Create** del menú lateral izquierdo


![Imagen 56.](/images/Imagen1.png "Imagen 56")


3.	Elige la opción **Create an image**


![Imagen 57.](/images/Imagen1.png "Imagen 57")


4.	Escriba y aplique alguno de los siguientes prompts (luego de escribir haga clic en **Create**):

**Opcion 1:**  
``` 
Reunión de negocios en una sala de juntas corporativa moderna. Un consultor senior de tecnología está sustentando una propuesta técnica frente a directivos, utilizando una pantalla grande con diagramas de arquitectura, indicadores KPI y gráficos técnicos. Ejecutivos sentados alrededor de una mesa, atentos y participativos. Ambiente corporativo elegante, paredes de vidrio, iluminación natural, laptops y tablets sobre la mesa. Fotografía realista, alta resolución, iluminación profesional, vestimenta formal de negocios, profundidad de campo, sin texto visible ni logotipos.
``` 


**Opcion 2:**  
``` 
Primer plano de un consultor senior explicando una propuesta técnica en una reunión de negocios, señalando una pantalla con diagramas de arquitectura tecnológica. Al fondo, ejecutivos escuchando atentamente con efecto desenfocado. Profundidad de campo reducida, iluminación cinematográfica, fotografía corporativa ultra realista, expresión segura y profesional.
``` 

**Opcion 3:**  
``` 
Reunión híbrida de negocios donde un consultor sustenta una propuesta técnica. Parte del equipo se encuentra en la sala de reuniones y otros participantes aparecen en videollamada en una pantalla grande. La presentación incluye diagramas técnicos, cronogramas y arquitectura de solución. Oficina corporativa moderna, ambiente profesional, fotografía realista, iluminación balanceada, alta definición.
``` 
5.	Espere a que se genere la imagen, y luego observe la imagen generada (imagen referencial)


![Imagen 58.](/images/Imagen1.png "Imagen 58")


6.	En las herramientas de la derecha selecciona **Transform**


![Imagen 59.](/images/Imagen1.png "Imagen 59")


7.	Describe un cambio que quieras realizar a la imagen usando un prompt ``` (ejemplo: quita 2 personas de la reunion. el consultor que expone debe estar mas animado). ``` Finalmente selecciona **Update**

8.	Observa los cambios aplicados en la imagen

9.	Nota: tambien se pueden modifcar **Style**, **Brand and color** y **Square**.


![Imagen 60.](/images/Imagen1.png "Imagen 60")


10.	Finalmente puede descargar la imagen si desea.

11.	Seleccione la opción **Create** del menú izquierdo

12.	Seleccione la opción **Create a video**


![Imagen 61.](/images/Imagen1.png "Imagen 61")

13.	Escribe y aplica el siguiente prompt, luego haz clic en Create:  
```Genera un video de marketing dinámico para impulsar la venta rápida de un producto perecible con alta rotación.  
Objetivo: incentivar la compra inmediata.  
Público objetivo: compradores habituales de supermercados.  
Duración: máximo 15 segundos.  
El video debe transmitir urgencia positiva, mostrando el producto fresco, listo para consumir, con escenas rápidas y música energética.  
Mensaje clave: “aprovéchalo hoy”, “fresco por tiempo limitado”.  
Estilo visual: moderno, colores brillantes, ritmo ágil.  
Incluye: estructura de escenas, copy sugerido y tipo de música recomendada.  
El resultado debe ser adecuado para campañas en redes sociales y pantallas digitales en tienda.
``````
14.	Espera a que el video se genere, luego observa el video generado (imagen referencial):

![Imagen 62.](/images/Imagen1.png "Imagen 62")

15.	Edita partes del transcript que desees cambiar, modifica el texto y selecciona Update. Vuelve a reproducir el video (imagen referencial)


![Imagen 63.](/images/Imagen1.png "Imagen 63")

16.	En el menú lateral derecho selecciona Adjust. Modfica Music, Voice y Brand and color a tu gusto. Vuelve a reproducir el video.

![Imagen 64.](/images/Imagen1.png "Imagen 64")

17.	Si deseas realizar ajustes mas apreciables al video selecciona Transform en el menú lateral derecho. Puedes cambiar el prompt, ajustar el Tone y hacer clic en Regenerate.

![Imagen 65.](/images/Imagen1.png "Imagen 65")

18.	Seleccione la opción Create del menú izquierdo

19.	Elige la opción Design an infographic (imagen referencial)

![Imagen 66.](/images/Imagen1.png "Imagen 66")

20.	Aplica el siguiente prompt  
```
Diseña una infografía de concientización sobre el uso de contraseñas seguras para nuestros accesos de usuario. Incluye problema, impacto, datos relevantes y acciones recomendadas. Usa un tono claro, responsable y motivador.
```
21.	Ajusta Brand and Color y Portrait a tu gusto, luego selecciona Create

22.	Observa el resultado generado

23.	Seleccione la opción Create del menú izquierdo

24.	Selecciona la opción Create a story (imagen referencial)

![Imagen 67.](/images/Imagen1.png "Imagen 67")

25.	Escribe y aplica el siguiente prompt, luego haz clic en Create:  
```
Desarrolla una historia sobre innovación en la que un equipo adopta una nueva idea o tecnología y transforma su forma de trabajar. El tono debe ser motivador y realista.  
Debe tener 5 escenas con la siguiente estructura

ESCENA 1  
Titulo: Un nuevo reto aparece  
Debe mostrarse un equipo de trabajo preocupado

ESCENA 2:  
Titulo: Como resolverlo  
El equipo debate e intercambia ideas

ESCENA 3:  
Titulo: Blockchain al rescate  
El equipo define que Blockchain es la tecnologia ideal para resolver el problema

ESCENA 4:  
Titulo: Resolviendo el reto  
El equipo aplica Blockchain, se toman acciones concretas

ESCENA 5:  
Titulo: Transformacion lograda  
El reto de innovación fue resuelto, se muestra al equipo exitoso
```
26.	Espera a que se genere la historia

27.	Puede editar alguna de las escenas si desea (imagen referencial):

![Imagen 68.](/images/Imagen1.png "Imagen 68")

28.	Puede modificar la imagen con un nuevo prompt, también ajustar **Brand and Color, Style y Square** a su gusto, luego seleccione **Update**

29.	Puede repetir el procedimiento para editar las demás escenas (imagen referencial):

![Imagen 69.](/images/Imagen1.png "Imagen 69")

30.	Observe el resultado generado. Si desea exporte el resultado a PowerPoint.

31.	Seleccione la opción **Create** del menú izquierdo

32.	Elige la opción **Design a poster** (imagen referencial)

![Imagen 70.](/images/Imagen1.png "Imagen 70")

33.	Escriba y aplique el siguiente prompt y luego haga clic en **Create:**  
```
Crea un póster de lanzamiento para la nueva versión de la Intranet Corporativa, destacando su propuesta de valor, beneficio principal y un llamado a la acción claro.
```
34.	Ajusta **Brand and Color** a tu gusto, luego selecciona **Create**

![Imagen 71.](/images/Imagen1.png "Imagen 71")

35.	Observa el resultado generado. Realiza los ajustes que desees.

36.	Elige la opción **Design a banner (si no la ubicas selecciona More…, Banner)**



![Imagen 72.](/images/Imagen1.png "Imagen 72")

(imagen referencial)

![Imagen 73.](/images/Imagen1.png "Imagen 73")


37.	Aplica el siguiente prompt  
```
Genera un banner para campaña por tiempo limitado sobre el producto Toallas de baño para bebé. El mensaje debe transmitir urgencia positiva y claridad.
```
38.	Selecciona **Teams post** y luego selecciona **Create**

![Imagen 74.](/images/Imagen1.png "Imagen 74")

39.	Observa las alternativas generadas. Sobre la que desees selecciona Edit (imagen referencial)


![Imagen 75.](/images/Imagen1.png "Imagen 75")

40.	Aplica las modificaciones que desees usando las opciones del menú derecho como **Transform, Edit** y actualiza con **Update**
