# Suavalúo · Validación de avalúos (Resolución IGAC 941 de 2026)

Skill para **revisar informes de avalúo** en Colombia contra la **Resolución IGAC 941 de 2026**, artículo por artículo. Primero verifica si la 941 **aplica** al avalúo (fecha de inicio y propósito); luego entrega una **ficha resumen** y un resultado claro: **✅ APTO · 🟡 AJUSTAR · ❌ NO APTO · ⚪ NO APLICA**, con el detalle por numeral del informe y artículo de la 941, y las 3 acciones prioritarias.

**Autor:** José Andrés Mejía López — Avaluador RAA (AVAL-98380867) · **Suavalúo.org** (https://suavaluo.org)

**Licencia:** Creative Commons Atribución 4.0 (CC BY 4.0). Úsela y compártala conservando la atribución. Ver LICENSE.

## Qué es
La skill «informe-avaluo-941» es un conjunto de instrucciones de Suavalúo que usted instala en **Claude** (la inteligencia artificial de Anthropic). Con ella, Claude revisa su informe de avalúo contra la Resolución IGAC 941 de 2026 y le devuelve un resultado. La revisión no es manual: la hace Claude. Usted sube el informe, escribe una frase y lee el resultado.

## 1. Lo que necesita
- Una cuenta en Claude (claude.ai). Sirve cualquier plan: gratuito, Pro, Max, Team o Enterprise.
- Tener activada la creación de archivos: Configuración › Capacidades (Settings › Capabilities) › «Ejecución de código y creación de archivos» (en algunas versiones, «Crear y editar archivos»). En cuentas Team o Enterprise, quien administra la cuenta debe permitir las skills.
- El archivo **informe-avaluo-941.zip**, que le entrega Suavalúo. No lo descomprima.

## 2. Instale la skill (una sola vez)
1. En Claude, entre a Personalizar › Skills (Customize › Skills), o abra claude.ai/customize/skills.
2. Pulse «+» y luego «Crear skill» (Create skill).
3. Elija «Subir una skill» (Upload a skill).
4. Seleccione el archivo informe-avaluo-941.zip.
5. La skill aparece en su lista. Revise que su interruptor quede encendido.

Si la carga falla, confirme que subió el .zip tal como lo recibió, sin descomprimirlo ni cambiarle el nombre.

## 3. Revise un informe
1. Abra un chat nuevo en Claude.
2. Adjunte el informe en PDF.
3. Escriba: **valide 941**.
4. Espere el resultado. Si son varios informes, adjúntelos juntos y Claude le entrega una fila por informe.

Si Claude no usa la skill por sí solo, escriba: «Use la skill informe-avaluo-941 y valide 941 este informe».

## 4. Cómo leer el resultado
1. **Ficha resumen:** fecha que tomó, si la 941 aplica, si es obligatoria o solo referencia, el resultado y cuántos errores encontró.
2. **Resultado**, uno solo:
   - **✅ APTO:** el informe cumple; puede traer sugerencias de mejora.
   - **🟡 AJUSTAR:** faltan datos, citas o fuentes, pero el valor no cambia.
   - **❌ NO APTO:** errores de fondo que pueden cambiar el valor (método, PH sin valor integral por m², CV por encima del tope, valor adoptado sin sustento, depreciación fuera de Ross-Heidecke, cifra sin fuente o conflicto de norma urbanística sin tratar). Corrija antes de entregar.
   - **⚪ NO APLICA:** el avalúo se inició antes del 3 de agosto de 2026. No se revisa con la 941.
3. **Detalle:** cada hallazgo con el numeral del informe, el artículo de la 941 y qué hacer.
4. **Las 3 acciones prioritarias** para mejorar el resultado.

## 5. Qué revisa
- **Si la 941 aplica.** Por fecha (arts. 59 y 60): rige desde el 3 de agosto de 2026; los avalúos iniciados antes siguen con la norma anterior. Toma la fecha de la solicitud; si no aparece, la de la visita y, si tampoco, la del informe *(Criterio Suavalúo)*. Por propósito (art. 2): obligatoria en los encargos del Decreto 1170 de 2015; en los demás (hipotecario, particular, contable) es referencia metodológica. Derogatorias (art. 60): si la 941 aplica, citar la Res. 620 de 2008 es un error.
- **Gestión valuatoria (arts. 6 a 14):** marco jurídico, plazo, visita, parámetros, identificación física, jurídica y normativa (uso del suelo consultado directamente en el POT, PBOT o EOT), las 11 etapas del art. 13 y el contenido mínimo del art. 14 (coordenadas del centroide, memoria de cálculo y certificado RAA).
- **Métodos (arts. 15 a 34):** método justificado (la 941 no exige dos). Mercado con fecha de captura, sin homogenización por factores y CV de hasta 7,50 % urbano y 10,0 % rural (art. 21). Costo con Ross-Heidecke y vida útil de la Tabla 2 del Anexo. También renta y técnica residual.
- **Propiedad horizontal (arts. 13.9 y 36):** valor integral por m² de área privada; parqueaderos y depósitos valorados por separado. Si el área privada de la casa es el lote, acepta componentes con el resumen del valor integral por m² *(Criterio Suavalúo)*.
- **Casos especiales (arts. 35 a 57):** procedimientos específicos, zonas rurales, suelos de protección, plusvalía y controversia, cuando apliquen.
- **Forma:** toda cifra con fuente, áreas que multiplican bien y coma decimal.

## 6. Tenga en cuenta
- Los puntos marcados como *Criterio Suavalúo* son criterios de aplicación de Suavalúo; no salen literalmente de la norma.
- La skill no cambia su valor ni corrige su informe: le dice qué revisar.
- Es apoyo metodológico. Usted, como avaluador RAA, revisa, decide el valor, firma y responde por el informe (Ley 1673 de 2013).
- Antes de citar un numeral, confírmelo en el texto oficial de la Resolución IGAC 941 de 2026 (Diario Oficial 53.575, 3 de agosto de 2026) y su Anexo Técnico.
- Claude puede equivocarse. Si un hallazgo no le parece correcto, pídale que le muestre el artículo en que se basa.
