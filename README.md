# 📊 Dashboard Text Mining - Plan de Gobierno "Compromiso Molinero" 2026-2030

<p align="center">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Shiny-shinyapps.io-blue?style=for-the-badge&logo=r&logoColor=white" alt="Shiny">
  <img src="https://img.shields.io/badge/Text_Mining-FF6F00?style=for-the-badge" alt="Text Mining">
  <img src="https://img.shields.io/badge/NLP-9C27B0?style=for-the-badge" alt="NLP">
</p>

<p align="center">
  <a href="https://javieranthonyuracosilva.shinyapps.io/DashboardAnalisisCompromisoMolinero/">
    <img src="https://img.shields.io/badge/🚀_VER_DASHBOARD_EN_VIVO-00C851?style=for-the-badge&logoColor=white" alt="Dashboard">
  </a>
</p>

---

## 🌐 Demo en Vivo

### 👉 [Ver Dashboard Interactivo](https://javieranthonyuracosilva.shinyapps.io/DashboardAnalisisCompromisoMolinero/)

---

## 📋 Descripción

**Dashboard interactivo** de Minería de Texto y Análisis de Sentimientos aplicado al Plan de Gobierno "Compromiso Molinero" (Lista 2), propuesta presentada para las elecciones rectorales 2026-2030 de la **Universidad Nacional Agraria La Molina (UNALM)**.

Este proyecto fue desarrollado como **Examen Final** del curso **Técnicas de Exploración de Datos**, donde se implementó un dashboard desplegado en **ShinyApps.io** para visualizar de forma interactiva los resultados del análisis.

## 🎯 Características del Dashboard

- 📈 **Análisis de Frecuencias**: Visualización de palabras más frecuentes
- 💭 **Análisis de Sentimientos**: Distribución emocional del documento
- 🔗 **Bigramas**: Pares de palabras más frecuentes
- 🌐 **Redes de Palabras**: Visualización de correlaciones
- 📊 **Gráficos Interactivos**: Filtros y visualizaciones dinámicas
- 👤 **Biografía del Candidato**: Información contextual

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| **R** | Lenguaje de programación |
| **Shiny** | Framework para dashboard interactivo |
| **flexdashboard** | Estructura del dashboard |
| **tidytext** | Análisis de texto |
| **ggplot2** | Visualizaciones |
| **plotly** | Gráficos interactivos |
| **ShinyApps.io** | Despliegue en la nube |

## 📁 Estructura del Proyecto

```
├── 📄 DashboardAnalisisCompromisoMolinero.Rmd    # Dashboard principal
├── 📄 DashboardAnalisisCompromisoMolinero.html   # Versión HTML compilada
├── 📄 DashboardAnalisisCompromisoMolinero.dcf    # Configuración de despliegue
├── 📊 COMPROMISO_MOLINERO.pdf                    # Documento analizado
├── 📊 CustomStopWords.xlsx                       # Stopwords personalizadas
├── 📊 sentimientos_2.txt                         # Diccionario de sentimientos
├── 📁 rsconnect/                                 # Configuración ShinyApps
└── 📄 shiny.txt                                  # URL del dashboard
```

## 📄 Documento Analizado

**Plan de Gobierno "Compromiso Molinero"** - Lista 2
- **Candidato a Rector**: Sady García Bendezú
- **Candidato a Vicerrectorado Académico**: Rino Sotomayor Ruíz
- **Candidata a Vicerrectorado de Investigación**: Fanny Ludeña Urquizo
- **Periodo propuesto**: 2026-2030

### Ejes Temáticos del Plan:
1. Excelencia Académica y Formación Integral
2. Investigación, Innovación y Transferencia Tecnológica
3. Vinculación con el Entorno y Responsabilidad Social
4. Gestión Institucional Moderna, Transparente y Participativa
5. Calidad, Evaluación y Mejora Continua
6. Internacionalización, Cooperación y Posicionamiento

## 🚀 Cómo Ejecutar Localmente

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/JavierAnthonyUS/Dashboard-TextMining-CompromisoMolinero.git
   ```

2. **Abrir en RStudio**

3. **Instalar dependencias**
   ```r
   install.packages(c("shiny", "flexdashboard", "tidyverse", "tidytext", 
                      "plotly", "wordcloud2", "DT", "pdftools"))
   ```

4. **Ejecutar el dashboard**
   ```r
   rmarkdown::run("DashboardAnalisisCompromisoMolinero.Rmd")
   ```

## 👤 Autor

**Javier Anthony Uraco Silva**  
Estudiante de Estadística e Informática  
Universidad Nacional Agraria La Molina (UNALM)

[![GitHub](https://img.shields.io/badge/GitHub-JavierAnthonyUS-black?style=flat-square&logo=github)](https://github.com/JavierAnthonyUS)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Javier_Anthony-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/javier-anthony-uraco-silva-477334291)

## 🏫 Información Académica

- **Universidad**: Universidad Nacional Agraria La Molina (UNALM)
- **Departamento**: Estadística e Informática
- **Curso**: Técnicas de Exploración de Datos
- **Tipo**: Examen Final
- **Docente**: Jesús Salinas

## 📜 Licencia

Este proyecto es de uso académico. Los datos analizados son de dominio público (propuesta electoral).

---

<p align="center">
  <a href="https://javieranthonyuracosilva.shinyapps.io/DashboardAnalisisCompromisoMolinero/">
    <img src="https://img.shields.io/badge/🔗_ACCEDER_AL_DASHBOARD-007bff?style=for-the-badge" alt="Dashboard Link">
  </a>
</p>

<p align="center">
  <em>Universidad Nacional Agraria La Molina - 2025</em>
</p>
