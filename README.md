## java code exercise

### We wish to gather a shared understanding of the team's skill-set.

#### When you do the exercise, take the following into consideration:

* ability to follow these instructions;
* attention to detail;
* correct output;
* simplicity;
* readability;
* test-driven development;
* separation of concerns;
* the “4 rules of simple design;”
* a README.md of explicit instructions detailing how to compile and execute your exercise; and
* the timeliness of the completed exercise.


#### GOAL:
#### In Java, parse the following set of three input files

````
space:

1 book 12.49
1 music CD 14.99
1 chocolate bar 0.85

````


````
pipe:

Imported | 1 bottle of perfume | 47.50
Imported | 1 box of chocolates | 10.00

````


````
comma:

1 bottle of perfume, 27.99, imported
1 bottle of perfume, 18.99
1 packet of headache pills, 9.75
1 box of chocolates, 11.25, imported


````

___

#### apply the following rules:
    SALES TAXES

    Basic sales tax is applicable at a rate of 10% on all goods,
    except books, food, and medical products that are exempt.

    Import duty is an additional sales tax applicable on all imported goods at a rate of 5%,
    with no exemptions.

    When I purchase items I receive a receipt which lists the name of all the items and their price (including tax),
    finishing with the total cost of the items, and the total amounts of sales taxes paid.
    The rounding rules for sales tax are that for a tax rate of n%,
    a shelf price of p contains (np/100 rounded up to the nearest 0.05) amount of sales tax.

#### and produce the following report:

```
    Output 1:
    1 book: 12.49
    1 chocolate bar: 0.85
    1 music CD: 16.49

    Sales Taxes: 1.50
    Total: 29.83


    Output 2:
    1 imported box of chocolates: 10.50
    1 imported bottle of perfume: 54.65

    Sales Taxes: 7.65
    Total: 65.15


    Output 3:
    1 packet of headache pills: 9.75
    1 bottle of perfume: 20.89
    1 imported box of chocolates: 11.85
    1 imported bottle of perfume: 32.19

    Sales Taxes: 6.70
    Total: 74.68
```
