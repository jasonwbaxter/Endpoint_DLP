# General

Devices need to be on-boarded with a MDM Solution. You can onboard a device into Defender for Endpoint with a local script ,but for purview they need to be enrolled with Intune / Jamf especially for Mac Devices.

## Troubleshooting

Familiarise yourself with the MdatAnalyser commands as these are especially useful in getting a basic understanding of what the Defender for endpoint app is doing and the status of the endpoint.

Download the Analyser tool 

https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/run-analyzer-windows?view=o365-worldwide
 
 Windows
Run MDEClientAnalyser.cmd - q 

- Confirm Client Health

mac

run MDEClientAnalyser.cmd - t

Tracing Analysis of DLP for these actions https://learn.microsoft.com/en-us/purview/endpoint-dlp-learn-about#endpoint-activities-you-can-monitor-and-take-action-on

https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/data-collection-analyzer?view=o365-worldwide

 

Lastly review the report to understand more

https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/analyzer-report?view=o365-worldwide
