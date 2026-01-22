# ❄️ ESM-SnowMIP — Snow Forecasting Dataset

This folder contains the in-situ subset of the ESM-SnowMIP collection: meteorological (`meteo`) and snow water equivalent (`swe`) observations prepared for the workshop.

## 📚 Sources

- Original dataset (ESM-SnowMIP): [https://doi.org/10.1594/PANGAEA.897575](https://doi.org/10.1594/PANGAEA.897575)
- Descriptor paper (supplement): Menard, Cecile; Essery, Richard; et al. (2019). Meteorological and evaluation datasets for snow modelling at 10 reference sites: description of in situ and bias-corrected reanalysis data. Earth System Science Data, 11(2), 865-880. [https://doi.org/10.5194/essd-11-865-2019](https://doi.org/10.5194/essd-11-865-2019)

If you use these prepared data, please cite the original ESM-SnowMIP dataset and the descriptor paper (examples below).

> Menard, Cecile; Essery, Richard (2019): ESM-SnowMIP meteorological and evaluation datasets at ten reference sites (in situ and bias corrected reanalysis data) [dataset]. PANGAEA, https://doi.org/10.1594/PANGAEA.897575
>
> Menard, Cecile; Essery, Richard; Barr, Alan; Bartlett, Paul; Derry, Jeff; Dumont, Marie; Fierz, Charles; Kim, Hyungjun; Kontu, Anna; Lejeune, Yves; Marks, Danny; Niwano, Masashi; Raleigh, Mark; Wang, Libo; Wever, Nander (2019): Meteorological and evaluation datasets for snow modelling at 10 reference sites: description of in situ and bias-corrected reanalysis data. Earth System Science Data, 11(2), 865-880. https://doi.org/10.5194/essd-11-865-2019

## 🛠️ Modifications

- **Daily aggregation:** All in-situ `meteo` and `swe` variables were aggregated to daily frequency (date-based daily summaries). The aggregation methods include taking the average of the hourly values (avg), the average only over the daytime hours (dav), the maximum hourly value (max) and the integration of the positive values over time (int).
- **Subsetted:** Only in-situ `meteo` and `swe` variables are retained; other variables (including non-insitu and model/reanalysis fields) were removed for this packaged subset.


## 📝 Notes

- This folder provides the processed daily in-situ subset used in the workshop and is not the full ESM-SnowMIP distribution. Consult the DOI above for the complete dataset and original metadata.

