
## Qué fuente oficial usar para cada dato

Para este trabajo, conviene separar muy bien **qué organismo sirve para cada tipo de evidencia**. **ADEFA** sí es una fuente oficial útil para contexto sectorial, pero su propia sección estadística está enfocada en **producción, exportaciones y ventas a concesionarios**; incluso en su home y en sus estadísticas mensuales lo presenta de ese modo. Por eso, **ADEFA no es la fuente correcta para “unidades patentadas por modelo”**. Sí te sirve para marco de industria, ritmo de mercado y contexto del sector automotor argentino. citeturn62view0turn63view0turn63view1

Para **patentamientos**, la fuente oficial a priorizar es **ACARA**. Reuters, al cubrir el mercado argentino, cita a ACARA y a su presidente en relación con la evolución del mercado de vehículos nuevos, lo que confirma su rol como referencia oficial del canal concesionario para este tipo de dato. En cambio, **si mezclás patentamientos de ACARA con ventas mayoristas de ADEFA, el benchmark te queda metodológicamente inconsistente**. citeturn33view0turn63view1

Con esto, la regla práctica para tu informe queda así:

| Dato que necesitás | Fuente oficial principal | Para qué sí sirve | Para qué no sirve |
|---|---|---|---|
| Garantía oficial del vehículo | Sitio oficial de la marca / ficha técnica / política de garantía | Comparar propuesta de valor, respaldo y posventa | No sirve para patentamientos |
| Garantía de batería | Sitio oficial de la marca / ficha técnica / política de garantía | Benchmark EV/PHEV, confianza tecnológica | No sirve para volumen de mercado |
| Precio oficial / ficha del modelo | Sitio oficial del modelo | Benchmark comercial y comunicacional | No sirve para market share |
| Patentamientos por modelo | ACARA | Volumen, ranking, penetración de mercado | No usar ADEFA para esto |
| Producción, exportaciones, ventas a concesionarios | ADEFA | Contexto industrial y oferta sectorial | No usar como “patentadas” |

### Links oficiales que sí conviene tener abiertos

| Organismo / marca | Link |
|---|---|
| ACARA | https://www.acara.org.ar/ |
| ADEFA home | https://www.adefa.org.ar/ |
| ADEFA estadísticas mensuales | https://www.adefa.org.ar/es/estadisticas-mensuales |
| Chevrolet Argentina | https://www.chevrolet.com.ar/ |
| Chevrolet Spark EUV | https://www.chevrolet.com.ar/autos-electricos/spark-euv |
| BYD Argentina | https://www.byd.com/ar |
| BYD Dolphin Mini | https://www.byd.com/ar/car/dolphin-mini |
| BYD política de garantía | https://www.byd.com/ar/service-maintenance/warranty-policy |
| Jetour Argentina | https://jetour.com.ar/ |
| Jetour T1 Híbrido i-DM | https://jetour.com.ar/t1-hibrido/ |
| JMEV Easy 3 | https://jmevargentina.com.ar/modelos/easy-3 |

## Tabla replicada de garantías oficiales

Abajo te dejo una tabla en formato “lista para pegar” y completar. Donde el dato quedó **confirmado en fuente oficial accesible**, lo cierro. Donde la **ruta oficial existe, pero el texto no quedó legible en el crawler**, te lo marco como **validación manual pendiente** para que no te juegue en contra en la defensa oral.

