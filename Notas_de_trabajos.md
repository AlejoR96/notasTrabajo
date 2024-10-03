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

# Cambio - Despliegue SIREC version 3.6.3.9 - Ajustes para dispersión de pagos FIC

## desplegar el archivo anexo en /var/www/html/sirec/application/controllers/reporteador.php

## desplegar el archivo anexo en /var/www/html/sirec/application/models/reporteador_model.php

## desplegar el archivo anexo en /var/www/html/sirec/application/views/reporteador/certificados.php

## En los nodos  
## 172.29.19.105, 
## 172.29.19.106, 
## 172.29.19.108


CITAS ABUELA 

VSGSEFRONAAPP01-BCK
VSGSEFRONAAPP02-BCK
VSGSEPENTHAAPP02-BCK
VSGSETOMAPP02-BCK
VSPDAPOSOA01-BCK
VSGSEIISAPP02-BCK

VSPDBDOSOA01-BCK
Sc01zdbadm21-BCK
Sc01zdbadm09-BCK

Enviar correo a linux para que validen los servidores si estan apagado 
Copiar a Paola Burgos, OVM, Claudia. 
Validar segmento de red 


Ejecutar una WO  indicando que los servidores estan apagado 



KActus 
172.29.19.229:443 RDP ----> Validar que IP de balanceo es esta


cd /appserver/oracle/Oracle/Middleware/Oracle_Home/user_projects/domains/vspreapconv01/bin
. ./setDomainEnv.sh
java weblogic.WLST
from weblogic.security.internal import BootProperties
BootProperties.load("/appserver/oracle/Oracle/Middleware/Oracle_Home/user_projects/domains/vspreapconv01/servers/AdminServer/security/boot.properties", false)
prop = BootProperties.getBootProperties()
print "username: " + prop.getOneClient()
print "password: " + prop.getTwoClient()
tiene menú contextual



Constructora: Prodesa
Nombre del proyecto: Alonda
Fecha de entrega del apto : 
Monto de crédito : 
Precio del apartamento:
Torre:    interior :       apto:
Ya tiene vivienda o aparece en escrituras?
Estado civil:
Tiene hijos? :
Profesión :
Dirección de residencia:
Teléfono fijo:
Teléfono celular:
Correo electronico:
Referencia familiar (nombre completo y numero de celular) :
Referencia personal (nombre completo y numero de teléfono celular) :
Plazo el crédito:
PARA EMPLEADO 
Nombre de la empresa:
NIT de la empresa:
Dirección de la empresa:
Teléfono de la empresa:
Cargo:
Tipo de contrato(termino):
Salario:
Fecha de ingreso:
SI ES INDEPENDIENTE
Ingreso o salario :
Actividad o cargo:



/resourcedata/ADMIN/SOFIA/Scripts/Deploy_sofia_Nodo1.sh /resourcedata/ADMIN/SOFIA/deploys/30082024/jboss-as-oferta-gwt-ear.ear


/resourcedata/ADMIN/SOFIA/Scripts/Deploy_sofia_Nodo1.sh /resourcedata/ADMIN/SOFIA/backups/2024_08_30_20_00/sofia-1.1.1.ear

/resourcedata/ADMIN/OFERTA/Scripts/Deploy_oferta_Nodo1.sh /resourcedata/ADMIN/OFERTA/deploys/30082024/jboss-as-oferta-gwt-ear.ear



Consola 
Credenciales - Laboratorio weblogic
user>weblogic
pass>123456789#

ssh 
user weblogic 
pass weblogic14

user root 
pass alejandro 

user oracle
pass alejandro14

Comandos weblogic 
ifconfig
tail -100 nohup.out 
nohup ./startWeblogic.sh &
nohup ./stopWeblogic.sh &


./startWebLogic.sh -Dweblogic.management.username=weblogic -Dweblogic.management.password=123456789# -Dweblogic.system.StoreBootIdentity=true -Dweblogic.configuration.schemaValidationEnable=false


