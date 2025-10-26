# diwali-mini-projects-
I have prepared these three mini projects under geeks for geeks diwali bootcamp in which I solved the problem statement of  sweet distribution in friends and remaining , diwali discount calculator , and diya pattern 
# program to print pattern of diyas or stars 
# Input: number of rows
n = int(input("Enter the number of rows: "))

# Task: Print Diya symbols (★ ) in increasing order
for i in range(1, n + 1):
    print("★" * i)

    # Input: total sweets and number of friends
total_sweets = int(input("Enter the total number of sweets: "))
num_friends = int(input("Enter the number of friends: "))

# Task: Calculate maximum sweets per friend and remaining sweets
max_per_friend = total_sweets // num_friends        # Integer division
remaining_sweets = total_sweets % num_friends       # Modulo operation

print(f"Each friend gets {max_per_friend} sweet(s).")
print(f"Sweets remaining: {remaining_sweets}")
print ("bache hue sbhi mil baat kr khao ")
