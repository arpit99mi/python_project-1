class Customer:
    def __init__(self,name,age,initial_balance=0):
        self.name=name
        self.age=age
        self.initial_balance=initial_balance
    def deposite(self,amount):
        self.initial_balance+=amount
        print(f'deposite of Rs. {amount} is successful.new balance is Rs. {self.initial_balance}')
    def withdraw(self,amount):
        if amount>self.initial_balance:
            
             print('Aukaat me')
        else:
         self.initial_balance-=amount
         print(f'withdraw of Rs. {amount} is successfull. new balance is Rs. {self.initial_balance}')
        
c1=Customer('arpit',23,1000)
c1.withdraw(200)




        
        
        
