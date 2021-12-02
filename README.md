# Component library
A component library used for power platforms apps.

## Tech stack
- [Power Platform](https://powerplatform.microsoft.com/en-us/)
  
## Get started
- Creates an .msapp file from the previously unpacked source files.
The result can be opened in Power Apps Studio by navigating to File > Open > Browse.
```
pac canvas pack --sources MyHelloWorldFiles --msapp HelloWorld.msapp
```
- Unpacks the .msapp source file.
Download the .msapp file from Power Apps Studio by navigating to File > Save as > This computer.
```
pac canvas unpack --msapp HelloWorld.msapp --sources MyHelloWorldFiles
```
