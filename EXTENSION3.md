## Extension 3: Discount Receipts

While receipts are important, showing the customer their savings is even more important!

## Task

Update and extend your program to handle showing savings to the customer.

Start with extracting useful stories and a functional domain model that represents these requirements.

#### Example Receipt
```
    ~~~ Bob's Bagels ~~~

    2021-03-16 21:38:44

----------------------------

Onion Bagel        2   £0.98
Plain Bagel        12  £3.99
                     (-£0.69)
Everything Bagel   6   £2.49
                     (-£0.45)
Coffee             3   £2.97

----------------------------
Total                 £10.43

 You saved a total of £1.14
       on this shop

        Thank you
      for your order!
```

```
    ~~~ Bob's Bagels ~~~

    2021-03-16 21:40:12

----------------------------

Plain Bagel        16  £5.55
                     (-£0.69)

----------------------------
Total                  £5.55

You saved a total of £0.69
      on this shop

        Thank you
      for your order!
```
## User Stories

```
As a customer,
So I can track my savings,
I'd like to be able to see on the receipt how much I saved on my order.
```