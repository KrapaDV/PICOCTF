# PICOCTF

## Reverse Engineering

## Shop
  When we connect to the server, we get 40 coins and 3 items which we can buy. The 3rd option is 'Fruitful Flag', tis contains our flag but needs 100 coins. When we select any item and for quantity if entered a negative value we get extra coins based on the item and quantity. Now we will be able to purchase 'Fruitful Flag'. When we purchase it with get a list of numeric values. These values look very close to each other. 'p' has a ASCII value of 112, 'i' has a value of 105. Based on this conclusion when we convert ASCII to Char we get our flag. 
  
## Flag
  picoCTF{b4d_brogrammer_532bcd98}
