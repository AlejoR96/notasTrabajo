# Correo misena
> Se pidio desconectar los siguientes servidores VSMISENAAPP02	172.29.19.163
VSMISENABD01	172.29.10.183
ya que no hace parte de la infraestructura el dia . 


![alt text](Misena_img1.png)

# PAP Bizagi
[comment]: <Descripcion de la herramienta>
> Es una herramienta en donde cumple el siguiente objetivo 
> Plataforma de implementación y automatización de Procesos
La plataforma cuenta con los siguientes procesos:
BPM - Registro Plan Anual de Adquisiciones y Etapa Inicial del Proceso de Gestión Contractual.
### Categorización de HT: Medio
### Lider funcional: tres (3) LF 
* Jenny Angelica Algarra Caballero Correo jalgarra@sena.edu.co  
* Jared Jafet Forero Alvarez > correo: jfforero@sena.edu.co  
* Javier Armando Cardenas Pena correo : jacardenasp@sena.edu.co  
### Lider tecnico: Uno (1) LT
* Maria Fernanda Solorzano  Correo mfsolorzano@sena.edu.co
### Arquitectura tecnologica: Servicio cloud y base de datos en sql server
### integraciones con: LDAP y Directorio activo.

# Ambientes aprobados

## Desarrollo 
## uno (1) servidor de aplicación
## VSDEAPBIZG01	172.30.176.127
## uno (1) servidor de base de datos
## VSDEBDBZIG01	172.30.162.161
## Capa media: ISS
## Preproducción
## uno (1) servidor de aplicación
## VSPPAPBIZG01	172.30.164.146
## uno (1) servidor de base de datos
## VSPPBDBIZG01	172.31.4.177
## Capa media: ISS
## Producción
## Tener en cuenta que la solucion en produccion se va a encontrar desplegada en la infraestructura nube del proveedor

# Intrasuite

## Ejecutar una presentacion en donde se detalle los errores econtrados 
## Razones en donde se evidencia que solicitudes por correo no son respondidas ni ejecutadas en su respectivo tiempo
## No queda claro quien es el responsable de la actividad ni los tiempos que tomo para las respuesta
## No queda la traza de manera publica ya que los correos solo es informado quien es copiado y ademas no esta en la traza GSI o cualquier interesado de nivel jerarquico superior
[comment]: <Colocar img >
![alt text](intrasuite.png)

## Revisar ultima Correo Misena 

# Tecnoparque 
## Validar informacion de contacto 
## Activar nuevamente agenda PAP

## ETL 
## Realizar manual de cargue de datos desde excel a SQL 
## Validar cotejamientos en MySQL para las tildes 

# Portal Web institucional 
## crear WO para informar actualización de LF y LT
## enviar correo a Hector solicitando informacion de proveedor de soporte y la licencia 

# 26 de marzo 2024
# AGENCIA PÚBLICA DE EMPLEO (PORTAL)
## Agregar en la arquitectura los servidores wiki 
##  vspdbdwkape01 vspdapwkape01
## -----------------
## KACTUS | APROBADO
## SISTEMA DE INFORMACIÓN DE BIBLIOTECAS - ALEPH500 | APROBADO
## SISTEMA DE INFORMACIÓN DE GESTIÓN VIRTUAL DE APRENDICES (SGVA) | 
## GESTIÓN DOCUMENTAL ONBASE
## SERVICIO MÉDICO ASISTENCIAL (SMA)

# 22 de abril 
## Validar formatos de PAP por lo que estan vigentes consultar con calidad para proponer plan de trabajo 
## Formato de script de pruebas funcionales 

# 16 de mayo 2024
# DSNFT 
## TOMCAT 8.5 ultima version 
## java 1.8.0_261

## Ejecutar actividades para ampliacion de memoria el dia 24 de Mayo de 2024 

## Memoria actual 31 GB objetivo de aumento es tener un total 43 GB aumento 12 GB por nodo.

## ajustar arquitectura de Registradura ANI de acuerdo a las integraciones 


# 17 de junio 

## Revisar Sede electronica componentes tramites si tiene integraciones o interoperabilidades con otras aplicaciones y enviar reporte a ing Yohan 

# 21 De Junio 

# * Se debe validar de validar los chatbot de automation anywhere control room actualizaron y  maneja las demas/.

# * tener presente las app de en PAP

# * Raas solo se activa por demanda de acuerdo a solicitud de LT 

# * Se entrega documentacion de los servicios o app montadas en AZURE en el proceso de migracion

# * Seguimiento de PAP Sistemas de vigilancia (Orientar PAP).

# * Aplicaciones migradas 70 y operativas 54

# * Nslookup a las aplicaciones migradas.


# 26 DE JUNIO 2024 

# Cambios para esta semana 

##  PLATAFORMA DE SALUD DIGITAL CSS --->  APP MIGRADA Y ENTREGADA AL NUEVO PROVEEDOR NO APLICA A TELEFONICA 
##  SISTEMA DE INFORMACIÓN DE RECAUDO, CARTERA Y COBRO COACTIVO (SIREC) ---> APLICA CAMBIO A TELEFONICA(APLICACIONES), PREPARAR MEDIOS VA POR ANSIBLE 
## SISTEMA DE INFORMACIÓN DE GESTIÓN VIRTUAL DE APRENDICES (SGVA) ---> APLICA CAMBIO A TELEFONICA(APLICACIONES), PREPARAR MEDIOS VA POR ANSIBLE
 


desplegar el archivo anexo en /var/www/html/sirec/application/controllers/aplicacion_pago_cnm.php 

desplegar el archivo anexo en /var/www/html/sirec/application/controllers/multasministerio.php 

desplegar el archivo anexo en /var/www/html/sirec/application/controllers/reporteador.php

desplegar el archivo anexo en /var/www/html/sirec/application/models/aplicacion_pago_cnm_model.php

desplegar el archivo anexo en /var/www/html/sirec/application/models/reporteador_model.php

desplegar el archivo anexo en /var/www/html/sirec/application/views/reporteador/certificado_no_misional.php

en los servidores  172.29.19.105, 172.29.19.106, 172.29.19.108

