# Mendix-AzurePack

This repository contains:

* PowerShell Module [MXWAPack](/MXWAPack) to work with the Azure Pack Public Tenant API
* VM Role artifacts
  * [MendixSingleInstance](/VMRole/MendixSingleInstance)
  * [MendixMultiInstance](/VMRole/MendixMultiInstance)
* Documentation
  * Base Image Creation
    * [Single Instance](/Documentation/BaseImage.md)
    * [Multi Instance](/Documentation/BaseImage_MultiInstance.md)
  * [Make VM Role available for tenants](/Documentation/AddVMRole.md)
  * [Deploy VM Role using MXWAPack PowerShell module](/Documentation/DeployVMRole.md)
  * [Mendix operational instructions using MXWAPack PowerShell module](/Documentation/MendixOperations.md)
* Examples
  * [Single Instance End to End](/Examples/01-SingleInstance_End2End.ps1)
  * [Deploy SQL VM Role and acquire data to construct connection string](/Examples/02-SQLInstance.ps1)
  * [Multi Intance](/Examples/03-MultiInstance.ps1)

\* Currently the MXWAPack PowerShell module only works when the Public Tenant API Certificate is trusted.

