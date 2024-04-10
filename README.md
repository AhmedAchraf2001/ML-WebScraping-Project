# Scrapping data from the transferMarket website about Summer Football 2022 markert transfer
Data scraped from [Market Transfer website](https://www.transfermarkt.com/) in below images show the data that has scraped for each player. 

for example Phili Foden mancity player 
- **Frist webpage has his name, age, market value and other.**
- **Second webpage has some insights about progress with team.**
- **Third webpage has some insights about progress with National team.**

</br>
</br>

<div>
	<img align="center" width="300"  src='00 Docs/image_1.png'> 
	<img align="center" width="300"  src='00 Docs/image_2.png'> 
 	<img align="center" width="300"  src='00 Docs/image_3.png'> 
  
</div>

</br>
</br>

# Dataset Descrption
### Data contains 28401 players each one has 19 feature represents below.

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

	

## libraries used 
### Regex used to extract data from the website using some libraries:
1. **selenium**
2. **beautifulsoup**
3. **requests**


</br>

## Machine learning algorithms
|Model Name     	 |Train accuracy %               |Test accuracy %       |
|------------------------|-------------------------------|----------------------|
|Simple Linear Regression|**75.07**           		 |**71.97**   		|
|XGBoost Algorithm       |**99.15**                    	 |**98.99**      	|
</br>

|Model Name     	 |Train MSE                      |Test MSE              |
|------------------------|-------------------------------|----------------------|
|Neural Network          |**2.6162e-05**                 |**2.0937e-05**        |

</br>
</br>

### Graph show losses during training and validation 
<img align="center" src='00 Docs/model_losses.png'>  
