# Component library
A component library used for power platforms apps.

## Tech stack
- [Power Platform](https://powerplatform.microsoft.com/en-us/)
- [Power Platform Cli](https://docs.microsoft.com/en-us/powerapps/developer/data-platform/powerapps-cli)
  
## Get started
- Creates an .msapp file from the previously unpacked source files.
The result can be opened in Power Apps Studio by navigating to File > Open > Browse.
```
pac canvas pack --sources ComponentLibrary --msapp component_library.msapp
```
- Unpacks the .msapp source file.
Download the .msapp file from Power Apps Studio by navigating to File > Save as > This computer.
```
pac canvas unpack --msapp component_library.msapp --sources ComponentLibrary
```
