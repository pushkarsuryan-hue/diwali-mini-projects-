     1} # diwali-mini-projects-
I have prepared these three mini projects under geeks for geeks diwali bootcamp in which I solved the problem statement of  sweet distribution in friends and remaining , diwali discount calculator , and diya pattern 
# program to print pattern of diyas or stars 
# Input: number of rows
n = int(input("Enter the number of rows: "))

# Task: Print Diya symbols (★ ) in increasing order
for i in range(1, n + 1):
    print("★" * i)

 2}    # Input: total sweets and number of friends
total_sweets = int(input("Enter the total number of sweets: "))
num_friends = int(input("Enter the number of friends: "))

# Task: Calculate maximum sweets per friend and remaining sweets
max_per_friend = total_sweets // num_friends        # Integer division
remaining_sweets = total_sweets % num_friends       # Modulo operation

print(f"Each friend gets {max_per_friend} sweet(s).")
print(f"Sweets remaining: {remaining_sweets}")
print ("bache hue sbhi mil baat kr khao ") 


3}    # Input: list of item prices
item_prices = input("Enter item prices separated by spaces: ")
prices = [float(x) for x in item_prices.split()]

# Calculate total price
total = sum(prices)

# Apply 10% discount if total exceeds ₹500
if total > 500:
    final_price = total * 0.9  # 10% discount
    print(f"Discount applied! Final price: ₹{final_price:.2f}")
else:
    final_price = total
    print(f"No discount. Final price: ₹{final_price:.2f}")
    print("paisa hatho ka mael hai ise jaane do ,happy diwali") 





    the all three codes are end now happy diwali 
