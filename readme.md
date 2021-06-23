# 100 Days Of Code
### Day 12: 06-23

**Progreso**: Buscando automatizar los reportes para la consultora que trabajo, estoy comenzando a utilizar FPDF, para imprimir los graficos y datos analizados en un reporte en pdf

![image](https://user-images.githubusercontent.com/43462439/123166654-074caa80-d44c-11eb-9d14-c40a8cb04172.png)

_

### Day 11: 06-22

**Progreso**: Utilice la libreria TextBlob para hacer traducciones ingles-español y tener todas las historias de las empresas argentinas 
![image](https://user-images.githubusercontent.com/43462439/123165456-a2448500-d44a-11eb-9da6-e75e0c890363.png)

_

### Day 10: 06-21

**Progreso**: Utilice la libreria mplfinance para graficar velas de AAPL, con medias moviles de 20/50 y volumen. Tambien los maximos y minimos historicos a 1y

![image](https://user-images.githubusercontent.com/43462439/123164952-fbf87f80-d449-11eb-82f8-cc8b088801a1.png)

_

### Day 9: 06-20

**Progreso**: Logre descargar y procesar en formato DataFrame (o tabla) indicadores fundamtentales de una cartera de activos

![image](https://user-images.githubusercontent.com/43462439/123157615-23971a00-d441-11eb-8220-bd44665d3494.png)
_

### Day 8: 06-19

**Progreso**: Con las corrleaciones calculadas el dia de ayer, logre multiplicarlo para una cartera y armar un heatmap con correlacion entre mas de dos activos
![image](https://user-images.githubusercontent.com/43462439/123156485-b931aa00-d43f-11eb-8635-e6958f5d738f.png)
_


### Day 7: 06-18 

**Progreso**: Logre calcular correlacion entre los precios diarios de cierre de dos activos (con los precios ajustados y utilizando yfinance)
![image](https://user-images.githubusercontent.com/43462439/123156739-04e45380-d440-11eb-9ee3-4f601e01f03b.png)

_

### Day 6: 06-17 

**Progreso**:Rendimiento acumulado en el mismo grafico de cualquier ticker en yfinance
![rendcumulado](https://user-images.githubusercontent.com/43462439/122509645-7f454b80-cfda-11eb-94ef-d593065119c5.png)
_

### Day 5: 06-16 

**Progreso**: Utilice la libreria request para extraer datos de bonos, los cuales no podia descargar de ningun otro lado que no sea pago. Los encontre en la pagina de rava.com

_

### Day 4: 06-15 

**Progreso**: Aprendi a imprimir datos desde Spyder a Google Sheets, conectandome con la API. Proximamente voy a probar si puedo usar los datos de pandas que use dias anteriores 

**Comentarios:** Tengo que aprender a hostear un script en la web para que corra solo sin que se me trabe toda la pc (:

Precios de cierre, apertura, maximos, minimos y volumen de MSFT impresos en google sheet lml
![image](https://user-images.githubusercontent.com/43462439/122153785-0d360080-ce3a-11eb-8ee4-bdd08ce9a28c.png)

_

### Day 3: 06-14 

**Progreso**: Analice la primera señal positiva de la informacion sobre arbitraje de CEDEARs/Acciones. Utilizando data de yfinance cree un DataFrame donde compara el precio de la accion contra el cedear, dando un precio de dolar ccl. Luego scrapea con BeautifulSoup la cotizacion desde la pagina dolarhoy.com. Finalmente los compara y analiza el gap entre ambos CCL para ver si el papel se encuentra desarbitrado. 

**Comentarios:** La data de yfinance no tiene buena fuente del volumen operado, ya que en Balanz Capital dice que hubo mas volumen operado que el de la tabla

La imagen izquierda es del dia de ayer y la derecha de hoy. Se puede ver que el precio de TSLA estaba desabitrado, con un CCL de 157.2, cuando la cotizacion estaba en 164.84 (un gap del 4.7%). Lo que paso fue que al abrir el mercado, el precio subio un 6%, desde $6390 a $6788 y corrijio el dolar CCL, ahora encontrandose con un gap del 0.4%
![image](https://user-images.githubusercontent.com/43462439/121975214-7a249a00-cd57-11eb-816c-76d68102f231.png)
_

### Day 2: 06-14 

**Progreso**: Analice la primera señal positiva de la informacion sobre arbitraje de CEDEARs/Acciones. Utilizando data de yfinance cree un DataFrame donde compara el precio de la accion contra el cedear, dando un precio de dolar ccl. Luego scrapea con BeautifulSoup la cotizacion desde la pagina dolarhoy.com. Finalmente los compara y analiza el gap entre ambos CCL para ver si el papel se encuentra desarbitrado. 

**Comentarios:** La data de yfinance no tiene buena fuente del volumen operado, ya que en Balanz Capital dice que hubo mas volumen operado que el de la tabla

La imagen izquierda es del dia de ayer y la derecha de hoy. Se puede ver que el precio de TSLA estaba desabitrado, con un CCL de 157.2, cuando la cotizacion estaba en 164.84 (un gap del 4.7%). Lo que paso fue que al abrir el mercado, el precio subio un 6%, desde $6390 a $6788 y corrijio el dolar CCL, ahora encontrandose con un gap del 0.4%
![image](https://user-images.githubusercontent.com/43462439/121975214-7a249a00-cd57-11eb-816c-76d68102f231.png)
_

### Day 1: 06-13

**Progreso**: Hoy investigue otra herramienta de data visualization: Tableau. Grafique rendimientos acumulados, diarios y evolucion YTD de toda la cartera en el monitor, usando yfinance y pandas

**Comentarios:** Me gustaria aprender a hacer la misma visualizacion de datos con matplotlib, es algo que actualmente me encuentro mejorando

**Link to work:** [Monitor en tableau](https://public.tableau.com/app/profile/franco.maciel/viz/Data_16236214946620/Monitor)
_

### Day 0: 06-12 

**Progreso**: Hace un mes comence a programas de forma frecuente en python y hoy me enfoco en este desafio de 100 dias. Hoy cree mi perfil de GitHub, y realice el segundo informe semi-automatizado para el proyecto que actualmente trabajo BDI Consultora

**Comentarios:** Quise hacer graficos con la leyenda de cada uno, y con pandas_ta, pero todavia no pude. Por el momento solo pude realizarlos con matplotlib. Lo bueno es que esta casi todo automatizado, solo falta juntarlo y ver como hacer que me lo imprima solo en PDF con el formato diseñado

**Link to work:** [Monitor CEDEARs Nº2 (11-06-21)](https://github.com/xfrancomaciel/100-days-of-code/files/6651941/Monitor.CEDEARs.N.2.11-06-21.pdf)

