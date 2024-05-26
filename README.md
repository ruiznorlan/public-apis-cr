<div align="center">
    <h1>API Públicas Costa Rica</h1>
    <i>Una lista colectiva de APIs abiertas de Costa Rica para uso en software y desarrollo web</i>
</div>

<br />

---

<br />

## Indice

* [ARESEP](#aresep)
    - [Autobus](#autobus)
    - [Combustible](#combustible)
    - [Agua](#agua)
    - [Electricidad](#electricidad)
    - [Gas](#gas)
    - [Taxi](#taxi)
    - [Tren](#tren)
    - [RITEVE](#riteve)
    - [Peajes](#peajes)
    - [Cabotaje](#cabojate)
    - [Correo](#correo)
    - [Riego y Avenamiento](#riego-y-avenamiento)
    - [Puertos](#puertos)
    - [Aeropuertos](#aeropuertos)
    - [RECOPE](#recope)
* [Banco Central de Costa Rica](#bccr)
* [Ministerio de Hacienda](#ministerio-de-hacienda)


<br />

<br />

### ARESEP

La sección de Datos Abiertos busca que la ciudadanía tenga acceso a datos e información, con lo cual se cumplen los principios de transparencia y acceso a información pública.
ARESEP presenta información y datos actualizados sobre cada servicio regulado. Se muestra un diagrama sobre el servicio, su cobertura y datos estadísticos.

Fuente: [Datos Abiertos ARESEP](https://aresep.go.cr/transparencia/datos-abiertos)

<br />

#### Autobus
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Pasajeros movilizados e ingresos percibidos](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Autobus.svc) | Cantidad de pasajeros movilizados e ingresos percibidos en el servicio remunerado de personas, modalidad autobús, según los datos proporcionados directamente al Sistema de Información Regulatoria por los prestadores del servicio. La Autoridad somete esta información a procesos de validación de previo a su uso en procesos de regulación económica. | No | Yes |
| [Tarifas de Autobús](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/PliegoTarifario.svc) | Tarifas del servicio de autobús clasificadas por ruta, ramal y fraccionamiento aprobados por el CTP. | No | Yes |
| [Flota autorizada](https://web.aresep.go.cr/ws.datosAbiertos/Services/IT/Autobus.svc) | Se refiere a la cantidad de unidades autorizadas para brindar el servicio de autobús por cada operador y ruta. | No | Yes |
| [Histórico de variables utilizadas en las fijaciones tarifarias de autobús](https://web.aresep.go.cr/ws.datosAbiertos/Services/IT/Autobus.svc) | Se refiere a todas las variables que se utilizan para las fijaciones tarifarias de autobús, las fuentes pueden ser diversas. | No | Yes |
| [Rutas de autobuses](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Autobus.svc) | Se muestra información sobre los recorridos por los ramales de las rutas de autobús. | No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Combustible
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas de combustibles](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifaCombustible.svc) | Se muestra información histórica de los precios de los combustibles en Costa Rica, según cadena de valor y tipo de producto. | No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Agua
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Producción neta de agua](https://web.aresep.go.cr/ws.datosabiertos/Services/IA/AguaPotable.svc) | Estos datos se refieren a la producción neta (no incluye las pérdidas en la planta o conducción) de las fuentes de los operadores AyA y ESPH, por región, año, mes y tipo de fuente. | No | Yes |
| [Mercado de los servicios regulados por operador](https://web.aresep.go.cr/ws.datosabiertos/Services/IA/AguaPotable.svc) | Estos datos se refieren a las variables de mercado (conexiones, consumo e ingresos) de los servicios regulados por AyA y ESPH (acueducto, alcantarillado, hidrantes y protección del recurso hídrico). | No | Yes |
| [Tarifas de los servicios de acueducto, alcantarillado, hidrantes y TPRH por operador](https://web.aresep.go.cr/ws.datosabiertos/Services/IA/AguaPotable.svc) | Estos datos se refieren a las tarifas de acueducto y alcantarillado para el servicio que suministran AyA, ESPH y ASADAS.| No | Yes |
| [Plantas de tratamiento para agua potable (PTAP), AyA](https://web.aresep.go.cr/ws.datosAbiertos/Services/IA/Calidad.svc) | Información de distribución de los sistemas para potabilización del agua destinada para consumo humano en los diferentes sistemas de AyA a nivel nacional. | No | Yes |
| [Acueducto Comunales (ASADAS)](https://web.aresep.go.cr/ws.datosabiertos/Services/IA/Asadas.svc) | Ubicación de las oficinas de las Asociaciones Administradoras de Acueductos y Alcantarillados Comunales (ASADAS). | No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Electricidad
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas de electricidad del sistema de distribución](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifasElectricidad.svc) | Tarifas fijadas por ARESEP, en colones por kWh, clasificadas de acuerdo al año, empresa, tipo de tarifa. | No | Yes |
| [Tarifas electricidad del sistema de generación](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifasElectricidad.svc) | Tarifas fijadas por ARESEP, en colones por kWh, clasificadas de acuerdo al año, empresa, tipo de tarifa. | No | Yes |
| [Tarifas electricidad de alumbrado público](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifasElectricidad.svc) | Tarifas fijadas por ARESEP, en colones por kWh, clasificadas de acuerdo al año, empresa, tipo de tarifa. | No | Yes |
| [Tarifas de electricidad del sistema de transmisión eléctrica](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifasElectricidad.svc) | Tarifas fijadas por ARESEP, en colones por kWh, clasificadas de acuerdo al año, empresa, tipo de tarifa. | No | Yes |
| [Precios medios](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/TarifasElectricidad.svc) | Tarifas fijadas por ARESEP, en colones por kWh, clasificadas de acuerdo al año, empresa, tipo de tarifa. | No | Yes |
| [Fiscalización calidad de la tensión eléctrica](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Se muestra las actividades de fiscalización de la calidad del servicio eléctrico, en la cual se verifican, a lo largo y ancho del país, variedad de parámetros relativos a la tensión eléctrica (voltaje) en el punto de entrega. | No | Yes |
| [Zonas de concesión por operador eléctrico](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Se muestra los límites de las zonas de concesión de cada operador eléctrico. En las zonas que no se pudo identificar a ningún operador, dado que estos no las declararon como propias, han sido asignadas al ICE y serán corroboradas próximamente. | No | Yes |
| [Transformadores por distrito y operador](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Se muestra información y localización de los transformadores en cada distrito del país, así como el operador al que corresponde. | No | Yes |
| [Postes por distrito y operador](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Se muestra información básica y localización de los postes en cada distrito del país, así como el operador al que corresponden. | No | Yes |
| [Centrales Eléctricas](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Proyectos de inversión de centrales eléctricas. | No | Yes |
| [Subestaciones eléctricas](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Electricidad.svc) | Proyectos de inversión de subestaciones. | No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Gas
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Plantas envasadoras de gas licuado de petróleo](https://web.aresep.go.cr/ws.datosabiertos/Services/IE/Gas.svc) | Se muestra el total de las plantas envasadoras del país y su ubicación exacta.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Taxi
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas de Taxi](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Taxi.svc) | Tarifas para el servicio de taxi, que se clasifica de acuerdo con su base de operación en regular ( taxis rojos) y en base de operación especial ( taxis aeropuerto).| No | Yes |
| [Flota autorizada Taxi](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Taxi.svc) | Base de datos de la flota autorizada por el Consejo de Transporte Público (CTP) suministrada a la ARESEP en junio 2015, actualizada con la base de datos de placas de taxi contenida en el Registro Nacional al 20 de febrero de 2019.| No | Yes |
| [Paradas de taxi](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Taxi.svc) | Datos muestran información sobre las paradas de taxi autorizadas.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Tren
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Tarifas para el servicio de ferrocarril, en el cual se brindan servicios de transporte remunerado de personas en el GAM.| No | Yes |
| [Tarifas históricas transporte de carga](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Tarifas para el servicio de transporte de carga en ferrocarril.| No | Yes |
| [Pasajeros movilizados](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Cantidad de pasajeros movilizados en la modalidad de: turismo y las rutas metropolitanas..| No | Yes |
| [Pasajeros adultos mayores movilizados](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Cantidad de pasajeros adultos mayores movilizados en el servicio de turismo y rutas urbanas.| No | Yes |
| [Carga movilizada](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Cantidades movilizadas en los servicios de transporte de: banano, acero, papel, cartón y pasajeros sector atlántico.| No | Yes |
| [Recorridos del servicio del tren](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) |Se muestra información sobre los recorridos del tren.| No | Yes |
| [Paradas del servicio del tren](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Ferrocarril.svc) | Se muestra información de las paradas del tren.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### RITEVE
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas de la Revisión Técnica Vehicular -RTV-](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/RTV.svc) | Tarifas para el servicio de revisión técnica vehicular.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Peajes
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Flujos vehiculares ruta 27](	https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Peaje.svc) | Cantidad de vehículos contabilizados en cada uno de los puntos de conteo definidos en el contrato de concesión.| No | Yes |
| [Flujo vehicular CONAVI](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Peaje.svc) | Cantidad de vehículos que transitan por las carreteras nacionales y que son sujetas de pago de peaje.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Cabotaje
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas cabotaje mayor](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Cabotaje.svc) | Tarifas de pasajeros que utilizan el servicio de cabotaje mayor, conocidos como ferrys, los cuales transportan personas y vehículos (las tarifas de los vehículos las define la División Marítima Portuaria del MOPT).| No | Yes |
| [Tarifas históricas cabotaje menor](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Cabotaje.svc) | Tarifas para el servicio de transporte de personas y mercancías pequeñas (capacidad aproximada de 30 personas).| No | Yes |
| [Pasajeros movilizados](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Cabotaje.svc) | Cantidad de pasajeros movilizados en el servicio de transporte de pasajeros en la modalidad de cabotaje mayor, conocidos como ferrys que pueden transportar personas y vehículos.| No | Yes |
| [Recorrido del servicio de cabotaje](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Cabotaje.svc) | Se muestra información sobre el recorrido de las rutas de cabotaje.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Correo
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas servicio nacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas para el servicio social postal, correo tradicional y comercial, con un peso límite de 2 kilogramos y que brinda la empresa Correos de Costa Rica.| No | Yes |
| [Tarifas históricas de correo internacional prioritario](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas históricas de correo tradicional y/o comercial prioritario que cuente con un peso límite de 2 kilogramos, que su imposición sea local y el destino internacional.| No | Yes |
| [Tarifas históricas de correo internacional no prioritario](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas históricas de correo tradicional y/o comercial no prioritario que cuente con un peso límite de 2 kilogramos, que su imposición sea local y el destino internacional.| No | Yes |
| [Tarifas históricas de Porte Pago con preclasificación](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas para el servicio Porte Pago con preclasificación, que se otorga a clientes con más de 3000 envíos mensuales.| No | Yes |
| [Tarifas históricas de Porte Pago sin preclasificación](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas para el servicio Porte Pago sin preclasificación, que se otorga a clientes con más de 3000 envíos mensuales.| No | Yes |
| [Tarifas históricas de tasas especiales de correo nacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas de servicios que se pueden adicionar al correo tradicional con destino nacional, dependiendo de la necesidad del usuario, tales como listas de correo, acuse de recibo, entrega en mano propia, valor declarado, carta manifiesta y devoluciones al expedidor.| No | Yes |
| [Tarifas históricas de tasas especiales de correo internacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas de servicios que se pueden adicionar al correo tradicional con destino internacional dependiendo de la necesidad del usuario, tales como acuse de recibo, entrega en mano propia, servicio express, devoluciones al expedidor, cupones de respuesta internacional.| No | Yes |
| [Tarifas históricas de tasas de certificado y bodegaje](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Tarifas del servicio certificado, el cual hace referencia al momento de entregar la correspondencia sólo a una persona mayor de 18 años en el domicilio postal del destinatario. Además de las tarifas por el servicio de bodegaje.| No | Yes |
| [Volumen postal con destino nacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Total de correo tradicional y correo comercial que cuente con un peso límite de 2 kilogramos y que su imposición y destino sea local.| No | Yes |
| [Volumen postal certificado y corporativo](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Total de correo tradicional corporativo que cuente con un peso límite de 2 kilogramos y que su destino sea local.| No | Yes |
| [Volumen postal con destino internacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Correo.svc) | Total de correo tradicional y correo comercial que cuente con un peso límite de 2 kilogramos y que su imposición sea local y el destino internacional.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Riego y Avenamiento
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas de SENARA en el servicio de riego y avenamiento](https://web.aresep.go.cr/ws.datosabiertos/Services/IA/AguaPotable.svc) | Estos datos se refieren a las tarifas de SENARA aprobadas por ARESEP en el servicio de riego y avenamiento.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Puertos
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas a estibadoras](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Tarifas para los servicios de estiba y desestiba que se brinda a las navieras en los puertos de Limón y Moín.| No | Yes |
| [Tarifas históricas de los puertos del Pacífico -INCOP](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Tarifas para los servicios que se brindan a las navieras en los puertos del Pacífico.| No | Yes |
| [Tarifas históricas de los puertos del Caribe -JAPDEVA-](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Tarifas para los servicios que se brindan a las navieras en los puertos de Limón y Moín.| No | Yes |
| [Carga movilizada estibadoras](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Carga movilizada en todas las operaciones realizadas en los puertos de Limón y Moín por medio de compañías estibadoras, según tipo de mercancía.| No | Yes |
| [Carga Movilizada en los Puertos del Pacífico](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Carga movilizada en las operaciones realizadas en los puertos del Pacífico.| No | Yes |
| [Carga Movilizada en los Puertos de Limón y Moín](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Puerto.svc) | Carga movilizada en las operaciones realizadas en los puertos de Limón y Moín.| No | Yes |

**[⬆ Volver al inicio](#indice)**

#### Aeropuertos
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Tarifas históricas en servicios aeronáuticos](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Aeropuerto.svc) | Tarifas para los servicios prestados a operadores aéreos en las terminales, tales como: aterrizaje, aproximación, iluminación, puentes, buses, estacionamiento, carga, entre otros.| No | Yes |
| [Carga movilizada por aeropuerto internacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Aeropuerto.svc) | Carga movilizada medida en MTOWS que significa masa máxima al momento de despegue, según aeropuerto.| No | Yes |
| [Operaciones realizadas por aeropuerto internacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Aeropuerto.svc) | Total de vuelos que se realizaron en los aeropuertos o aeródromos.| No | Yes |
| [Pasajeros movilizados por aeropuerto internacional](https://web.aresep.go.cr/ws.datosabiertos/Services/IT/Aeropuerto.svc) | Cantidad de pasajeros nacionales e internacionales transportados en los aeropuertos nacionales.| No | Yes |

**[⬆ Volver al inicio](#indice)**


### BCCR

Con motivo de la continua modernización e implementación tecnológicas de punta en el
Banco Central de Costa Rica, esta institución ofrece un nuevo servicio a clientes
nacionales e internacionales, el cual permite que los sistemas de instituciones o
empresas puedan conectarse con el web service del BCCR y consultar información como
el tipo de cambio con respecto al EUA dólar, otros tipos de cambio, tasas de interés,
inflación, y otros indicadores de interés para el público, de una manera transparente y
rápida. Cualquier persona o institución, sea privada o pública, puede acceder esta
información del día o histórica desde cualquier parte del mundo y sin ningún costo
monetario

Fuente: [Web Service de Indicadores Económicos](https://gee.bccr.fi.cr/indicadoreseconomicos/Documentos/DocumentosMetodologiasNotasTecnicas/Webservices_de_indicadores_economicos.pdf)

<br />

#### Banco Central de Costa Rica
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Indicadores Económicos](https://gee.bccr.fi.cr/Indicadores/Suscripciones/WS/wsindicadoreseconomicos.asmx) | El web service del BCCR permite consultar información como el tipo de cambio con respecto al EUA dólar, otros tipos de cambio, tasas de interés, inflación, y otros indicadores de interés para el público, de una manera transparente y rápida. | Yes | Yes |

**[⬆ Volver al inicio](#indice)**

### Ministerio de Hacienda

Información general y de uso público para el consumo desde aplicaciones creadas por desarrolladores de soluciones.

Fuente: [API Ministerio de Hacienda](https://bit.ly/2McNcpX)

<br />

#### Ministerio de Hacienda
API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Contribuyentes](https://api.hacienda.go.cr/fe/ae) | Permite obtener el nombre, el tipo de identificación, el régimen, la situación tributaria y las actividades económicas asociadas a un contribuyente, usando como parámetro el número de identificación (sin hacer uso de guiones).  Para la consulta de identificaciones físicas nacionales no es necesario incluir el 0 como primer dígito. En el caso de las identificaciones jurídicas y NITES tributarios es necesario el uso de los primeros 10 dígitos, sin utilizar los dos últimos dígitos verificadores. | No | Yes |
| [Tipo de Cambio](https://api.hacienda.go.cr/indicadores/tc) | Permite obtener el tipo de cambio del dólar y euro.  No requiere de ningún tipo de parámetro. | No | Yes |
| [Exoneraciones](https://api.hacienda.go.cr/fe/ex) | Permite obtener la información correspondiente a una exoneración.  Requiere el parámetro _*autorizacion*_ cuyo formato debe seguir la regla al-00000000-00. | No | Yes |
| [Agropecuario](https://api.hacienda.go.cr/fe/agropecuario) | Permite obtener el nombre, el estado, el indicador de si está activo y la fecha de baja de los productores agropecuarios en el MAG, usando como parámetro el número de _*identificacion*_ (sin hacer uso de guiones).  Para la consulta de identificaciones físicas nacionales es necesario incluir el 0 como primer dígito. En el caso de las identificaciones jurídicas es necesario el uso de los primeros 10 dígitos, sin utilizar los dos últimos dígitos verificadores.  | No | Yes |
| [Pesca](https://api.hacienda.go.cr/fe/pesca) | Permite obtener los siguientes datos:<br/> - Del registro de productores agropecuarios del MAG: el nombre, el estado, el indicador de si está activo y la fecha de baja.<br/> - Del registro de INCOPESCA: el indicador de si está activo, el nombre del permisionario y la fecha de vencimiento.  <br/> - Del registro de acuicultores: el indicador de si está activo, el nombre del acuicultor y la fecha de vencimiento. <br/>  Se usa como parámetro el número de _*identificación*_ (sin hacer uso de guiones).  Para la consulta de identificaciones físicas nacionales es necesario incluir el 0 como primer dígito. En el caso de las identificaciones jurídicas es necesario el uso de los primeros 10 dígitos, sin utilizar los dos últimos dígitos verificadores. | No | Yes |
| [CAByS](https://api.hacienda.go.cr/fe/cabys) | Permite obtener la información correspondiente al Catalago de Bienes y Servicios (CABYS), a partir de la descripción de los bienes y servicios o su número de código.  Puede utilizar los parámetros _*q*_ o _*codigo*_ de la siguiente manera: | No | Yes |

**[⬆ Volver al inicio](#indice)**

<br />

### RECOPE

#### RECOPE

El API dispone de varios recursos sobre los que puede realizar consultas. A continuación el detalle de recursos disponibles y las operaciones que puede realizar en cada uno de ellos, incluyendo una muestra de la solicitud (request) y su respuesta (response).

Fuente: [API RECOPE](https://datosabiertos.recope.go.cr/servicio-api)

API | Descripción | Auth | HTTPS |
|---|---|---|---|
| [Precio Internacional](https://api.recope.go.cr/precio-internacional) | Obtiene el precio internacional del combustible para cada producto comercializado. Opcionalmente se pueden agregar los parámetros de inicio y fin para especificar el rango de fechas del cual se desea obtener los precios, siguiendo el formato YYYYMMDD. | No | Yes |
| [Precio Consumidor](https://api.recope.go.cr/ventas/precio/consumidor) | Obtiene el precio actualizado del combustible para cada producto comercializado. | No | Yes |
| [Precio Plantel](https://api.recope.go.cr/ventas/precio/plantel) | Obtiene el precio actualizado del combustible disponibles en los planteles de distribución. | No | Yes |
| [Precio Plantel](https://api.recope.go.cr/ventas/precio/plantel) | Obtiene el precio actualizado del combustible disponibles en los planteles de distribución. | No | Yes |

**[⬆ Volver al inicio](#indice)**