## Plantillas 

Procedemos a realizar la solicitud expresada sobre el ambiente QA en la aplicación SOFIA PLUS  y compartiremos los resultados.

Buenas tardes Compañeros @Mesa de Servicio por favor su apoyo en crear el ticket en la herramenta de gestión GLPI para proceder con la solicitud. 
 
Muchas gracias 


## Comandos APACHE 

httpd.exe -t  ----> revisar la Sintaxis de SSL 
httpd.exe -k restart  -----> Reiniciar el apache por CMD
httpd.exe -k install -n "Apache2.4" -----> Instalar apache por CMD 
httpd.exe -k start   -n "Apache2.4" -----> Iniciar el apache 


/resourcedata/ADMIN/SOFIA/Scripts/Deploy_sofia_Nodo1.sh  /resourcedata/ADMIN/SOFIA/deploys/16092024/sofia-1.1.1.ear


## prueba de relay | correo 

telnet relay.sena.edu.co 25
ehlo
mail from: ape@sena.edu.co
rcpt to: jaira.rivera@sticcoltel.onmicrosoft.com
data
subject: prueba de correo 07.10 am
esto es una prueba
.
enter


# Aplicaciones 
# Rues 
## preproduccion
* sc01zfadmqa01	172.29.10.130 ----> S.O Oracle Solaris 11.4 rol APP | BD
* sc01zfdbqa01	172.29.10.224 ----> S.O Oracle Solaris 11.4 rol BD
* sc01zfmdlqa01	172.29.10.160 ----> S.O Oracle Solaris 11.4 rol APP | BD
* sc01zfmdlqa02	172.29.10.213 ----> S.O Oracle Solaris 11.4 rol APP | BD
* sc01zfdbqa02	172.29.10.228 ----> S.O Oracle Solaris 11.4 rol  BD
## produccion 
* VSPDAPXROAD01	172.30.163.65 ----> S.O Red Hat Enterprise Linux 7 Rol APP
# Seguimiento a proyectos   y presupuestos
## Desarrollo 
* sc01zdbadm10	172.29.10.59 ----> S.O Oracle Solaris 11.4 Rol BD
* sc01zdbadm22	172.29.10.179 ----> S.O Oracle Solaris 11.4 Rol BD 
## preproduccion
* VSPPAPDASHB01	172.30.164.28 ----> S.O Windows Server 2019  Standard Rol APP
* VSPPAPSDCACE01	172.30.164.143 ---->S.O  Red Hat Enterprise Linux 8 Rol APP
* VSPPAPSDCACE02	172.30.164.144 ----> S.O Red Hat Enterprise Linux 8 Rol APP
* sc01zdbadm10	172.29.10.59 ----> S.O  Oracle Solaris 11.4 Rol BD
* sc01zdbadm22	172.29.10.179 ----> S.O Oracle Solaris 11.4 ROL BD

## Produccion
* VSPDAPDASHB01	  172.30.163.63 ---->  S.O Windows Server 2019  Standard Rol APP
* VSPDAPSDCACE01	172.30.163.171 ----> S.O Red Hat Enterprise Linux 8 Rol APP
* VSPDAPSDCACE02	172.30.163.172 ----> S.O Red Hat Enterprise Linux 8 Rol APP 
* sc01zdbadm10	172.29.10.59 ----> S.O Oracle Solaris 11.4 Rol BD
* sc01zdbadm22	172.29.10.179 ----> S.O Oracle Solaris 11.4 Rol BD


# Deploy en sofia QA

/resourcedata/ADMIN/SOFIA/Scripts/Deploy_sofia_Nodo1.sh //resourcedata/ADMIN/SOFIA/deploys/25092024/sofia-1.1.1.ear

# Deploy bk QA
/resourcedata/ADMIN/SOFIA/Scripts/Deploy_sofia_Paso0_tomaBK.sh /resourcedata/ADMIN/SOFIA/backups/2024_09_16_17_54 

