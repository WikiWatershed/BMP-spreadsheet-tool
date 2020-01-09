# MMW-BMP-Spreadsheet-Tool
An Excel workbook for advanced BMP planning based on model output from the [WikiWatershed / Model My Watershed (MMW) web application](https://app.wikiwatershed.org). The tool was designed to help meet permit renewal obligations in Pennsylvania, but it is also useful for MS4 permitting and watershed conservation plans in other regions.

Download our **[MMW-BMP-Spreadsheet-Tool.xlsx](https://raw.githubusercontent.com/WikiWatershed/MMW-BMP-spreadsheet-tool/master/MMW_BMP_Spreadsheet_Tool.xlsx.)** file to get started!

Download our **[User Manual](https://raw.githubusercontent.com/WikiWatershed/MMW-BMP-spreadsheet-tool/master/docs/MMW_BMP_Spreadsheet_Tool_UserManual.pdf)** for detailed instructions.

There is also a completed [example workbook](https://raw.githubusercontent.com/WikiWatershed/MMW-BMP-spreadsheet-tool/master/docs/MMW_BMP_Spreadsheet_Tool(Example).xlsx) to help you get started.

### Overview
This tool provides the ability to use output results from a [Model My Watershed "multi-year" model](https://wikiwatershed.org/documentation/mmw-tech/#watershed-multi-year-model) run for the purpose of estimating loading rates for different "source areas", and then subsequently calculating potential load reductions that might result from the implementation of both urban and agricultural BMPs in a given watershed.

The tool is based on the concept of "composite" loading rates whereby both "upland" and "streambank-eroded" loads are combined to facilitate the estimation of load reductions based on the use of various BMPs as applied to different developed land and agricultural land categories.

### History & Limitations
This Excel workbook tool was originally developed for use by municipalities that have MS4 discharges and load reduction responsibilities in Pennsylvania. This tool calculates land use pollutant loading rates for TSS, TN and TP using calculations, methodology, assumptions, and data based on, and consistent with, the MapShed model used in PA, and is also consistent with PADEP’s 2017 TMDL and PRP instructions for MS4s.
Now that the modeling routines in MapShed have been incorporated into Model My Watershed, this tool can also utilize output from a MMW run for a given watershed. Similarly, it can be used in other geographic areas where similar load reduction estimates have to be made.

## Change list:

2020-01-09 - v1.0.0:  Both the spreadsheet tool and the user manual have been updated.
   - Allows for input of farm animal information returned by Model My Watershed
   - Allows for calculation of streambank loading rates based on information returned by Model My Watershed
   - Incorporates data checks to avoid over-implementation of various agricultural BMP's.

2018-10-17 - v0.8.0:  Spreadsheet released.
    - Still available in the [Archives](https://github.com/WikiWatershed/MMW-BMP-spreadsheet-tool/tree/master/Archives) folder.

2018-08-02 - v0.7.0beta:  Beta version
