# Loan payment and credit risk project

The loan-risk-project folder contains the final Python program and its full Git history. All three versions were run successfully. The three commits use the exact messages requested in the assignment. Commits were created by Codex; they are attributed to Codex rather than to an unverified student identity.

## Completed

- Version 1 calculates the monthly payment.
- Version 2 adds total interest paid.
- Version 3 adds the debt-to-income ratio and the assignment's risk classification.
- All three versions are recorded as separate Git commits on the main branch.
- The working directory is clean.

## Remaining submission step

The repository still needs to be pushed to your GitHub account. Keep the extracted folder intact so its Git history is preserved. Uploading only the Python file through the GitHub website will not transfer the required three commits.

Create an empty GitHub repository named loan-risk-project without a README, license, or .gitignore. Open a terminal inside the extracted loan-risk-project folder. Run the exact `git remote add origin ...` command GitHub supplies for your repository, then:

```sh
git remote -v
git push -u origin main
```

Complete GitHub authentication if prompted. Submit the repository link after confirming that loan_calculator.py appears and the history contains three commits.

## Inspect or run the project

```sh
git log --oneline
git status
```

On macOS run `python3 loan_calculator.py`. On Windows run `python loan_calculator.py` or `py loan_calculator.py` if you use the Python launcher. Git is needed to push; Python is needed only to run the calculator.

## What the results mean

The assignment uses a $20,000 loan at 6 percent annual interest over 60 monthly payments. The monthly payment is $386.66. Total interest is $3,199.36, calculated with the unrounded monthly payment before displaying cents.

The DTI calculation adds the new loan payment to $900 of other monthly debt, then divides by $4,000 of monthly income. This gives 32.17 percent. Under the assignment's illustrative rules, below 36 percent is Lower Risk, 36 percent to below 50 percent is Moderate Risk, and 50 percent or more is Higher Risk. This is the lab's simplified classification.

Git records each saved snapshot as a commit. GitHub stores the repository online after a push. See RESULTS.txt for the verified output and commit identifiers.
