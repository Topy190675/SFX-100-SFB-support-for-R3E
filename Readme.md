# SFX-100 - telemetry support for R3E (Raceroom Racing Experience) in Simfeedback (SFB)
This updated telemetry provider re-enabled now (after API changes in R3E applied by its developer team from Sector 3) again full motion 
support in Simfeedback. 
- add new controller and set it up by defining controller's COM port (physical connection inside PC configuration; only available ports
  within your pc will be shown), user-defined controller-name.
- edit / change parameter for all already existing controllers (nice function if you e.g. have to change Arduino controller because of a
  defect since Windows most commonly will declare different Arduino with new COM port to avoid issue). Selection of controller to work on
  is done from drop-down list
- delete an existing controller configuration from active (useful if old, no longer needed controller has been removed)

FYI: this extension always creates a backup of your SimFeedback configuration (XML based) in advance of any change is done / written to your
     existing software config (previous XML config backups can be found within your SFB installation directory named "SimFeedback-bkp?.xml"
     where "?" represents a number counting upwards with each save operation in advance of new created or edit / changed file will be saved).
  

# Installation  
Do not click on the green Download button on this page. This would download the sources (if available) only.  
Download the files from the releases page instead or download latest version below 

https://github.com/Topy190675/SFX-100-SFB-support-for-R3E/releases

- Close SimFeedback
- Extract the zip file and copy content of created sub-folders into SimFeedback's root installation folder.
- If asked to overwrite DLL file, you should do this
- Run remove_blocking.bat as admin
- Start SimFeedback


This telemetry support file / provider is based on original source as published by Saxxon66 with his Simfeedback package and has been just updated
with latest API (C-Sharp based example and info) as released by Sector 3 on their GitHub page (https://github.com/sector3studios/r3e-api/tree/master).
Basic concepts for such telemetry support have also been developed by SimFeedBack community (in particular I would like to name here daCujo, Dsl71) 
and especially SFX-100 motion controller project's mastermind Saxxon. 

**Please really support this fantastic project.**
https://opensfx.com

