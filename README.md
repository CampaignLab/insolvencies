# Individual Insolvencies vs Local Election 2018

## Aims
* Try to link insolvencies with the 2018 Local General election results.
* Get experience with this kind of correlation task

## Data Used
* Insolvencies data: https://www.gov.uk/government/statistics/individual-insolvencies-by-location-age-and-gender-england-and-wales-2017

* LE2018 data: https://docs.google.com/spreadsheets/u/1/d/14GKPoj-E1CN0ZmiUd5gQWUi5zvGWbDoNoGT82RqKEno/edit?ts=5b07edf9#gid=0

## Results
Sanity check of the data:


![alt text](images/national_insolvencies_rate.png)

Do some correlations for each party with the insolvency rate:



![alt text](images/all_parties_insolvencies.png)

```
              r         r^2
UKIP PCT +/- -0.585808  0.343171
LDem PCT +/- -0.083332  0.006944
Lab PCT +/-   0.131011  0.017164
Grn PCT +/-   0.351160  0.123313
Con PCT +/-   0.585564  0.342885
```

The collapse of UKIP is very evident in the data. This is an issue as places with high insolvency rates, often used to have a high UKIP vote share. Hence UKIP PCT +/- shows a big correlation with insolvency.

As a first step in removing the UKIP influence, we tried to look at swing:

![alt text](images/UKIP2Con.png)
