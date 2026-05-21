 # Manual de explotacion
 **Fecha:** 21 de mayo de 2026
 **Autor:** Joaquin Torrubia Oria
  
  ## 1. Introduccion y arquitectura
  El sistema ERP/CRM esta basado en Odoo

  Esta compuesta por 

  **servidor web**
  **Base de datos Postgresql**
  utiliza **docker-compose**

  ## 2. Guia de instalacion de reinstalacion

  servidor con docker y docker compose instalados

  docker-compose up -d
  esperar unos minutos 

  enlace : http://localhost

  ## 3. Seguridad y control de acceso

 Estos estan definidos en Odooo:

 Aministrador tiene acceso total
 contable se encarga de la gestion de facturas
 comercial se encarga de los clientes y ventas

 La constraseña debe ser fuerte con minimo de 12 caracteres.
 

 ## 4. Procedimiento de Backup y restauracion

 Para hacer el backup de la base de datos 
 docker exec -t willmantech_db pg_dump -U odoo -d odoo > backup_$(date +%y%m%d).sql

 
 
 
 
 
 
 
 
 # # Entregable 1: Generación del Informe Dinámico

 Para utilzar la sintaxis Qweb utilzado como referencia, la actividad ecosistema Odoo y una pagina web https://angelmoya.es/blog/odoo/dia-21-creacion-de-informes-pdf-con-qweb-documentos-imprimibles/

