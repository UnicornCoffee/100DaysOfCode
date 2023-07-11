print("Welcome to the tip calculator!")
bill = float(input("What was your total bill? €"))
tip = int(input("What amount would you like to tip? 10, 12 or 15?"))
people = int(input("How many people are splitting the bill?"))

tipped_bill = tip / 100 * bill + bill
split_bill = tipped_bill / people
total = round(split_bill, 2)
total = "{:.2f}".format(split_bill)
print(f"Each person pays: €{total}")
