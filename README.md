# D1
# Simple Cryptocurrency Wallet

class Wallet:
    def __init__(self):
        self.balance = 0
        self.transactions = []

    def deposit(self, amount):
        if amount > 0:
            self.balance += amount
            self.transactions.append(f"Deposited {amount} coins.")
        else:
            print("Invalid deposit amount.")

    def withdraw(self, amount):
        if 0 < amount <= self.balance:
            self.balance -= amount
            self.transactions.append(f"Withdrew {amount} coins.")
        else:
            print("Insufficient funds or invalid withdrawal amount.")

    def get_balance(self):
        return self.balance

    def get_transactions(self):
        return self.transactions

if __name__ == "__main__":
    my_wallet = Wallet()

    my_wallet.deposit(100)
    my_wallet.withdraw(30)

    print(f"Current balance: {my_wallet.get_balance()} coins")
    print("Transaction history:")
    for tx in my_wallet.get_transactions():
        print(tx)
def deposit(self, amount):
    if amount > 0:
        self.balance += amount
        self.transactions.append(f"Deposited {amount} coins.")
    else:
        print("Invalid deposit amount.")

def withdraw(self, amount):
    if 0 < amount <= self.balance:
        self.balance -= amount
        self.transactions.append(f"Withdrew {amount} coins.")
    else:
    


 

def get_transactions(self):
    return self.transactions
    def get_transactions(self):

