#Principal is the initial amount of money invested innto the account.
#Interest rate is the current interest rate from Trading 212.

Principal = 1000
Interest_rate = 5

daily_interest = Principal*((1+((Interest_rate)/100))**(1/365.25)-1)

print(f"Daily Interest:   £{round(daily_interest,2)}")
print(f"Weekly Interest:  £{round(daily_interest * 7,2)}")
print(f"Monthly Interest: £{round(daily_interest * 30,2)}")
print(f"Yearly Interest:  £{round(daily_interest * 365.25,2)}")
