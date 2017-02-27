
<div id="devex-badge">
<a rel="Delivery" href="https://github.com/BCDevExchange/docs/blob/master/discussion/projectstates.md"><img alt="In production, but maybe in Alpha or Beta. Intended to persist and be supported." style="border-width:0" src="http://bcdevexchange.org/badge/3.svg" title="In production, but maybe in Alpha or Beta. Intended to persist and be supported." /></a>
</div>
---

# Housing Data: BCIC Innovation Exchange™ Public Service Challenge for BC Stats

_This repo provides additional details about the BC Innovation Council's Data Visualization Tech Challenge.
For more information, please see the BC Innovation Council's press release, ["$75,000 available to solve government’s needs for data visualization".](http://bcic.ca/news/blog/75000-available-solve-provincial-governments-data-visualization-challenges/)_

The Province of British Columbia and other agencies collect a wealth of administrative data that relates to housing, including the market for housing, as a consequence of their regulatory and administrative authorities. These include data about legal ownership (Land Titles BC), the total stock of housing (BC Assessment), and taxation information (Ministry of Finance). In addition, socio-demographic information is available, such as ownership status (owner or renter), through the Census of Canada.

The British Columbia Government seeks to develop statistics that will provide greater certainty about the state of housing in the province, including the role of foreign ownership, real estate as an investment or business strategy (rather than home ownership), and insights into the regional impact of these issues.

As one example, starting on 2016-06-10 the [Property Transfer Tax](http://www2.gov.bc.ca/gov/content/taxes/property-taxes/property-transfer-tax) form began collecting information about the citizenship and residency status of purchasers. This data is the source of the widely reported information about foreign ownership of residential properties; see for example this [news release from the Ministry of Finance](https://news.gov.bc.ca/releases/2016FIN0034-001354). Summary tables of these data are now available in the Data BC catalogue, under [Property Transfer Tax Data](https://catalogue.data.gov.bc.ca/dataset/property-transfer-tax-data); the tables are licensed under the Open Government License - British Columbia.

While there is much value in these data, the data are about transactions of a very small proportion of properties in B.C., and do not reflect the ownership of the total housing stock in British Columbia. By linking the foreign transaction data to the housing stock data, it would be possible to estimate the share of the B.C. housing stock that is owned by non-Canadians. It would also indicate the proportion of properties that are changing hands multiple times over short periods (potentially an indicator of investment, rather than residential, activity).


### Problem statement 

"In this challenge, participants will develop and submit an engaging on-line visualization platform of B.C. housing
market information, using the following types of data: population data, property assessments, property transfer tax
records, home owner grant records, land title records, etc. The platform will enable government, infrastructure
planners and the wider public to interact with, understand and make decisions based on community growth and
housing data." (BC Innovation Council)


### Background


#### Data sets

The data for the project is publically available from a variety of sources, including DataBC's catalogue, BC Stats, and Statistics Canada (including the Census). See the [listing of specific data sets](data-sets-list.md) for details.

Data sourced from Statistics Canada and saved in this repository is covered under the [Statistics Canada Open Licence Agreement](http://www.statcan.gc.ca/eng/reference/licence).

#### Examples / Inspiration

These are included as examples of the type of visualizations that might be suitable for the British Columbia housing data.

**Mapping**

- **{NEW}** [Canadian Rental Housing Index](http://rentalhousingindex.ca/), driven by Census & National Household Survey data from Statistics Canada. Via the [BC Non-Profit Housing Association](http://bcnpha.ca/research/rental-housing-index/)

- **{NEW}** [B.C. Paired Sales Analysis](https://public.tableau.com/profile/bcpairedsalesdata#!/vizhome/BCPairedSalesAnalysis-v12-2016-07-14/PairedSalesSummaryTable). 

- **{NEW}** [padmapper.com](https://www.padmapper.com/apartments/vancouver-bc) -- rental accommodation

- [Locating neighborhood diversity in the American metropolis](https://walkerke.shinyapps.io/neighborhood_diversity/) {created using the open source statistical software R with the Shiny package; code is available via [the project github repo](https://github.com/walkerke/neighborhood_diversity)}

- [Is $2 million the New $1 million?](http://www.btaworks.com/2016/01/28/is-2-million-the-new-1-million/) {blog post from [BTAworks](http://www.btaworks.com/) in Vancouver; uses open data from the City of Vancouver; software unknown}

- [Trick-or-Treat Onslaught](https://censusmapper.ca/maps/136) {uses data from Statistics Canada}

- [Invest in the Future of Baltimore](http://files.zillowstatic.com/research/public/Whitehouse_Hackathon/index.html) {information about platform and data are not shared}

- [London’s Housing Market Is Slumping and Still Hugely Expensive](http://www.bloomberg.com/graphics/uk-property) {Bloomberg.com; Land Registry data from [Gov.UK open data site](https://www.gov.uk/guidance/about-the-price-paid-data); mapping code not shared}

**Modeling, charts & tables**

- [Gapminder (birth rate by GDP, over time)](http://www.gapminder.org/tools/#_chart-type=bubbles)

- [Commuting to work](http://www12.statcan.gc.ca/nhs-enm/2011/as-sa/99-012-x/99-012-x2011003_1-eng.cfm)

- [Health Indicators in Utah Counties](https://juliasilge.shinyapps.io/CountyHealthApp/) (app) and [blog, including principle component analysis](http://juliasilge.com/blog/Health-Care-Indicators/)

- **{NEW}** [House price appreciation by year, at zip code level](https://twitter.com/lenkiefer/status/834943798417440768) -- interesting use of violin plot (also known as beeswarm or column scatter plot) to show the distribution of the number of areas (by zip code) across the range of appreciation rates (the Y axis). Data source: Federal Housing Finance Agency, [Working Paper 16-01: Local House Price Dynamics: New Indices and Stylized Facts](https://www.fhfa.gov/PolicyProgramsResearch/Research/Pages/wp1601.aspx)


**Articles, news stories, etc.**

- **{NEW}** ["Density map shows where Vancouver’s people live — and where they don’t"](http://www.metronews.ca/news/vancouver/2017/02/23/density-map-shows-where-vancouvers-people-live.html)



#### Code

---

### Getting Help or Reporting an Issue

To report bugs/issues/feature requests, please file an [issue](https://github.com/bcgov/bc_population_indicator/issues/).

### How to Contribute

If you would like to contribute, please see our [CONTRIBUTING](CONTRIBUTING.md) guidelines.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

### License

    Copyright 2016 Province of British Columbia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at 

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
Where specified, data housed in this repository is is covered under the [Statistics Canada Open Licence Agreement](http://www.statcan.gc.ca/eng/reference/licence).

Details about individual data files are specified in the R, RMD, and MD files that reference them.

This repository is maintained by [BC Stats](bcstats.gov.bc.ca). Click [here](https://github.com/bcgov/BCStats) for a complete list of our repositories on GitHub.
