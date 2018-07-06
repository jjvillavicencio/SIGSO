# Requerimientos

- [Requerimientos](#requerimientos)
    - [GESTIÓN DE LA SEGURIDAD CIVIL](#gesti%C3%B3n-de-la-seguridad-civil)
        - [Generación de informes](#generaci%C3%B3n-de-informes)
        - [Aplicaciones en línea](#aplicaciones-en-l%C3%ADnea)
        - [Aplicación Walk-in](#aplicaci%C3%B3n-walk-in)
        - [Generar número de solicitante](#generar-n%C3%BAmero-de-solicitante)
        - [Registro del solicitante](#registro-del-solicitante)
        - [Imagen del solicitante](#imagen-del-solicitante)
        - [Formulario de solicitud](#formulario-de-solicitud)
        - [Procesar y emitir permisos/licencias](#procesar-y-emitir-permisoslicencias)
            - [División de Licencias de Armas de Fuego](#divisi%C3%B3n-de-licencias-de-armas-de-fuego)
            - [División de Gestión de Explosivos](#divisi%C3%B3n-de-gesti%C3%B3n-de-explosivos)
            - [División de Gestión de la Educación y la Ejecución](#divisi%C3%B3n-de-gesti%C3%B3n-de-la-educaci%C3%B3n-y-la-ejecuci%C3%B3n)
        - [CRUD de datos](#crud-de-datos)
            - [Ingresar y cargar información](#ingresar-y-cargar-informaci%C3%B3n)
            - [Ingresar información de importación o exportación](#ingresar-informaci%C3%B3n-de-importaci%C3%B3n-o-exportaci%C3%B3n)
            - [Emitir licencia o permiso para aprobación](#emitir-licencia-o-permiso-para-aprobaci%C3%B3n)
            - [Carga de requisitos documentales](#carga-de-requisitos-documentales)
            - [Almacenar y recuperar licencias y permisos](#almacenar-y-recuperar-licencias-y-permisos)
            - [Actualizar la entrada de datos](#actualizar-la-entrada-de-datos)
            - [Generar licencia y numero de permiso](#generar-licencia-y-numero-de-permiso)
            - [Bloquear licencias y permisos](#bloquear-licencias-y-permisos)
            - [Estado licencias y permisos](#estado-licencias-y-permisos)
            - [Corregir la entrada de datos](#corregir-la-entrada-de-datos)
            - [Completar información](#completar-informaci%C3%B3n)
            - [Información para importar](#informaci%C3%B3n-para-importar)
            - [Información para exportar](#informaci%C3%B3n-para-exportar)
        - [Verificación](#verificaci%C3%B3n)
            - [Verificar licencia comercial](#verificar-licencia-comercial)
            - [Verificar estado licencia y permiso](#verificar-estado-licencia-y-permiso)
            - [Verificar número de licencia](#verificar-n%C3%BAmero-de-licencia)
            - [Verificar número de permiso](#verificar-n%C3%BAmero-de-permiso)
            - [Verificar propietario o representante legal](#verificar-propietario-o-representante-legal)
            - [Verificar destinatario de los bienes](#verificar-destinatario-de-los-bienes)
        - [Cálculo](#c%C3%A1lculo)
            - [Saldo de importación o exportación](#saldo-de-importaci%C3%B3n-o-exportaci%C3%B3n)
            - [Certificación en el Balance](#certificaci%C3%B3n-en-el-balance)
            - [Cálculo de tarifas](#c%C3%A1lculo-de-tarifas)
            - [Emitir orden de pago](#emitir-orden-de-pago)
    - [Gestión del Grupo de Patrulla de caminos](#gesti%C3%B3n-del-grupo-de-patrulla-de-caminos)
        - [Autorizaciones](#autorizaciones)
        - [Gestión vehículos](#gesti%C3%B3n-veh%C3%ADculos)
    - [Gestión del módulo de inteligencia](#gesti%C3%B3n-del-m%C3%B3dulo-de-inteligencia)
        - [Numero de Solicitud](#numero-de-solicitud)
        - [Autorización](#autorizaci%C3%B3n)
    - [Generación de informes](#generaci%C3%B3n-de-informes)
        - [Gestión de Informes](#gesti%C3%B3n-de-informes)

## GESTIÓN DE LA SEGURIDAD CIVIL

En esta sección se enlistan todos los requerimientos relacionados con el módulo de gestión de la seguridad civil.

### Generación de informes

| Número de requerimiento | RQ01 |
| --- | --- |
| Nombre de requerimiento | Generación de informes |
| Descripción | El sistema generará informes de acuerdo con los informes actuales generados por GSC (Grupo de Seguridad Civil), OAE (Oficina de Armas y Explosivos), PPAFR (Permiso para Portar Armas de Fuego fuera de la Residencia) y OSASI –SOSIA Oficina de Supervisión de Agencias de Seguridad e Investigación |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-001** |
| Versión | 0.1 |

### Aplicaciones en línea

| Número de requerimiento | RQ02 |
| --- | --- |
| Nombre de requerimiento | Aplicaciones en línea |
| Descripción | Aplicaciones en línea |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado |   |
| Versión | 0.1 |

### Aplicación Walk-in

| Número de requerimiento | RQ03 |
| --- | --- |
| Nombre de requerimiento | Aplicación Walk-in |
| Descripción | Captura de datos a través de kioskos |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-004** |
| Versión | 0.1 |



### Generar número de solicitante

| Número de requerimiento | RQ04 |
| --- | --- |
| Nombre de requerimiento | Generar número de solicitante |
| Descripción | El sistema debe poder generar un número de solicitante único. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-003** |
| Versión | 0.1 |

### Registro del solicitante

| Número de requerimiento | RQ05 |
| --- | --- |
| Nombre de requerimiento | Registro del solicitante |
| Descripción | El sistema debe poder capturar el registro del solicitante |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-004** |
| Versión | 0.1 |



### Imagen del solicitante

| Número de requerimiento | RQ06 |
| --- | --- |
| Nombre de requerimiento | Imagen del solicitante |
| Descripción | El sistema debe poder capturar la imagen del solicitante |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-004** |
| Versión | 0.1 |

### Formulario de solicitud

| Número de requerimiento | RQ07 |
| --- | --- |
| Nombre de requerimiento | Formulario de solicitud |
| Descripción |  El sistema debe ser capaz de generar un formulario de solicitud |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |



### Procesar y emitir permisos/licencias
 #### División de Licencias de Armas de Fuego

| Número de requerimiento | RQ08 |
| --- | --- |
| Nombre de requerimiento | Permisos/licencias Armas de Fuego |
| Descripción | El sistema debe poder procesar y emitir permisos / licencias para poseer y usar armas de fuego |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |

#### División de Gestión de Explosivos

| Número de requerimiento | RQ09 |
| --- | --- |
| Nombre de requerimiento | Permisos/licencias Explosivos |
| Descripción | El sistema debe poder procesar y emitir permisos / licencias para toda actividad que implique explosivos/ingredientes explosivos |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |

#### División de Gestión de la Educación y la Ejecución

| Número de requerimiento | RQ10 |
| --- | --- |
| Nombre de requerimiento | Permisos/licencias de armas de fuego transporte/educación/clubs |
| Descripción | El sistema debe poder procesar y emitir permisos / licencias para transportar armas de fuego y municiones ciudadano/tiradores deportivos. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |

### CRUD de datos

#### Ingresar y cargar información

| Número de requerimiento | RQ11 |
| --- | --- |
| Nombre de requerimiento | Ingresar y cargar información |
| Descripción | El sistema debe permitir al solicitante o partes interesadas ingresar y cargar información de transacciones mensuales: ventas / distribución, importación, exportación, para ser confirmado por el OAE. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-008 CU-009** |
| Versión | 0.1 |

#### Ingresar información de importación o exportación

| Número de requerimiento | RQ12 |
| --- | --- |
| Nombre de requerimiento | Ingresar información de importación o exportación |
| Descripción | El sistema debe permitir que el solicitante ingrese el número y la descripción de los elementos reales que se importarán o exportarán, incluido el país de origen/destino, el nombre de la empresa y la dirección que deberá confirmar el OAE. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-008** |
| Versión | 0.1 |

#### Emitir licencia o permiso para aprobación

| Número de requerimiento | RQ13 |
| --- | --- |
| Nombre de requerimiento | Emitir licencia o permiso para aprobación |
| Descripción | El sistema debe poder emitir una licencia o permiso para su aprobación (jefe de la Oficina de Armas y Explosivos, Director del Grupo de Seguridad Civil, Jefe de la Policía Nacional o Secretario del Interior y Gobierno Local) |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-010** |
| Versión | 0.1 |

#### Carga de requisitos documentales

| Número de requerimiento | RQ14 |
| --- | --- |
| Nombre de requerimiento | Carga de requisitos documentales |
| Descripción | El sistema debe acomodar la carga de requisitos documentales y aportes de información por parte del solicitante para ser confirmado o validado por personal autorizado de OAE |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-009** |
| Versión | 0.1 |

#### Almacenar y recuperar licencias y permisos

| Número de requerimiento | RQ15 |
| --- | --- |
| Nombre de requerimiento | Almacenar y recuperar licencias y permisos |
| Descripción | El sistema debe poder almacenar y recuperar licencias y permisos aprobados, incluidos los requisitos presentados |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-011 CU-012** |
| Versión | 0.1 |

#### Actualizar la entrada de datos

| Número de requerimiento | RQ16 |
| --- | --- |
| Nombre de requerimiento | Actualizar la entrada de datos |
| Descripción | El sistema debe actualizar la entrada de datos en caso de que haya cambios o modificaciones en las licencias entregadas a concesionarios, fabricantes o armeros, su validez cuando ya se haya renovado, cambio de representante de la compañía, incremento, disminución, omisión o adición de elementos indicados en la licencia, cambio de domicilio comercial y otros |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-010** |
| Versión | 0.1 |

#### Generar licencia y numero de permiso

| Número de requerimiento | RQ17 |
| --- | --- |
| Nombre de requerimiento | Generar licencia y numero de permiso |
| Descripción | El sistema debe generar la licencia y número de permiso para evitar la duplicación. La validez del número de licencia asignado es perpetuo (se refiere a concesión, fabricación y licencia de armero) para incluir el registro de chaleco/vestimenta de airgun, airsoft y bala, mientras que la validez del número de permiso asignado es por transacción (refiriéndose al permiso de importación o exportación) |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-013** |
| Versión | 0.1 |

#### Bloquear licencias y permisos

| Número de requerimiento | RQ18 |
| --- | --- |
| Nombre de requerimiento | Bloquear licencias y permisos |
| Descripción | El sistema bloqueará automáticamente las licencias o permisos que ya hayan expirado, o estén bajo investigación, suspendidas, canceladas, dejado de operar, revocadas o tiene un caso pendiente |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Estado licencias y permisos

| Número de requerimiento | RQ19 |
| --- | --- |
| Nombre de requerimiento | Estado licencias y permisos |
| Descripción | El sistema debe indicar el estado de una licencia emitida o un permiso ya sea suspendido, cancelado, revocado, cerrado o cesado de operar, temporal cerrado y otros. Las razones de tal estado también deberían reflejarse / indicarse |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Corregir la entrada de datos

| Número de requerimiento | RQ20 |
| --- | --- |
| Nombre de requerimiento | Corregir la entrada de datos |
| Descripción | El sistema debe ser capaz de corregir la entrada de datos, incluidas las tasas que se cobrarán |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-015** |
| Versión | 0.1 |

#### Completar información

| Número de requerimiento | RQ21 |
| --- | --- |
| Nombre de requerimiento | Completar información |
| Descripción | La licencia debe tener la siguiente información para ser completada por el personal autorizado de OAE |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-15** |
| Versión | 0.1 |

#### Información para importar

| Número de requerimiento | RQ22 |
| --- | --- |
| Nombre de requerimiento | Información para importar |
| Descripción | El sistema debe reflejar el propósito de la importación, como con fines comerciales, exposiciones comerciales, muestras, pruebas y evaluaciones, educativos, teatrales, para el gobierno, donaciones y otros. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |

#### Información para exportar

| Número de requerimiento | RQ23 |
| --- | --- |
| Nombre de requerimiento | Información para importar |
| Descripción | El sistema debe reflejar el propósito de la exportación, como con fines comerciales, exposiciones comerciales, muestra, prueba y evaluación, educativo, teatral, para el gobierno, donación. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-006** |
| Versión | 0.1 |

### Verificación

 #### Verificar licencia comercial

| Número de requerimiento | RQ24 |
| --- | --- |
| Nombre de requerimiento | Verificar licencia comercial |
| Descripción | El sistema debe tener la capacidad de verificar si una entidad comercial tiene una licencia emitida para fabricar, comerciante, o armero. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-009** |
| Versión | 0.1 |

#### Verificar estado licencia y permiso

| Número de requerimiento | RQ25 |
| --- | --- |
| Nombre de requerimiento | Verificar estado licencia y permiso |
| Descripción | El sistema debe poder verificar el estado de una licencia o permiso emitido en cuanto al período de validez, o si está suspendido, cancelado, revocado, cerrado o dejó de funcionar, temporal cerrado y otros |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Verificar número de licencia

| Número de requerimiento | RQ26 |
| --- | --- |
| Nombre de requerimiento | Verificar número de licencia |
| Descripción | El sistema debe tener la capacidad de verificar el número de licencia emitido o asignado a un fabricante, distribuidor, o armero en particular. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Verificar número de permiso

| Número de requerimiento | RQ27 |
| --- | --- |
| Nombre de requerimiento | Verificar número de permiso |
| Descripción | El sistema debe tener la capacidad de verificar el número de permiso expedido a un determinado exportador o importador de armas de fuego, partes y accesorios de armas de fuego, municiones y componentes de municiones, pistolas de aire comprimido o aeromotores |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Verificar propietario o representante legal

| Número de requerimiento | RQ28 |
| --- | --- |
| Nombre de requerimiento | Verificar propietario o representante legal |
| Descripción | El sistema debe tener la capacidad de verificar el propietario o el representante oficial de la compañía de un distribuidor autorizado, fabricante, o armero. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

#### Verificar destinatario de los bienes

| Número de requerimiento | RQ29 |
| --- | --- |
| Nombre de requerimiento | Verificar destinatario de los bienes |
| Descripción | El sistema debe tener la capacidad de verificar el destinatario de los bienes utilizados en exposiciones comerciales, fines teatrales, educativos y otros. Esto ocurre en los casos en que la importación o exportación no requiere un distribuidor autorizado, o fabricante |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-014** |
| Versión | 0.1 |

### Cálculo
#### Saldo de importación o exportación

| Número de requerimiento | RQ30 |
| --- | --- |
| Nombre de requerimiento | Saldo de importación o exportación |
| Descripción | El sistema debe poder calcular el saldo restante de la importación o exportación comparando el permiso aprobado con el número real de artículos importados o exportados. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-016** |
| Versión | 0.1 |

#### Certificación en el Balance

| Número de requerimiento | RQ31 |
| --- | --- |
| Nombre de requerimiento | Certificación en el balance |
| Descripción | El sistema debe poder proporcionar el número de control y la fecha de emisión de cada Certificación en el Balance de Importación que se emitirá |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-015** |
| Versión | 0.1 |

#### Cálculo de tarifas

| Número de requerimiento | RQ32 |
| --- | --- |
| Nombre de requerimiento | Cálculo de tarifas |
| Descripción | Debe poder calcular tarifas de licencia, tarifas de registro y otras tarifas |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-017** |
| Versión | 0.1 |

#### Emitir orden de pago

| Número de requerimiento | RQ33 |
| --- | --- |
| Nombre de requerimiento | Emitir orden de pago |
| Descripción | Debe poder emitir la Orden de pago para las tarifas requeridas |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-018** |
| Versión | 0.1 |

## Gestión del Grupo de Patrulla de caminos
### Autorizaciones

| Número de requerimiento | RQ34 |
| --- | --- |
| Nombre de requerimiento | Autorizaciones |
| Descripción | El sistema debe ser capaz de generar el formulario de Solicitud de Autorización para Vehículos Motorizados |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-019** |
| Versión | 0.1 |

### Gestión vehículos

| Número de requerimiento | RQ35 |
| --- | --- |
| Nombre de requerimiento | Gestión de vehículos |
| Descripción | El sistema debe poder validar el registro del vehículo (si el estado es deseado / o no deseado) |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-020** |
| Versión | 0.1 |



## Gestión del módulo de inteligencia
### Numero de Solicitud

| Número de requerimiento | RQ36 |
| --- | --- |
| Nombre de requerimiento | Gestión de vehículos |
| Descripción | El sistema debe tener la capacidad de recuperar una solicitud por su número. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-021** |
| Versión | 0.1 |

### Autorización

| Número de requerimiento | RQ37 |
| --- | --- |
| Nombre de requerimiento | Gestión de vehículos |
| Descripción | El sistema debe poder generar un numero de autorización, una autorización, aprobaciones de autorizaciones electrónicas de Dirección de Inteligencia. |
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-022** |
| Versión | 0.1 |



## Generación de informes
   ### Gestión de Informes

| Número de requerimiento | RQ38 |
| --- | --- |
| Nombre de requerimiento | Gestión de Informes |
| Descripción | El sistema debe poder consultar todos los incidentes relacionados con: Incidentes con vehículos Incidentes con guardias Incidentes con armas de fuego|
| Tipo | Funcional |
| Prioridad | Alta |
| Módulo asociado | Gestión de la seguridad civil |
| Caso uso asociado | **CU-023** |
| Versión | 0.1 |

