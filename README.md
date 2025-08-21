This module teaches error handling in Python using try-except, input validation, and user-safe programs.

⸻

1. Safe Calculator
	•	Normal calculator with + - * /.
	•	Division by zero is caught with ZeroDivisionError.
	•	Invalid inputs (like letters instead of numbers) are handled with ValueError.

⸻

2. Safe File Reader
	•	Asks for a filename.
	•	If the file doesn’t exist, catches FileNotFoundError and warns the user.
	•	Prevents program crashes.

⸻

3. Valid Integer Input
	•	Keeps asking until user enters a valid integer.
	•	Uses a loop + try-except to re-prompt on invalid input.

⸻

4. Mini Project: Safe Banking System
	•	Simulates a bank account with starting balance = 1000.
	•	Options:
	•	Deposit → must be positive number.
	•	Withdraw → must be positive and ≤ balance.
	•	Exit → ends program and shows final balance.
	•	Handles:
	•	Invalid numbers (ValueError).
	•	Negative or zero amounts.
	•	Overdrawing account.

⸻

5. Main Menu
	•	Lets user run any of the four programs.
	•	Loops until Exit chosen.
