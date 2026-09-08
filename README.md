# Muestreo y distribuciones muestrales

Sitio de la sesión · Doctorado en Ciencias Económicas y Administrativas, Universidad de Sonora ·
materia de Procesamiento y análisis de datos.
Base: Anderson, Sweeney y Williams, *Estadística para administración y economía* (10a. ed.), capítulo 7.
Software de los ejercicios: IBM SPSS.

Presentación interactiva para la sesión de **Luis Antonio Alonso Reyna**.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio **público** en GitHub. Un nombre corto ayuda porque será parte del link:
   por ejemplo `muestreo-distribuciones`.
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (los archivos, no la carpeta
   que los contiene). Puedes arrastrarlos a la interfaz web de GitHub con *Add file → Upload files*.
3. En el repositorio ve a **Settings → Pages**.
4. En *Source* elige **Deploy from a branch**; en *Branch* elige **main** y la carpeta **/ (root)**.
   Guarda.
5. Espera uno o dos minutos. GitHub te mostrará el link, con la forma
   `https://TU-USUARIO.github.io/muestreo-distribuciones/`
6. Comparte ese link con el grupo **antes** de la sesión.

## Estructura

```
index.html                          La presentación: 37 láminas en un solo archivo, funciona sin internet
datos/Escuelas.sav                  600 escuelas en 20 distritos (Puntaje, Ausentismo, Nivel, Gestion, ...)
datos/Hogares.sav                   1 000 hogares en 25 colonias (Ingreso, Internet, Vivienda, ...)
docs/Presentacion_muestreo.pdf      Respaldo en PDF de las 37 láminas
docs/Guia_SPSS.pdf                  Guía paso a paso de los ejercicios en SPSS (8 páginas)
```

## Cómo descargan las bases tus compañeros

En la lámina 30 («Tres esquemas de muestreo») y en la 36 («Materiales») hay un botón por cada
base. Al hacer clic, el archivo `.sav` se descarga directo a la carpeta de descargas y abre en SPSS
sin conversión. Esto funciona porque GitHub Pages sirve los archivos igual que cualquier servidor
web y los enlaces llevan el atributo `download`.

Tres cosas que conviene cuidar:

1. **Sube la carpeta `datos/` completa.** Si solo subes `index.html`, los botones darán error 404.
2. **Comparte el link de Pages, no el del repositorio.** El de Pages tiene la forma
   `https://TU-USUARIO.github.io/repo/`. Si compartes `https://github.com/TU-USUARIO/repo`,
   tus compañeros verán el código fuente en vez de la presentación.
3. **Respeta mayúsculas y minúsculas.** GitHub Pages distingue entre `Escuelas.sav` y
   `escuelas.sav`; tu computadora no. Si renombras un archivo, actualiza también el enlace.

Si más adelante se agrega el artículo científico (lineamiento 3), la lámina 35 («Referencias») y
la 36 son el lugar natural para el enlace.

## Cómo usar la presentación

| Acción | Cómo |
|---|---|
| Avanzar y retroceder | Flechas `→` `←`, barra espaciadora, o deslizar en móvil |
| Abrir el índice de bloques | Tecla `M` o botón **Bloques** |
| Saltar a un bloque | Teclas `1` a `6` |
| Cambiar entre tema claro y oscuro | Tecla `T` |
| Pantalla completa | Tecla `F` |
| Exportar a PDF | Botón **PDF** de la barra inferior |

Láminas interactivas (todo se calcula en el navegador, sin conexión):

- **5** Calculadora del número de muestras posibles, N!/(n!(N−n)!).
- **6** Selección paso a paso con números aleatorios (ejercicio 3 del capítulo).
- **11** Simulación de 500 muestras con el tamaño de muestra que se elija.
- **16** Teorema del límite central con tres poblaciones y n = 1, 2, 5, 30.
- **17** Probabilidad de que x̄ quede a ±$500 de μ, con n = 30 y n = 100.
- **27** Muestreo sistemático con N, n e inicio aleatorio.
- **31** Calculadora del tamaño de la muestra (misma fórmula que SurveyMonkey).

Pasa el cursor sobre barras, curvas sombreadas y puntos para ver el dato exacto.

## Si falla el internet en el aula

`index.html` es autocontenido: no carga nada de la red. Descárgalo antes y ábrelo desde tu
computadora. Como segundo respaldo está `docs/Presentacion_muestreo.pdf`.

## Fuentes

- Anderson, D. R., Sweeney, D. J., & Williams, T. A. (2008). *Estadística para administración y
  economía* (10a. ed.). Cengage Learning. ISBN 978-607-481-319-7. Capítulo 7.
- Calculadora del tamaño de la muestra de SurveyMonkey:
  <https://es.surveymonkey.com/mp/sample-size-calculator/>
