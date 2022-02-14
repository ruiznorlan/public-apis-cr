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