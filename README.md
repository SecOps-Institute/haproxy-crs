# haproxy-crs

# Description:
Trying build the CRS Rule-Set for HAProxy where we can scan the Request and Response Body Scans.

Rules Included are:
bad-bots.lst 	--> Known Bad-Bots User-Agents list \n
known-restricted-locations.lst 	--> Known restircted locations on a web server which should be secured \n
known-scanner-headers.lst 	--> Known HTTP Request Headers which are used by Vulnerability Scanners \n
known-scanner-urls.lst 	--> Known Common URLs which are accessed by Vulnerability Scanners \n
known-scanner-user-agents.lst 	--> Known Scanners User-Agents list \n
lfi.lst 	--> Regex signatures for Local File Inclusion Attacks \n
php.lst 	--> Regex signatures for PHP Injection Attacks \n
rce.lst 	--> Regex signatures for Remote Code Execution Attacks \n
rfi.lst 	--> Regex signatures for Remote File Inclusion Attacks \n
scanners.lst 	--> Other Scanners User-Agents list \n
scripting-user-agents.lst 	--> Scripting tools default User-Agents list \n
sql-commads.lst 	--> All known SQL Commands \n
sql-errors-response-body.lst 	--> Regex signatures for SQL Error Response pages \n
sqli.lst 	--> Regex signatures for SQL Injection Attacks \n
unix-shell-command-injections.lst --> All known Unix Shell Commands \n
windows-powershell-command-injection.lst 	--> All known Windows PowerShell Commands \n
xss.lst 	--> Regex signatures for Cross-Site Scripting Attacks \n
