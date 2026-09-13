# Quiz 03 - Validators

Email and age validation helpers. Tests check both valid inputs (positive tests) and invalid inputs (negative tests).

## How to run
`python3 -m pytest quiz-03/test_positive.py quiz-03/test_negative.py`

## Sample output
test_positive.py::test_valid_email_accepted PASSED
test_negative.py::test_email_without_at_rejected PASSED
test_negative.py::test_negative_age_rejected PASSED