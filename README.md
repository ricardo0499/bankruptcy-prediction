# bankruptcy-prediction
A project to predict bankruptcy on taiwanese companies data

La predicción de la quiebra empresarial ha sido un área de intensa investigación en finanzas y contabilidad desde hace décadas, el estudio más antiguo en términos de predicción moderna de quiebras se remonta a 1932, cuando Fitzpatrick presentó una forma eficaz de distinguir entre empresas en quiebra y sanas mediante el análisis de 20 pares de ratios contables de empresas. Tradicionalmente, se han utilizado modelos estadísticos como el análisis discriminante (ej. modelo Z-score de Altman) para evaluar la salud financiera de las empresas. Sin embargo, con el avance del Machine Learning, han surgido nuevas oportunidades para construir modelos más precisos y robustos que puedan identificar patrones complejos en grandes volúmenes de datos financieros. La quiebra es un evento multifactorial influenciado por aspectos económicos, sectoriales y de gestión interna. Un modelo predictivo eficaz no solo señala el riesgo, sino que también puede ofrecer información sobre las variables financieras clave que contribuyen a este riesgo, permitiendo intervenciones proactivas y una mejor gestión del capital.

# La Data
El problema central consiste en desarrollar un modelo predictivo capaz de clasificar las empresas taiwanesas como en quiebra o no en función de sus características financieras y operativas. El objetivo de esta clasificación es anticiparse a la quiebra de las empresas y proporcionar información valiosa a las partes interesadas, como inversores, acreedores y organismos reguladores.

El modelo utilizará 95 características de entrada distintas (X1 a X95), que son ratios y métricas financieras cuantitativas. Estos atributos abarcan una amplia gama de indicadores de salud financiera, entre los que se incluyen:
Ratios de rentabilidad: Como el rendimiento de los activos totales (X1, X2, X3), el margen bruto de explotación (X4) y varios tipos de interés netos (X7, X8, X10). Indican la eficacia con la que una empresa genera beneficios a partir de sus activos y ventas.
Ratios de liquidez: Incluyen el Ratio Corriente (X33), el Ratio Rápido (X34) y el Índice de Flujo de Caja (X13). Evalúan la capacidad de una empresa para hacer frente a sus obligaciones a corto plazo.
Ratios de Solvencia: Como Deuda total/Patrimonio neto total (X36) y Ratio de endeudamiento (X37). Miden la capacidad de una empresa para cumplir sus compromisos financieros a largo plazo.
Ratios de eficiencia: Como la rotación total de activos (X45) y la rotación de cuentas por cobrar (X46). Reflejan la eficiencia con la que una empresa utiliza sus activos para generar ventas.
Tasas de crecimiento: Incluyendo la Tasa de Crecimiento del Beneficio Bruto de las Ventas Realizadas (X24) y la Tasa de Crecimiento del Activo Total (X29). Indican la expansión o contracción de la empresa.
Métricas por acción: Como el valor neto por acción (X16, X17, X18) y el flujo de caja por acción (X20). Proporcionan información sobre los resultados de la empresa desde la perspectiva del accionista.
Indicadores operativos y estructurales específicos: Como la Tasa de Gastos de Investigación y Desarrollo (X12), el Beneficio de Explotación por Persona (X52), e indicadores como el Indicador de Pasivo-Activo (X85) y el Indicador de Beneficio Neto (X94).

# Resultados

<img width="580" height="329" alt="image" src="https://github.com/user-attachments/assets/e2260fed-919e-4ad1-8bc1-77c10602c09c" />

# Cómo reproducir resultados
- Empezar por tener instalado jupyter notebook y sus dependencias
- abrir el archivo pry_final_modelos.ipynb
- instalar requerimientos con pip install -r 'requirements.txt'
- correr cada celda y observar resultads
- opcional se incluye el notebook final_test_2.ipynb con el modelo final y su proceso de optimización

