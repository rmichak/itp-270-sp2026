# Exam 1 Practice Test 2: Python Fundamentals

**Time Limit:** 90 minutes\
\
**Total Points:** 100\
\
**Format:** Timed test (single attempt)

## Instructions

1. Read each problem carefully.

2. Write Python code that solves each problem.

3. Test your code in the Python interpreter.

4. Submit your code file when finished.

***

## Problems

### Problem 1: Password Strength Checker (20 points)

Write a program that asks the user to enter a password and reports whether it is **Weak**, **Moderate**, or **Strong** based on its length.

* Less than 8 characters: Weak

* 8–11 characters: Moderate

* 12 or more characters: Strong

**Example:**

```text
Enter password: abc123
Strength: Weak

Enter password: secure99
Strength: Moderate

Enter password: MyP@ssword123
Strength: Strong
```

***

### Problem 2: Login Attempt Counter (20 points)

Write a program that simulates a login system. The correct password is `"cyber2026"`. Allow the user up to 3 attempts to enter the correct password. Display a success message if they get it right, or a lockout message after 3 failed attempts.

**Example (success on attempt 2):**

```text
Enter password: wrongpass
Incorrect. Attempts remaining: 2
Enter password: cyber2026
Access granted!
```

**Example (lockout):**

```text
Enter password: abc
Incorrect. Attempts remaining: 2
Enter password: 123
Incorrect. Attempts remaining: 1
Enter password: test
Incorrect. Attempts remaining: 0
Account locked.
```

***

### Problem 3: IP Address List (20 points)

Write a program that:

1. Creates a list of 5 IP addresses (as strings)

2. Displays the total number of addresses in the list

3. Displays the first and last address in the list

4. Displays all addresses using a loop

**Example:**

```text
IP Addresses: ['192.168.1.1', '10.0.0.1', '172.16.0.1', '8.8.8.8', '1.1.1.1']
Total: 5
First: 192.168.1.1
Last: 1.1.1.1

Listing all addresses:
192.168.1.1
10.0.0.1
172.16.0.1
8.8.8.8
1.1.1.1
```

***

### Problem 4: Port Scanner Lookup (20 points)

Write a program that:

1. Creates a dictionary mapping 5 common port numbers (as integers) to their service names

2. Asks the user to enter a port number

3. Displays the service name if found, or "Unknown service" if not

**Example:**

```text
Enter port number: 80
Service: HTTP

Enter port number: 9999
Service: Unknown service
```

***

### Problem 5: Caesar Cipher (20 points)

Write a program that asks the user to enter a word and a shift value, then displays the word with each letter shifted forward by that many positions in the alphabet. Only shift letters — leave other characters unchanged. You may assume lowercase input.

**Example:**

```text
Enter a word: hello
Enter shift: 3
Encoded: khoor

Enter a word: xyz
Enter shift: 2
Encoded: zab
```

*Hint: Use `ord()` and `chr()` to work with character codes. The letter `'a'` has an ASCII value of 97.*

***

## Submission

Submit your completed code file before time expires.
