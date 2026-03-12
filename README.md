📊 ¿Son realmente 'refugio' los activos refugio?
Análisis de comportamiento de activos en eventos de estrés geopolítico

"El mercado lleva décadas mintiendo sobre los activos refugio — los datos lo demuestran"


🎯 Descripción del proyecto
Este proyecto analiza el comportamiento de los principales activos considerados "refugio" en los días posteriores a los grandes conflictos bélicos y eventos geopolíticos de los últimos 25 años.
El objetivo es contrastar empíricamente si el mito de los valores refugio se sostiene con datos reales — y en la mayoría de los casos, la respuesta es incómoda.

📅 Eventos analizados
EventoFecha D0Descripción11-S11 sep 2001Atentados Torres Gemelas, Nueva YorkInvasión EEUU a Iraq20 mar 2003Inicio Operación Libertad Iraq11-M Madrid11 mar 2004Atentados estación de AtochaRusia-Ucrania24 feb 2022Invasión rusa a gran escalaHamas 7-O7 oct 2023Ataque Hamas a Israel

💰 Activos analizados
ActivoTicker Yahoo FinanceTipoOroGC=FFuturos — refugio clásicoBono EEUU 10Y^TNXYield — huida a calidad (signo invertido)Franco SuizoUSDCHF=XDivisa refugio (signo invertido)Dólar (DXY)DX-Y.NYBÍndice dólar americanoPetróleo WTICL=FFuturos — activo paradójicoS&P 500^GSPCReferencia bolsa americana

📐 Metodología

Retornos: Aritméticos — (P_final - P_base) / P_base × 100
Base de referencia: Precio de cierre del día anterior al evento (D-1)
Ventanas temporales: 1 día, 1 semana (5 sesiones), 2 semanas (10 sesiones)
Fuente de datos: Yahoo Finance vía yfinance
Activos inversos: Bono 10Y y Franco Suizo tienen el signo ajustado para lectura intuitiva (verde = comportamiento refugio)


🔍 Principales hallazgos

Oro → Refugio parcial: funciona en shocks inesperados (11-S, Hamas, Rusia) pero falla cuando el mercado anticipa el conflicto (Iraq)
Dólar (DXY) → Estable: fluctuaciones muy leves en todos los eventos, no actúa como refugio claro
Bono 10Y → Contextual: funcionó en el pánico puro del 11-S pero en 2022 la inflación y la Fed rompieron su comportamiento histórico
Petróleo WTI → Inclasificable: es un termómetro de la naturaleza del conflicto, no un activo refugio
S&P 500 → Resiliente: solo cae con fuerza ante shocks genuinamente inesperados


📁 Estructura del repositorio
├── analisis_activos_refugio.ipynb   # Notebook principal (Google Colab)
├── README.md                        # Este archivo
└── output/
    ├── slide_01_hook.png
    ├── slide_02_heatmap_1_dia.png
    ├── slide_03_heatmap_1_semana.png
    ├── slide_04_heatmap_2_semanas.png
    ├── slide_05_oro.png
    ├── slide_06_petroleo.png
    ├── slide_07_conclusiones.png
    └── slide_08_pregunta_abierta.png

🚀 Cómo ejecutar

Abre el notebook en Google Colab:
Mostrar imagen
Ejecuta las celdas en orden (Paso 1 → Paso 6)
Los slides del carrusel se generarán automáticamente en el directorio de trabajo

Dependencias
pythonyfinance
pandas
numpy
matplotlib
seaborn
Todas se instalan automáticamente en la primera celda del notebook.




⚠️ Disclaimer
Este análisis tiene finalidad exclusivamente divulgativa y educativa.
No constituye asesoramiento financiero ni recomendación de inversión.
Los datos históricos no garantizan comportamientos futuros.
