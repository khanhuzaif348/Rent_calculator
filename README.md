# Rent Calculator

# **Input we need from the user** 

  **Total rent** 
  
**Total food ordered for snacking**

**Electricity units spend**

**Charge per unit** 

**Input   members** 


## output

 # **total amount you're to pay is**  

# **Python Code**

rent = int(input("Enter your flat rent: - "))

food = int(input("Enter food has ordered : - "))

electric_spends = int(input("Enter electricity charge spend : - "))

charge_per_unit = int(input("Enter charge : -  "))

person = int(input("Enter the number of person living in room  : - "))

total_bill = electric_spends * charge_per_unit 

total_amount = rent + food + total_bill

print(f'Your total rent : -  {total_amount}')

amount_each_person = total_amount // person

print(f'you are a  {person}  member  and each person rent  : - {amount_each_person}')
