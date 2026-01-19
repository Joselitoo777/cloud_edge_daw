# # Tarea (a+b) · Cloud: niveles y funciones (DAW 1º)

## 🅰️ Tarea A — Niveles de cloud (IaaS/PaaS/SaaS)
Crea una tabla con 10 servicios reales. Incluye enlace oficial y justifica responsabilidades.

| **Servicio**                         | **Categoría** | **Enlace oficial**                                                                                                               | **Justificación (qué gestiona el proveedor vs. el equipo)**                                                     |
| ------------------------------------ | ------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Amazon EC2**                       | IaaS          | [https://aws.amazon.com/ec2/](https://aws.amazon.com/ec2/) ([Wikipedia][1])                                                      | *Proveedor* gestiona la infraestructura, red y virtualización. *Equipo* gestiona OS, middleware y aplicaciones. |
| **Microsoft Azure Virtual Machines** | IaaS          | [https://azure.microsoft.com/services/virtual-machines/](https://azure.microsoft.com/services/virtual-machines/) ([genos.es][2]) | *Proveedor* ofrece hardware virtualizado. *Equipo* gestiona OS, configuración y apps.                           |
| **Google Compute Engine**            | IaaS          | [https://cloud.google.com/compute](https://cloud.google.com/compute) ([Wikipédia][3])                                            | *Proveedor* provee servidores y redes. *Equipo* instala y mantiene software y servicios.                        |
| **Google App Engine**                | PaaS          | [https://cloud.google.com/appengine](https://cloud.google.com/appengine) ([Google Cloud][4])                                     | *Proveedor* gestiona infraestructura, runtime y ajustes de escalado. *Equipo* desarrolla y despliega código.    |
| **AWS Elastic Beanstalk**            | PaaS          | [https://aws.amazon.com/elasticbeanstalk/](https://aws.amazon.com/elasticbeanstalk/) ([Wikipedia][5])                            | *Proveedor* administra infraestructura y plataforma. *Equipo* sube y configura la app.                          |
| **Heroku**                           | PaaS          | [https://heroku.com/](https://heroku.com/) ([Wikipedia][6])                                                                      | *Proveedor* gestiona stack, runtime, escalado y servidores. *Equipo* desarrolla y despliega.                    |
| **Microsoft 365 (Office 365)**       | SaaS          | [https://www.microsoft.com/microsoft-365](https://www.microsoft.com/microsoft-365) ([genos.es][2])                               | *Proveedor* ofrece app completa y datos alojados. *Equipo/usuario* solo usa la app.                             |
| **Salesforce (CRM)**                 | SaaS          | [https://www.salesforce.com/](https://www.salesforce.com/) ([Stackscale][7])                                                     | *Proveedor* gestiona la app empresarial completa. *Usuario* configura flujos y usa datos.                       |
| **Gmail (Google Workspace)**         | SaaS          | [https://workspace.google.com/products/gmail/](https://workspace.google.com/products/gmail/) ([Stackscale][7])                   | *Proveedor* gestiona la plataforma de correo y almacenamiento. *Usuario* solo envía/recibe correo.              |
| **Zoom**                             | SaaS          | [https://zoom.us/](https://zoom.us/) ([Blog de HubSpot][8])                                                                      | *Proveedor* gestiona la infraestructura de videoconferencia y servicios. *Usuario* solo usa la app.             |

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
(Pega aquí el diagrama)

### Explicación (8–12 líneas)
(Describe el flujo front → API → BBDD/storage y dónde entra la cloud)

### Mapeo de funciones cloud a componentes (mínimo 3)
- Procesamiento → …
- Ejecución → …
- Almacenamiento → …
- Intercambio → … (opcional si ya tienes 3)

## 📚 Fuentes (enlaces oficiales)
(Enlaces oficiales usados en la tabla A y en la B)
