# py
#atm-interface
import time
print("please insert your CARD")
time.sleep(5)
password=12345
pin=int(input("enter your atm pin"))
balance=5000
while TRue:
  if pin = password:
    print("""
          1==balance
          2==withdraw_balance
          3==deposit_balance
          4=exit
                            """)
try:
  option = int(input("please enter your choice"))
except:
  print("please enter valid option")
if option==1:
  print(f"your current balance is {balance}")
if option==2:
  withdraw_amount=int(input("please enter withdraw amount")
  print(f"your updated balance is {balance}")
if option==3:
  deposit_amount=int(input("please enter deposit amount"))
  blance=balance+deposit_amount
  print(f"{deposit_amount} is created to your account")
  print(f"your updated is {balance}")
if option==4:
  break  
else:
  print("wrong pin please try again")
















