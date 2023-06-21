# PI02 Analytics

Este es el último proyecto individual de la etapa de labs en el bootcamp: SoyHenry. Los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, Se realizará un analisis de diferentes plataformas plantear reesultados.

- - - 

# MOOCs

![image info](/_src/Images/mooc.jpg)

Se tienen distintos sets de datos de MOOCs: *Coursera*, *EDx* y *Udemy*.
Los datos varían entre si es pago o no, precio de inscripción, precio de certificado, nivel *(introductory, itermediate, etc)*, links, cantidad de suscriptores, cantidad de reviews, y descripciones de los cursos como fecha o resumen. 

## Carpetas
- **_src:** Los recursos necesarios tanto imagenes como datasets. Dentro existe el lake de los sets en bruto sin transformaciones. 
- **ETL_main:** Es donde se realizan la mayor transformación que por separado se fueron limpiando.
- **ETL_mooc:courses:** Es donde Todos los datasets se cruzan para formar uno sólo.
- **Dashboard:** Son las conclusiones más importantes. Hecho en Power BI.


## KPIs
- Tasa de conversión de inscriptos gratuitos a inscriptos pagados.
- Promedio del rating en coursera.
- Total de suscripciones.
- Tasa de suscripciones en cursos introductorios.