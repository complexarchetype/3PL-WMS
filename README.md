# 3PL-WMS
Warehouse Management System for 3PL Logistics

## LSMW Recordings

### Packaging Material Creation (AFS)

This LSMW Program creates the AFS Packaging master data.

- Project: ZPSA
- Sub-Project: PACK_MASTER_UPD
- Object: PACK_MASTER_UPD

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	Column I and K must be in “General” data format and numeric values must be rounded to 2 decimal places. 
4.	Column R, S, T and U can be used when PSA has specified Maximum Allowed Load Weight and Volume. Otherwise they are to be kept blank.
5.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.

Caution: While completing the file ensure that the measurement unit of the packaging material is same as that of part material. If part material and packaging material have different measurement units then LSMW will not be able to pack it properly.

###  Packaging Material Creation (KDDC)

This LSMW Program creates the KDDC Packaging master data.

- Project: ZPSA
- Sub-Project: PACK_MASTER_UPD
- Object: PACK_MASTER_UPD

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	Column I and K must be in “General” data format and numeric values must be rounded to 2 decimal places. 
4.	Column R, S, T and U are to be kept blank.
5.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.


Caution: While completing the file ensure that the measurement unit of the packaging material is same as that of part material. If part material and packaging material have different measurement units then LSMW will not be able to pack it properly.
 