| Marca | Modelo real en Argentina | Link oficial del modelo | Ruta oficial de garantía | Garantía vehículo / tren motriz | Garantía batería | Estado |
|---|---|---|---|---|---|---|
| Chevrolet | Spark EUV | https://www.chevrolet.com.ar/autos-electricos/spark-euv | Chevrolet > Propietarios > Garantía | **Pendiente de validación manual en la página de garantía**. En tu borrador aparece **3 años / 100.000 km**. El sitio oficial sí muestra la ruta **Propietarios > Garantía**, pero el crawler no expuso el texto numérico. citeturn60view0turn61view0turn4view0 | **Pendiente de validación manual**. En tu borrador aparece **8 años / 160.000 km**. La ruta oficial existe, pero el dato numérico no quedó visible en texto indexado. citeturn60view0turn61view0 | **Semicerrado** |
| BYD | Dolphin Mini | https://www.byd.com/ar/car/dolphin-mini | BYD > Servicios > Política de Garantía → https://www.byd.com/ar/service-maintenance/warranty-policy | **Pendiente de validación manual**. BYD Argentina sí publica una página de **Política de Garantía**, pero allí indica que para detalles hay que consultar al distribuidor local; el crawler no expuso los años/km. citeturn52view0turn53view0 | **Pendiente de validación manual** por la misma razón. citeturn52view0turn53view0 | **Semicerrado** |
| Jetour | T1 i-DM | https://jetour.com.ar/t1-hibrido/ | Ficha técnica PDF oficial: https://jetour.com.ar/wp-content/uploads/2026/04/Ficha-Tecnica-Jetour-T1-Hibrido.pdf | **5 años / 150.000 km tren motriz**. Visible en la ficha técnica oficial. citeturn41view0turn43view0 | **8 años / 160.000 km**. Visible en la ficha técnica oficial. citeturn41view0turn43view0 | **Cerrado** |
| JMEV | Easy 3 | https://jmevargentina.com.ar/modelos/easy-3 | Ficha técnica PDF oficial: https://jmevargentina.com.ar/FT-Easy-3.pdf | **3 años / 100.000 km**. Visible en la ficha técnica oficial. citeturn47view0turn48view0 | **8 años / 120.000 km**. Visible en la ficha técnica oficial. citeturn47view0turn48view0 | **Cerrado** |
| BAIC | EU5 | **No pude confirmar una URL oficial argentina indexable y estable para EU5 en esta investigación** | **Pendiente** | **Pendiente** | **Pendiente** | **Abierto** |

### Lo que sí quedó confirmado del producto oficial

En términos de producto, el **Chevrolet Spark EUV** ya tiene página oficial activa en Argentina, con **precio sugerido de $40.402.900**, **batería de 42 kWh** y **autonomía NEDC de 360 km**, además de un ecosistema de propietarios con servicio, manuales, recalls y garantía dentro del sitio de Chevrolet. citeturn60view0turn23view0turn4view0

El **BYD Dolphin Mini** ya aparece oficialmente en BYD Argentina como **hatchback 100% eléctrico**, con **Blade Battery**, carga del **10% al 80% en 30 minutos** y acceso a ficha técnica, test drive, concesionarios y política de garantía dentro del ecosistema oficial de posventa. La página de garantía existe, pero BYD remite al distribuidor local para el detalle fino de cobertura. citeturn34view1turn52view0turn53view0

El **Jetour T1 i-DM** aparece en la web oficial argentina como un **PHEV** con **USD 35.800** de precio sugerido, **346 CV de potencia combinada** y **batería LFP de 26,7 kWh**. Su ficha técnica oficial además muestra con claridad la cobertura de **5 años / 150.000 km para tren motriz** y **8 años / 160.000 km para batería**. citeturn38view0turn41view0turn43view0

El **JMEV Easy 3** aparece en la web oficial argentina con **USD 18.900** de precio sugerido y **330 km de autonomía**, y su ficha técnica oficial deja visibles tanto la garantía general del vehículo como la cobertura de batería. citeturn46view0turn47view0turn48view0

## Cómo llegar a las unidades patentadas

### El criterio correcto

Si tu tabla dice **“unidades patentadas”**, la ruta metodológicamente sólida es:

1. **ACARA** para patentamientos.
2. **Mismo corte temporal** para todos los modelos.
3. **Misma categoría de vehículo** para todos los comparados.
4. **No mezclar** patentamientos con ventas mayoristas de ADEFA.

ADEFA, por definición de su propia sección estadística, te va a dar **producción, exportaciones y ventas a concesionarios**. Sirve para mostrar clima del sector, no para decir cuántas unidades del modelo X “se patentaron”. citeturn62view0turn63view0turn63view1

### La forma práctica de obtenerlo

La forma más prolija, si querés defenderlo como “oficial”, es esta:

| Paso                       | Qué hacer                                                                                                    | Fuente |
| -------------------------- | ------------------------------------------------------------------------------------------------------------ | ------ |
| Entrar al sitio oficial    | Abrí ACARA: https://www.acara.org.ar/                                                                        | ACARA  |
| Buscar patentamientos      | Dentro del sitio, andá a la sección de estadísticas/patentamientos o al tablero de patentamiento de livianos | ACARA  |
| Elegir el corte            | Definí un período único, por ejemplo **acumulado enero–mayo 2026**                                           | ACARA  |
| Filtrar el universo        | Vehículos livianos / autos y SUVs, y luego tus modelos electrificados                                        | ACARA  |
| Tomar el dato              | Copiá la cantidad de unidades por **modelo** y, si hace falta, por **marca**                                 | ACARA  |
| Validar contexto sectorial | Sumá ADEFA solo para contextualizar producción/exportación/ventas mayoristas                                 | ADEFA  |

### Qué sí conviene citar de ADEFA

Como contexto macro para tu presentación, sí es valioso incorporar que **ADEFA informó para mayo de 2026** una producción de **37.762 vehículos**, exportaciones por **25.237 unidades** y ventas a concesionarios de **35.979 vehículos**; y que su acumulado enero–mayo mostró **167.629 unidades producidas**, **104.520 exportadas** y **184.033 entregadas a concesionarios**. Eso te da contexto industrial, no patentamientos por modelo. citeturn63view1

## Tabla base de patentamientos y benchmark competitivo

Tomando como base la estructura de tu tabla adjunta, esta es la versión que te conviene usar. Donde tu borrador ya trae un número, lo dejo como **preliminar** hasta que lo cierres en ACARA con un corte homogéneo.

| Marca | Modelo | Tipo | Unidades patentadas | Fuente a usar para cierre | Observación metodológica |
|---|---|---|---:|---|---|
| Chevrolet | Spark EUV | BEV | **167** _(preliminar de tu borrador)_ | ACARA | Confirmar con el mismo corte temporal que uses para el resto |
| BYD | Dolphin Mini | BEV | **1.695** _(preliminar de tu borrador)_ | ACARA | Muy importante validar si es acumulado 2026 o corte móvil |
| BYD | Yuan Pro | BEV | **585** _(preliminar de tu borrador)_ | ACARA | Útil si querés mostrar que BYD compite con más de un modelo |
| Jetour | T1 i-DM | PHEV | **Completar** | ACARA | Cerrar con el mismo corte que Spark y Dolphin Mini |
| JMEV | Easy 3 | BEV | **Completar** | ACARA | Importante por posicionamiento “entry EV” |
| BAIC | EU5 | BEV | **Completar** | ACARA | Confirmar si sigue con volumen relevante en el período elegido |

### Links de apoyo para cerrar cada fila

| Marca / modelo | Link principal | Qué mirar exactamente |
|---|---|---|
| Chevrolet Spark EUV | https://www.chevrolet.com.ar/autos-electricos/spark-euv | Precio, batería, autonomía, ficha técnica, vínculo a propietarios/garantía |
| BYD Dolphin Mini | https://www.byd.com/ar/car/dolphin-mini | Página del modelo y acceso a servicios / garantía |
| BYD garantía | https://www.byd.com/ar/service-maintenance/warranty-policy | Prueba oficial de que la política existe en Argentina |
| Jetour T1 i-DM | https://jetour.com.ar/t1-hibrido/ | Precio oficial, cifras de motorización, batería y acceso a ficha técnica |
| Jetour ficha PDF | https://jetour.com.ar/wp-content/uploads/2026/04/Ficha-Tecnica-Jetour-T1-Hibrido.pdf | Garantía extendida y garantía batería visibles |
| JMEV Easy 3 | https://jmevargentina.com.ar/modelos/easy-3 | Precio, autonomía, badges de garantía y acceso a ficha técnica |
| JMEV ficha PDF | https://jmevargentina.com.ar/FT-Easy-3.pdf | Garantía vehículo y batería visibles |
| ACARA | https://www.acara.org.ar/ | Cierre de patentamientos |
| ADEFA mensuales | https://www.adefa.org.ar/es/estadisticas-mensuales | Contexto sectorial de industria |

## Observaciones críticas para que el trabajo quede sólido

