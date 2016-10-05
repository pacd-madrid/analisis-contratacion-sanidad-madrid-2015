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


---

## Objetivos

> 1. **Cuantificar los contratos** adjudicados por la Consejería de Sanidad
a empresas privadas **y su importe** en cinco modalidades de contratación:
  - Suministros
  - Servicios
  - Gestión de Servicios Públicos
  - Obras
  - Administrativos especiales

> 2. Investigar las **conexiones entre empresas adjudicatarias y los lobbies** más
representativos en el sector sanitario

> 3. **Difundir eficazmente los resultados de esta investigación a la ciudadanía**

<!-- Incremental lists -->
<script>
$('ul.incremental li').addClass('fragment')
$('ol.incremental li').addClass('fragment')
</script>

--- 

## Metodlogía

Principal fuente de información:
**Boletín Oficial de la Comunidad de Madrid (BOCM)**.
(Del 1 de enero al 31 de diciembre de 2015)

Sólo se han tenido en cuenta para esta investigación los contratos adjudicados y formalizados dentro de ese marco cronológico.

No se han considerado:
- Concesiones administrativas (Hospitales modelo PFI y PPP)
- Conciertos realizados con hospitales y clínicas privadas para el tratamiento de pacientes
- Prescripción de recetas por parte de los profesionales sanitarios a pacientes (Recetas)
- Trabajos realizados por empresas de proceso de datos

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
<iframe src=' figure/deuda-comunidad-madrid-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac4fff741c ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

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
#### Presupuestos Consejería Sanidad de Madrid 2015 (3.143.914.276 €)

<iframe src=' figure/gasto-medios-ajenos-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac27f840c4 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Actividades realizadas con medios ajenos
#### Presupuestos Consejería Sanidad de Madrid 2015

<iframe src=' figure/actividades-medios-ajenos-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac2f1ab781 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## Contratación pública en 2015
### 1.295 contratos por valor de 490.932.459 €

<iframe src=' figure/contratacion-publica-modalidad-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac510367b8 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

--- &vertical

## Ranking de empresas adjudicatarias 

<iframe src=' figure/ranking-empresas-adjudicatarias-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac8af9af1 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

***

## Ranking de empresas adjudicatarias 
## Top 10

<iframe src=' figure/ranking-empresas-adjudicatarias-top-10-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac47b37feb ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

---

## La Industria Farmaceútica
#### Contratos por un valor de 235.875.604€ (48,05%)

- Roche SA
- Novartis
- Pfizer SLU
- Gilead Sciences SL
- Janssen Cilag SA–Johnson & Johnson SA
- Sanofi
- GlaxoSmithKline

---

## Empresas de Tecnología Médica
#### Contratos por valor de 23.891.312€ (4,87%)

- Siemens
- Medtronic Ibérica SA – Covidien Spain SA
- General Electric Healthcare
- Philips Ibérica SA
- Boston Scientific Ibérica SA

--- &vertical

## Los Lobbies
#### Contratos por valor de 299.472.851€ (61%)

- Farmaindustria
- Fundación IDIS (Instituto para el Desarrollo e Integración de la Sanidad)
- SEDISA
- Federación Española de Empresas de Tecnología Sanitaria (FENIN)
- Club Gertech, ASEBIO, Fundación ECO, FUINSA y el
- Foro PPP

**¡Claro indicador del fortalecimiento del sector privado!**

***

## Ranking lobbies adjudicatarios 

<iframe src=' figure/ranking-lobbies-1.html ' scrolling='no' frameBorder='0' seamless class='rChart nvd3 ' id=iframe- chart21ac6351070c ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

--- 

## Propuestas de Audita Sanidad

Las partidas presupuestarias o contratos que beneficien a ciertos sectores económicos antes que al interés general de la ciudadanía deben denunciarse como configuradores de **deuda ilegítima**.

- Hospital de Collado Villalba. La Consejería de Sanidad ha abonado a Quirónsalud (antes IDC Salud, previamente Capio) 900.000,- euros mensuales durante dos años permaneciendo durante este tiempo cerrado.
- Hospitales modelo PFI y modelo PPP.
- Consumo farmacéutico.

Es urgente y necesario que se inicie un proceso sistemático de **Auditoría Ciudadana de la Deuda en Sanidad** para pormenorizarla, hacerla visible y, en su caso, no pagarla, transfiriendo la responsabilidad a los políticos implicados.

---

## ¡Gracias por su atención!

<img src="assets/img/nodebemos_nopagamos.jpg" alt="No debemos, no pagamos">

