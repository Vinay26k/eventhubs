# Event Hub Ingestion Scripts
## Instructions to configure Event Hub load test
To setup event hubs load test, we need to configure the following files:
1. Config file - ```config.yaml```
2. sample data file - ```file.json```

### Configuration File
1. Add details of event hubs to the parameters - ```CONNECTION_STRING``` && ```NAME```
2. Add details related to logging
   - ```LOG_FILE_INTERM``` - intermediate log file name
   - ```LOG_FILE``` - final log file with all the debug information
   - ```TIMESTAMPS_LOG``` - log file without debug information
   - ```show_process_info``` - deprecated not actively being used
3. Data File - ```file.json``` (can be any name that contains sample data)
4. Inputs
   - ```duration``` - how long to run
   - ```quantity``` - how records/events/messages to ingest
   - ```interval``` - time interval to be set for each batch to be sent (1 sec by default)
   - ```buffer``` - pre-ingestion time to keep the data & threads ready to ingest

<br/>
<br/>

# Links/ References: 
[Vinay26k/EventHubs](https://github.com/Vinay26k/eventhubs)
