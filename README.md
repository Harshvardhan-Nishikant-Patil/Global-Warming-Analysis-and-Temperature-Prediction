# weather-prediction-using-machine-learning
Climate change is a controversial topic of debate, where many of us do not believe in anthropogenic climate change. Because its consequences are predicted to be dire, such as mass ocean extinction and frequent extreme weather events, it is important to learn what causes the warming in order to better combat it. This project’s main objective is to predict weather and analyze various atmospheric gases that are causing harm to global warming up until now. In this study, the first challenge dwells on how to construct reliable statistical models based on climate data of few hundred years and accurately capture the relationship between temperature and potential factors such as concentrations of carbon dioxide (CO2), carbon monoxide (CO), nitrogen dioxide (NO2), sulfur dioxide (SO2), ozone (O3), nitrous oxide (N2O), hydrofluorocarbon (HFC) and methane (CH4). We compared the performance of several mainstream machine learning algorithms on our data, which includes linear regression, random forest, and Autoregressive Integrated Moving Average (ARIMA) model to build the state-of-theart model to verify the warming of the earth and identifying factors contributing to global warming. We found that random forest outperforms other algorithms to create accurate climate models which use features including various different versions of temperature to precisely predict global temperature. But the problem that arises in the current random forest model is that it can’t forecast temperature in future so we’ve used the Autoregressive Integrated Moving Average (ARIMA) model to fill that gap. It was found that CO2 is the largest contributor to temperature change, followed by CH4, HFC, SO2 and then by CO. They all had some sorts of impact, though, meaning their release into the atmosphere should all be controlled to help restrain temperature increase, and help prevent climate change’s potential ramifications.
