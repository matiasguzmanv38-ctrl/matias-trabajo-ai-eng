# Elección de empresa: Brasaland

## Empresa elegida

Elegí **Brasaland**, la cadena de 14 restaurantes de cocina a la brasa con locales en Colombia y Florida (Estados Unidos).

## Por qué la elegí

Mi familia tiene un restaurante, así que el tipo de trabajo de Brasaland me sirve directamente para el negocio familiar. Aunque nuestro restaurante tiene una sola sucursal, tiene varios de los mismos problemas que describe el briefing: dificultades con los pedidos a proveedores y un marketing que funciona casi sin información sobre los clientes. En tecnología estamos incluso más atrás que Brasaland, aunque usamos Toteat como sistema de punto de venta, algo parecido a los sistemas de punto de venta separados que Brasaland tiene en cada país. Me interesa resolver estos problemas a escala de cadena (14 locales, dos países, dos monedas) porque lo que aprenda lo puedo aplicar después en un negocio real que conozco desde dentro.

## Departamentos que más me interesan

### Compras y proveedores (Lucía Fernández)

Brasaland trabaja con unos 20 proveedores entre Colombia y Florida, negocia por email y Excel, y Lucía se entera de los cambios de precio recién cuando llega la factura. No existe ningún dato consolidado de compras de la cadena. Es el mismo tipo de problema que vivimos en el restaurante de mi familia con los pedidos a proveedores, y me interesa ver cómo los datos permiten pedir mejor, negociar mejor y evitar sorpresas en los costos.

### Marketing y experiencia digital (Camila Ospina)

El programa de fidelización Brasa Points funciona con tarjetas de sellos de papel que el 60 % de los clientes no usa y que no generan ningún dato, así que la empresa no sabe quiénes son sus clientes. Me interesa porque en el negocio de mi familia pasa algo parecido: no tenemos información de nuestros clientes ni de lo que prefieren, y un CRM con historial de pedidos cambiaría la forma de hacer marketing.

## Reto que quiero construir

**Sistema inteligente de pedidos de ingredientes** (Operaciones de restaurante): calcular qué pedir a cada proveedor a partir de las ventas históricas y del stock actual de cada local. Hoy en Brasaland los pedidos se hacen por WhatsApp o por teléfono, sin datos detrás, lo que provoca exceso de stock en algunos locales y quiebres en otros. Este reto conecta Operaciones con Compras y Proveedores, y más adelante se puede ampliar con alertas de cambios de precio de los proveedores.

## Mi idea de Agente de IA (My AI Agent Idea)

**Qué haría:** Cada noche, al cierre, el agente revisa lo que vendió cada local y cuánto stock queda de cada ingrediente. Calcula qué ingredientes van a faltar en los próximos días y prepara un borrador de pedido para cada proveedor. Envía ese borrador por WhatsApp al encargado del local, que puede aprobarlo, corregir cantidades o rechazarlo respondiendo el mensaje. Además, avisa si el precio de un ingrediente subió respecto a la última compra.

**Qué información necesitaría:**

- Las ventas por plato y por local, tomadas del sistema de punto de venta (en el caso de mi familia, Toteat).
- Las recetas de cada plato, para saber cuánto de cada ingrediente se usa.
- El stock actual de cada ingrediente en cada local.
- La lista de proveedores con lo que vende cada uno, sus precios, pedido mínimo y días de entrega.
- El historial de pedidos y de precios anteriores.

**Qué produciría o activaría:**

- Un borrador de pedido por proveedor, enviado por WhatsApp al encargado del local para su aprobación.
- Una vez aprobado, el mensaje de pedido listo para enviar al proveedor.
- Alertas cuando un ingrediente está por agotarse o cuando un proveedor sube un precio.
- Un registro de cada pedido, para que las estimaciones mejoren con el tiempo.
