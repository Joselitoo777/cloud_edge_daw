# # Tarea (a+b) · Cloud: niveles y funciones (DAW 1º)

## 🅰️ Tarea A — Niveles de cloud (IaaS/PaaS/SaaS)
Crea una tabla con 10 servicios reales. Incluye enlace oficial y justifica responsabilidades.

| Servicio                         | Proveedor                 | Nivel (IaaS/PaaS/SaaS) | Enlace oficial                                                   | ¿Qué gestiona el proveedor?                     | ¿Qué gestiona el equipo/usuario?      |
| -------------------------------- | ------------------------- | ---------------------- | ---------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------- |
| Amazon EC2                       | AWS                       | IaaS                   | [Enlace](https://aws.amazon.com/ec2/)                            | Infraestructura, red y virtualización           | OS, middleware, aplicaciones          |
| Microsoft Azure Virtual Machines | Microsoft                 | IaaS                   | [Enlace](https://azure.microsoft.com/services/virtual-machines/) | Hardware virtualizado, red                      | OS, configuración, aplicaciones       |
| Google Compute Engine            | Google                    | IaaS                   | [Enlace](https://cloud.google.com/compute)                       | Servidores, almacenamiento y red                | OS, software, servicios               |
| Google App Engine                | Google                    | PaaS                   | [Enlace](https://cloud.google.com/appengine)                     | Infraestructura, runtime, escalado automático   | Desarrollo y despliegue de código     |
| AWS Elastic Beanstalk            | AWS                       | PaaS                   | [Enlace](https://aws.amazon.com/elasticbeanstalk/)               | Infraestructura y plataforma                    | Subida y configuración de la app      |
| Heroku                           | Salesforce                | PaaS                   | [Enlace](https://www.heroku.com/)                                | Stack, runtime, servidores y escalado           | Desarrollo y despliegue de apps       |
| Microsoft 365 (Office 365)       | Microsoft                 | SaaS                   | [Enlace](https://www.microsoft.com/microsoft-365)                | Aplicaciones completas, almacenamiento y datos  | Uso de la aplicación                  |
| Salesforce (CRM)                 | Salesforce                | SaaS                   | [Enlace](https://www.salesforce.com/)                            | Aplicación empresarial completa                 | Configuración de flujos, uso de datos |
| Gmail (Google Workspace)         | Google                    | SaaS                   | [Enlace](https://workspace.google.com/products/gmail/)           | Plataforma de correo y almacenamiento           | Envío y recepción de correo           |
| Zoom                             | Zoom Video Communications | SaaS                   | [Enlace](https://zoom.us/)                                       | Infraestructura de videoconferencia y servicios | Uso de la aplicación                  |


[1]: https://en.wikipedia.org/wiki/Amazon_Elastic_Compute_Cloud?utm_source=chatgpt.com "Amazon Elastic Compute Cloud"
[2]: https://genos.es/iaas-paas-saas?utm_source=chatgpt.com "Todo sobre IaaS PaaS SaaS services | Servicios Cloud"
[3]: https://pt.wikipedia.org/wiki/Plataforma_Google_Cloud?utm_source=chatgpt.com "Plataforma Google Cloud"
[4]: https://cloud.google.com/appengine?utm_source=chatgpt.com "App Engine Application Platform"
[5]: https://es.wikipedia.org/wiki/AWS_Elastic_Beanstalk?utm_source=chatgpt.com "AWS Elastic Beanstalk"
[6]: https://en.wikipedia.org/wiki/Heroku?utm_source=chatgpt.com "Heroku"
[7]: https://www.stackscale.com/es/blog/modelos-de-servicio-cloud/?utm_source=chatgpt.com "Modelos de servicio cloud: IaaS, PaaS y SaaS | Stackscale"
[8]: https://blog.hubspot.es/service/iaas-paas-saas?utm_source=chatgpt.com "Qué es IaaS, PaaS y SaaS: diferencias clave y ejemplos"

IaaS (Infrastructure as a Service): el proveedor ofrece infraestructura virtualizada (servidores, red, almacenamiento). El equipo cliente instala y gestiona sistema operativo, middleware y aplicaciones.


PaaS (Platform as a Service): el proveedor ofrece plataforma lista con runtime y herramientas de desarrollo, liberando al equipo de gestionar la infraestructura y la plataforma subyacente; el equipo se enfoca en desarrollar y desplegar aplicaciones.


SaaS (Software as a Service): el proveedor ofrece software completo accesible por internet; gestiona todo el stack (infraestructura, plataforma y aplicación). El equipo/usuario solo utiliza el servicio.

## 🅱️ Tarea B — Funciones principales de cloud (arquitectura)
Incluye un diagrama (ASCII/Mermaid/imagen) y una explicación breve.

### Diagrama
flowchart LR

    A[Usuario / Browser] -->|HTTP(S) Request| B[Frontend (Web App)]
    
    B -->|API Call| C[API / Backend Service]
    
    C -->|Consulta/Actualiza| D[(Base de Datos)]
    
    C -->|Guarda/Recupera archivos| E[Storage (S3 / Blob)]
    
    D -->|Respuesta| C
    
    E -->|Respuesta| C
    
    C -->|Datos procesados| B
    
    B -->|Renderiza| A


### Explicación (8–12 líneas)
El usuario interactúa con la aplicación web desde el navegador.

El frontend envía solicitudes HTTP(S) al API.

El backend procesa la lógica de negocio y decide si necesita datos de la base de datos o archivos del storage.

La base de datos devuelve información estructurada (usuarios, productos, etc.).

El storage devuelve o guarda archivos grandes (imágenes, PDFs, logs).

El backend integra datos de ambos componentes y los prepara para la app.

El frontend recibe la respuesta, renderiza la información y muestra resultados al usuario.

Cada interacción puede desencadenar nuevos llamados al API según la navegación.

Los logs, cachés y métricas se pueden almacenar en servicios cloud adicionales.

El flujo garantiza escalabilidad, redundancia y disponibilidad gracias a los servicios en la nube.

### Mapeo de funciones cloud a componentes (mínimo 3)
| **Componente** | **Función Cloud**                                            | **Servicio Ejemplo**                      |
| -------------- | ------------------------------------------------------------ | ----------------------------------------- |
| Base de datos  | Base de datos administrada, backup automático, escalabilidad | Amazon RDS / Azure SQL Database           |
| Storage        | Almacenamiento de objetos, replicación, CDN                  | Amazon S3 / Azure Blob Storage            |
| API / Backend  | Autoescalado, balanceo de carga, monitoreo                   | AWS Elastic Beanstalk / Azure App Service |
| Frontend       | Distribución global, caching, SSL automático                 | CloudFront / Azure CDN                    |
| Observabilidad | Logs, métricas y alertas                                     | CloudWatch / Azure Monitor                |


## 📚 Fuentes (enlaces oficiales)
1 https://en.wikipedia.org/wiki/Amazon_Elastic_Compute_Cloud?utm_source=chatgpt.com "Amazon Elastic Compute Cloud"

2 https://genos.es/iaas-paas-saas?utm_source=chatgpt.com "Todo sobre IaaS PaaS SaaS services | Servicios Cloud"

3 https://pt.wikipedia.org/wiki/Plataforma_Google_Cloud?utm_source=chatgpt.com "Plataforma Google Cloud"

4 https://cloud.google.com/appengine?utm_source=chatgpt.com "App Engine Application Platform"

5 https://es.wikipedia.org/wiki/AWS_Elastic_Beanstalk?utm_source=chatgpt.com "AWS Elastic Beanstalk"

6 https://en.wikipedia.org/wiki/Heroku?utm_source=chatgpt.com "Heroku"

7 https://www.stackscale.com/es/blog/modelos-de-servicio-cloud/?utm_source=chatgpt.com "Modelos de servicio cloud: IaaS, PaaS y SaaS | Stackscale"

8 https://blog.hubspot.es/service/iaas-paas-saas?utm_source=chatgpt.com "Qué es IaaS, PaaS y SaaS: diferencias clave y ejemplos"
