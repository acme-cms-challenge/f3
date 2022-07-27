# ACME sample data files for Phase 3 Exercise

The files in this repository are examples of source data that could be available for an early application development sprint.  The data is based on information from public sources, and as a result some aspects may not be necessary for the challenge.  

Document any assumptions made regarding the data provided in the Decisions section of the Case Study document.   

Do not contact any individuals or organizations included in this data set as part of the challenge.  

## patient_out.csv  (compressed)
- Represents a list of patients who could be impacted by a disaster. 

## npi_data_out.csv  
- Represents a list of healthcare professionals who could be impacted by a disaster.  
- Data elements are described in https://download.cms.gov/nppes/NPI_Files.html.  

## provider_out.csv
- Represents a list of healthcare facilities that could be impacted by a disaster.  
- Data elements generally follow the description in https://www.cms.gov/Medicare/End-Stage-Renal-Disease/ESRDGeneralInformation/Downloads/ESRD-Provider-PUF-Specification-04AUG2005.pdf, however the 7th to 26th character is allocated for a provider number.  

## patient_admit_out.csv (compressed)
- Represents a list of patient interactions with a healthcare facility.     
- The admit_date is represented as the number of days since an arbitrary system start date.
