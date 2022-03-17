# AK8PO
Time frame for AK8PO subject

# Work
----------------
### Task 1 - Every location should have own ATS field
#### Description:
There is a separate job in ATS for every location. A compound field needs to be created. We need to implement a new field Location + ATS number and hide the old Location field. Data from the new Location field will be written into the old hidden field so we don't need to change anything in Frontend.
#### Task size
Estimated: **24 hours**
<br />Spent: **28 hours**

I spent more hours here because it was tricky to create new compound field which would work with current implementation of hiring system. So hiring system needed to be little bit reworked here. This extra work was considered in the estimated time.

----------------
### Task 2 - Create paragraph template for job position.
#### Description:
A paragraph template needs to be created so CNPD (our HR) won't have to create new paragraphs all over again. This needs to be discussed with Andrea Soumarová.
#### Task size
Estimated: **6 hours**

----------------
### Task 3 - Implement button in job position which will lead to FE page.
#### Description:
We need to implement a button in the job position which will lead to the FE page with the position so it can be viewed without finding it in the table of positions. It should lead straight to the first branch in the list.
F.E. https://www.cngroup.dk/careers/position/vuejs-developer/prague
#### Task size:
Estimated: **4 hours**

----------------
### Task 4 - Add collapse all button to paragraphs in the job position
#### Description:
There should be a button to collapse all paragraphs in the job position. So we can drag and drop them easily.
### Task size:
Estimated: **1 hour**

----------------
### Task 5 - Add to HR role rights for adding technologies.
#### Description:
Currently HR role can only select technologies in the job position. Add rights to allow them create new technologies in that field
### Task size:
Estimated: **1 hour**

----------------
### Task 5 - Remove language filter from careers positions
#### Description:
There is a language filter in the *adress of webpage*
<br />It should be removed since positions are always in English.
### Task size:
Estimated: **1 hour**

----------------

### Task 6 - Implement image conversion from PNG to WebP
#### Description:
Automatic conversion from png to WebP should be implemented so editors don't need to think about it. Image styles need to be changed too. We need to implement php extension Imagick and set it up. We need to convert all images besides logos, charts and icons.
### Task size:
<br />Estimated: **4 hours**
Spent: **4 hours**
