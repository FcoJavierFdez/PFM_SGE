**************************
ECHOCAR, IB, SA.
**************************

**PROYECTO FINAL MODULO**

# FASE 3

**************************
MÓDULOS IMPLANTADOS
**************************

**************************
1er. módulo: Facturación.
**************************
Nombre técnico: account
Licencia: LGPL versión 3
Categoría: Contabilidad
Resumen: Factura y pagos
Versión: 14.0.1.1

Funcionalidad: El modulo gestiona la facturación tanto de los clientes como de los proveedores, 
aplicandoles el IVA por defecto en la moneda EUR. Se generan las facturas en los diferentes estados, 
desde el inical hasta el pagado, pasando por sus diferentes etapas como no pagado. 
En este modulo se deben de incluir los productos facturables tanto los tenemos que comprar como 
los que se venden en la empresa, se pueden filtrar aquellos productos que utilizan los clientes y 
también los que son utilizados con los proveedores, como tambien las facturas de los clientes y la 
de los proveedores.
Del mismo modo se genera la lista de clientes y la de proveedores, con todos sus datos de contacto, 
el metodo de pago y domiciliacion bancaria, como si tiene presupuestos o facturas.

Configuración realizada: He configurado varias empresas como clientes y un proveedor, realizado dos facturas.
En las facturaciones realizadas he configurado el pago con pago por transferencia, aunque
existe la posibilidad con SEPA, pero esa opción esta de pago.


**************************
2o. módulo: Empleados.
**************************
Nombre técnico: hr
Licencia: LGPL versión 3
Categoría: Empleados
Versión: 14.0.1.1

Funcionalidad: El módulo gestiona a los empleados de la empresa clasificandolos en sus departamentos
correspondientes, creandoles una ficha con datos personales de cada uno de ellos, y datos laborales 
con respecto a su puesto de trabajo, cuenta bancaria y demas información laboral.
Este módulo sirve para gestionar los empleados y departamentos de la empresa.

Configuración realizada: Se puede configurar cada empleado para que se pueda visualizar a que departamento pertenece 
y quien es su gerente, generando de este modo los organigramas correspondientes. He creado 3 departamentos por el momento.
Dirección y Sales. He creado un control de asistencias, que deriva a otro modulo pero este no lo he puesto, y 
he permitido a los usuarios que modifiquen sus datos personales. 


**************************
3er. módulo: Compras.
**************************
Nombre técnico: purchase
Licencia: LGPL versión 3
Categoría: Compra
Versión: 14.0.1.2

Funcionalidad: Permite la creación y envío de solicitudes de cotización a proveedores,
así como el seguimiento de su estado. Las órdenes de compra se generan automáticamente según la planificación de necesidades,
con opción de aprobarlas antes de su emisión. Se integra con el módulo de inventario para actualizar existencias 
de forma automática al recibir productos, y alerta sobre niveles de stock para evitar la falta de ellos.
Ofrece análisis detallados de proveedores y costos, con reportes sobre precios históricos.
También permite automatizar procesos mediante reglas de compra basadas en necesidades específicas de inventario o producción,
optimizando lotes de compra. El sistema es compatible con diferentes monedas e idiomas, lo que facilita la gestión de compras 
internacionales, y proporciona trazabilidad completa de cada proceso y un control interno.

Configuración realizada: En este módulo he modificado la opción de la aprobación de pedido de compra. 
Solicitar a administradores que aprueben pedidos superiores a un importe mínimo de 300€. Ya que por 
la cantidad de dinero pueden cubrirse gastos de materiales necesitarios de oficina o diversos pequeños 
gastos. las demás opciones estan configuradas según la forma predefinida.


**************************
4o. módulo: Ventas.
**************************
Nombre técnico: sale_management
Licencia: LGPL versión 3
Categoría: Ventas
Versión: 14.0.1.0

Funcionalidad: Este módulo de Odoo sirve para gestionar todas las actividades relacionadas con
las ventas, desde la creación de presupuestos, hasta la factura, pudiendo rastrear el estado del pedido
en todo momento. Las facturas que se realicen se verán reflejadas en el modulo Facturación.

Configuración realizada: El único cambio que he realizado en la configuración de este modulo ha sido la
activación de la opción “Firma en linea” que permite a los clientes confirmar los pedidos a través de
internet mediante una firma.


**************************
5o. módulo: Encuestas.
**************************
Nombre técnico: survey
Licencia: LGPL versión 3
Categoría: Encuesteas
Versión: 14.0.3.2

Funcionalidad: El módulo Encuestas facilita el diseño y la administración de encuestas adaptadas
a las necesidades de la empresa, permitiendo recopilar información valiosa de usuarios, clientes o empleados. 
Permite crear preguntas con distintos formatos de respuesta, como opciones múltiples, escalas de calificación 
o respuestas abiertas, lo que lo hace perfecto para recoger opiniones y tomar decisiones basadas en datos organizados.
También incluye herramientas para distribuir las encuestas a través de múltiples canales, como correo electrónico 
o sitios web, y analizar los resultados mediante gráficos y reportes detallados. Además, ofrece la posibilidad 
de personalizar las encuestas de acuerdo con los objetivos específicos de la organización.

Configuración realizada: He creado una encuesta llamada Survey NPS por la que mediante 3 preguntas el cliente
recibirá un correo evaluandola en una matriz con 3 respuestas posibles.


***************************
6o. módulo: Inventario.
***************************
Nombre Técnico: stock
Licencia: LGPL versión 3
Categoría: Inventario
Versión: 14.0.1.1

Funcionalidad: está diseñado para facilitar una gestión eficiente de las existencias en cualquier empresa.
Su funcionalidad permite registrar, organizar y supervisar productos en almacenes, optimizando los procesos relacionados 
con recepciones, despachos, transferencias internas y ajustes de stock. Con este módulo, las empresas pueden tener un 
control preciso del inventario en tiempo real, mejorando la planificación y evitando rupturas de stock.

Configuración realizada: Como la empresa Echocar se dedica al alquiler de vehículos, he creado a parte
de los productos que ya habia creado, los vehiculos como productos, he creado por el momento un unico vehiculo 
con su precio de compra, su proveedor y la ubicación de almacenamiento para que se sepa en que lugar se 
encuentra este producto.

****************************
7o. módulo: CRM.
****************************
Nombre Técnico: crm
Licencia: LGPL versión 3
Categoría: CRM
Versión: 14.0.1.2

Funcionalidad: Este módulo está diseñado para gestionar de manera eficiente las interacciones con clientes y potenciales,
consolidando la información para potenciar las oportunidades comerciales. Facilita el registro, organización y 
seguimiento de contactos, leads y oportunidades, mejorando la colaboración entre equipos y aumentando la tasa de éxito en ventas.
Su funciones clave incluye la automatización de tareas comerciales, la programación de actividades como reuniones y llamadas, 
y la generación de reportes que analizan el desempeño de las ventas. Además, se conecta de forma integral con otros módulos 
como Ventas y Correo Electrónico, ofreciendo una herramienta completa para gestionar el ciclo de vida del cliente y optimizar las operaciones comerciales.

Configuración realizada: He creado dentro del flujo una oportunidad de negocio de un cliente potencial. Este puede 
pasar en 4 fases: nuevo, calificado, propuesta o ganado.
También he intentado generar un lead para buscar 3 compañias dentro del sector transporte para poder investigar el mercado y captar clientes,
pero no si es por mi equipo pero no lo ha generado bien. De todos modos he marcado la casilla Leads y la extensión outlook de 
CRM para recopilar toda la información de los correos y registrar el contenido de los correos como notas internas. También se pueden 
generar leads de productos.


