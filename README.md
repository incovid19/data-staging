The following data APIs are functional. We have ensured that the data APIs generate outputs in the same format as earlier (data.covid19india.org) to ensure continuity in your downstream applications.

### JSON endpoints 

|  Link to API                                              | Description            |
| -------------------------------------------------------- | ---------------------- |
| <https://data.incovid19.org/v4/min/timeseries.min.json>  | Daily numbers across Confirmed, Recovered, Deceased, Vaccinated and Tested per state  |
| <https://data.incovid19.org/v4/min/data.min.json>  | Current day numbers across districts and state   |
| <https://data.incovid19.org/v4/min/timeseries-XX.min.json>  (where XX is a two letter state code) e.g <https://data.incovid19.org/v4/min/timeseries-KA.min.json>  | District-level daily timeseries data containing Confirmed, Recovered, Deceased, Vaccinated and Tested per state   |  

**Note**: These are the same data APIs that were fueling the [covid19india.org](https://www.covid19india.org) website. These data APIs are responsible for all the data on [incovid19.org](https://www.incovid19.org/) as well.

#### Aggregated Sheets (CSV)

| CSV Data                    | CSV Data Link                                                                 | Contents                                                                                     |
| ----------------------------- | --------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| case_time_series              | <https://data.incovid19.org/csv/latest/case_time_series.csv>              | India level timeseries for Confirmed, Recovered and Deceased cases
| States                        | <https://data.incovid19.org/csv/latest/states.csv>                        | Statewise timeseries of Confirmed, Recovered and Deceased numbers.
| districts                        | <https://data.incovid19.org/csv/latest/districts.csv>                  | Districtwise timeseries of Confirmed, Recovered and Deceased numbers.                           |
| sources_list              | <https://data.incovid19.org/csv/latest/sources_list.csv>              | List of Sources for incovid19 portal  
| cowin_vaccine_data_statewise                    | <https://data.incovid19.org/csv/latest/cowin_vaccine_data_statewise.csv>                    | Key data points from CoWin database at a state level.<br/> **Note**: These numbers might not match the state-wise numbers displayed on the portal since we call the API each time while compiling this data and these numbers change each time the cowin API is invoked. However, the differences will be minimal.                                             |                                        
| cowin_vaccine_data_districtwise                | <https://data.incovid19.org/csv/latest/cowin_vaccine_data_districtwise.csv>                 | Key data points from CoWin database at a district level. |
| state_wise_daily | <https://data.incovid19.org/csv/latest/state_wise_daily.csv> | Statewise per day delta of Confirmed, Recovered and Deceased numbers. ** <br/>** Will be updated soon
 |
| tested_numbers_icmr_data      | <https://data.incovid19.org/csv/latest/tested_numbers_icmr_data.csv>      | Number of tests reported by ICMR                                                                |
| icmr_labs_statewise           | <https://data.incovid19.org/csv/latest/icmr_labs_statewise.csv>      | Number of Labs in each state as per ICMR                                                                |
| sources_list                  | <https://data.incovid19.org/csv/latest/sources_list.csv>                  | List of sources that we are using.                                                              |
| rtpcr_samples_collected       | <https://data.incovid19.org/csv/latest/icmr_rtpcr_tests_daily.csv>          | Number of RTPCR samples collected statewise in ICMR Application                             |
| vaccine_doses_administered_statewise      | <https://data.incovid19.org/csv/latest/vaccine_doses_statewise_v2.csv>  | Number of vaccine doses administered statewise - Collected from MOHFW daily bulletin                              |
| cowin_vaccine_data_statewise      | <https://data.incovid19.org/csv/latest/cowin_vaccine_data_statewise.csv>  | Key data points from CoWin database at a state level                              |
| cowin_vaccine_data_districtwise      | <https://data.incovid19.org/csv/latest/cowin_vaccine_data_districtwise.csv>  | Key data points from CoWin database at a district level                           |
