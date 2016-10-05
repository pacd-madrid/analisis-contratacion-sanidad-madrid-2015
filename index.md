---
title: "Contratatción Pública de la Consejería de Sanidad de Madrid 2015"
author:  
mode : selfcontained #{standalone, draft, selfcontained}
framework: revealjs
revealjs: {theme: white, transition: convex, center: "true"}
ext_widgets: {rCharts: libraries/nvd3}
knit        : slidify::knit2slides
---



<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

## El papel del sector privado en el Presupuesto de la Consejería de Sanidad de Madrid 2015

<img src='assets/img/logo-audita-sanidad.jpg' alt='Logo Auditoría en Sanidad' width='200px'></p>

<a href="http://auditasanidad.org/">http://auditasanidad.org/</a>


--- &vertical

<!-- ## Evolución de la deuda de la Comunidad de Madrid -->
<!-- ```{r, results='asis'} -->
<!-- require(htmlwidgets) -->
<!-- require(dygraphs) -->
<!-- datos <- read.csv("datos/evolucion-deuda-madrid.csv") -->
<!-- deuda <- ts(datos$Deuda, start=c(2000, 1), end=c(2015, 1), frequency=1) -->
<!-- dygraph(deuda, main = "") -->
<!-- ``` -->

<!-- *** -->

<!-- ## Evolución de la deuda de la Comunidad de Madrid -->
<!-- ```{r deuda_comunidad_madrid2} -->
<!-- require(htmlwidgets) -->
<!-- require(plotly) -->
<!-- datos <- read.csv("datos/evolucion-deuda-madrid.csv") -->
<!-- x <- list(title = "Año") -->
<!-- y <- list(title = "Millones de €") -->
<!-- p <- plot_ly(x = datos$Anio, y = datos$Deuda, name = "Deuda", type = "bar") %>% -->
<!--   layout(xaxis = x, yaxis = y) -->
<!-- p -->
<!-- ``` -->

<!-- *** -->

## Evolución de la deuda de la Comunidad de Madrid
<iframe src=' figure/deuda-comunidad-madrid-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart199f7bcd8467 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

<!-- *** -->

<!-- ## Evolución de la deuda de la Comunidad de Madrid -->
<!-- ```{r } -->
<!-- require(htmlTable) -->
<!-- colnames(data) <- c("Año", "Deuda") -->
<!-- tmp <- htmlTable(data, align="lr", rnames=FALSE, css.class="colortable",  -->
<!--   tfoot="<span class=\"footnote\">Fuente: Elaboración propia</span>") -->
<!-- (tmp <- gsub('<td', '<td nowrap="nowrap"; ', tmp)) -->
<!-- ``` -->

---

## Gasto en medios ajenos

<iframe src=' figure/gasto-medios-ajenos-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart199f12c84e4e ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Actividades realizadas con medios ajenos
### 3.143.914.276 €

<iframe src=' figure/actividades-medios-ajenos-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart199f77a27d90 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Importe de la contratación pública en 2015
### 490.932.459 €

<iframe src=' figure/contratacion-publica-modalidad-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart199f7b3f1ac4 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---


## Evolución de la venta de genéricos vs medicamentos innovadores

<iframe src=' figure/evolucion-ventas-genericos-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart199f41f36828 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## ¡Gracias por su atención!

<img src="assets/img/nodebemos_nopagamos.jpg" alt="No debemos, no pagamos">

