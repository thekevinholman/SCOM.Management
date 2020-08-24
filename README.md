# SCOM.Management 10.19.10407.1

Download Here:  https://github.com/thekevinholman/SCOM.Management/releases/download/10.19.10407.1/SCOM.Management.10.19.10407.1.zip


SCOM - Management Pack to discover properties and add tasks to make SCOM Admins life easier

https://kevinholman.com/2017/05/09/scom-management-mp-making-a-scom-admins-life-a-little-easier/

Version History:

* 1.0.0.65 – Initial Release
* 1.0.0.72 – Updated with additional properties and dual versions for safer tasks.
* 1.0.0.73 – Corrected minor bug in script names in export event log task
* 1.0.0.75 – Updated to support SCOM 2012R2 UR13 and SCOM 2016 UR3 in update rollup discovery
* 1.0.0.77 – Updated OS Version discovery to PowerShell to better handle WS2016 and Windows 10
* 7.0.0.4 – Major Re-write to include Server Roles, add OMS workspaces, UR levels
* 7.0.0.20 – Renamed Views, Added Health Service Watcher View, Added Agent install and delete tasks, Added install path property
* 7.0.0.27 – Added AD Integration discovered property and tasks to enable/disable AD integration
* 7.0.0.33 – Added APM installed discovery to find agents that need NOAPM reinstall, Added Tasks for Agent Delete, and Set IsManualyInstalled to false, Added view for HealthService objects
* 7.0.0.42 – Added discovery for OMS proxy, Added tasks for OMS Workspace ADD and REMOVE, Minor bug fixes to Agent Properties powershell discovery.
* 7.0.0.45 – Bug fixes, Added properties for OMS, Added tasks for OMS, Changes to views based on customer requests
* 7.0.0.46 – Updated server properties discovery to properly detect UR level on Gateways
* 7.0.0.47 – Updated to support discovery of SCOM 2016 UR4
* 7.0.0.50 – Updated for SCOM 2012 R2 UR14
* 7.0.0.51 – Updated for SCOM 2016 UR5
* 7.0.0.53 – Updated for TLS 1.2 support
* 7.0.0.54 – Added OS/CPU Architecture property
* 7.0.0.58 – Added IP address and Port availability check
* 7.0.0.59 – Added support for SCOM UR6
* 7.0.0.62 – Fixed bugs for UR6 display, Added properties for certificates such as expiration, thumbprint, issuer
* 7.0.0.63 – Added tasks for HSLockdown, Added preliminary support for SCOM 2019
* 7.0.0.64 – Added support for SCOM 2019 RTM
* 7.0.0.65 – Added support for SCOM 2016 UR7
* 7.0.0.66 – Added support for SCOM 2016 UR8, and added support for US Government Cloud Type for onboarding Log Analytics direct agent configuration (OMS Workspace)
* 10.19.10311.0 – Added support for SCOM 2019 UR1
* 10.19.10311.2 – Added support for SCOM 2016 UR9
* 10.19.10349.0 – Added support for SCOM 2019 Post UR1 Hotfix.  Fixed bug when a management server config file is huge and the script runs out of resources getting XML content.
* 10.19.10407.0 – Added support for SCOM 2019 UR2
* 10.19.10407.1 - Minor bug fix with quotation marks
