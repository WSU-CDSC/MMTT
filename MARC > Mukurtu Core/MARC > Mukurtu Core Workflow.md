# Converting LOC-AFC provided MRC to Mukurtu CSV format 

## Table of Contents
- [Convert MARC XML to MRC](#id-section1)
- [Join multiple MRC records](#id-section2)
- [Generate field count report](#id-section3)
- [Create field settings list](#id-section4)
- [Export MRC to tab-delimited records](#id-section5)
- [Crosswalk MRC to Mukurtu Core](#id-section6)
- [Format fields for Mukurtu import](#id-section7)
- [Add remaining required fields for Mukurtu import](#id-section8)

This workflow requires at least two programs: 
- MarcEdit: https://marcedit.reeset.net/downloads 
- A spreadsheet editor of your choice that properly supports UTF-8 encoded CSV files. We recommend something other than Microsoft Excel – see more information here: https://mukurtu.org/support/file-formats-character-encoding-and-spreadsheet-tools/  

<div id='id-section1'/></div>
## If required, convert MARC XML records to MRC 
- https://www.youtube.com/watch?v=nt2RChF_hgQ

<div id='id-section2'/>
## If required, join multiple MRC records 
- https://www.youtube.com/watch?v=wOIL435CxMI

<div id='id-section3'/>
## Generate a field count report 
![MarcEdit - Tools](https://github.com/WSU-CDSC/MMTT/blob/7acf1d93872697b5ca65448c145897fa4e7f2f06/MARC%20%3E%20Mukurtu%20Core/Workflow%20Images/Screen%20Shot%202022-06-30%20at%202.03.33%20PM.png)
![MarcEdit - Generate field count report](https://github.com/WSU-CDSC/MMTT/blob/7acf1d93872697b5ca65448c145897fa4e7f2f06/MARC%20%3E%20Mukurtu%20Core/Workflow%20Images/Screen%20Shot%202022-06-30%20at%202.03.53%20PM.png)
![MarcEdit - field countr report example](https://github.com/WSU-CDSC/MMTT/blob/7acf1d93872697b5ca65448c145897fa4e7f2f06/MARC%20%3E%20Mukurtu%20Core/Workflow%20Images/Screen%20Shot%202022-07-18%20at%2012.24.51%20PM.png)

<div id='id-section4'/>
## Create a field settings list 

<div id='id-section5'/>
## Export MRC to tab-delimited records 
- https://www.youtube.com/watch?v=qkzJmNOvY00

<div id='id-section6'/>
## Crosswalk MARC fields to Mukurtu fields 
- https://mukurtu.org/support/digital-heritage-metadata-fields-2-1/  
- Rename 
- Concatenate 
- Divide 

<div id='id-section7'/>
## Format fields for Mukurtu import 
- https://mukurtu.org/support/digital-heritage-metadata-fields-2-1/ 
- Plain text 
- Multi-value taxonomy 
- Rich text 
- NID 
- SID 
- URL 
- Date 
- Location 
- Other? 

<div id='id-section8'/>
## Insert remaining required fields for Mukurtu import 
- https://mukurtu.org/support/digital-heritage-metadata-fields-for-roundtrip/  
- Community 
- Protocol 
- Item Sharing Settings 
- Category 
- Username 
