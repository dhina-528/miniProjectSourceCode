# Transaction Processing System

## Overview

This project is a Transaction Processing System that manages bank account data. It allows users to perform various operations on account records stored in a binary file (`credit.dat`).

## Features

1. **List All Accounts**: Display all account details in a tabular format.
2. **Search for an Account**: Find an account by account number.
3. **Export to CSV**: Export account data to a CSV file for external use.
4. **Sort Accounts**: Sort accounts by account number.
5. **Account Summary**: View a summary of all accounts, including total and average balances.
6. **Create a Text File**: Generate a text file from the binary file.
7. **Update an Account**: Modify details of an existing account.
8. **Add a New Account**: Add a new account to the system.
9. **Delete an Account**: Remove an account from the system.

## Compilation

To compile the program, use the following command:

```bash
gcc trans.c -o trans
```

## Running the Program

Run the compiled program using:

```bash
./trans
```

## Usage Instructions

1. Follow the on-screen menu to perform operations.
2. Input the required details when prompted.

## Edge Cases to Test

- Empty `credit.dat` file.
- Duplicate account numbers.
- Large numbers of accounts.
- Invalid user inputs (e.g., non-numeric values for account numbers).

## Preparing for Submission

1. Ensure the program is well-tested.
2. Package the following files:
   - `trans.c`
   - `README.md`
   - `credit.dat` (if applicable)
   - Any other necessary files.
3. Submit the package as per the project guidelines.

## References

- [Markdownlint Documentation](https://github.com/DavidAnson/markdownlint)
- [Markdown Syntax Guide](https://www.markdownguide.org/basic-syntax/)

---

## Objective

This mini project focuses on understanding, modifying, and extending a **Transaction Processing System** program. Students are expected to analyze existing code, improve it, and add new functionalities while following good coding practices.

---

## Reference Code

Review the given source code before starting the project:

🔗 [Replit Source Code](https://replit.com/@ashokb/Unit5Programs#trans.c)

---

## Tasks to be Performed

1. Compile and run the given executable code.
2. Perform your own testing of the program.
3. Add a new account detail and regenerate the `accounts.txt` file.
   - Inspect the contents of the file.
   - Verify whether the output matches your expectations.
4. Identify and fix any logical errors in the program.
5. Add new functionality  
   - Example: Listing all account information.
6. Optimize the program for better performance and efficiency.

---

## Evaluation Criteria

### 1. General (25 Points)

| Activity       | Points | Remarks                                                                 |
|----------------|--------|-------------------------------------------------------------------------|
| Self-effort    | 5      | Student’s own assessment of hours spent (no copying or external references) |
| Turnaround Time| 10     | Provide three time slots; earlier demo gets more points                 |
| Project Demo   | 10     | Demo must be done using repl.it                                        |

---

### 2. Comprehension (15 Points)

| Activity              | Points |
|-----------------------|--------|
| Domain Knowledge      | 5      |
| Added Functionality (Ideas) | 5 |
| Code Comprehension    | 5      |

---

### 3. Modification (35 Points)

| Activity              | Points |
|-----------------------|--------|
| Code Improvement      | 5      |
| Functional Decomposition | 10   |
| Refactoring for Memory Usage | 10 |
| Refactoring for Speed  | 10     |

---

### 4. Innovation (45 Points)

| Activity              | Points |
|-----------------------|--------|
| New Features / User Stories (Faculty specified) | 5 |
| Requirement to Code Translation | 10 |
| Added Functionality (Simple – Error Handling) | 10 |
| Added Functionality (Advanced) | 20 |

---

## Total Marks

**120 Marks**  
➡ Reduced to **20 Marks** for final evaluation

---

## Rules for Mini Project Implementation

- Maximum of **2 attempts** will be given for project presentation.
- If dissatisfied with the first score, a second attempt is allowed.
- The **best score** out of the two attempts will be considered final.
- Discussion and clarification among students are allowed.
- **Copying or borrowing code is strictly prohibited.**
- Violation of plagiarism rules will result in a **zero (0 / NULL) score**.

---

## Additional Reference

🔗 [Transaction Unit 5](http://j.mp/transactionUnit5)  
🔗 [HTML Preview](https://htmlpreview.github.io/?https://github.com/kgisl/makesite/blob/master/content/blog/2021-06-23-unit5-mini-project.md.html)  
🔗 [GitHub Repository](https://github.com/24UCS271-MiniProject/miniProjectSourceCode/)
