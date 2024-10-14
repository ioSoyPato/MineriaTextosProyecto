# 🖥️ Sistema de Monitorización y Análisis de Medios para Gestión de Crisis
>[!note]
> Te invitamos a darte una vuelta por nuestros githubs para que revises más proyectos increibles :)

Proyecto realizado por:
- <a href='https://github.com/dafnetamayo'>Dafne Tamayo Leon</a> 
- <a href='https://github.com/ioSoyPato/'>Patricio Adulfo Villanueva Gio</a> 

## 🔎 Descripción del Proyecto:
Este proyecto tiene como objetivo desarrollar un sistema integral que monitoree, analice y responda a la información que circula en los medios de comunicación y redes sociales, particularmente útil para empresas y gobiernos durante crisis o eventos importantes.

## 🧩 Componentes del Proyecto:
- __Extracción de Información:__

    - Implementar herramientas que automáticamente recojan datos de noticias, blogs, redes sociales y foros en tiempo real. Esta información incluiría artículos, posts y comentarios relacionados con eventos específicos o temas de interés.
- __Clustering de Documentos:__

    - Agrupar automáticamente el contenido recopilado en categorías relevantes para la crisis o evento en cuestión. Por ejemplo, durante un desastre natural, se podrían identificar categorías como 'ayuda y rescate', 'impactos ambientales', 'declaraciones oficiales', etc.

- __Análisis de Sentimiento:__

    - Aplicar análisis de sentimiento a los textos recogidos para evaluar las emociones y opiniones del público. Esto ayudaría a entender la percepción pública hacia la gestión de la crisis o evento.

- __Análisis de Tendencias:__

    - Identificar temas que están ganando tracción o perdiendo interés a lo largo del tiempo. Esto es crucial para ajustar las estrategias de comunicación y respuesta en tiempo real.

- __Clasificación de tematicas:__
  >[!TIP]
    > Puedes agregar una noticia en particular para clasificarla

    - Utilizar modelos de clasificación de texto para identificar y categorizar las temáticas de los contenidos recopilados. Esto permite una segmentación más precisa del contenido, facilitando la respuesta específica a cada tipo de mensaje o información.
- __Extracción de Palabras Clave:__

    - Destacar las palabras clave y frases más mencionadas en los medios para identificar rápidamente los principales puntos de discusión o preocupación.

## ⛳ Objetivo:
El objetivo principal es proporcionar a las organizaciones una plataforma que les permita estar informadas en tiempo real sobre cómo se está comunicando y percibiendo una situación de crisis. Esto permite una gestión más efectiva y una respuesta más rápida y adecuada a la evolución de la situación.

Incluir la Clasificación de Temáticas no solo enriquece la capacidad de análisis del sistema, sino que también refina la precisión con la que se pueden identificar y responder a diferentes aspectos de una crisis, lo cual es vital para manejar situaciones complejas y dinámicas eficientemente.


>[!IMPORTANT]
> Este proyecto corre sobre un flujo de prefect en un servidor web. Es imperativo que si deseas clonar este repositorio para realizar modificaciones __actualices__ el codigo ya se __para correr__ en un servidor web de tu propiedad o __en tu maquina local__
