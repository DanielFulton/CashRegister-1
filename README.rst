Cash Register
==============

Setup:
----------

1. Fork this repo on GitHub
2. Create the iOS program described below. 
3. Commit early and often, with good messages.
4. Push your code back to GitHub and send me a pull request.

(Don't be offended when I don't actually pull. I will clone your repo and inspect it locally when I receive the request. This repo will be left solution-less for obvious reasons.)

Description:
------------

The goal of this challenge is to design a cash register program. You will be given two float numbers. The first is the purchase price (PP) of the item. The second is the cash (CH) given by the customer. Your register currently has the following bills/coins within it:

 'PENNY': .01,

 'NICKEL': .05,

 'DIME': .10,

 'QUARTER': .25,

 'HALF DOLLAR': .50,

 'ONE': 1.00,

 'TWO': 2.00,

 'FIVE': 5.00,

 'TEN': 10.00,

 'TWENTY': 20.00,

 'FIFTY': 50.00,

 'ONE HUNDRED': 100.00

The aim of the program is to calculate the change that has to be returned to the customer.

Input sample:
--------------

Your program should accept as its first argument a path to a filename.The input file contains several lines. Each line is one test case. Each line contains two numbers which are separated by a semicolon. The first is the Purchase price (PP) and the second is the cash(CH) given by the customer. eg.

 15.94;16.00

 17;16

 35;35

 45;50

Output sample:
---------------

For each set of input produce a single line of output which is the change to be returned to the customer. In case the CH < PP, print out ERROR. If CH == PP, print out ZERO. For all other cases print the amount that needs to be returned, in terms of the currency values provided. The output should be alphabetically sorted. eg.

 NICKEL,PENNY

 ERROR

 ZERO

 FIVE


