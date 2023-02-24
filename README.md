# TelemetrySource
 Project created to map functions repsonsible for triggering events from various telemetry sources. 

Main Mapping Sheet: [Event Mapping Google Sheet](https://docs.google.com/spreadsheets/d/1d7hPRktxzYWmYtfLFaU_vMBKX2z98bci0fssTYyofdo/edit?usp=sharing)

## Currently mapped sources: 
### Sysmon 
  ![Sysmon-Overview](Sysmon/API-Mapping-Images/overview.png)
### Window Security Events (Microsoft-Windows-Security-Auditing)
  ![WSE-Overview](Microsoft-Windows-Security-Auditing/Images/overview.png)


* Each source has it's own README file with the necessary information needed to understand how the mappings work. 

## Feedback: 
If anyone has suggestions on how this data could be exposed differently to better help defenders or any other feedback, please reach out! The goal with this project is to help defenders understand how data is generated, so that we can be more informed in our decisions when leveraging that data. 

## To-Dos: 
* [ ] Update Sysmon to v14
* [ ] Expand events in Microsoft-Windows-Security-Auditing
