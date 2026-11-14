## Nombre del proyecto
Encuesta local o global
## Descripción                                                                                                                
Cada compra es una decisión económica con impacto ambiental: comprar en el mercado o la tienda del barrio
mantiene el dinero en la comunidad y reduce el transporte, mientras que comprar en cadenas internacionales
o apps extranjeras suele ser más barato pero aleja la producción y su impacto. En esta práctica se construyó
una encuesta anónima en una página web. Make guarda cada respuesta en Google Sheets y, con un botón,
una inteligencia artificial genera un reporte con porcentajes y conclusiones que luego se verifica contando las
filas de la hoja.                                      
## Objetivos de aprendizaje
Al terminar, el alumno es capaz de: (1) distinguir economía local y global con ejemplos de Mazatlán; (2)
explicar qué es el PIB y cómo aportan distinto una compra local y una en plataforma extranjera; (3) construir
un flujo página web - webhook - Router - Google Sheets - IA en Make; y (4) verificar con conteos propios los
porcentajes que entrega una IA.
## Resultados
[PDF](https://github.com/nnblzaa/Desarrollom-Tareas-/blob/main/Biodiversidad/Resultados/Biodiversidad_Nicolas_Niebla.pdf)

## Material y herramientas utilizadas
IA generativa
Make > Webhooks > Custom webhook
Generar la página index.html con el prompt de la práctica.
Recibe las respuestas de la encuesta y la orden de generar reporte (campo
accion).
Make > Router y filtros
Separa la ruta 1 (accion = respuesta) de la ruta 2 (accion = reporte).
Página 1
Instituto Tecnológico de Mazatlán - Desarrollo Sustentable - Unidad 4
Herramienta
Google Sheets (Add a Row / Search
Rows)
Make > Tools > Text aggregator
Para qué se usó
Guarda cada respuesta en la hoja Encuesta_Equipo#, pestaña Respuestas, y
las lee para el reporte.
Junta todas las filas en un solo texto para que la IA se ejecute una sola vez.
Make AI Agent + Make's AI Provider
Make > Webhook Response
GitHub Pages
Aprendizaje obtenido
Calcula porcentajes y redacta análisis y conclusiones.
Devuelve a la página el mensaje de confirmación o el reporte.
Publicación de la página para aplicar la encuesta desde el celular
## Imagen
<img width="5712" height="4284" alt="image" src="https://github.com/user-attachments/assets/1aeab424-3e16-417d-a555-cd35cfda0484" />
<img width="1170" height="791" alt="image" src="https://github.com/user-attachments/assets/b5e5106a-ca54-4a39-9730-8d2da5de9e06" />

## Video
[Video](https://youtube.com/shorts/QauQs2S7ddI?si=g9ITLb_4faRAbpVY)

## Codigo
[main.txt](./codigo/main.txt)



