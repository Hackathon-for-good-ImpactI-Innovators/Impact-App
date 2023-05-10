# Hackathon For Good: La Región de AWS en España al Servicio de la Sociedad

# Impact Innovators - Proyecto para Cruz Roja España en colaboración con AWS España

Repositorio para el proyecto del grupo Impact Innovators en el Hackthon for Good Spain de AWS - España 2023.
Una solución que mejora la experiencia de los usuarios de Cruz Roja y sus beneficiarios a través de una aplicación web.

##  Descripción del Proyecto

Nuestra solución te ayuda a arropar mejor a quienes lo necesitan. Olvídate de tratar a las personas con un formulario, como si fuera un cliente y centrate en simplemente escuchar, entender y ayudar.


### Propuesta de valor

(Impact - App) es una aplicación que facilita la labor de los empleados y voluntarios de Cruz Roja permitiendoles poder brindar ayuda humanitaria de una forma más cercana.
La persona que solicita ayuda y el trabajador de Cruz Roja mantienen una conversación que es grabada, almacenada y convertida a texto utilizando los servicios de AWS.
Ese texto mediante el uso de Machine Learning y el uso de servicios de AWS como SageMaker es convertido y devuelto al trabajador de Cruz Roja en forma de información categorizada y facil de consultar.


Mas que resolver un problema, lo que buscamos es ayudar a Cruz Roja España con una solución	tecnológica con base en los servicios on-cloud de AWS España que permita mejorar los procesos de valoración y acogida en terreno o sus oficinas de sus beneficiarios.

Con nuestra web-app lo que buscamos es un proceso que ayude al voluntario o trabajador en ofrecer un servicio más cálido y menos burocrático, en el que el usuario no tenga que teclear en un ordenador todos los datos del usuario que busca ayuda.

Además de eficientar los procesos de toma de información, nuestra solución ofrece una visualización de los datos y su análisis, y busca optimizar el almacenamiento de los datos para que estén guardados de forma segura y accesible y puedan posteriormente servir para su activación tanto en el seguimiento del usuario como en soluciones innovadoras como la utilización de modelos de Machine Learning en el futuro.

### ¿Qué hacemos?

Nuestra propuesta se centra en las siguientes soluciones con una interfaz de usuario muy fácil y práctica para que los voluntarios y trabajadores de la Cruz Roja puedan ayudar a más gente.

- En primer lugar, proveemos de un sistema de grabación en el navegador para grabar al usuario bajo su consentimiento explícito en su entrevista de acogida y procesar está conversación para transcribirla, traducirla y almacenarla para generar un formulario autorrellenado de forma automática.

-  En segundo lugar, con la información almacenada la procesaremos para analizar la información y mostrarla en un dashboard con estadisticas agregadas que ayuden a Cruz Roja a tomar decisiones y dos preparar la información para aplicar modelos de procesamiento de lenguaje natural en el futuro. Generando este "corpus" de entrevistas se podrá automatizar un modelo de generación del formulario con alta precisión. Esta última parte no está en nuestra demo dada el escazo tiempo para entrenar un modelo y datos para entrenarlo. 

- Por útlimo, nuestra web app ofrece la posibilidad de que el voluntario pida ayuda a otros compañeros, se capacite con la misma información de Cruz Roja y pueda ver las preguntas de la entrevista en múltiples idiomas.

## ¿Cómo lo hacemos?

### Arquitectura

Api design and web app:
![App Screenshot](https://user-images.githubusercontent.com/57040777/236698243-ac45504c-aeef-4bbf-8ec5-e6ed57255057.jpg) 

Data Transformations and reporting:
![App Screenshot](https://github.com/Hackathon-for-good-ImpactI-Innovators/Impact-DataInsights/blob/main/pythonfunctions/Hackathon_AWS-Page-1.jpg) 

Utilizando los siguientes servicios de AWS en diferentes regiones, dando prioridad siempre a la nueva región de España: 

### Servicios usados de AWS
- <b>Amazon S3 Buckets</b> para el almacenamiento de archivos de audio, texto, json, etc.
- <b>Amazon Transcribe</b> para convertir los archivos de audio a texto.
- <b>Secrets Manager</b> para el almacenamiento de secretos de forma segura.
- <b>CloudWatch</b> para el registro de actividades.
- <b>Elastic Beanstalk</b> para el hospedaje de la web api.
- <b>SageMaker</b> para generar modelos de NLP.
- <b>AWS Lambda</b> para ejecutar piezas de código ejecutables antes un evento, como puede ser un archivo subido a un S3 bucket.
- <b>Amazon Quick Sight</b> para la creacion y visualización de datos en forma de gráficos.

### Repositorios de código

En esta organización, teneis 2 repositorios de código donde se detalla la funcionalidad de cada uno y los servicios utilizados:

https://github.com/Hackathon-for-good-ImpactI-Innovators/Impact-DataInsights

https://github.com/Hackathon-for-good-ImpactI-Innovators/ImpactInnovatorsAPI
# Demo Video

Para ver la solución integral pueden dirigirse a este link: 

https://share.vidyard.com/watch/LsxSufKf9usPrNBu663Qs7 

Para las descripciones técnicas: 

Api service: 
https://drive.google.com/drive/folders/1CdklyiheV5JxB9y6lYoPQppFMBvoOSld?usp=sharing

Data Insights y Procesamiento de datos:
https://drive.google.com/file/d/1DTQNVNdsm31TgtuiUy1gRH7jyztDI8yP/view?usp=drive_web


# Miembros: 

Berta Bonastre
Email: bbonastre1@gmail.com  

Cristian Rodríguez 
Email: C.fernandoro@gmail.com  

Gabriel Canosa 
Email: g.canosa90@gmail.com
