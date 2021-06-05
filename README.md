# EN LA PREDICCIÓN DE LA MERMA DE DEFECTOS EN CULTIVOS DE BANANO

## Autor
Sebastian Monsalve Solis  
CC 1128273363  
e-mail: sebastian.monsalves@udea.edu.co

## Resumen ejecutivo

La agricultura de precisión (AP), según la Sociedad Internacional de Agricultura de Precisión (ISPA), es una estrategia de gestión que recoge, procesa y analiza datos temporales, espaciales e individuales y los combina con otras informaciones para respaldar las decisiones de manejo de acuerdo con la variabilidad estimada, y así mejorar la eficiencia en el uso de recursos, la productividad, la calidad, la rentabilidad y la sostenibilidad de la producción agrícola. La AP se conoce también como agricultura de precisión o gestión de cultivos específica del lugar.  

C.I. Unibán S.A. es la comercializadora internacional colombiana que desarrolla negocios de agroindustria de alto valor, intensivos en logística, y que desde hace más de 50 años en el mercado lidera la actividad agroindustrial y comercial principalmente de banano, plátano y bananos exóticos del país. Unibán requiere dentro de su estrategia optimizar la productividad de las fincas, analizando las diferentes variables que afectan la cantidad de cajas exportadas por hectárea y las interacciones entre tales variables.

Se entenderán los datos y cómo están relacionados entre sí para impactar la productividad, considerando como variables objetivo el aumento del peso y la reducción de la merma, para lo cual se analizan el perfil del racimo; los defectos naturales (daño animal, quemaduras, manchas, etc.) y defectos de proceso (mal uso de plástico, maltrato, cicatrices de manejo, etc.); y las variables medioambientales.

Con el conocimiento obtenido a partir del análisis exploratorio, se plantea experimentar con diferentes modelos supervisados de ML que permitan hacer diferentes predicciones, en particular el peso de los defectos que tendrá determinado cultivo, y así poder tomar calcular el peso neto que se podrá comercializar.



## Datos

Uniban S.A tiene diversas fuentes de información tanto internas como externas las cuales son centralizadas en su DataHub. Para el interés de esta monografía nos centramos en los datos generados por su aplicación TROPICO las cual gestiona desde el cultivo de la fruta hasta su comercialización, esta información se almacena es sus bases de datos transaccionales, información de su ERP (SAP) y de estaciones meteorológicas distribuidas en sus diferentes fincas.

Los datos son propiedad de Uniban S.A y solo está permitido el uso de ellos por los autores de esta monografía y con fines académicos. 