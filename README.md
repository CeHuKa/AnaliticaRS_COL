# Workshop Analítica con redes sociales - Twitter

Este taller ofrece un acercamiento teórico-práctico a conceptos como *web scraping*, análisis de redes, grafos, *NLP*, análisis de sentimiento, clusterización y predicción mediante el uso de información obtenida de la red social *Twitter*. 

El mundo de la analítica es muy extenso y variado. Mediante aplicaciones sencillas aprenderemos varios conceptos, su implementación y uso potencial en información obtenida de una fuente de contenidos conocida por todos como es *Twitter*.

## ¿Que necesitamos para empezar?

### Lo básico: Twitter, R y RStudio.

* Si aún no la tienes, crea una cuenta en [Twitter](http://www.twitter.com)
* Instala [R](https://cran.r-project.org/) en tu computador.
* Es recomendable instalar también [R Studio](https://www.rstudio.com/) en tu computador.
* Acá un [tutorial](https://medium.com/datos-y-ciencia/tutorial-instalaci%C3%B3n-r-y-rstudio-563771a29289) de instalación de estos dos. 

### Complementos: NodeXL y Gephi

**NodeXL**
* Obtenerlo diligenciando este [formulario](https://www.nodexlgraphgallery.org/Pages/RegistrationBasic.aspx). A vuelta de correo recibiras un link para descargar el archivo *.exe*. 
* Una vez descargado Hacer clic en *Ejecutar*.
* Si te pregunta por el *Microsoft Visual Studio*, aceptar, también es necesario aceptar los términos y condiciones que le aparezcan.

**Gephi**
* Instala [Gephi](https://gephi.org/) . Descargar el archivo e instala en tu equipo.

**LostCircles (Opcional)**
* Si tienes cuenta en [Facebook](https://www.facebook.com/) configura el lengujae de tu perfil a English(US)
* Instala el complemento de chrome [LostCircles](https://chrome.google.com/webstore/detail/lost-circles-social-netwo/ehpmfdlcppenimpibdifodjgfafkjhjl?hl=es-419.Como%20Tunear%20El%20Fondo%20De%20GooGleEspero) . Instala en tu equipo.

### Librerias

Para el desarrollo del taller, haremos uso de las siguientes librerias, las cuales es recomendable tener instaladas previamente:

```{r}
library(ggplot2)
library(lubridate)

library(tm)
library(tidyverse)
library(tidytext)
library(dplyr)
library(quanteda)

library(RColorBrewer)
library(wordcloud)
library(gridExtra)
library(scales)

library(rtweet)        
library(httpuv)             

library(randomForest)
library(mlbench)
library(caret)
library(pROC)
```
## Datos

En este repositorio se encuentran los sets de datos con los cuales se trabajará el sábado.
