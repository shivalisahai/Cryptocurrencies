# Cryptocurrencies
Unsupervised Machine Learning and Cryptocurrencies

### Overview

This analysis studies cryptocurrencies trading on the makert and groups them in to a classification system to create a new cryptocurrency investment portfolio. The available data is processed to fit machine learning models. Since there is no known output, an unsupervised machine learning model is used. Clustering algorithm is used to group the cryptocurrencies and findings are shared using data visualization.


### Tools Used

  - Python 3.7 with Pandas
  - Scikit-learn, Plotly, hvPlot libraries
  - Jupyter Notebook

### Results

#### Deliverable-1: 

  - DataFrame cleaned to remove
    - Cryptocurrencies not being traded
    - IsTrading Column dropped
    - Rows with null value removed
    - Rows with coins not being mined removed
    - CoinName column dropped

  <img width="324" alt="CoinName_Dropped" src="https://user-images.githubusercontent.com/104603128/190925691-1d8c2a3f-3df1-4417-9396-bc7ef8b07646.png">


  - New Dataframe with CoinName and crypto_df index
  
  <img width="118" alt="CoinName_DF" src="https://user-images.githubusercontent.com/104603128/190925737-35827cba-4e86-4b26-b4ef-fc94532b2026.png">

  - New DataFrame with text features and standardized with StandardScaler

  <img width="380" alt="Scaled_Data" src="https://user-images.githubusercontent.com/104603128/190926061-c7fa0f42-85b1-4eed-adc0-bbdf105784e9.png">
  
  
#### Deliverable-2:

  - DataFrame with 3 Principal Components and index
  
  <img width="197" alt="PrincipalComponents" src="https://user-images.githubusercontent.com/104603128/190926165-da6fb3fb-5f51-415d-ac6c-c7b9d3002a70.png">


#### Deliverable-3:

  - Elbow curve for best value of K
  
  ![bokeh_plot](https://user-images.githubusercontent.com/104603128/190926191-c46301ca-ccff-4164-8a94-ca1c3f505746.png)


  - New DataFrame
  
  <img width="602" alt="Clustered_DF" src="https://user-images.githubusercontent.com/104603128/190926229-32983ba2-c4a2-4418-94b2-6a29b5875180.png">


#### Deliverable-4:

  - Clusters plotted in a 3D Scatter Plot

  ![3D_Scatter](https://user-images.githubusercontent.com/104603128/190926278-80f58a17-a3da-435e-8855-5c0b84204868.png)

  - Table with tradable cryptocurrencies

  <img width="532" alt="hvPlot_Table" src="https://user-images.githubusercontent.com/104603128/190926297-5e547cd8-dc82-4faa-8031-2c6fb9c3a088.png">
  
  
  - Total number of tradable currencies

  <img width="253" alt="Tradeable_Currencies" src="https://user-images.githubusercontent.com/104603128/190926307-ea9119ec-1fac-439d-8e84-1f23a0a625f4.png">
  
  
  - DataFrame with scaled data

  <img width="327" alt="DF4" src="https://user-images.githubusercontent.com/104603128/190926341-3b25f0a2-6c37-4d09-8477-44160f085769.png">
  
  
  - Scatter plot - TotalCoinsMined vs TotalCoinSupply
  
  ![bokeh_plot (1)](https://user-images.githubusercontent.com/104603128/190926370-a365273a-7d7b-45e6-8159-0f6d8836bc45.png)

  

  

  

  
  
  
    

