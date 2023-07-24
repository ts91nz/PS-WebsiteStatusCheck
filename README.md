# PS-WebsiteStatusCheck
Powershell: Perfoms basic website check for status and keyword search.


.Synopsis
   Perfoms basic website check for status and keyword search. 
   
.DESCRIPTION
   Perfoms basic website check for status and saves file for keyword search. 
   
   Write results to event log for monitoring detection. 

   
.EXAMPLE
   .\PS-WebsiteCheck.ps1 -url https://google.com -SearchString "Google" -workingDir C:\temp
   
.INPUTS
   URL - Website address (requires full HTTPS://).
   
.OUTPUTS
   Writes to terminal and to Event Log. 
   
