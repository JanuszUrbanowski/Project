**Data Audit Challenge: "The lying Report**

In this project, I take on the role of a Data analyst who inherits a crucial 2025 Sales Report from a former employee. The report is scheduled to be prented to the board in two days. The problem? The report is full of hidden erros.

My task is to audit to provided Excel file,identify the mistakes,fix them, and provide the management with the ture number

The original report contains 12 specific errors hidden within the data, formulas, and business logic. Some of these errors completely distort the final business conclusions.

My goals for this project are:
1. Anaylyze the raw data and find the hidden errors.
2. List each error, explain why it is wrong, adn describe how I found it.
3. Rebuild the report to calculate the metrics correctly.
4. Write an executive memo to the boss with the real numbers and update business insights.


Tools & Skills Demonstrated
Microsoft Excel
Data Auditing, Data cleaning, Business Logic Verification, Pivot tables, Executive Communication.


Dateset Overview

<img width="770" height="876" alt="image" src="https://github.com/user-attachments/assets/1f803d01-becf-4eb0-95ae-ceb2c1648c39" />

This sheet contains the final summary prepared by the previous analyst. It includes aggregated metrics like Total Net Revenue, Number of Transactions, and Sales by City.



<img width="1502" height="917" alt="image" src="https://github.com/user-attachments/assets/f1fc3306-2b12-44f3-b253-3ed6b874e53b" />
The core dataset containing 14,998 rows of sales transactions from 2025.

* ID_transakcji - Unique transaction identifier
* Data - Date and time OF the transaction
* Sklep - Store location
* Kategoria - Product category
* ID_produktu - Unique product code
* Nazwa produktu - Name of the product
* Ilość - Number of items bought
* Cena_jednostkowa Price per single item
* Rabat_% - Discount applied to the transaction
* Wartość_netto - Final transaction value after discount
* Status - Order status
* Koszt - Total cost of goods for the transaction


  <img width="1061" height="891" alt="image" src="https://github.com/user-attachments/assets/ccd37afa-188c-472f-a68a-519ca7ec52da" />

The official catalog used to verify pricing and costs.
*ID_produktu - Product code matching the transaction data
*Nazwa_produktu - Name of the product
* Kategoria -Category
* Cena_katologowa - Official standard price
* Koszt_jednostkowy - Official standard price




<img width="1025" height="906" alt="image" src="https://github.com/user-attachments/assets/ed393915-5f83-443a-a6dc-36786f886da3" />

An additional catalog, likely for new releases like e-bikes 


<img width="775" height="920" alt="image" src="https://github.com/user-attachments/assets/fd4a1956-e8c6-49ef-ad6a-bd892126354c" />

A small lookup table containing the 2025 revenue targets for specific cities.
