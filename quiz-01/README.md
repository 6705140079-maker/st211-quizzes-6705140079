# Quiz 01 - BankAccount

A BankAccount class with deposit and withdraw methods. Raises a ValueError for non-positive deposit amounts and for withdrawing more than the current balance.

## How to run
`python3 -m pytest quiz-01/test_bank.py`

## Sample output
test_bank.py::test_deposit_positive_amount_increases_balance PASSED
test_bank.py::test_withdraw_exact_balance_leaves_zero PASSED