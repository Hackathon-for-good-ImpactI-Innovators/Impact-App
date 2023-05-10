# ImpactInnovators-CruzRoja

Repositorio para el proyecto del grupo Impact Innovators en el Hackthon for Good Spain de AWS - España. 
Una solución que mejora la experiencia de los usuarios de Cruz Roja y sus beneficiarios a través de una aplicación web.  

### Propuesta de valor

(APP_NAME) es una aplicación que facilita la labor de los empleados y voluntarios de Cruz Roja permitiendoles poder brindar ayuda humanitaria de una forma más cercana.
La persona que solicita ayuda y el trabajador de Cruz Roja mantienen una conversación que es grabada, almacenada y convertida a texto utilizando los servicios de AWS.
Ese texto mediante el uso de Machine Learning y el uso de servicios de AWS como SageMaker es convertido y devuelto al trabajador de Cruz Roja en forma de información categorizada y facil de consultar.

### Servicios usados de AWS
- <b>Amazon S3 Buckets</b> para el almacenamiento de archivos de audio, texto, json, etc.
- <b>Amazon Transcribe</b> para convertir los archivos de audio a texto.
- <b>Secrets Manager</b> para el almacenamiento de secretos de forma segura.
- <b>CloudWatch</b> para el registro de actividades.
- <b>Elastic Beanstalk</b> para el hospedaje de la web api.
- <b>SageMaker</b> para generar modelos de MLP.
- <b>AWS Lambda</b> para ejecutar piezas de código ejecutables antes un evento, como puede ser un archivo subido a un S3 bucket.
- <b>Amazon Quick Sight</b> para la creacion y visualización de datos en forma de gráficos.

### Repositorios de código

En esta organización, teneis 2 repositorios de código donde se detalla la funcionalidad de cada uno y los servicios utilizados:

https://github.com/Hackathon-for-good-ImpactI-Innovators/Impact-DataInsights

https://github.com/Hackathon-for-good-ImpactI-Innovators/ImpactInnovatorsAPI


### Miembros del equipo

Berta Bonastre
Email: bbonastre1@gmail.com  

Cristian Rodríguez 
Email: C.fernandoro@gmail.com  

Gabriel Canosa 
Email: g.canosa90@gmail.com
