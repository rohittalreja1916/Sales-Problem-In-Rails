# Sales Problem Calculator In Ruby

## Question

Basic sales tax is applicable at a rate of 10% on all goods, except books, food, and medical
products that are exempt. Import duty is an additional sales tax applicable on all imported
goods at a rate of 5%, with no exemptions.

When I purchase items I receive a receipt which lists the name of all the items and their price
(including tax), finishing with the total cost of the items, and the total amounts of sales taxes
paid. The rounding rules for sales tax are that for a tax rate of n%, a shelf price of p contains
(np/100 rounded up to the nearest 0.05) amount of sales tax.

Write an application that prints out the receipt details for these shopping baskets...

### INPUT:
Input 1:
```bash
1 book at 12.49
1 music CD at 14.99
1 chocolate bar at 0.85
```

Input 2:
```bash
1 imported box of chocolates at 10.00
1 imported bottle of perfume at 47.50
```

### OUTPUT
Output 1:
```bash
1 book : 12.49
1 music CD: 16.49
1 chocolate bar: 0.85
Sales Taxes: 1.50
Total: 29.83
```

Output 2:
```bash
1 imported box of chocolates: 10.50
1 imported bottle of perfume: 54.65
Sales Taxes: 7.65
Total: 65.15
```

## Usage

- Run this command to test program
```bash
ruby Sales_Program.rb
```
- or Run this command to test program created using classes and modules
```bash
ruby Sales_Tax_Program/main.rb
```

### Program Using Classes and Modules
- Input must be given as asked.

### Program Using Methods
- Input Example 
```bash 
3
1 book at 12.49
1 music CD at 14.99
1 chocolate bar at 0.85
```
