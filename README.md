🚲 Data Analysis: Bike Purchase Trends
This project explores factors influencing bike purchases through data cleaning, transformation, and visualization.

🔹 Key Steps:
✅ Data Cleaning & Preparation:

   1️⃣ Created a working copy to prevent accidental modifications.
  
   2️⃣ Removed duplicate entries using all columns.
  
   3️⃣ Standardized gender values ("M" → "Male", "F" → "Female") and formatted income as currency.
  
  :four: Introduced an "Age Bracket" column using a nested IF statement to classify individuals as "Young," "Middle-Aged," or "Old."
   =IF(L2:L1001 > 50, "Old", IF( L2:L1001 > 30, "Middle-Aged", IF(L2:L1001 < 31, "Young", "Invalid")))

✅ Data Analysis & Visualization:

  Pivot Tables:
    1️⃣ Analyzed the impact of gender & average income on bike purchases.
    ![image](https://github.com/user-attachments/assets/ef66ebc6-2b35-4bfd-9963-5ef3751f9ecb)

    2️⃣ Assessed how commute distance affects purchasing behavior.

   
    3️⃣ Examined the relationship between age brackets and bike purchases.




  Interactive Dashboard:
  
   1️⃣ Visualized insights from pivot tables using charts.
    
   2️⃣ Enhanced with three slicers for filtering by education, region, and marital status.
   ![image](https://github.com/user-attachments/assets/2474f2b0-c1b5-44d5-9073-3228a58763b4)

