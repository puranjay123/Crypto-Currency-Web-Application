# Crypto-Currency-Web-Application
# Streamlit-Cryptocurrencies-Dashboard
About Streamlit Dashboard returning technical indicators for a given crypto (using coin market cap API).

##### Running: `streamlit run crypto.py`
![](https://github.com/poltys/Streamlit-Cryptocurrencies-Dashboard/blob/master/extra/streamlit-crypto-2020-08-31-17-08-89.gif)

#### To Do
- [X] Add option to download list with USD or EUR
  - [X] Defined eur-usd ticker conversion():
    - however some ticker do not provide result
    - and first summary table is not updating
    - alternative source to be identified
- [X] Add issues here([https://github.com/poltys/Streamlit-Dashboard-Ticker_Technical_Analysis](https://github.com/puranjay123/Crypto-Currency-Web-Application/issues))
  - [X] Buying Price
  - [ ] Add shapes(i.e. means)
  - [X] Create button to upload portfolio details and define global buying price / weighted av.
  - [ ] Portfolio Size
  - [X] T Price
  - [ ] Add Dynamic Indicators
    - [X] Momentum Indicators
    - [X] Volatility Indicators
  - [ ] Define df.style specific rules based on each technical indicators
  - [X] df.style apply to axis=1
- [ ] Add means
- [ ] Dynamically generate annotations
- [X] Add technical indicators
- [X] Add already trained ML predictive model - google colab
  - [ ] Allow user to use the model
- [ ] Deploy on streamlit cloud
