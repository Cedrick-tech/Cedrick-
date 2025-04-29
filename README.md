# Introduction to GitHub

_Get started using GitHub in less than an hour._

## Welcome

People use GitHub to build some of the most advanced technologies in the world. Whether you’re visualizing data or building a new game, there’s a whole community and set of tools on GitHub that can help you do it even better. GitHub Skills’ “Introduction to GitHub” exercise guides you through everything you need to start contributing in less than an hour.

- **Who is this for**: New developers, new GitHub users, and students.
- **What you'll learn**: We'll introduce repositories, branches, commits, and pull requests.
- **What you'll build**: We'll make a short Markdown file you can use as your [profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme).
- **Prerequisites**: None. This exercise is a great introduction for your first day on GitHub.
- **How long**: This exercise takes less than one hour to complete.

In this exercise, you will:

1. Create a branch
2. Commit a file
3. Open a pull request
4. Merge your pull request

### How to start this exercise

1. Right-click **EF-PRIME;;;eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoic0pkWnlSbi9hQmlhTjlIZHhZcDdpend5bGxyeng5UjJVeFZoNDRPam9Ydz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiaHArMTdZbWFsOW5ERzc2c1UrWVh1bmRLdURVT09BUnZ0VWU3T25TVmkwaz0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJrS3Mra0lFbE9JWHRsT0pVL2tkdStYSnVzVGxLbk11T0VZTWNNMFF1UjNVPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJZTlNMdnRDVkRiaVhPbDNjRjFxOFZFb25vaTJzdmZUTG5sR3FqV1BqSlVjPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6ImNEd0tCZ1FWNTM2NVR0Z2dIZllkMzV5UHNoOHVldGxsSm1Tbi8wU1dRSGs9In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkRoc0JVRkswVHJrRm92UHhFZXdQL1lIUHVEWmJoeTBnR1lEcFhQbXNPSGs9In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiMkQ2THplTUtkRzlXYmNCUFdocENiSXEyZGFLN0pEcWZtZDJlWnB6V0xsWT0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoianJvT20zSjhVSi9LZzlOYi90KzRWU1lsYk1CMHNoY0tqSkkyemhvUHdoWT0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IlVEK2FLdFZUTnhhcVFRM1F6VjZDYUxDL1ZZdjFTSVExZE9sRFBPR1lLc1hiakVhTHhvN2VZd0xCN0ltZ3p1eFZTZ3JsSWJZUzhjV0RtNk5kRjNUSkN3PT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MTIyLCJhZHZTZWNyZXRLZXkiOiJDZTI5Y0FKQTg0U3hXUkR1RVZHY0FyWFJ4VWo5c0toR0Q0eHdUTFdwTnhjPSIsInByb2Nlc3NlZEhpc3RvcnlNZXNzYWdlcyI6W10sIm5leHRQcmVLZXlJZCI6MzEsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjozMSwiYWNjb3VudFN5bmNDb3VudGVyIjowLCJhY2NvdW50U2V0dGluZ3MiOnsidW5hcmNoaXZlQ2hhdHMiOmZhbHNlfSwiZGV2aWNlSWQiOiJiSUZtelZ0bVRCMlJsSWpyTmItUXRRIiwicGhvbmVJZCI6ImVhODhiZTA0LTJjNmQtNDJhNy04YzBkLTNiZjFkMjM0ZmU1MCIsImlkZW50aXR5SWQiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJhb2k5cktmWWpHbWpWM1JnV0lWT2lQZk9HOFE9In0sInJlZ2lzdGVyZWQiOnRydWUsImJhY2t1cFRva2VuIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoic2hoakk2eUlHZUk5NkZmbUVKU0FSY29HVUlJPSJ9LCJyZWdpc3RyYXRpb24iOnt9LCJwYWlyaW5nQ29kZSI6IkRYN0cxUloxIiwibWUiOnsiaWQiOiIyNTY3NDYzNjg3NTc6NkBzLndoYXRzYXBwLm5ldCJ9LCJhY2NvdW50Ijp7ImRldGFpbHMiOiJDTmZ2NTdNR0VLMm54TUFHR0FJZ0FDZ0EiLCJhY2NvdW50U2lnbmF0dXJlS2V5IjoiVUxKTE04N1kzTExQZGlPbjA2Z2JlQ1VFa0xzREhPMFNmTWgvUEhOUnZ3QT0iLCJhY2NvdW50U2lnbmF0dXJlIjoiZlJMOHNaSGJuVU0wemg1V2JTS3diSG0zWmRUQytad1Y1aXFDZWE5Z3pMUHJxNFNNcThRNTZndFV0STlkUGZVRWFWdmhmTStrbVpkZ3ZmNGg3UGR6RHc9PSIsImRldmljZVNpZ25hdHVyZSI6InJFaFUyNEg3VllVbnpvVllSOS9rOWd6YVpEZ0NxK2JNTXROTnFUNFFNZ3VMcmUyb1VPcDUwYVhWTWFDQ0d6YTE3UDlXSVpJT3VTeE9WbjlnRkJCNkJ3PT0ifSwic2lnbmFsSWRlbnRpdGllcyI6W3siaWRlbnRpZmllciI6eyJuYW1lIjoiMjU2NzQ2MzY4NzU3OjZAcy53aGF0c2FwcC5uZXQiLCJkZXZpY2VJZCI6MH0sImlkZW50aWZpZXJLZXkiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJCVkN5U3pQTzJOeXl6M1lqcDlPb0czZ2xCSkM3QXh6dEVueklmenh6VWI4QSJ9fV0sInBsYXRmb3JtIjoiYW5kcm9pZCIsImxhc3RBY2NvdW50U3luY1RpbWVzdGFtcCI6MTc0NTk0OTYyNiwibXlBcHBTdGF0ZUtleUlkIjoiQUFBQUFKcG8ifQ==![Uploading prime.jpg…]()
** and open the link in a new tab.

   <a id="copy-exercise">
      <img src="https://img.shields.io/badge/📠_Copy_Exercise-AAA" height="25pt"/>
   </a>

2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.chttps://github.com/Cedrick-tech/Cedrick-/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.

3. After your new repository is created, wait about 20 seconds for the exercise to be prepared and buttons updated. You will continue working from your copy of the exercise.
   - The **Copy Exercise** button will deactivate, changing to gray.
   - The **Start Exercise** button will activate, changing to green.
   - You will likely need to refresh the page.

4. Click **Start Exercise**. Follow the step-by-step instructions and feedback will be provided as you progress.

   <a id="start-exercise" href="https://github.com/Cedrick-tech/Cedrick-/issues/1">
      <img src="https://img.shields.io/badge/🚀_Start_Exercise-008000" height="25pt"/>
   </a>

> [!IMPORTANT]
> The **Start Exercise** button will activate after copying the repository. You will probably need to refresh the page.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
