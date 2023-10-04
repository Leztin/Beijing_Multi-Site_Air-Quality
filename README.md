# Beijing_Multi-Site_Air-Quality

## Dataset

El **dataset** empleado se puede obtener de manera pública a través del siguiente enlace: [beijing_air_quality.csv](https://www.kaggle.com/datasets/sid321axn/beijing-multisite-airquality-data-set).

## Objetivo

El objetivo de esta práctica es **predecir** la variable **continua** `PM2.5` a través de las técnicas de **regresión multivariante** y de **red neuronal en modo regresión** con **selección de modelos** (BIC, AUC, etc.). **Para este primer PDF, la práctica se resolverá utilizando el software de R**.

La **materia particulada 2.5** (`PM2.5`) es un tipo de partícula muy pequeña, suspendida en el aire, que tiene un **diámetro de menos de 2.5 micras** y que se utiliza usualmente como medida de **contaminación atmosférica**. La monitorización de este tipo de partículas en grandes ciudades es **fundamental** debido a que son lo suficientemente pequeñas como para ser **inhaladas en los pulmones** y llegar al **torrente sanguíneo**. Ello puede provocar **consecuencias nocivas para la salud**, especialmente para personas con afecciones respiratorias como el **asma** o **enfermedades cardíacas**. 

La exposición prolongada a niveles elevados de `PM2.5` también se ha relacionado con un **mayor riesgo** a padecer enfermedades cardiovasculares, respiratorias y cáncer de pulmón.
Por esta razón, las regulaciones ambientales y de salud pública en la mayoría de países buscan **limitar la presencia de esta partícula en la atmósfera**. Los modelos que en esta práctica se proponen están enfocados a **predecir la variable continua** `PM2.5` en función del resto de características **meteorológicas y de calidad del aire** de las que se disponen.
