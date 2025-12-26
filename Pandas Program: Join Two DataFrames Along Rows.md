# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

import pandas as pd 
student_data1 = pd.DataFrame({ 
'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'], 
'name': ['Danniella Fenton', 'Ryder Storey', 'Bryce Jensen', 'Ed Bernal', 'Kwame Morin'],  
'marks': [200, 210, 190, 222, 199]}) 
student_data2 = pd.DataFrame({ 
'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'], 
'name': ['Scarlette Fisher', 'Carla Williamson', 'Dante Morse', 'Kaiser William', 'Madeeha Preston'],  
'marks': [201, 200, 198, 219, 201]}) 
print("Original DataFrames:") 
print(student_data1) 
print("-------------------------------------") 
print(student_data2) 
print("\nJoin the said two dataframes along rows:") 
result_data = pd.concat([student_data1, student_data2]) 
print(result_data)

## Output

## Result<img width="893" height="610" alt="438909547-742744ac-b0ae-4cea-b07d-11a2d3c62553" src="https://github.com/user-attachments/assets/f7ddd6f7-b4fa-4fc5-9a4a-87168078f753" /> 

<img width="893" height="505" alt="438909575-2c2dbb49-8359-41d1-b417-05c1afcc1afd" src="https://github.com/user-attachments/assets/d415f6e4-4912-497e-bc37-2f5f71a0ddd9" />

##Result

Thus, the program has been successfully executed.
