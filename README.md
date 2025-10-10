**Project Title**: Integrated Export Pricing Framework using N-HiTS Forecasting, Econometrics and Game Theory

**Project Overview**: 
This project aims to design an integrated pricing framework by using historical data, predictive modeling, and economic concepts such as price elasticity. The sector chosen for the project is 
‘agri-business and export’ with a focus on HAFED, a Haryana based leading organization involved in processing, marketing, and export of agricultural products. Given that basmati rice is one of HAFED’s 
primary export commodities, the framework has been developed around the export pricing of basmati rice for a selected international market. However, the approach and underlying methodology are generalizable 
and can be adapted by private exporters or other agri-based enterprises. 

**Problem Statement**: The profitability of Haryana-based exporters, including HAFED, in international markets can be adversely affected by several factors, such as:
•	Competition from both international and domestic players.
•	Factors affecting cost of goods such as paddy prices, domestic taxation policies, and limited government subsidies.
•	Changes in trade policies, particularly import tariffs imposed by foreign governments.

**Project Objectives**: 
•	Develop a predictive model to estimate future auction prices (modal rates) of basmati paddy.
•	Develop a predictive model to evaluate how changes in export prices affect the market share of Indian and Haryana-based exporters in the U.S. basmati rice market.
•	Evaluate exporter’s profitability due to changes in price points and market shares.
•	Use the previous analysis to estimate an optimal price range for exporters.

**Project Details**:  
The project report, located in the main branch (file name: Integrated Pricing Framework.pdf), provides a full breakdown of the methodology and findings, including:

- Auction Rate Prediction

- Price-Demand Elasticity and Market Share Predictions

- Pay-Off Matrix Assessment

- Results

**Tools and libraries used**: Software: Python, Excel; Libraries: darts, pandas, statsmodels, nashpy; Neural Network: N-HiTS, TFT; Tradiitonal ML: Regression(OLS);
To execute the NHiTS model install following versions:
!pip install pip==23.3.1
!pip install pytorch-lightning==2.2.1
!pip install u8darts==0.27.0

**Respository Contents**: 
- 5 python notebooks: PriceNHiTS.ipynb and PriceTFT.ipynb for auction rate prediction using Neural Network Models; export_rate.ipynb for India vs Pakistan regression;Share elasticity.ipynb for state-wise regression
  Game Theory.ipynb for Nash equilibrium analysis 
- Project report (Integrated Pricing Framework.pdf) to provide detailed discription of the project and the results.
- Complete dataset in Int_Pricing_FM.xlsx: NHiTS_TFT dataset for auction rate prediction; India Pak DF for India vs Pak regression; State DF for state-wise regression; Payoff matrix for game theory analysis. 

**How to run the model**: Pre-requisites: Python environment- python 3.9+, an IDE like JupyterLab, MS Excel.
1. Download the Int_Pricing_FM.xlsx dataset file, place this file into the python working directory
2. Open python notebooks in a Python IDE, update the file paths and file/sheet names to correctly reference the respective dataset.
3. Execute the code snippets in respective notebooks to perform the required analysis

**Data Source:** Data Sources for various datasets are specified in the Project report (Integrated Pricing Framework.pdf)
