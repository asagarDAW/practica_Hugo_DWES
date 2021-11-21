---
title: "Comunicación Cliente-Servidor"
date: 2021-11-20T22:28:13+01:00
draft: false

---
***

**Diagrama comunicación Cliente-Servidor Web**
{{< mermaid align="left" >}}
graph LR;
    A[Usuario] -->B[Navegador]
    B -->|solicita recurso| F(HTTP) -->|solicitud a servidor| C{<strong>Servidor Apache</strong>}
    B -->|solicita recurso| G(HTTPS) -->|solicitud a servidor| C
    C -->|construye recurso| I(construcción de recurso)
    I --> J[MySQL] --> I
    I --> K[PHP] --> I
    I -->|recurso construido| C
    C -->|recurso HTML+Javascript| B
    
{{< /mermaid >}}

### Pasos del proceso de carga web

* El proceso que sigue la comunicación cliente-servidor se inicia cuando un usuario hace uso de un navegador web que solicita un recurso al servidor para poder cargar la web.

* La solicitud o petición que se envía al servidor puede ser de protocolo HTTP o si está securizada HTTPS. Ambas peticiones siguen protocolo TCP/IP. 

* La petición de recurso es enviada en este caso al servidor Apache, tal y como se indica en el diagrama.

* Entonces el servidor Apache hace uso de sus módulos, en el caso del diagrama son MySQL y PHP para construir el recurso solicitado.

* Una vez construído el recurso, con HTML y Javascript, el servidor Apache lo devuelve ya como respuesta al navegador, y de ahí al usuario.

