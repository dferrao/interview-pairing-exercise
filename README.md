A. Write a class to represent an bank account. 
* Use a double to represent the balance. 
* Add a method to return the current balance.

B. Add deposit and withdraw methods to the bank account class 
* Make sure that the methods are tested.

C. Enhance the bank account class to keep a list of operations applied to it.
* Consider adding a method like the one below in the bank account object. 
* Add a method to the bank account which will return a list of transactions that are performed up to date. 
* Make sure that that all methods are well tested.
```
public void apply(com.jpmorgan.grt.gim.geq.banking.model.Transaction transaction)
``` 

 
D. We have a request to implement Swift transfers. We have received a jar from SWIFT with the code as below
* Create a swift transfer transaction using the jar (image it is a jar) as below.
* Make sure that the swift transfer is tested.
```
    package org.swift;

    public final class SwiftAgent {
        public void transfer(String swiftIdFrom, String swiftIdTo, double amount) {
            // the actual transfer will happen here
        }
    }
```

E. Implement incoming messages by utilising the swift agent interface.

