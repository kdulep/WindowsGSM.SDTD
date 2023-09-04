## 7 Days to Die Plugin

i forked plugin from https://github.com/LegendSeeker/WindowsGSM.SDTD_ExperimentalBeta

## Initial Setup
When you install the server, run update once

### Known issue
It looks like Windows GSM doesn't specify it is done validating after an update so please wait some time before starting the server. You will receive error `-1073741819` if the update is still in progress.

## Server Configuration
In order to configure  the server, please find the `serverconfig.xml` file located in `\serverfiles\serverconfig.xml`

### Notable Fields:

|FieldName|Default  |
|--|--|
|ServerName   | "My Game Host"  |
|ServerPassword |""|
|Region|"NorthAmericaEast"|
|ServerPort|26900|
|ServerVisibility|2 (public)|
|EACEnabled |true|
