# Brazil Container Troughput

## This project was presented at XXIX COPINAVAL (Pan-american Congress of NAval Architecture, Transport and Logistics, and Port Engineering)

Based on public avalible data on https://web3.antaq.gov.br/ea/sense/Relatorio.html#pt

How is Brazil doing in terms of maritime transportation?

It is possible to predict the total TEUs for the next year?

How different models behave and predict?

![container](https://thenational-the-national-prod.cdn.arcpublishing.com/resizer/v2/DMKCUFXHCVFUVLOANCJUQL7OPQ.png?smart=true&auth=7e9fa1ff7365344a4f47b4ac6643d9d8c64c92127065010ffccde6d632faaaf3&width=400&height=292)

# Abstract

Brazil's container volume has shown steady growth, reaching a 20% year-over-year increase in 2024. This trend, along with planned investments in the port sector, highlights the need for accurate forecasting to support strategic planning and operational efficiency. This study evaluates forecasting models for Brazil's container throughput using public data from ANTAQ’s Waterway Sta-tistical Panel. Two main approaches are compared: the Seasonal Autoregressive Integrated Moving Average (SARIMA) and the Long Short-Term Memory (LSTM) neural network. The impact of lag selection and cyclical encoding in LSTM is also explored through feature engineering. Python is used for model development, with pandas, numpy, statsmodels, and tensorflow libraries. Re-sults show that LSTM outperforms SARIMA in forecasting, achieving an aver-age combined training and test MAPE of 5.76% and RMSE of 61.54 thousand TEU, further improved to 5.15% and 60.45 thousand TEU with cyclical encod-ing.

**keywords**: Container Throughput; Forecasting; Time Series; Brazil; ARIMA; LSTM


# References
1.
Santos Brasil 4T24 | RELEASE DE RESULTADOS
2.
PSA Annual & Sustainability Report 2024. In: Annual & Sustainability Report 2024. https://annualreport.globalpsa.com/group-financial-highlights/. Accessed 23 Apr 2025
3.
Wilson Sons (25AD) Wilson Sons divulgação de resultados do 4T24. https://ri.wilsonsons.com.br/publicacoes/resultados-trimestrais/. Accessed 23 Apr 2025
4.
Cabral AMR, Ramos FS (2018) EFFICIENCY CONTAINER PORTS IN BRAZIL: A DEA AND FDH APPROACH. CEREM 2:43. https://doi.org/10.29015/cerem.579
5.
ANTAQ (2025) Recorde nos portos: setor aquaviário movimenta mais de 1,32 bi de tone-ladas em 2024. In: Agência Nacional de Transportes Aquaviários (ANTAQ). https://www.gov.br/antaq/pt-br/noticias/2025/recorde-nos-portos-setor-aquaviario-movimenta-mais-de-1-32-bi-de-toneladas-em-2024. Accessed 20 Mar 2025
6.
DP World and Maersk Sign Long-Term Agreement to Expand Maritime Services in Bra-zil. In: DP World and Maersk Sign Long-Term Agreement to Expand Maritime Services in Brazil. https://www.dpworld.com/news/releases/dp-world-and-maersk-sign-long-term-agreement-to-expand-maritime-services-in-brazil/. Accessed 24 Mar 2025
7.
(2025) Terminal de Contêineres do Porto de Imbituba recebe investimentos de R$ 75 mi-lhões da Santos Brasil – Porto de Imbituba. In: Porto de Imbituba. https://portodeimbituba.com.br/terminal-de-conteineres-do-porto-de-imbituba-recebe-investimentos-de-r-75-milhoes-da-santos-brasil/. Accessed 23 Mar 2025
8.
(2024) Porto Central Construction Begins in Brazil’s Espírito Santo: BRL 16 Billion In-vestment. In: DatamarNews. https://www.datamarnews.com/noticias/porto-central-construction-begins-in-brazils-espirito-santo-brl-16-billion-investment/. Accessed 23 Mar 2025
9.
(2025) Portos assinam contrato histórico para dragagem do canal de acesso da Baía da Ba-bitonga. In: Porto de São Francisco do Sul. https://portosaofrancisco.com.br/saiba-mais/id/339. Accessed 23 Mar 2025
10.
Nosso Terminal - APM Terminals. https://www.apmterminals.com/pt/suape/about/our-terminal. Accessed 24 Mar 2025
11.
ANTAQ AN de TA (2025) Painel Estatístico Aquaviário. https://web3.antaq.gov.br/ea/sense/Relatorio.html#en. Accessed 2 Mar 2025
12.
Li Y, Li T, Zuo Y, Chen CLP, Shan Q, Xiao Y, Fan X (2019) A Review of Research on Port Throughput Forecasting. In: 2019 IEEE International Conference on Smart Internet of Things (SmartIoT). pp 449–453
13.
Liu S, Huang L (2025) Application of machine learning in port throughput prediction. In: Fourth International Conference on Computer Vision, Application, and Algorithm (CVAA 2024). SPIE, pp 691–696
14.
Fiskin CS, Cerit AG (2021) Which Forecasting Models Are Employed in The Shipping Industry? Identifying Key Themes and Future Directions Through an Integrative Review. International Journal of Maritime Engineering 163:. https://doi.org/10.5750/ijme.v163iA4.1184
15.
Rashed Y, Meersman H (2013) A Univariate Analysis: Short-term Forecasts of Container Throughput in the Port of Antwerp
16.
García TR, Cancelas NG, Soler-Flores F (2014) The Artificial Neural Networks to Obtain Port Planning Parameters. Procedia - Social and Behavioral Sciences 162:168–177. https://doi.org/10.1016/j.sbspro.2014.12.197
17
17.
Wang M, Guo X, She Y, Zhou Y, Liang M, Chen ZS (2024) Advancements in Deep Learning Techniques for Time Series Forecasting in Maritime Applications: A Compre-hensive Review. Information 15:507. https://doi.org/10.3390/info15080507
18.
Gosasang V, Chandraprakaikul, W, Kiattisin S (2010) An Application of Neural Networks for Forecasting Container Throughput at Bangkok Port. In: International Conference of Wireless Networks (ICWN’10) ; (London, U.K.) : 2010.06.30-07.02 (ed) Proceedings of the World Congress on Engineering 2010. IAENG, Hong Kong
19.
Rashed Y, Meersman H, Van de Voorde E, Vanelslander T (2017) Short-term forecast of container throughout: An ARIMA-intervention model for the port of Antwerp. Marit Econ Logist 19:749–764. https://doi.org/10.1057/mel.2016.8
20.
Nakashima M, Shibasaki R (2024) Can AIS data improve the short-term forecast of week-ly dry bulk cargo port throughput? - a machine-learning approach. Maritime Policy & Management 51:1788–1804. https://doi.org/10.1080/03088839.2023.2212264
21.
Gao Y, Chang D, Fang T, Fan Y (2019) The Daily Container Volumes Prediction of Stor-age Yard in Port with Long Short-Term Memory Recurrent Neural Network. Journal of Advanced Transportation 2019:5764602. https://doi.org/10.1155/2019/5764602
22.
Lee E, Kim D, Bae H (2021) Container Volume Prediction Using Time-Series Decomposi-tion with a Long Short-Term Memory Models. Applied Sciences 11:8995. https://doi.org/10.3390/app11198995
23.
Li Y, Li Z (2024) Research on Cargo Forecasting Based on ARIMA Time Series Forecast-ing and LSTM Models. Highlights in Business, Economics and Management 36:76–84. https://doi.org/10.54097/a4kxgv35
24.
Shankar S, Ilavarasan PV, Punia S, Singh SP (2019) Forecasting container throughput with long short-term memory networks. IMDS 120:425–441. https://doi.org/10.1108/IMDS-07-2019-0370
25.
Box GEP, Jenkins GM, Reinsel GC, Ljung GM (2015) Time Series Analysis: Forecasting and Control
26.
Nielsen A (2020) Practical Time Series Analysis. O’Reilly Media, Inc.
27.
Hochreiter S, Schmidhuber J (1997) Long Short-Term Memory. Neural Computation 9:1735–1780. https://doi.org/10.1162/neco.1997.9.8.1735
28.
Bansal A, Balaji K, Lalani Z (2025) Temporal Encoding Strategies for Energy Time Series Prediction
29.
Bin F, He J (2023) A short-term photovoltaic power prediction model using cyclical en-coding and STL decomposition based on LSTM. In: 2023 3rd International Conference on Electronic Information Engineering and Computer Communication (EIECC). pp 260–266
30.
Hokmabad HN, Husev O, Belikov J (2025) Day-Ahead Solar Power Forecasting Using LightGBM and Self-Attention Based Encoder-Decoder Networks. IEEE Trans Sustain En-ergy 16:866–879. https://doi.org/10.1109/TSTE.2024.3486907


