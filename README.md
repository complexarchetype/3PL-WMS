# 3PL-WMS
Warehouse Management System for 3PL Logistics

## LSMW Recordings

### Packaging Material Creation (AFS)

This LSMW Program creates the AFS Packaging master data.

- Project: ZPSA
- Sub-Project: PACK_MASTER_UPD
- Object: PACK_MASTER_UPD

Screenshot

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_afs_part1.png)

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_afs_part2.png)


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

Excel Formatting

Part 1

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_kddc_part1.png)

Part 2

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_kddc_part2.png)

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	Column I and K must be in “General” data format and numeric values must be rounded to 2 decimal places. 
4.	Column R, S, T and U are to be kept blank.
5.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.


Caution: While completing the file ensure that the measurement unit of the packaging material is same as that of part material. If part material and packaging material have different measurement units then LSMW will not be able to pack it properly.

### Packaging Instruction and Condition record Maintenance

This LSMW Program Creates the Packaging instruction, Packaging Determination and Condition Record.

- Project: ZPSA
- Sub-Project: PACKAGING
- Object: PACKAGING

Excel Formatting

Part 1

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_instr_part1.png)

Part 2
 
![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_master_instr_part2.png)

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	Column J, K, L, M and T must be in “General” data format and numeric values must be rounded to 2 decimal places. 
4.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.
5.	The Valid to and from must be maintained as per SOA with PSA Gruppe.


Caution: While completing the file ensure that the measurement unit of the packaging material is same as that of part material. If part material and packaging material have different measurement units then LSMW will not be able to pack it properly.

### Condition Record Update (KDDC)

This LSMW Program updates new Condition Records for KDDC Billing

- Project: ZPSA
- Sub-Project: CONDT_UPD
- Object: CONDT_UPD

![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_condt_upd.png)
 

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	 The “Valid to” and “Valid From” must be maintained as per SOA with PSA Gruppe.
4.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.

### Packaging Instruction Update (KDDC)

This LSMW Program updated existing Packaging Instruction for KDDC

- Project: ZPSA
- Sub-Project: CONDT_UPD
- Object: CONDT_UPD

 ![alt text](https://github.com/complexarchetype/3PL-WMS/blob/main/Images/pack_inst_upd.png)

File Preparation Rules:

1.	All Columns highlighted in Green must not be changed. They should merely be copied over to fill new rows.
2.	All Columns highlighted in Yellow can be changed as per criteria.
3.	Column F, G, H and I must be in “General” data format and numeric values must be rounded to 2 decimal places. 
4.	Column H and I can be used when PSA has specified Maximum Allowed Load Weight and Volume. Otherwise they are to be kept blank
5.	After the excel file has been prepared it must be saved in txt – delimited format and run through all steps in LSMW.
 
