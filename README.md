# haproxy-crs

## Description:
Trying build the CRS Rule-Set for HAProxy where we can scan the Request and Response Body Scans.

## Rules Included are:
bad-bots.lst 	--> Known Bad-Bots User-Agents list

known-restricted-locations.lst 	--> Known restircted locations on a web server which should be secured

known-scanner-headers.lst 	--> Known HTTP Request Headers which are used by Vulnerability Scanners

known-scanner-urls.lst 	--> Known Common URLs which are accessed by Vulnerability Scanners

known-scanner-user-agents.lst 	--> Known Scanners User-Agents list

lfi.lst 	--> Regex signatures for Local File Inclusion Attacks

php.lst 	--> Regex signatures for PHP Injection Attacks

rce.lst 	--> Regex signatures for Remote Code Execution Attacks

rfi.lst 	--> Regex signatures for Remote File Inclusion Attacks

scanners.lst 	--> Other Scanners User-Agents list

scripting-user-agents.lst 	--> Scripting tools default User-Agents list

sql-commads.lst 	--> All known SQL Commands

sql-errors-response-body.lst 	--> Regex signatures for SQL Error Response pages

sqli.lst 	--> Regex signatures for SQL Injection Attacks

unix-shell-command-injections.lst --> All known Unix Shell Commands

windows-powershell-command-injection.lst 	--> All known Windows PowerShell Commands

xss.lst 	--> Regex signatures for Cross-Site Scripting Attacks

