### Request:
1. **Navigate and Search**:
   -  access the site **OLX**
   -  search next type of car: **AUDI A6**
   -  Choose the category **CAR** and apply the next filters:
       - **Kilometers** up to 30.000 km
       - **Year of manufacture**: between 2010 and 2017
       - **Fuel**:  Diesel
2. **Extract the date**:
   - **Year of manufacture**
   - **Kilometers**
   - **Price** (in **Euro** or in **LEI** as the case may be
3. **Data Transformation**:
   - **Data Cleaning**
   - remove symbols like "." or "," and the extra characters from circulation and price
   - Convert the price from EURO to LEI at the next Exchange rate: 1 Euro = 4.95 lei
4. **Create a Excel file**:
   - Create a **table** with the next information:
       - **URL of the car**
       - **Year of manufacture**
       - **Kilometers (km)**
       - **Price (lei)**
5. **Calculate the best options**:
   - Calculate the **Circulation / price Report** for every car and insert it in a new column
   - Identify the **best 5 options** base on the Circulation/Price report (the smaller price is the best)
   - **Add a new column "Status"** the value "Top 5" for the Top 5 best options
6. **Final Report**:
   - write in a Excel File all the ads and highlight top 5 best cars base on the Circulation/Price report   
     
