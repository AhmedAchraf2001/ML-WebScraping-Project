# Scrapping data from the transferMarket website about Summer Football 2022
Data Source: https://www.transfermarkt.com/
    
</br>
</br>

## Algorithm
**Description :** I scraped many information about players 

## Data description
|Feature Name    |Type                           |Description                    |
|----------------|-------------------------------|-------------------------------|
|age             |Numerical                               |Player age at this season|
|position        |Categorical                             |player position could be `goolkeeper`, `defence`, `midfield` or `attack`|
|country         |Categorical                             |Player country        |
|apperance       |Numerical                               |No. Played matches    |
|goals           |Numerical                               |No. Scored goals      |
|assists         |Numerical                               |No. Assists           |
|yellow_card     |Numerical                               |No. Yellow card       |
|2nd_ycard       |Numerical                               |No. 2nd yellow card   |
|red_card        |Numerical                               |No. Red card          |
|min             |Numerical                               |No. Played minutes    |
|National_Team   |Binary                                  |Refer to has play with national team before or not `1` play and `0` doesn't|
|apperance_NT    |Numerical                               |No. Played matches with national team    |
|goals_NT        |Numerical                               |No. Scored goals with national team      |
|assists_NT      |Numerical                               |No. Assists with national team            |
|yellow_card_NT  |Numerical                               |No. Yellow card with national team        |
|2nd_ycard_NT    |Numerical                               |No. 2nd yellow card with national team    |
|red_card_NT	 |Numerical                               |No. Red card with national team           |
|min_NT	         |Numerical                               |No. Played minutes with national team     |	
|cost	         |Numerical                               |Transfer cost         |




</br>
</br>





	
	

## libraries used 
Regex used to extract data from the website using some libraries:
1. **selenium**
2. **beautifulsoup**
3. **requests**





