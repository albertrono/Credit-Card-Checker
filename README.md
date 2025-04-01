# Credit Card Checker

## Overview
This Python project validates credit card numbers using the **Luhn Algorithm** and determines the card issuer (Visa, MasterCard, American Express, Discover, Diners Club, JCB).

## Features
- **Validates credit card numbers** using the Luhn Algorithm.
- **Identifies the card issuer** based on standard issuer rules.
- **Supports multiple card types**:
  - Visa
  - MasterCard
  - American Express (Amex)
  - Discover
  - Diners Club
  - JCB

## How It Works
1. The user inputs a credit card number.
2. The program reverses the number and applies the Luhn Algorithm to check validity.
3. If valid, it identifies the card issuer based on the first few digits and the card length.
4. The program outputs whether the card is valid and the corresponding issuer.

## Installation & Usage
### Prerequisites
- Python 3.x installed

### Run the Script
Clone the repository and navigate to the project directory:
```sh
$ git clone https://github.com/yourusername/credit-card-checker.git
$ cd credit-card-checker
```

Run the script:
```sh
$ python credit_card_checker.py
```

### Example Input/Output
```
Enter the credit card number: 4111111111111111
Card Number: 4111111111111111
The reversed card number is: 1111111111111114
Sum of digits: 30
The sum of the odd placed numbers: 8
The sum of the doubled placed numbers: 22
Valid: Visa Credit Card
```

## Contribution
Feel free to fork this repository, open issues, and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Your Name](https://github.com/yourusername)

