# Simple Banking System in R5RS Scheme

A console-based banking system developed in R5RS Scheme.

The project demonstrates functional programming concepts such as closures,
higher-order functions, recursive list processing, message passing, and
controlled mutable state.

## Features

- Creates bank accounts with unique account numbers
- Stores account names and passwords
- Supports user login
- Allows deposits and withdrawals
- Displays account names, numbers, and balances
- Prevents withdrawals that exceed the available balance
- Supports administrator account creation
- Calculates the combined balance of all accounts
- Displays logout messages

## Concepts Demonstrated

- Closures
- Lexical scoping
- Higher-order functions
- Message-passing objects
- Recursive functions
- Mutable state with `set!`
- Association lists
- Input and output
- Basic authentication logic

## Example Accounts

The program includes sample accounts for testing:

- Administrator account
- `anh`
- `joe`

These credentials are included only for demonstration purposes.

## How It Works

Each account is created using the `make-account` constructor.

The constructor stores private account data inside a closure, including:

- Account holder name
- Account balance
- Unique account number

The returned function accepts messages such as:

- `get-name`
- `get-account-number`
- `deposit`
- `withdraw`
- `get-ballance`
- `log-out`

The administrator can create new accounts and calculate the total balance
across all registered accounts.

## Technologies

- R5RS Scheme
- DrRacket

## How to Run

1. Open the project in DrRacket.
2. Select the R5RS language.
3. Run the file.
4. Follow the prompts in the console.

# Assembly Programming Exercises

These programs were completed as part of the Computer Information Systems program at Okanagan College.

They demonstrate fundamental assembly programming concepts, including arithmetic operations, recursion, sorting algorithms, and mathematical computations.

## Programs

### factorial_iterative.m
Calculates the factorial of a number using an iterative approach.

### factorial_recursive.m
Calculates the factorial of a number using recursion.

### shellsort.m
Implements the Shell Sort algorithm to sort a list of values.

### binomial.m
Computes binomial coefficients using assembly language.

### easter.m
Calculates the date of Easter using a mathematical algorithm.
