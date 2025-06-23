# task_1__elevate_labs
Clean and prepare a raw dataset

the repository contains following files
1.task1__data_cleaning.ipynb    (where the code is written)
2.data.csv                      (data set)

the dataset have column named == ID,Name,Age,Gender,City,Email,Phone_Number,Subscription_Date,Order_Value,Comments 

Issues
0. in the column ID there are no visible problem
1. Name                 : whitespace  
2. Age                  : null value, 
                          negative value(-10), 
                          whitespace
3. Gender               : Inconsistent formats (Female, female, FEMALE, F)(Male, male, M)
4. City                 : Misspelled city
5. Email                : Invalid email format (eve@example)
6. Phone_Number         : Inconsistent formats (123-456-7890,  (987)654-3210, 1112223333, 555.666.7777, 0000000000)
7. Subscription_Date    : Inconsistent formats (2023-01-15, 2022/11/01, 05-20-2023)
8. Order_Value          : no problem
9. Comments             : assining nan to empty blocks