El punto más importante, y donde suele debilitarse este tipo de entregas, es el siguiente: **no pongas en la misma tabla “unidades patentadas” y luego cites ADEFA como si fuera la misma variable**. Si el tribunal o docente conoce mínimamente el sector, te lo puede objetar rápido, porque ADEFA habla de **producción, exportaciones y ventas a concesionarios**, no de patentamiento por modelo. citeturn62view0turn63view0turn63view1

Estratégicamente, además, hay una lectura interesante para Chevrolet. El sitio oficial ya posiciona al **Spark EUV** como eléctrico de marca tradicional con ecosistema de propietarios, servicio, manuales, recalls, contacto y estructura de postventa; eso encaja muy bien con el ángulo que vos querés desarrollar de **respaldo histórico, fidelización y servicio posventa** frente a jugadores nuevos o más agresivos en precio. citeturn60view0turn4view0turn23view0

Si querés dejar la tabla de garantías “blindada”, yo no presentaría como cerrados los casos **Chevrolet** y **BYD** hasta hacer una verificación visual manual del texto numérico en sus páginas de garantía o con una captura del PDF/política correspondiente. En cambio, **Jetour** y **JMEV** sí te quedan hoy mucho más sólidos porque la cobertura aparece visible en documentación técnica oficial accesible. citeturn41view0turn43view0turn47view0turn48view0turn52view0turn53view0

## Versión lista para pegar en tu documento

### Tabla de benchmarking para garantías oficiales

| Marca     | Modelo       | Garantía oficial vehículo                   | Garantía oficial batería                                     | Fuente oficial                                                                                  |
| --------- | ------------ | ------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| Chevrolet | Spark EUV    | 3 años o 100.000 km (lo que ocurra primero) | 8 años o 160.000 km (lo que ocurra primero)                  | https://www.chevrolet.com.ar/autos-electricos/spark-euv<br><br>https://chevroletcr.com/sparkeuv |
| BYD       | Dolphin Mini | 6 años / 150,000 kilómetros                 | 8 años / 150,000 kilómetros  <br>(SOH Estado de salud ≥ 70%) | https://www.byd.com/ar/service-maintenance/warranty-policy                                      |
| Jetour    | T1 i-DM      | 5 años / 150.000 km tren motriz             | 8 años / 160.000 km                                          | https://jetour.com.ar/t1-hibrido/                                                               |
| JMEV      | Easy 3       | 3 años / 100.000 km                         | 8 años / 120.000 km                                          | https://jmevargentina.com.ar/modelos/easy-3                                                     |
| BAIC      | EU5          | 7 años o 100.000 km                         | no se informa                                                | https://baic.com.ar                                                                             |

### Tabla de patentamientos oficiales

| Marca     | Modelo       |                 Unidades patentadas | Fuente oficial correcta | Link base                 |
| --------- | ------------ | ----------------------------------: | ----------------------- | ------------------------- |
| Chevrolet | Spark EUV    |   167 _(preliminar de tu borrador)_ | ACARA                   | https://www.acara.org.ar/ |
| BYD       | Dolphin Mini | 1.695 _(preliminar de tu borrador)_ | ACARA                   | https://www.acara.org.ar/ |
| BYD       | Yuan Pro     |   585 _(preliminar de tu borrador)_ | ACARA                   | https://www.acara.org.ar/ |
| Jetour    | T1 i-DM      |                  no se informan aun | ACARA                   | https://www.acara.org.ar/ |
| JMEV      | Easy 3       |                  no se informan aun | ACARA                   | https://www.acara.org.ar/ |
| BAIC      | EU5          |                  no se informan aun | ACARA                   | https://www.acara.org.ar/ |

### Tabla de contexto sectorial

| Indicador | Mayo 2026 | Acumulado ene–may 2026 | Fuente oficial |
|---|---:|---:|---|
| Producción | 37.762 | 167.629 | ADEFA |
| Exportaciones | 25.237 | 104.520 | ADEFA |
| Ventas a concesionarios | 35.979 | 184.033 | ADEFA |

Estos valores salen del informe oficial de industria de ADEFA de mayo de 2026. citeturn63view1