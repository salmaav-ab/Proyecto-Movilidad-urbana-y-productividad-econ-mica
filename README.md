# Proyecto: Movilidad urbana y productividad económica

- Contexto: El American Development Bank busca identificar en qué ciudades invertir en infraestructura de transporte para elevar la productividad y el bienestar de su población. Mi equipo entregará un reporte sobre la relación entre movilidad urbana (congestión, tiempos de viaje y retrasos) y productividad económica (PIB per cápita y desempleo) en las principales ciudades del mundo.
  
- Dataset utilizado: Dos fuentes reales de datos:

   > TomTom Traffic Index (tomtom_traffic.csv) — niveles de congestión, retrasos, longitud de embotellamientos y tiempos de viaje por ciudad.
   > OECD Cities (oecd_city_economy.csv) — indicadores económicos anuales: PIB per cápita, desempleo, contaminación (PM2.5) y población por ciudad.

-Herramientas:
   > Python (pandas, numpy, seaborn, matplotlib) dentro de Jupyter Notebook.

-Insights principales: 
   > Las ciudades con mayor población y PIB alto muestran los tiempos de viaje más ineficientes, lo que indica que la congestión merma directamente la actividad
     económica. Se observa una relación clara: a mayor PIB per cápita, mayor traffic_index_live y mayor jams_delay, es decir, la productividad trae consigo más
     saturación y, por tanto, mayor pérdida de tiempo.
     Sin embargo, el tráfico no depende únicamente del PIB. Hay ciudades con alto PIB y poca o nula congestión, y otras con congestión elevada y bajo PIB, lo que
     sugiere que la eficiencia urbana (infraestructura y sistema de transporte) es también un factor determinante.

-Conclusión y recomendaciones:
   > Bogotá es un caso representativo: siendo una ciudad altamente turística, la ausencia de un sistema de transporte subterráneo genera cuellos de botella que se      traducen en una pérdida masiva de horas productivas. A esto se suma la saturación del espacio público por comercio informal en zonas turísticas, lo que puede      generar una experiencia abrumadora para el visitante y, en lugar de fomentar el consumo, desincentivarlo.
     La inversión en infraestructura de transporte en ciudades como Bogotá no solo mejoraría la movilidad, sino que potenciaría también la dinámica comercial y la      experiencia urbana en su conjunto.

