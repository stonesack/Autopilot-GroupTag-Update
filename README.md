# Autopilot-GroupTag-Update
powershell script to update group tag for a group of autopilot devices using the microsoft graph API

NOTE: requires the WindowsAutoPilotIntune module to run properly, can be installed with
Install-Module -Name WindowsAutoPilotIntune

You will need to make sure you have edit permissions for your Azure environment and access to the Microsoft Graph API

HOW TO USE:

1. fill in the DeviceList.txt file with the serial numbers of the devices you want to change the group tag for
2. edit the last ForEach loop to include the groupTag you want to apply to those devices
3. run.ps1 from an elevated prompt and enter your Azure credentials when prompted
