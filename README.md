# ChikungunyaDataset2013
Datasets for the  2013 Chikungunya outbreak in the Caribbean

The model codes are available in the next link:
https://github.com/LeonardoL87/ChickModelCaribbean.git

In this repository, you can find and download the datasets used for the model implementation and fitting for the 2013 Chikungunya outbreak in the Caribbean Region.

In 2013, the Caribbean underwent an unprecedented epidemic of Chikungunya that affected 29 islands and mainland territories throughout the Caribbean in the first 6 months. In the model we analyze the spatio-temporal spread of the outbreak among the Caribbean islands, showing that the initial patterns of the epidemic can be explained by a simple network model based on the flight connections among islands. The flight connection network does not follow a random graph model. Its topology is likely the product of geo-political relationships that generate increased connectedness among locations sharing the same language. 

The infection is propagated preferentially among islands that belong to the same cultural domain, irrespective of their human and vector population densities. The model shows how a simple epidemic coupled with an appropriate human mobility model can reproduce the observed epidemiological dynamics. 

The files you can download from this repository are the following:

_________________________________________________________________________________________________________________________________________________________


PAHOTable.csv: This file have the number of cases reported to PAHO by each country. According to PAHO, this data correspond to fully confirmed cases. The attributes in this data set are

            (*) Cases: Total number of cases (Confirmed)
            
            (*) Date: Date of the report
            
            (*) Country: Name of the country 
            
_________________________________________________________________________________________________________________________________________________________


PAHO_ChartxCountry_data.csv: This file have the number of cases reported to PAHO by each country as the PAHOTable.csv but with some extra data attributes. The attributes in this data set are

            (*) Country: Name of the country  
            
            (*) Date: Date of the report	
            
            (*) YEAR: The year the outbreak	
            
            (*) WEEK: epidemiological week
            
            (*) Cases: Number of confirmed cases
            

_________________________________________________________________________________________________________________________________________________________

island_connections_caribbean.csv: Connection Matrix for the Islands. Here you can find the ID of each node and the connectivity weight between them.

_________________________________________________________________________________________________________________________________________________________

locations_populations.csv: The information about the spatial location of each node is described in this file. The data attributes are the next.

            (*) location:	Country name
            
            (*) pop_size:	Number of inhabitants
            
            (*) density: Population density 	
            
            (*) year:	Update year
            
            (*) reference: Data source
            
            (*) lat: Latitude
            
            (*) lon: Longitude	
            
            (*) area-sqkm: Size of the country in km²
            

_________________________________________________________________________________________________________________________________________________________

airports.csv: Information about air connectivity

            (*) Airport ID: International identification number of the Airport
            
            (*) Name: Name of the airport	
            
            (*) City: The city where the airport is located	
            
            (*) Country: The country where the airport is located	
            
            (*) IATA/FAA: International Air Transport Association code	
            
            (*) ICAO: International Civil Aviation Organization code 	
            
            (*) Latitude	
            
            (*) Longitude	
            
            (*) Altitude	
            
            (*) Timezone	

_________________________________________________________________________________________________________________________________________________________

Chikungunya_file_28August2014_Tycho.csv: This is the TYCHO data set. This data set was discontinued but this is the very last version of 2017-2018. This data come from several data sources. you can find more information on TYCHO project

            (*) id: Country ID	
            
            (*) COUNTRY: Country name	
            
            (*) YEAR: Year of the outbreak	
            
            (*) WEEK: Epidemiological week	
            
            (*) Week_Sus_Cases: Suspected cases	
            
            (*) Incidence_sus_cases: Incidence of suspected cases	
            
            (*) Cum_sus_cases: Cumulative suspected cases	
            
            (*) Week_conf_cases: Confirmed cases
            
            (*) Incidence_conf_cases: Incidence of confirmed cases
            
            (*) Cum_conf_cases: Cumulative confirmed cases	
            
            (*) Week_import_cases: Imported cases	
            
            (*) Cum_import_cases: Cumulative imported cases	
            
            (*) Week_deaths: Deaths	
            
            (*) Cum_deaths: Cumulative deaths	
            
            (*) Population: Population size	
            
            (*) Source: Source of the data.


_________________________________________________________________________________________________________________________________________________________

Sources:


https://www.tycho.pitt.edu/data/


https://www3.paho.org/hq/index.php?option=com_topics&view=rdmore&cid=5927&Itemid=40242&lang=en



