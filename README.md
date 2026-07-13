Modelling the impact of macroeconomic indicators on currency depreciation in emerging markets.

This project tests a set of key macroeconomic indicators to determine if there is a relationship with currency depreciation in 14 emerging market economies, from 2000-2025.


DATA

Data was pulled directly from the World Bank database for: foreign exchange rate ('fx_rate'), debt-to-GDP ratio (%) ('debt_to_gdp'), annual inflation rate (%) ('inflation'), annual GDP growth (%) ('gdp_growth'), current account balance (% of GDP) ('current_account_balance'), and real interest rate (%) ('real_interest_rate').

In the process of cleaning the data, forward-filling was used in order to fill intermittent gaps in the data. Backward-filling was avoided in order to prevent look-ahead bias, which could impact the integrity of the dataset.

Initially, the sample included 19 countries, but data was unavailable for at least one key macroeconomic indicator in 5 of the countries in the sample (Czechia, Nigeria, Poland, Turkiye, Vietnam), so these countries had to be dropped, leaving the final sample with 14 countries. In the future, alternative sources of data collection would be considered in order to obtain this data (e.g. FRED, IMF, OECD), in order to include these dropped countries and strengthen the generalisability of the model.

