# Housing Data Visualization Project

## Suggested data for visualization

The data below are by no means intended to be a comprehensive list of data that are relevant to answering the research questions posed, but are viewed to be necessary to understanding.

### Population & Socio-economic statistics

#### BC Stats

- [Population Estimates](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/PopulationEstimates.aspx)
- [Population Projections](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/PopulationProjections.aspx)
- [Households](http://www.bcstats.gov.bc.ca/StatisticsBySubject/Demography/Households.aspx)


#### DataBC Catalogue

- [DataBC Catalogue](https://catalogue.data.gov.bc.ca/dataset?download_audience=Public)

- [Property Transfer Tax data](https://catalogue.data.gov.bc.ca/dataset/property-transfer-tax-data)

#### City of Vancouver 

- [City of Vancouver Open Data catalogue](http://vancouver.ca/your-government/open-data-catalogue.aspx)

#### Teranet & National Bank of Canada

- [Teranet - National Bank National Composite House Price Index ™](http://www.housepriceindex.ca/)

#### TransLink

- [SkyTrain: travel times between stations](http://www.translink.ca/site-info/document-library-result.aspx?id={0F4E7466-A7AB-4D17-8241-D9D01C23EE9A}|{72FCB85B-D728-4710-BF91-C4F8D308107E}|{B11A2FC3-956F-403F-8FCC-2F1F9D44EE1A}&ref={FFCD8EFA-A8B3-47FA-97D3-4523903C5195})

#### Statistics Canada: Census and National Household Survey (NHS)

- [Census of Canada: Geosuite](http://www12.statcan.gc.ca/census-recensement/2011/geo/ref/geosuite-eng.cfm). This page has links to the Geosuite tool for the 2016, 2011, 2006, and 2001 Censuses. 

- [Census Datasets](http://www12.statcan.gc.ca/datasets/Index-eng.cfm) This page has links to data tables for the 2016, 2011, 2006, and 2001 Censuses. It seems these tables replicate what's in the Geosuite tool above.

- [2016 Census of Canada: Population and Dwelling Count Highlight Tables](http://www12.statcan.gc.ca/census-recensement/2016/dp-pd/hlt-fst/pd-pl/comprehensive.cfm) -- of greatest relevance are the Census Tract and Census Subdivision tables.
  - This report, about the population growth in the City of Toronto, has some good examples of visualizations of population change in that city's census tracts.  [Dahab Ibrahim,_Growth and Change in Toronto's Neighbourhoods_, Social Planning Toronto, February 2017](http://www.socialplanningtoronto.org/new_census_report_shows_toronto_faces_unprecedented_density_surge_leaving_city_struggling_to_keep_pace)

- [2011 Census of Canada: Topic-based tabulations](http://www12.statcan.gc.ca/census-recensement/2011/dp-pd/tbt-tt/Index-eng.cfm)

- **{NEW}** [National Household Survey: data table, British Columbia, all variables](https://github.com/bcgov/housing-data-visualization-project/blob/master/data/NHS2011_BC.csv) 
  - this table has the British Columbia-only aggregation of all 2,621 variables reported for the NHS.
  - these data are available for geography as fine as Dissemmination Area (the full table has 7731 rows for the province of B.C.).
  - Refer to the Statistics Canada [National Household Survey Dictionary](https://www12.statcan.gc.ca/nhs-enm/2011/ref/dict/index-eng.cfm) for more information about each variable. 

- [2011 National Household Survey: Data tables](http://www12.statcan.gc.ca/nhs-enm/2011/dp-pd/dt-td/Index-eng.cfm)

   - [Income and Housing](http://www12.statcan.gc.ca/nhs-enm/2011/dp-pd/dt-td/Lp-eng.cfm?LANG=E&APATH=3&DETAIL=0&DIM=0&FL=A&FREE=0&GC=0&GID=0&GK=0&GRP=0&PID=0&PRID=0&PTYPE=105277&S=0&SHOWALL=0&SUB=0&Temporal=2013&THEME=98&VID=0&VNAMEE=&VNAMEF=)
       - A variety of data tables are available, each summarizing different dimensions of housing and income-related data

   - [Commuting to work](http://www12.statcan.gc.ca/nhs-enm/2011/as-sa/99-012-x/99-012-x2011003_1-eng.cfm)
   
      - [Journey to Work Reference Guide](https://www12.statcan.gc.ca/nhs-enm/2011/ref/guides/99-012-x/99-012-x2011008-eng.cfm)

  - [National Household Survey Dictionary](https://www12.statcan.gc.ca/nhs-enm/2011/ref/dict/index-eng.cfm)

- [2011 Census - Dissemination Area comprehensive table](https://www12.statcan.gc.ca/census-recensement/2011/dp-pd/prof/details/download-telecharger/comprehensive/comp-csv-tab-dwnld-tlchrgr.cfm?Lang=E#tabs2011)

- [2011 Census - Census Tract comprehensive table](https://www12.statcan.gc.ca/nhs-enm/2011/dp-pd/prof/details/download-telecharger/comprehensive/comp-csv-tab-nhs-enm.cfm?Lang=E)


#### Statistics Canada: other data

- [Residential and Non-Residential Property Assessment Values](http://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=318595)

- [Tables by subject: Residential construction](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/ind01/l3_2162_2166-eng.htm?hili_cpis04)

   - [Building permits, values by activity sector](http://www5.statcan.gc.ca/cansim/a26?lang=eng&retrLang=eng&id=0260003&&pattern=&stByVal=1&p1=1&p2=37&tabMode=dataTable&csid=)
   
   - [Housing starts, by province](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/cst01/manuf05-eng.htm)

   - [New Housing Price Index (NHPI)](http://www.statcan.gc.ca/tables-tableaux/sum-som/l01/cst01/manuf12-eng.htm)


#### non-Canadian data sources

- Federal Housing Finance Agency (U.S.A.), [Working Paper 16-01: Local House Price Dynamics: New Indices and Stylized Facts](https://www.fhfa.gov/PolicyProgramsResearch/Research/Pages/wp1601.aspx)

---

### Geography

#### Geography concordance

- [geography-concordance.csv](housing-data-visualization-project/data/geography-concordance.csv). This file shows the relationship between municipalities, regional districts (including their varied names), the aggregation of regional districts using in the Property Transfer Tax aggregations, and development regions.

#### ParcelMap BC

- [ParcelMap BC Parcel Fabric](https://catalogue.data.gov.bc.ca/pt_BR/dataset/parcelmap-bc-parcel-fabric) at DataBC Catalogue

   - [ParcelMap BC at BC Land Titles & Survey Authority](https://ltsa.ca/online-services/parcelmap-bc)

   - [parcelMap BC at International Cadastral Information Society (ICIS)](http://www.icisociety.ca/parcelmap-bc/parcelmap-bc/)
