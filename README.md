# PS-WebsiteStatusCheck
Perfoms basic website check for status and keyword search using Powershell.  
Writes results to event log for monitoring system detection. 

### EXAMPLE
.\PS-WebsiteCheck.ps1 -url https://google.com -SearchString "Google" -workingDir C:\temp

### Inputs
URL - Website address (requires full HTTPS://).  
SearchString - String of text that the script will look for in the websites code.  
WorkingDir - Location to store output file and downloaded website file.   
   
### Outputs
Writes results to terminal and to Windows Event Log.   
   
