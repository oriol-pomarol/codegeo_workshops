# ❄️ ESM-SnowMIP — Snow Forecasting Dataset

This folder contains the in-situ subset of the ESM-SnowMIP collection: meteorological (`meteo`) and snow water equivalent (`swe`) observations prepared for the workshop.

## 📚 Sources

- Original dataset (ESM-SnowMIP): [https://doi.org/10.1594/PANGAEA.897575](https://doi.org/10.1594/PANGAEA.897575)
- Descriptor paper (supplement): Menard, Cecile; Essery, Richard; et al. (2019). Meteorological and evaluation datasets for snow modelling at 10 reference sites: description of in situ and bias-corrected reanalysis data. Earth System Science Data, 11(2), 865-880. [https://doi.org/10.5194/essd-11-865-2019](https://doi.org/10.5194/essd-11-865-2019)

If you use these prepared data, please cite the original ESM-SnowMIP dataset and the descriptor paper (examples below).

> Menard, Cecile; Essery, Richard (2019): ESM-SnowMIP meteorological and evaluation datasets at ten reference sites (in situ and bias corrected reanalysis data) [dataset]. PANGAEA, https://doi.org/10.1594/PANGAEA.897575
>
> Menard, Cecile; Essery, Richard; Barr, Alan; Bartlett, Paul; Derry, Jeff; Dumont, Marie; Fierz, Charles; Kim, Hyungjun; Kontu, Anna; Lejeune, Yves; Marks, Danny; Niwano, Masashi; Raleigh, Mark; Wang, Libo; Wever, Nander (2019): Meteorological and evaluation datasets for snow modelling at 10 reference sites: description of in situ and bias-corrected reanalysis data. Earth System Science Data, 11(2), 865-880. https://doi.org/10.5194/essd-11-865-2019

## 📝 License

This dataset is licensed under the [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license.  
You are free to share and adapt the data, provided you give appropriate credit to the original authors.

## 🛠️ Modifications

- **Daily aggregation:** All in-situ meteorological variables were aggregated to daily frequency by taking the average of the hourly values from 12:00 LT on the day before to 11:00 LT on the reported date. The snow water equivalent values were sampled at 12:00 LT.
- **Subsetted:** Besides the observed SWE at each station (obs_swe), only a subset of in-situ meteorological variables are reported, particularly the temperature (Tair), snowfall (Snowf), rainfall (Rainf) long-wave and short-wave radiations (LWdown and SWdown), humidity (Qair) and wind speed (Wind). Other variables, including model/reanalysis data, were excluded from this dataset.


## 📝 Notes

- This folder provides the processed daily in-situ subset used in the workshop and is not the full ESM-SnowMIP distribution. Consult the DOI above for the complete dataset and original metadata.

