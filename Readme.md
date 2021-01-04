# Lol professional games analysis (WIKI)

# Descripción
Este repositorio corresponde al código y resultados de la práctica 2 de Tipología y Ciclo de Vida de los Datos. En esta práctica se ha realizado un análisis de datos estadístico del dataset https://zenodo.org/record/4265268#.X_NXP9hKhPZ. El objetivo de este análisis es encontrar las variables más importantes para la victoria de una partida de LeagueOfLegends, encontrar diferencias estadísticas en el dataset, generar modelos de regresión logística para predecir el ganador y estudiar la influencia de las variables en ganar una partida. 

# Desarrolladores del análisis.
Esta práctica ha sido desarrollada en solitario por Manuel Ruiz Botella. 

# Descripción de los ficheros. 
Los ficheros principales son los siguientes: 

* LOL_professional_games_analysis.pdf: Fichero pdf donde se encuentra el pdf con el código utilizado para responder a las preguntas junto con la explicación de la respuesta a las preguntas. Además, se encuentra la tabla de contribuciones. El fichero se encuentra en la base del repositorio y en la carpeta Code, puesto que este pdf se genera automáticamente en Rstudio al hacer "Knit to pdf". 
* LOL_professional_games_analysis.Rmd: Se encuentra en el directorio Code. Fichero de código en R para generar el pdf con el código y respuestas. Para producir el pdf hay que hacer "Knit to pdf". En el código se responden las diferentes preguntas y se realiza todo el análisis de los datos. Para entender que se hace en el código acudir al pdf o el propio código. 
* Lol_ProfessionalGames.csv: Dataset inicial con una gran cantidad de variables de partidas profesionales de LeagueOfLegends. Se encuentra en Data/Input.
* lol_professional_games_final.csv: Dataset final base utilizado para los análisis estadísticos. Se encuentra en Data/Output.
* lol_professional_games_separated_teams.csv: Dataset final con un equipo por instancia utilizado para predecir si un equipo gana o pierde e interpretar la influencia de las variables en la victoria. Se encuentra en Data/Output.
* lol_professional_games_bluewins.csv: Dataset final que contiene solo las partidas donde gana el equipo azul. Se encuentra en Data/Output.
* lol_professional_games_redwins.csv: Dataset final que contiene solo las partidas donde gana el equipo rojo. Se encuentra en Data/Output.
* lol_professional_games_kdaofwinnerplayers.csv: Dataset final que contiene solo el kda de los jugadores del equipo que gana y su posicion. Se encuentra en Data/Output.

<sub><sup> Disclaimer: Lol_professional_games_analysis se creó según la política "Galimatías legal" de Riot Games usando recursos que son propiedad de Riot Games.  Riot Games no respalda ni patrocina este proyecto.
