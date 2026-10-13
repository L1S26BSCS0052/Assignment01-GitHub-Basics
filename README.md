# Assignment01-GitHub-Basics
Assignment 01 - Getting started with GitHub


## Task 1 — Create Your GitHub Account [2 Marks]

Sign up at `github.com/signup`. Your username must be your UCP registration number, written exactly as on your student card.

**Example:**
- **Username:** `L1F24BSCS0081`
- **Profile:** `https://github.com/L1F24BSCS0081`

1. Do **NOT** add your name, extra hyphens, underscores or any other characters.
2. Complete the puzzle and the email verification code step.
3. If GitHub says your registration number is already taken, inform the instructor — do not invent a different username.

## Task 2 — Create a Repository [1 Mark]

Create a new repository with the following settings:

| Setting | Required value |
|---|---|
| Repository name | `Assignment01-GitHub-Basics` |
| Description | `Assignment 01 - Getting started with GitHub` |
| Visibility | **Public** |
| Add README | **ON** — this creates Commit #1 automatically |

## Task 3 — Upload Your C++ Program [2 Marks]

Write a C++ program that calculates the sum of the first 50 natural numbers, then upload it to your repository using **Add file → Upload files**.

**File name (must be exactly):**

`sum_of_first_50_natural_numbers.cpp`

1. The first version you upload should contain only the loop that calculates the sum and prints it.
2. The file must compile and run without errors.
3. Commit message for this upload:

`Add C++ program to find sum of first 50 natural numbers`

**Sample Run:**

```text
Sum of first 50 natural numbers (loop): 1275
```

## Task 4 — Make At Least 5 Meaningful Commits [3 Marks]

Improve your work in small steps. Each improvement must be saved as a separate commit using the **Edit** button and **Commit changes**. Your history must contain at least these 5 commits:

| Commit | Message / Change |
|---|---|
| 1 | **Initial commit** — README, automatic |
| 2 | **Add C++ program to find sum of first 50 natural numbers** |
| 3 | **Add header comments with name and reg no** |
| 4 | **Add formula-based verification n(n+1)/2** |
| 5 | **Update README with program description and output** |

### Commit 3

Add a comment block at the top of the `.cpp` file with:
- Program title
- Your name
- Your registration number
- Assignment number

### Commit 4

Add a second calculation using the formula `n(n+1)/2` and print it, so both methods show `1275`.
