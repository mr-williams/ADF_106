# ADF Pipelines & Projects
### Rapid API Car Comparisons
This is my first project linking different tools to accomplish an ELT process as well as the medallion architecture.
- It takes the results from [Rapid](https://rapidapi.com/carapi/api/car-api2) which is an api website that allows for API calls to import data in different formats.
- The results are saved in a data lake storage on the azure platform using the hierachical namespace which enables multiple folder storage.
- The setup uses the Medallion architecture(Bronze, Silver, Gold) each level changing and modifying the data till it can be used for analytical purposes.
- Databricks is used as the centrepiece to Extract, Load and Transform the Data, While Azure Data Factory is the orchestrator that bring allows the notebooks to work together while being triggered at a certain time.
- Logs of the process are recorded and saved for analysis which also includes the ingestion time.


