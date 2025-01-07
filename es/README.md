# Fabricación de una Pieza Exterior Personalizada para M4 de Airsoft en Fibra de Carbono

![Imagen de presentación vista lateral](/content/IMG_9243.HEIC.jpg)
![Imagen de presentación tubos superpuestos](/content/IMG_9242.HEIC.jpg)


# Índice
1. [Introducción y Consideraciones de Diseño](#1-introducción-y-consideraciones-de-diseño)
2. [Modelado y Creación del Molde](#2-modelado-y-creación-del-molde)
3. [Cálculo de Materiales y Aplicación de Resina](#3-cálculo-de-materiales-y-aplicación-de-resina)
4. [Impresión de Piezas en PLA+](#4-impresión-de-piezas-en-pla)
5. [Preparación de las Piezas](#5-preparación-de-las-piezas)
6. [Encerado](#6-encerado)
7. [Capas de Resina y Carbono](#7-capas-de-resina-y-carbono)
8. [Montaje y Curado](#8-montaje-y-curado)
9. [Selección del Tubo de Carbono y Herramientas](#9-selección-del-tubo-de-carbono-y-herramientas)
10. [Corte y Ajuste del Tubo](#10-corte-y-ajuste-del-tubo)
11. [Montaje Final](#11-montaje-final)
12. [Pruebas y Ajustes](#12-pruebas-y-ajustes)
13. [Conclusiones](#13-conclusiones)

---

## 1. Introducción y Consideraciones de Diseño

Este manual detalla el proceso de fabricación de una pieza exterior personalizada para un M4 de Airsoft utilizando fibra de carbono. Se abordarán los desafíos y soluciones para componentes específicos como la punta roscada, el componente interno y la longitud del tubo.

![Imagen general](/content/image_1736195279192_0.png)

Primero, nos centraremos en la punta donde se colocará el supresor, un elemento crítico con rosca a contrarreloj. La dificultad radica en la imposibilidad de fresar la pieza para crear la rosca, ya que deberá soportar cierta presión y el desgaste por la inserción y extracción del supresor. Se experimentará con la creación de la rosca directamente con la prensa, evaluando cuidadosamente el resultado y la durabilidad.

Se considera la necesidad de refuerzo adicional, posiblemente con la incorporación de tornillos cónicos en miniatura.

En segundo lugar, abordaremos un componente interno complejo que se ajusta al cuerpo superior de la réplica. Esta pieza asegura el tubo al RIS y permite la inserción del hop-up. Su fabricación es compleja debido a las protuberancias y dimensiones variables.

Finalmente, el tubo tendrá una longitud variable que requerirá un corte preciso según las necesidades.

## 2. Modelado y Creación del Molde

El modelado 3D y la posterior impresión nos permiten crear prototipos y moldes de forma precisa.

El proceso de creación del molde para la punta del supresor consiste en construir un modelo con una base, tapa, pasador, pasadores de centrado y una arandela de bloqueo. La forma final será cúbica para asegurar un moldeo preciso.

![Punto](/content/image_1736195635219_0.png)

## 3. Cálculo de Materiales y Aplicación de Resina

Analizando el volumen de la pieza modelada, calculamos la cantidad necesaria de carbono y resina epoxi. Se recomienda una mezcla de ***60%*** carbono y ***40%*** resina, redondeando las cantidades para obtener resultados óptimos.

En el programa de modelado, al asignar propiedades a la pieza, se obtiene el volumen en milímetros cúbicos `(mm^3)`.

![image.png](/content/image_1736195659340_0.png)

**La fórmula de conversión es:**

```
gramos = milímetros cúbicos × 0.001 por lo tanto: X mm^3 / 1000
La punta tiene 3034.008mm^3 / 1000 = 3.034008g (gramos)
```

Este es el peso final de la pieza. Para calcular la cantidad de carbono y resina, utilizaremos las siguientes fórmulas:

```
porcentaje * cantidad / 100
60% * 3.034g = 1.8204g (carbono)
40% * 3.034g = 1.21g (resina)
```

Normalmente se usa un poco más, redondeando las cantidades y teniendo en cuenta que el exceso de resina saldrá del molde.

## 4. Impresión de Piezas en PLA+

Utilizaremos PLA+ para imprimir los modelos debido a su facilidad de impresión y manejo.

Mi impresora es una Ender 3 Pro con Klipper, que en el futuro se convertirá en una Voron Switch.

Configuramos las capas a `0.15mm` con Linear Advance para lograr una calidad de impresión similar a la normal pero en menos tiempo. La duración del proceso es de aproximadamente 4 horas para la punta y 8 horas para la pieza interna.

Recomiendo dejar la impresión durante la noche para tener las piezas listas al día siguiente. Prefiero imprimir las piezas por separado para realizar comprobaciones de medidas y detectar posibles errores.

En el diseño del modelo, consideramos un margen de ***0.20mm*** entre las piezas que se unen y también pensamos en cómo se evacuará el exceso de resina.

## 5. Preparación de las Piezas

Antes de comenzar el proceso, nos aseguramos de preparar meticulosamente las piezas. Para ello, lijamos cuidadosamente las superficies interiores, eliminando cualquier artefacto o defecto. Esta etapa es crucial, ya que cualquier imperfección se reflejará en el acabado final.

Además, realizamos pruebas exhaustivas para asegurar que las piezas encajen suave y sin problemas, evitando cualquier atasco durante el montaje.

## 6. Encerado

Para facilitar la extracción y lograr una superficie lisa, aplicamos cera tanto por dentro como por fuera del molde. En el interior utilizaremos aplicación manual de cera, ya que dejará la superficie más lisa y no se transparentarán las capas de la impresión 3D, mientras que en el exterior se utiliza un spray para retirar restos de resina sobrante.

## 7. Capas de Resina y Carbono

Aplicamos una primera capa de resina con una brocha especial, asegurándonos de cubrir cada rincón de las piezas. Luego, con cuidado y precisión, colocamos trozos de tela de carbono sobre la resina. Este proceso se repite meticulosamente hasta que todas las piezas estén completamente impregnadas.

En el caso de la tapa, aplicamos una cantidad generosa de resina y luego añadimos una capa uniforme de carbono.

## 8. Montaje y Curado

Una vez preparadas todas las piezas, las ensamblamos y envolvemos cuidadosamente con film transparente. Para asegurar una unión perfecta, utilizamos una abrazadera para aplicar presión uniformemente en todas las áreas. Durante este paso, es normal que sobresalga un poco de resina.

Después de completar todo el proceso, dejamos reposar las piezas durante aproximadamente 12 horas para que la resina y el carbono se endurezcan (no completamente), asegurando la integridad estructural de las piezas y permitiendo extraerlas del molde sin problemas. Las piezas deberán curar durante otras 12 horas para alcanzar su dureza final.

<video src="/content/rendition.m3u8_1736195937051_0.mp4-hevc-q28.mp4" controls preload></video>

## 9. Selección del Tubo de Carbono y Herramientas

Es crucial elegir el tubo adecuado para el proyecto. Generalmente optamos por tubos prefabricados de `50cm` de longitud. En este caso, compramos un tubo con dimensiones de `18x16x500mm` y uno de `32mm` de diámetro por un precio razonable de aproximadamente `10€`, incluyendo el envío, desde el siguiente sitio web: [Enlace de Compra](https://es.aliexpress.com/item/1005004139982617.html?spm=a2g0o.order_detail.order_detail_item.5.488a39d3IQXEao&gatewayAdapt=glo2esp)

Antes de comenzar el corte, asegúrate de tener las herramientas adecuadas. Puedes optar por una sierra tradicional, aunque el carbono no se corta fácilmente con este método. La opción más recomendada es utilizar una herramienta rotativa como una Dremel. Personalmente, utilizo un modelo **Teccpo** que viene con un cable de extensión.

![image.png](/content/image_1736195989372_0.png)

![image.png](/content/image_1736195995987_0.png)

![image.png](/content/image_1736196006220_0.png)

## 10. Corte del Tubo con Dremel

Para realizar cortes precisos y limpios en el tubo de carbono, diseñé un soporte que sujeta el tubo de forma segura y permite girarlo para realizar cortes rectos. El cable de extensión de la Dremel se conecta al mango principal y el tubo se mantiene en su lugar mediante clips. En la base del soporte, hay cuatro ruedas que facilitan la rotación del tubo para obtener cortes precisos y limpios.

![image.png](/content/image_1736196016462_0.png)

![image.png](/content/image_1736196021933_0.png)

![image.png](/content/image_1736196026756_0.png)

## 11. Resultados del Corte y Video

Una vez que hayas cortado el tubo según tus especificaciones, asegúrate de revisar los bordes para verificar que estén lisos y sin astillas.

En el siguiente video, he documentado el proceso de corte utilizando la Dremel y el soporte diseñado, lo que te dará una idea clara de cómo realizar este paso crucial en la creación de tu propia culata para M4.

Video de cómo se corta:

<video src="/content/rendition.m3u8-cutting.mp4" preload controls></video>

## 12. Lijado y Unión de Piezas

Comenzamos el proceso de lijado utilizando papel de lija tipo grid con grano 80 y 240 para asegurar un acabado suave y uniforme en las piezas. Elegimos no aumentar el grado del papel de lija, ya que esta textura es ideal para facilitar la adhesión entre las piezas durante el montaje.

Para proteger las áreas visibles y evitar arañazos accidentales, cubrimos cuidadosamente las piezas con especial atención al detalle.

Para unir las piezas, utilizamos un pegamento epoxi bicomponente de alta eficacia. Preparamos la mezcla correcta y la aplicamos con precisión en las juntas. La ventaja de este pegamento radica en su rápido proceso de endurecimiento, que tarda menos de un minuto, asegurando una unión sólida y duradera entre las piezas.

Este enfoque meticuloso del proceso de lijado y montaje nos permite lograr resultados de alta calidad y asegurar la integridad estructural de cada pieza. Cada paso se realiza con cuidado y precisión para garantizar un producto final impecable y duradero.

<video src="/content/3rendition.m3u8_1736196251750_0.mp4" controls preload></video>

## 13. Molde del Soporte del Tubo y Bracket del Hop-Up (Opcional)

El soporte del tubo y el bracket del hop-up son componentes críticos y complejos en su fabricación. Esta es la tercera versión del molde y pronto compartiré una versión más actualizada en futuras publicaciones. Este molde se compone de cuatro partes principales y dos partes internas, una de las cuales se desecha y la otra se conserva para su procesamiento.

El método de fabricación sigue el mismo proceso básico que aplicamos a otras partes: primero, lijamos cuidadosamente las superficies para asegurar un acabado liso; luego, aplicamos una capa de cera para facilitar la liberación del molde. A continuación, unimos las piezas del molde. En este caso particular, las sujetamos con tornillos. Para evitar la formación de burbujas u otros defectos durante el vertido, aplicamos plastilina en las juntas. Esta plastilina no solo previene imperfecciones, sino que también protege los tornillos durante el proceso.

Este enfoque meticuloso de la fabricación asegura que cada componente sea de la más alta calidad, sin defectos visuales ni estructurales. Cada paso, desde el lijado hasta la protección contra imperfecciones, se realiza cuidadosamente para lograr un producto final excepcional.

---

# Herramientas

* Dremel
* Guantes
* Mascara de particulas
* Gafas protectoras

# Costes

Asumiendo que tenemos herramientas básicas como dremel, taladro, papel de lija, impresora 3D, etc...

| Material | Unidad | Coste |
|--|--|--|
|[Tubo de Carbono](https://es.aliexpress.com/item/1005004139982617.html?spm=a2g0o.order_detail.order_detail_item.5.488a39d3IQXEao&gatewayAdapt=glo2esp)|1|9,05€ con (-20%)|
|[Adaptador de Aluminio 12mm CW a 14mm CCW]()| 1 | 0,92€ |
|[Macho de Roscar a Derechas HSS](https://es.aliexpress.com/item/4000712624358.html?spm=a2g0o.order_list.order_list_main.88.7d85194d3GhdmP&gatewayAdapt=glo2esp)|1|3,37€|
| ***TOTAL*** | 3 | ***13,34€*** |

## Modelos y Archivos

Los modelos son de pago y puedes encontrarlos aquí: [Cults3D](https://cults3d.com/es/modelo-3d/juegos/diy-outer-barrel-airsoft-m4-aeg)

### FAQ

- ***¿Por qué son de pago?***
    - _He dedicado tiempo a escribir este artículo, he pasado tiempo imprimiendo y probando piezas para darte todo listo..._


---

## Conclusión

Este manual le ha guiado a través del proceso de creación de un cañón exterior de fibra de carbono personalizado para una M4 de Airsoft, desde el diseño y el modelado hasta el corte, el montaje y el acabado. Siguiendo estos pasos y prestando atención a los detalles, podrá crear un componente personalizado de alta calidad para su réplica. Recuerda que la seguridad y la precisión son primordiales durante todo el proceso. Te animamos a que pruebes este proyecto y experimentes la satisfacción de crear tus propias piezas personalizadas.