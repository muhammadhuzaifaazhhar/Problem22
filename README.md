# Problem22
# Problem 2: Stock Value

# Input stock details
price_per_share = float(input("Enter price per share: "))
current_price = float(input("Enter current stock price: "))
quantity = int(input("Enter quantity of stock: "))

# Calculate stock value change
stock_value_change = (current_price - price_per_share) * quantity

# Display stock value change
print(f"\nStock Value Change: ${stock_value_change:.2f}")
