# Test
Testing 
from datetime import datetime

name = input("What's your name? ")

today = datetime.now().strftime("%A")

print(f"Hello, {name} 👋")
print(f"Today is {today}. Hope you have a great day!")
