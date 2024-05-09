# TelemetrySource
 Project created to map functions repsonsible for triggering events from various telemetry sources. 

Main Mapping Sheet: [Event Mapping Google Sheet](https://docs.google.com/spreadsheets/d/1d7hPRktxzYWmYtfLFaU_vMBKX2z98bci0fssTYyofdo/edit?usp=sharing)

## Currently mapped sources: 
### Sysmon 
  ![Sysmon-Overview](Sysmon/API-Mapping-Images/overview.png)
### Window Security Events (Microsoft-Windows-Security-Auditing)
  ![WSE-Overview](Microsoft-Windows-Security-Auditing/Images/overview.png)
### Threat Intelligence Events (Microsoft-Windows-Threat-Intelligence)
  ![Microsoft-Windows-Threat-Intelligence](Microsoft-Windows-Threat-Intelligence/Images/overview.png)


* Each source has it's own README file with the necessary information needed to understand how the mappings work. 

## Blogs: 
I have done a couple of write-ups on my methodology on tracking these events to APIs down, please read them if you are interested: 
* [Uncovering Windows Events - Part 1: TelemetrySource](https://medium.com/@jsecurity101/uncovering-window-security-events-ab72e1ec745c)
* [Uncovering Windows Events - Part 2: The Methodology](https://medium.com/@jsecurity101/uncovering-window-security-events-8c11a9dcdf34)
* [Uncovering Windows Events - Part 3: Threat Intelligence ETW](https://medium.com/@jsecurity101/uncovering-windows-events-b4b9db7eac54)

## Feedback: 
If anyone has suggestions on how this data could be exposed differently to better help defenders or any other feedback, please reach out! The goal with this project is to help defenders understand how data is generated, so that we can be more informed in our decisions when leveraging that data. 

## To-Dos: 
* [ ] Update Sysmon to v14
* [ ] Expand events in Microsoft-Windows-Security-Auditing
* [ ] Add other ETW Providers


