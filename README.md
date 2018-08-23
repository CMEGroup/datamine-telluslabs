# Datamine-Tellus Labs

This project outlines the potential use Tellus Lab data into forcasting and other
applications based upon specific users needs.

Information about Tellus Labs and Datamine:
[CME Datamine Tellus Labs Data](https://www.cmegroup.com/market-data/tellus-labs.html "CME Datamine Tellus Lab Data")
[Tellus Labs Information](https://telluslabs.com/ "Tellus Labs Homepage")


<!---
Insert Image of Seasonality Decom from Analysis
![alt text](http://url/to/img.png)
--->
## Run on Binder
Automatcially run this in a hosted jupyter notebook with all the dependencies.  

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CMEGroup/datamine-telluslabs/master)


## To Run This Analysis Locally

To use the examples in juptyer notebook from Anaconda Python.  The following will clone this repo, inlcuding an environment.yml file that will create the proper Anaconda environment with all the dependencies.  You then launch the juptyer lab environment.  

```
git clone https://github.com/CMEGroup/datamine-telluslabs.git
cd datamine-telluslabs
conda env create
source activate  datamine-telluslabs
juptyer notebook


```
Alternatively, you can use your own python environment but review the environment.yml file to determine the package dependencies.

## Notebook Summary

There are two primary notebooks for the analysis.  The generally summary of each is listed below.

### TellusLabs Blog - Intro
[CME Datamine Tellus Labs Data Analysis](https://github.com/CMEGroup/datamine-telluslabs/blob/master/TellusLabs-Intro.ipynb "Tellus Intro Analysis")

This analysis breaks down the Tellus Labs data into traditional annual analysis, seasonal decomposition, and does price
alignment to CME Corn Futures end of day settlements.


![Tellus Labs Seasonal Decomposition](https://github.com/CMEGroup/datamine-telluslabs/blob/master/image/TellusLabSeasonalDecomp.png)




### TellusLabs Blog - ARIMA
[TellusLabs Blog - ARIMA](https://github.com/CMEGroup/datamine-telluslabs/blob/master/TellusLabs-ARIMA.ipynb "Tellus ARIMA Analysis")


This analysis extends the Tellus Labs data into an ARIMA model for forward projection of the expected measurements.  


![Tellus Labs ARIMA Model](https://github.com/CMEGroup/datamine-telluslabs/blob/master/image/TellusLabARIMAPrediction.png)





## Data Supplied
This workbook leverages altered data in the analysis. It displays the general statistical 
properties of the orignial data set.

## Author
[Seo Wook Jang](https://github.com/sjangcme) - CME Group Global Data Licensing Services

## Questions and Comments?
Please contact markettechsales@cmegroup.com or use the Issues feature.

## Notice
The information herein has been complied by CME Group for general informational and education purposes only and does not constitute trading advice or the solicitation of purchases or sale of futures, options, or swaps. The views in this video reflect solely those of the author and not necessarily those of CME Group or its affiliated institutions. All examples discussed are hypothetical situations, used for explanation purposes only, and should not be considered investment advice of the results of actual market experience. Although every attempt has been made to ensure the accuracy of the information herein, CME Group and its affiliates assume no responsibility for any errors or omissions. All data is sourced by CME Group unless otherwise stated. All matters pertaining to rules and specification herein are made subject to and are superseded by official CME, CBOT, NYMEX, and COMEX rules. Current rules should be consulted in all cases concerning contact specifications.
 
CME Group, the Globe Logo, CME, Globex, E-Mini, CME Direct, CME Datamine and Chicago Mercantile Exchange are trademarks of Chicago Mercantile Exchange Inc.  CBOT is a trademark of the Board of Trade of the City of Chicago, Inc.  NYMEX is a trademark of New York Mercantile Exchange, Inc.  COMEX is a trademark of Commodity Exchange, Inc. All other trademarks are the property of their respective owners.
