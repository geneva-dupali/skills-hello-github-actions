# Hello GitHub Actions

_Create and run a GitHub Actions workflow._

## Welcome

Automation is key for repetitive tasks like testing, scanning, review, and deployment processes, and [GitHub Actions](https://docs.github.com/actions) is the best way to streamline that workflow.

- **Who is this for**: Developers, DevOps engineers, Security engineers
- **What you'll learn**: How to create GitHub Actions workflows, how to run them, and how to use them to automate tasks.
- **What you'll build**: An Actions workflow that will comment on a pull request when it is created.
- **Prerequisites**: [Introduction to GitHub](https://github.com/skills/introduction-to-github)
- **How long**: This exercise can be finished in less than 30min.

In this exercise, you will:

1. Create a workflow file
1. Add a job
1. Add a run step
1. See the workflow run
1. Merge your pull request

### How to start this exercise

Simply copy the exercise to your account, then give your favorite Octocat (Mona) **about 20 seconds** to prepare the first lesson, then **refresh the page**.

[![](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=skills&template_name=hello-github-actions&owner=%40me&name=skills-hello-github-actions&description=Exercise:+Create+and+run+a+GitHub+Actions+Workflow&visibility=public)

### Quick guide: complete the activity step by step

1. Copy this template to your GitHub account using the **Copy Exercise** button above.
1. Wait about 20 seconds, then refresh the repository page.
1. Open the first issue created by Mona and follow each step in order.
1. Create branch `welcome-workflow`, then create `.github/workflows/welcome.yml`.
1. Update the workflow in that same file by adding:
   - the `jobs` section
   - a `welcome` job on `ubuntu-latest`
   - a step that comments on newly opened pull requests
1. Open a pull request from `welcome-workflow` into `main` to trigger the workflow.
1. Confirm the workflow passes, then merge the pull request to finish.

<details>
<summary>Having trouble? 🤷</summary><br/>

When copying the exercise, we recommend the following settings:

- For owner, choose your personal account or an organization to host the repository.

- We recommend creating a public repository, since private repositories will use Actions minutes.

If the exercise isn't ready in 20 seconds, please check the [Actions](../../actions) tab.

- Check to see if a job is running. Sometimes it simply takes a bit longer.

- If the page shows a failed job, please submit an issue. Nice, you found a bug! 🐛

</details>

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
