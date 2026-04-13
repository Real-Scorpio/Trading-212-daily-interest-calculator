#Interest rate = i 
#Principal = r

Principal = 1000
Interest_rate = 5

daily_interest = Principal*((1+((Interest_rate)/100))**(1/365.25)-1)

print(f"Daily Interest: £{daily_interest}")

