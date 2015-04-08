Following will explain a daily use of SmartCSV, in my case I had to extract product data from manufacturer base and import it in a software database (OpenERP).

A sample can be downloaded here
http://www.schneider-electric.fr/sites/france/fr/myse/tarif-public/tarif.page

Raw data contains a lot of columns, most are not really usefull here.

First, as SmartCSV identify column to export via header font type (bold or colored), I need to remove font format of all headers

Now supposed that I'm just interested to export product designation and reference but "reference" must be composed from "Mqe" and "RefCiale". To do this, I create a new column that will be the composition of both column via spreadsheet string operations.

I'm tagging column to export by setting header font to bold. And I'm now ready to export. Note that data is automatically splitted into multiple files.

If I only want to export selected data, I just have to select it. (Note that the header must always be in the selection).