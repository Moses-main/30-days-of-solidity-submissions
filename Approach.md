✅ Steps to Clone, Create a Branch, Push, and Create a PR (without Forking):

1. **Clone the repository**:

   ```bash
   git clone https://github.com/The-Web3-Compass/30-days-of-solidity-submissions.git
   cd 30-days-of-solidity-submissions.git
   ```

2. **Make your changes** locally (edit files, add features, etc.)

3. **Stage and commit your changes**:

   ```bash
   git add .
   git commit -m "Day01 - Submission by @github_username"
   ```

5. **Push the branch to the origin (same repository)**:

   ```bash
   git push
   ```

6. **Go to GitHub** in your browser:

   * Navigate to the original repository [(`https://github.com/The-Compass/30-days-of-solidity`)](https://github.com/The-Web3-Compass/30-days-of-solidity-submissions)
   * GitHub will detect your recently pushed branch and show a “Compare & pull request” button.
   * Click it to open a new Pull Request.

7. **Fill out PR details**:

   * Title, description, what it fixes, how to test it, etc.
   * Choose the base branch you want to merge into (e.g., `main`, `develop`) and ensure your feature branch is selected as the compare branch.

8. **Submit the pull request**.

---

### 🧠 Important Notes:

* **You must have write/push access** to the repo; otherwise, GitHub will reject your `git push` to origin.
* If you **don’t have write access**, then the **only way** to contribute is:

  * Fork the repository.
  * Push to your fork.
  * Create a PR **from your fork to the original repo**.
