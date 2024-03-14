<header>

<!--
  <<< Author notes: Course header >>>
<<<<<<< HEAD
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Hello GitHub Actions

_Create a GitHub Action and use it in a workflow._
=======
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Introduction to secret scanning

_GitHub scans repositories for known types of secrets, to prevent fraudulent use of secrets that were committed accidentally. In this GitHub Skills course you will learn how to enable secret scanning to identify serets and prevent them from being committed to your repository._
>>>>>>> 86beacd (Initial commit)

</header>

<!--
<<<<<<< HEAD
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
  TBD-step-1-notes.
-->

## Step 1: Enable Secret Scanning

_Welcome to "Introduction to Secret Scanning"! :wave:_

In this step, you will enable secret scanning on this repository. Once secret scanning is enabled, you will add a new credential to see how secret scanning identifies the credential.

**What is a secret**: In the context of secret scanning, a secret (or credential) is a plain-text string that authorizes a user to any number of third-party services. Examples could be AWS secret access keys/ID's, Google API keys, or Stripe API tokens. GitHub Docs hosts the [entire list of supported patterns](https://docs.github.com/en/code-security/secret-scanning/secret-scanning-patterns#supported-secrets).

### :keyboard: Activity 1.1: Enable secret scanning

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
2. In your newly created repository, select **Settings** from the top navigation bar.
3. Under the **Security** section on the left side, select **Code security and analysis**.
4. Scroll to the bottom of this page and select the **Enable** button next to "Secret scanning"

> [!IMPORTANT]
> When you enable secret scanning, you may receive an email notification about credentials in your repository. Don't worry! The tokens in this Skills repo are inactive. There is no risk to your environment.

### :keyboard: Activity 1.2: Commit a token

Now that you have secret scanning enabled in this repository, let's commit a new token to see how it works. You'll commit an AWS key and access ID to the repository. Don't worry, this is an inactive token that can't be used to log in to AWS.

1. Like the first activity, you will need to work on these steps in a second browser tab.
2. Click the Code tab in your repository.
3. Select the `credentials.yml` file.
4. Click the Edit button to the right.

    ![A screenshot of credentials.yml on the GitHub web interface with the edit button outlined](/images/edit-credentials-file.png)

5. Copy the following text and paste it to the bottom of the `credentials.yml` file.

    ```yaml
    default:
      aws_access_key_id: AKIAQYLPMN5HNM4OZ56B
      aws_secret_access_key: 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
      output: json
      region: us-east-2
    ```

6. Click **Commit changes...** from the top right. The "Propose changes" window will pop up. Leave the defaults configured, and click **Commit changes** again.
7. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
=======
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

## Finish 🏆

_Congratulations friend, you've completed this course!_ 

Here's a recap of all the tasks you've accomplished in your repository:

- Enabled secret scanning on your repository
- Committed a secret to the repository
- Reviewed secrets that have been identified by secret scanning
- Closed a secret scanning alert
- Enabled secret scanning push protection to prevent secrets from being written to the repository
- Attempted to commit a secret, but had that commit stopped by push protection
- Bypassed the push protection

It's important to note that secret scanning capabilities are available for free for all public repositories. Customers needing secret scanning for private repos should investigate [GitHub Advanced Security](https://docs.github.com/en/enterprise-cloud@latest/get-started/learning-about-github/about-github-advanced-security). In addition to the features you worked with here, Advanced Security also provides the following features:

-  Custom secret scanning patterns
-  Non-partner and generic patterns including passwords, RSA and SSH keys, and database connection strings
-  Code scanning with CodeQL
-  Security Overview
-  Supply chain security capabilities

### What's next?

- [We'd love to hear what you thought of this course](TBD-feedback-link).
- [Take another Skills Course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).
>>>>>>> 78ffb61 (Update to X in STEP and README.md)

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

<<<<<<< HEAD
Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/hello-github-actions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)
=======
Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-secret-scanning) &bull; [Review the GitHub status page](https://www.githubstatus.com/)
>>>>>>> 86beacd (Initial commit)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
