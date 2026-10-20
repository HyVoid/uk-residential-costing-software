[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Software británico de estimación de costes de construcción residencial y plantilla Excel de cálculo de costes para constructores

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/Platform-Browser%20(Free)%20%7C%20Excel%20(Paid)-emerald.svg)](#)
[![Tool Type](https://img.shields.io/badge/Tool%20Type-Decision%20Support%20%7C%20Costing%20Engine-orange.svg)](#)

**Una plantilla británica avanzada de estimación de construcción residencial y un software de cálculo de costes de proyectos de obra, diseñados para convertir en segundos las cantidades medidas de los planos de arquitectura en presupuestos de licitación específicos del contratista, líneas de resultado comercial internas y presupuestos limpios para el cliente. Disponible como herramienta gratuita de cálculo de construcción basada en el navegador y como libro Excel profesional de estimación totalmente desbloqueado para constructores, con garantía de devolución del dinero de 30 días.**

> **Sin registro. Sin instalación.**  
> **Versión de navegador: gratuita.**  
> **Versión Excel: de pago con garantía de devolución del dinero de 30 días.**  
> [🌐 Abrir la aplicación gratuita de estimación de construcción basada en el navegador](https://hyvoid.github.io/uk-residential-costing-software/)
>
> [📥 Descargar la plantilla Excel profesional de estimación para constructores](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README)

<img width="1920" height="828" alt="image" src="https://github.com/user-attachments/assets/6d58eaae-fcd8-4407-8678-25f5f3067d57" />
<img width="1163" height="790" alt="image" src="https://github.com/user-attachments/assets/b156ab36-5886-40cb-879d-fbadbbf32a7a" />


---

## Funciones principales: seguimiento de costes de obra y soluciones de gestión de licitaciones

Las hojas de cálculo tradicionales fracasan porque mezclan cantidades con precios. Este sistema actúa como un auténtico **motor de fijación de precios de cuadros de cantidades (BOQ)**, diseñado explícitamente para resolver los errores más costosos de la estimación de construcción.

| Problema de la estimación de construcción (consulta de búsqueda) | Solución automatizada en el motor de cálculo |
| :--- | :--- |
| **Margen del contratista vs. seguimiento de pérdidas de explotación** | Separa los costes directos de los oficios, los costes preliminares de obra, los gastos generales reglamentarios y los imprevistos del margen del contratista, de modo que los márgenes de oferta nunca se conviertan en pérdidas de explotación. |
| **Precios de subcontratistas y análisis de desviaciones de tarifas** | Evalúa cómo el cambio de socios de oficio (p. ej., constructoras locales de Hertfordshire vs. subcontratistas regionales) altera al instante la rentabilidad base del proyecto sobre exactamente el mismo cuadro de cantidades físico. |
| **Desglose de costes directos (mano de obra y materiales)** | Proporciona desgloses exactos por partida entre mano de obra, materiales, subcontratistas especializados y alquiler de maquinaria para cada fase estructural y arquitectónica. |
| **Cálculo del desperdicio de materiales para la construcción** | Calcula dinámicamente los incrementos de volumen de compra a nivel de partida (p. ej., desperdicio por corte de ladrillos vistos) en lugar de enmascararlos con allowances uniformes de regla general. |
| **Precios orientados al cliente vs. márgenes internos** | Genera automáticamente un cuadro de oferta desensibilizado para el cliente que absorbe suavemente los gastos generales y los costes preliminares en precios unitarios mixtos, sin exponer los costes de subcontratación de oficios ni los márgenes brutos objetivo. |
| **Integridad de la oferta y conciliación del BOQ** | Proporciona validación en tiempo real que confirma la ausencia de códigos de partida no registrados, tarifas de oficio ausentes o rupturas de fórmulas, garantizando un equilibrio estricto entre los modelos de costes internos y los totales del cliente dentro de una tolerancia de 0,01 £. |

---

## Tutorial de inicio rápido: elabore su primera oferta de construcción

Siga este flujo de trabajo para generar estimaciones precisas y presupuestos listos para el cliente con nuestras funciones de cálculo comercial integradas.

1. **Establecer parámetros clave (configuración del proyecto)**: Abra `01_Setup` para configurar los metadatos del proyecto. Utilice la **lista desplegable dinámica de contratistas** para seleccionar su socio de oferta activo, establezca la visualización de moneda (£) y confirme los objetivos globales para el **modo de costes preliminares**, gastos generales y beneficio (OHP %), imprevistos % y el IVA legal.
2. **Introducir cantidades físicas (importación de mediciones)**: Abra `04_Project_Estimate` e introduzca los códigos de medición de los planos de arquitectura (`Takeoff_Item_Code`) junto con las cantidades físicas medidas (`Measured_Quantity`). El motor empareja al instante las **matrices de precios por oficio** de la biblioteca central, sin arrastrar fórmulas manualmente.
3. **Registrar logística de obra y allowances**: Introduzca los compromisos de obra no estándar (p. ej., duración del alquiler de andamios, alquiler de contenedores de escombros, instalaciones de bienestar) y las sumas provisionales del cliente (p. ej., paquetes de cocina, allowances de sanitarios) en la **calculadora de costes preliminares de obra** `05_Adjustments`.
4. **Inspeccionar vistas de decisión y exportar**: Revise los umbrales de margen interno y los suelos de rentabilidad en `06_Internal_Estimate`, verifique que `08_Checks` no activa ninguna alerta roja y exporte el cuadro de presupuesto desensibilizado y listo para el cliente directamente desde `07_Customer_Estimate` a PDF. 

> **¿Listo para escalar su proceso de oferta?** Después de probar la versión de navegador, [📥 descargue la plantilla Excel de estimación reutilizable para ofertas ilimitadas y acceso offline de por vida](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Por qué construí este software de cálculo

La mayoría de las estimaciones de proyectos residenciales domésticos y de mercado medio (100.000 £–500.000 £) fracasan mucho antes de romper tierra. Fracasan porque las constructoras pequeñas y medianas y los jefes de proyecto dependen de **hojas de cálculo de estimación de construcción** monolíticas en las que los precios de oficio, la logística de obra, el desperdicio de materiales y las cantidades físicas están soldadas en una sola celda. Cuando un contratista principal recibe tarifas actualizadas de subcontratistas o debe presentar una oferta con un equipo de carpintería alternativo, todo el BOQ debe reconstruirse a mano.

En una estimación reciente de una ampliación de dos plantas de 260.000 £, el constructor principal aplicó un recargo forfaitario habitual del 15% sobre una tarifa compuesta de albañilería por metro cuadrado. Sin embargo, la obra tenía un acceso restringido por un callejón trasero estrecho que requería transporte con maquinaria ligera, y los ladrillos vistos a medida llevaban un factor de desperdicio por corte del 10% en lugar del 5% estándar. Como la tarifa era un número compuesto codificado en duro, las 4.200 £ adicionales de exceso de ladrillos y las 3.800 £ de alquiler de maquinaria prolongado nunca se atribuyeron a la base del trabajo. La oferta parecía competitiva, pero a la finalización el contratista obtuvo un margen neto del 3,4% en lugar del 16% objetivo, eliminando por completo el flujo de caja de explotación.

Construí este **motor de estimación de construcción** para eliminar ese modo de fallo para siempre. En lugar de tratar una estimación como un lienzo aritmético estático, esta herramienta convierte la ingeniería de costes comercial en producto: separa la geometría física inmutable de un edificio de las tarifas de mano de obra de oficio volátiles, aísla los costes preliminares de obra y hace cascada dinámicamente los recargos comerciales sobre los documentos del cliente.

---

## Problemas habituales de la estimación residencial que esta herramienta resuelve

| Problema de estimación y cálculo | Limitaciones de las hojas de cálculo tradicionales | Solución del motor de cálculo automatizado |
| :--- | :--- | :--- |
| **Cantidades y precios de mano de obra acoplados** | Volver a calcular una oferta con un nuevo subcontratista exige reintroducir las dimensiones del proyecto y copiar fórmulas a lo largo de decenas de filas del BOQ. | Las cantidades de medición física permanecen intactas; cambiar la lista desplegable de contratistas en `01_Setup` reindexa todas las tarifas de mano de obra, maquinaria y materiales en menos de un segundo. |
| **Subestimación silenciosa del desperdicio de materiales** | Los porcentajes forfaitarios aplicados a las sumas globales no cubren el desperdicio por corte en albañilería, baldosas y madera estructural de alto valor. | Una lógica escalonada específica por partida aplica parámetros de desperdicio dedicados a las cantidades de compra antes de que se produzca la fijación de precios, garantizando **mediciones** precisas. |
| **Fuga de concesiones en costes previos** | Andamios, alquiler de contenedores y dirección de obra se listan como sumas transparentes, que los clientes negocian sistemáticamente durante la revisión del contrato. | Los costes preliminares de obra y los gastos generales de empresa se absorben matemáticamente en las tarifas mixtas de partida del cliente, garantizando que la recuperación de gastos generales queda protegida dentro de precios unitarios vinculantes. |
| **Deriva de fórmulas y referencias rotas** | Añadir partidas estructurales inesperadas exige insertar filas manualmente y arrastrar fórmulas, dejando a menudo filas excluidas de los totales. | Las modernas matrices dinámicas de desbordamiento de punto único ingieren automáticamente las nuevas líneas y propagan las sumas por todas las hojas analíticas para un **control de costes de obra** infalible. |
| **Exposición del cliente a las líneas de resultado comercial** | Los estimadores pasan horas desinfectando manualmente las hojas de cálculo internas en presupuestos de cliente, con el riesgo de divulgar accidentalmente márgenes de oficio. | Una hoja orientada al cliente completamente desacoplada lee del motor central, mostrando secciones de trabajo limpias y ocultando por completo las tarifas internas de oficio y los márgenes de beneficio. |

---

## Usuarios objetivo y escenarios de estimación específicos

Esta plantilla actúa como un ERP ligero para los profesionales de la construcción que gestionan contratos residenciales. 

- **Constructores residenciales y contratistas principales (100.000 £–500.000 £)**: Constructoras generales que usan este **software de estimación para ampliaciones de vivienda**, las reformas integrales de vivienda y las **plantillas de cálculo de costes de buhardillas** para asegurar márgenes internos defendibles antes de firmar contratos JCT a precio fijo.
- **Tasadores de cantidad y consultores de estimación**: Profesionales que gestionan múltiples archivos de tarifas de subcontratistas y necesitan una **plantilla de fijación de precios BOQ** escalable y un **libro Excel de cuadro de ofertas** repetible, sin mantener una infraestructura empresarial frágil y compleja.
- **Promotores inmobiliarios y autoconstructores**: Operadores que buscan una **calculadora de costes de construcción de vivienda** transparente y una herramienta de referencia ascendente para examinar los paquetes de oferta de los contratistas e identificar partidas de oficio sobrecargadas.

*No diseñado para*: Proyectos de ingeniería civil comerciales de gran altura que requieren cuadros de cantidades completos de consultor SMM7/NRM2, contabilidad ERP empresarial multiusuario, o extracción directa automatizada de polígonos CAD/BIM.

No se necesita experiencia en hojas de cálculo. Abra la aplicación gratuita de navegador y empiece a estimar inmediatamente. ¿Necesita la robusta versión de escritorio? [Compre la plantilla Excel profesional de estimación con garantía de devolución de 30 días](https://theseusworkshop.com/l/arnghy?utm_source=github&utm_medium=GitHub%20README).

---

## Sobre el desarrollador

Construyo herramientas de apoyo a la decisión productizadas y modelos operativos ligeros para entornos en los que hay simplemente demasiadas piezas en movimiento para gestionarlos por intuición. En la construcción residencial, los descuidos de estimación de un solo punto se acumulan hasta convertirse en fallos estructurales de flujo de caja. Mi trabajo se centra en responder a una pregunta fundamental: *«¿Qué información necesito en un lugar claro para tomar la siguiente decisión comercial con absoluta confianza?»* El **motor británico de estimación de construcción residencial** es la realización exacta de este enfoque.

---


## Detalles técnicos

<details>
<summary>Para revisores técnicos, practicantes de Excel y colaboradores</summary>

### Arquitectura del libro

El sistema opera a través de cuatro capas funcionales distintas repartidas en ocho hojas de cálculo. Los datos fluyen estrictamente en una sola dirección (Configuración $\rightarrow$ Datos maestros $\rightarrow$ Cálculo $\rightarrow$ Salida), eliminando las referencias circulares y salvaguardando la integridad de los datos:

```
[01_Setup] (Global Parameters & Contractor Switcher)
   │
   ├── Controls currency, contractor selection, waste defaults, prelims mode, and margin targets
   ▼
[02_Item_Master] ─────────────▶ [03_Rate_Library]
(WBS Taxonomy & Descriptions)    (Subcontractor Rate Matrix: Labour / Material / Plant)
   │                               │
   └──────────────┬────────────────┘
                  ▼
       [04_Project_Estimate] ◀────── [05_Adjustments]
       (Dynamic Calculation Engine)   (Prelims, Provisional Sums, Site Allowances)
                  │
         ┌────────┴────────────────────────┐
         ▼                                 ▼
[06_Internal_Estimate]           [07_Customer_Estimate]
(Detailed Commercial Bottom-Line) (Clean Desensitized Client Tender)
         │                                 │
         └────────────────┬────────────────┘
                          ▼
                     [08_Checks]
         (Data Integrity, Code Mapping, Margin Audit)
```

| Capa | Nombre de la hoja | Responsabilidad operativa | Tipo de entrada / fórmula |
| :--- | :--- | :--- | :--- |
| **01. Control** | `01_Setup` | Contiene todas las variables de configuración global, los metadatos de la empresa, los márgenes objetivo y los disparadores de la lista desplegable de contratistas. | Entradas de usuario y listas dinámicas |
| **02. Datos maestros** | `02_Item_Master` | Establece el WBS estándar, los códigos de oficio (`GW`, `MAS`, `CAR`, etc.), las unidades de medida y el desperdicio de materiales por defecto. | Taxonomía maestra (estática / ampliable) |
| **02. Datos maestros** | `03_Rate_Library` | Mantiene vectores de costes multicontratista sobre mano de obra, material, subcontratación y maquinaria. | Tablas de precios relacionales |
| **03. Cálculo** | `04_Project_Estimate` | Espacio de trabajo principal. Ingiere las cantidades de medición, evalúa el desperdicio efectivo, empareja las tarifas del contratista y agrega las líneas de coste directo. | Matrices dinámicas de desbordamiento de punto único |
| **03. Cálculo** | `05_Adjustments` | Aísla los costes preliminares de obra, las duraciones de andamios y contenedores, y las allowances provisionales del cliente. | Cuadros de partidas estructurados |
| **04. Informes** | `06_Internal_Estimate` | Construye la cascada comercial completa: costes directos + costes preliminares = coste primo $\rightarrow$ gastos generales y beneficio $\rightarrow$ imprevistos $\rightarrow$ punto de equilibrio. | Agregación dinámica por secciones |
| **04. Informes** | `07_Customer_Estimate` | Sintetiza un cuadro de presupuesto del cliente auditable y desensibilizado, mezclando los gastos generales en las tarifas de partida. | Matrices dinámicas de desbordamiento desensibilizadas |
| **04. Gobernanza** | `08_Checks` | Ejecuta de forma continua la integridad de datos en 6 puntos, la detección de códigos no mapeados, las alertas de tarifas ausentes y la conciliación del balance de sumas. | Audits booleanos automatizados y de desviación |

---

### Tres trampas que atrapan incluso a los estimadores experimentados

#### Trampa 1: compresión de tarifas mixtas de subcontratista
1. **Decisión tomada**: Un estimador aplica una tarifa histórica agregada de 85,00 £/m² a un lote de 140 m² de albañilería de bloques y ladrillos, suponiendo que la mano de obra y los materiales se promediarán sobre la base de un trabajo anterior.
2. **El defecto inadvertido**: El proyecto utiliza ladrillos vistos artesanales moldeados en húmedo (1.150 £/1.000 ladrillos) en lugar de ladrillos técnicos estándar (450 £/1.000 ladrillos), mientras que la obra está al final de un carril estrecho sin pavimentar que requiere transporte manual con carretilla.
3. **Impacto del defecto**: El coste real de materiales salta a 62,00 £/m² y la mano de obra sube a 48,00 £/m², totalizando 110,00 £/m² de coste directo.
4. **Por qué el razonamiento es defectuoso**: Las tarifas agregadas ocultan los cambios en las proporciones de recursos. La albañilería rara vez se reparte 50/50; la inflación de materiales y la logística de obra desacoplan la mano de obra y la velocidad de aprovisionamiento.
5. **Enfoque corregido**: Desagregar los costes directos en cuatro vectores distintos (mano de obra, material, subcontratación, maquinaria), vinculados directamente a la biblioteca de tarifas del contratista específico.
6. **Resultado corregido**: El coste real se marca en 110,00 £/m² de coste directo, fijando la partida en 15.400 £ en lugar de 11.900 £, protegiendo 3.500 £ de liquidez neta.

<details>
<summary>Ver la lógica de emparejamiento de tarifas multivector</summary>

```excel
=LET(
    target_contractor, '01_Setup'!$C$5,
    input_codes, A4:A500,
    rate_contractors, '03_Rate_Library'!A4:A1000,
    rate_codes, '03_Rate_Library'!B4:B1000,
    rate_matrix, '03_Rate_Library'!D4:G1000,
    composite_keys, rate_contractors & "|" & rate_codes,
    lookup_keys, target_contractor & "|" & input_codes,
    IF(input_codes="", "", 
        XLOOKUP(lookup_keys, composite_keys, rate_matrix, 0, 0)
    )
)
```
</details>

---

#### Trampa 2: desperdicio no capitalizado sobre cantidades netas
1. **Decisión tomada**: Para una losa de planta baja y un muro de doble hoja, el estimador mide 100 m² de baldosas de suelo y 80 m² de albañilería de ladrillos vistos del plano CAD, aplicando una contingencia presupuestaria global estándar del 5% en el resumen de la oferta.
2. **El defecto inadvertido**: Los patrones diagonales de baldosas en una habitación en L generan un 12% de desperdicio por corte; los ladrillos vistos alrededor de vanos escalonados producen un 8% de desperdicio.
3. **Impacto del defecto**: El contratista pide 7 m² menos de baldosas y 6,4 m² menos de albañilería, forzando un reaprovisionamiento de urgencia a precios premium de series cortas y deteniendo a los soladores durante tres días.
4. **Por qué el razonamiento es defectuoso**: El desperdicio es geometría física, no imprevistos financieros comerciales. Un imprevisto financiero no puede reponer palés ausentes de baldosas del mismo lote.
5. **Enfoque corregido**: Calcular el volumen neto de compra antes de la fijación de precios unitarios mediante una jerarquía escalonada: corrección manual % $>$ línea base de partida maestra % $>$ valor global por defecto %.
6. **Resultado corregido**: Los volúmenes de compra escalan correctamente a 112 m² para las baldosas y 86,4 m² para los ladrillos, eliminando el transporte de urgencia y la parada de obra.

<details>
<summary>Ver la lógica de determinación del desperdicio efectivo</summary>

```excel
=LET(
    codes, A4:A500,
    manual_waste, G4:G500,
    master_codes, '02_Item_Master'!A4:A500,
    master_waste, '02_Item_Master'!F4:F500,
    global_default, '01_Setup'!$C$6,
    looked_up_waste, XLOOKUP(codes, master_codes, master_waste, global_default, 0),
    IF(codes="", "", 
        IF(manual_waste<>"", manual_waste, 
            IF(looked_up_waste<>"", looked_up_waste, global_default)
        )
    )
)
```
</details>

---

#### Trampa 3: partidas preliminares transparentes negociadas por los clientes
1. **Decisión tomada**: El contratista incluye andamios (6.500 £), aseos portátiles e instalaciones de bienestar en obra (1.800 £) y dirección de obra por un supervisor (9.000 £) como partidas explícitas en el presupuesto del cliente.
2. **El defecto inadvertido**: El cliente argumenta: *«No voy a pagar 1.800 £ por un váter portátil y su presupuesto de andamios es más caro de lo que pagó mi amigo; quite esas líneas o buscaré otro constructor.»*
3. **Impacto del defecto**: Para asegurar el contrato, el contratista elimina 8.300 £ de costes preliminares del contrato, con la intención de «absorberlos en los beneficios generales».
4. **Por qué el razonamiento es defectuoso**: Los costes preliminares de obra son gastos de explotación directos rígidos, no un recargo discrecional. Eliminar la línea no reduce ni las instalaciones de bienestar ni los costes de alquiler de andamios.
5. **Enfoque corregido**: Mantener una visibilidad interna absoluta de los costes preliminares en `05_Adjustments` y `06_Internal_Estimate`, pero absorberlos dinámicamente en el cuadro del cliente mediante una distribución proporcional del recargo sobre las secciones de trabajo físicas.
6. **Resultado corregido**: El cliente recibe un cuadro de trabajo limpio en el que todos los costes preliminares y gastos generales están integrados matemáticamente en las tarifas unitarias por oficio, haciendo que la logística no sea negociable.

<details>
<summary>Ver la lógica de absorción proporcional del recargo</summary>

```excel
=LET(
    codes, '04_Project_Estimate'!A4:A500,
    base_rates, '04_Project_Estimate'!P4:P500,
    direct_total, '06_Internal_Estimate'!$C$22,
    internal_gross, '06_Internal_Estimate'!$C$28,
    ps_total, '06_Internal_Estimate'!$C$27,
    markup_factor, IF(direct_total>0, (internal_gross - ps_total) / direct_total, 1),
    filtered_rates, FILTER(base_rates, codes<>""),
    filtered_rates * markup_factor
)
```
</details>

---

### Escenario de ejemplo: ampliación y conversión de buhardilla en Hertfordshire

#### 1. Entradas brutas (`01_Setup` & `04_Project_Estimate`)
- **Proyecto**: ampliación envolvente de 45 m² en planta baja + conversión de buhardilla con lucarna trasera.
- **Contratista seleccionado**: `Apex_Builders_Herts`
- **Parámetros globales**: desperdicio por defecto = 5,0%, modo de costes preliminares = fijo (`05_Adjustments`), OHP = 15,0%, imprevistos = 5,0%, IVA = 20,0%.
- **Mediciones principales**:
  - `GW-001` (excavación de zanjas de cimentación): $24.0\,\text{m}^3$
  - `GW-002` (hormigón preparado C20/25 vertido): $16.5\,\text{m}^3$ (desperdicio estándar 5,0%)
  - `MAS-001` (albañilería de ladrillos vistos de 102,5 mm): $68.0\,\text{m}^2$ (corrección manual del desperdicio: 8,0%)
  - `STL-001` (vigas universales de acero estructural fabricadas e izadas): $1.85\,\text{t}$
  - `ROO-001` (tejas de hormigón entrelazadas): $52.0\,\text{m}^2$ (desperdicio estándar 8,0%)
- **Ajustes introducidos (`05_Adjustments`)**:
  - Andamios independientes (alquiler de 10 semanas): 4.800,00 £
  - Retirada de escombros de obra (4 contenedores de 8 yardas): 1.440,00 £
  - Instalaciones de bienestar temporales y almacenamiento seguro: 1.250,00 £
  - Suma provisional (allowance de mobiliario y electrodomésticos de cocina): 20.000,00 £

#### 2. Cálculos intermedios del motor (`04_Project_Estimate`)
- `MAS-001` cantidad neta calculada: $68.0 \times (1 + 0.08) = 73.44\,\text{m}^2$
- `MAS-001` tarifas del contratista: mano de obra 42,00 £, material 48,50 £, subcontratación 0,00 £, maquinaria 4,50 £ $\rightarrow$ tarifa compuesta = 95,00 £/m²
- `MAS-001` coste directo de la línea: $73.44\,\text{m}^2 \times £95.00 = £6,976.80$
- Costes directos agregados del proyecto ($\sum \text{Direct Cost}$ en todos los oficios): **112.450,00 £**

#### 3. Cascada comercial (`06_Internal_Estimate`)
$$\begin{aligned}
\text{Total Direct Cost} &= £112,450.00 \\
\text{Total Preliminaries} &= £7,490.00 \\
\hline
\mathbf{\text{Prime Cost}} &= £119,940.00 \\
\text{Overhead \& Profit (15.0\% on Prime)} &= £17,991.00 \\
\text{Contingency (5.0\% on Prime)} &= £5,997.00 \\
\text{Provisional Sums} &= £20,000.00 \\
\hline
\mathbf{\text{Gross Internal Contract Sum (Net of VAT)}} &= \mathbf{£163,928.00} \\
\text{Breakeven Floor (Direct + Prelims)} &= £119,940.00 \\
\text{Project Target Gross Margin} &= \frac{£163,928 - £119,940}{£163,928} = \mathbf{26.83\%} \quad (\text{includes Provisional Sums})
\end{aligned}$$

#### 4. Interpretación analítica y recomendación
- **Multiplicador de recargo**: factor de absorción proporcional aplicado a las partidas del cliente:
  $$\text{Markup Factor} = \frac{£163,928 - £20,000}{£112,450} = 1.27993$$
- **Traducción orientada al cliente**: El cliente ve `MAS-001` fijado en $£95.00 \times 1.27993 = \mathbf{£121.59/\text{m}^2}$, lo que produce una suma de línea de 8.929,57 £.
- **Resultado de la decisión**: El constructor oferta en **163.928,00 £ + IVA (196.713,60 £ bruto)**. Ninguna partida preliminar individual queda expuesta al examen línea por línea del cliente, y el colchón comercial de la empresa de 23.988 £ (OHP + imprevistos) permanece protegido.

---

### Referencia de fórmulas

<details>
<summary>01_Setup: indexación dinámica de contratistas</summary>

```excel
=SORT(UNIQUE(FILTER('03_Rate_Library'!A4:A500, '03_Rate_Library'!A4:A500<>"")))
```
*Objeto*: Extrae un vector ordenado y único de contratistas activos de la matriz de tarifas para rellenar dinámicamente la validación de datos de la celda `$C$5`.
</details>

<details>
<summary>04_Project_Estimate: multiplicación vectorial completa del coste directo</summary>

```excel
=LET(
    codes, A4:A500,
    net_qty, I4:I500,
    labour_r, J4:J500,
    mat_r, K4:K500,
    subc_r, L4:L500,
    plant_r, M4:M500,
    tot_rate, P4:P500,
    IF(codes="", "",
        HSTACK(
            net_qty * labour_r,
            net_qty * mat_r,
            net_qty * subc_r,
            net_qty * plant_r,
            net_qty * tot_rate
        )
    )
)
```
*Objeto*: Ejecuta un desbordamiento horizontal de 5 columnas (de Q a U) multiplicando las cantidades netas por los vectores de costes de cuatro componentes y las tarifas compuestas simultáneamente.
</details>

<details>
<summary>06_Internal_Estimate: agregación dinámica de secciones de trabajo</summary>

```excel
=LET(
    active_sections, SORT(UNIQUE(FILTER('04_Project_Estimate'!D4:D500, '04_Project_Estimate'!D4:D500<>""))),
    labour_col, SUMIFS('04_Project_Estimate'!Q$4:Q$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    mat_col, SUMIFS('04_Project_Estimate'!R$4:R$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    subc_col, SUMIFS('04_Project_Estimate'!S$4:S$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    plant_col, SUMIFS('04_Project_Estimate'!T$4:T$500, '04_Project_Estimate'!$D$4:$D$500, active_sections),
    total_col, labour_col + mat_col + subc_col + plant_col,
    HSTACK(active_sections, labour_col, mat_col, subc_col, plant_col, total_col)
)
```
*Objeto*: Agrupa dinámicamente todos los gastos directos del proyecto por sus respectivos oficios de construcción, sin necesidad de filas preestablecidas.
</details>

<details>
<summary>08_Checks: conciliación matemática del balance</summary>

```excel
=LET(
    customer_net, SUM('07_Customer_Estimate'!F4:F500) + '06_Internal_Estimate'!$C$27,
    internal_gross, '06_Internal_Estimate'!$C$28,
    tolerance, '01_Setup'!$C$12,
    IF(ABS(customer_net - internal_gross) <= tolerance, 
        "✅ PASS: Trial balance reconciled within tolerance", 
        "❌ FAIL: Imbalance detected [" & TEXT(customer_net - internal_gross, "£#,##0.00") & "]"
    )
)
```
*Objeto*: Realiza una verificación estricta del balance de sumas entre las ofertas orientadas al cliente y los costes internos de línea de resultado.
</details>

---

### Reglas de validación

| Hoja | Celda / rango | Objetivo de la regla | Regla de validación | Comportamiento en caso de error |
| :--- | :--- | :--- | :--- | :--- |
| `01_Setup` | `$C$5` | Contratista activo | Lista desplegable vinculada a `='01_Setup'!$F$4#` | Rechaza los nombres de contratista no registrados. |
| `01_Setup` | `$C$6:$C$11` | Porcentajes financieros | Validación numérica: $\ge 0.0\%$ y $\le 100.0\%$ | Evita entradas de impuestos o recargos negativas o matemáticamente catastróficas. |
| `02_Item_Master` | `A4:A500` | Código de partida maestra | Cadena de texto única; los duplicados se auditan en `08_Checks` | Marca una advertencia en el panel de gobernanza si la clave maestra está duplicada. |
| `04_Project_Estimate` | `A4:A500` | Código de partida de medición | Debe existir en `02_Item_Master!A4:A500` | Muestra `"⚠️ Unregistered Code"` en la descripción y desencadena un fallo de auditoría en `08_Checks`. |
| `04_Project_Estimate` | `B4:B500` | Cantidad medida | Valor numérico $\ge 0$ | La fórmula suprime los cálculos si la cantidad se omite o no es numérica. |
| `04_Project_Estimate` | `N4:N500` | Corrección de tarifa | Valor numérico $> 0$ | Exige un texto de explicación obligatorio en la columna O (`Override_Reason`). |
| `08_Checks` | `$C$9` | Control de equilibrio del modelo | $| \text{Customer Net} - \text{Internal Gross} | \le 0.01$ | Muestra una alerta roja prominente: `"❌ FAIL: Imbalance detected"`. |

</details>

---


## La lógica de negocio y la metodología

Este sistema se basa en una **descomposición de los costes unitarios en tres niveles**, combinada con un **modelo de costes por absorción proporcional**. La estimación de construcción tradicional se basa en tarifas unitarias históricas brutas (p. ej., 2.200 £ por metro cuadrado de superficie interior bruta), lo que oculta las desviaciones a nivel de oficio, las restricciones topográficas de la obra y las perturbaciones de la oferta del mercado.

Para resolverlo, el motor impone un desacoplamiento estricto:
1. **Capa de cantidades físicas**: Captura la medición geométrica real con factores de desperdicio de materiales dedicados.
2. **Matriz de precios de recursos**: Descompone cada tarea de construcción estándar en sus cuatro componentes comerciales fundamentales (mano de obra, material, subcontratación, maquinaria), vinculados dinámicamente a contratistas de oficio designados.
3. **Cascada de doble margen**: Distingue los costes directos de producción de los costes preliminares específicos de la obra para establecer una **línea base de coste primo**. Los gastos generales comerciales, los márgenes de beneficio y los imprevistos del proyecto se aplican posteriormente sobre esta línea base consolidada, estableciendo un suelo de rentabilidad infranqueable.

Para evitar la erosión de márgenes del lado del cliente durante las negociaciones comerciales de oferta, el cuadro orientado al cliente emplea la **absorción proporcional**. En lugar de presentar los costes preliminares, el margen del contratista y las reservas de riesgo como sumas discrecionales independientes, el motor asigna matemáticamente estas cargas entre las partidas físicas facturables. El cuadro del cliente resultante se alinea al céntimo con la valoración comercial interna, manteniendo los márgenes sensibles de oficio totalmente protegidos.

---

## Otras herramientas de esta serie

- **[Motor de comparación de ofertas de subcontratistas y análisis de desviaciones](#)**: Examina múltiples ofertas de oficio frente a las estimaciones internas de referencia para identificar anomalías de precios y lagunas de alcance.
- **[Planificador de flujo de caja de obra y curva en S de hitos](#)**: Convierte los cuadros de cantidades en previsiones de valoración mensuales, seguimiento de retenciones de garantía y disposiciones de capital de trabajo.
- **[Rastreador de costes de obra y costes reales de proyectos residenciales](#)**: Sistema de control de costes posadjudicación que sigue pedidos de compra, partes de trabajo y órdenes de variación frente a las líneas base de oferta originales.

---

## Licencia

Este proyecto está licenciado bajo la **Apache License 2.0**. Consulte el archivo [LICENSE](LICENSE) para más detalles.
