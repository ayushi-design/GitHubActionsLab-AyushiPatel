Student Name: Ayushi Patel
Student ID: 991752412

GitHub Actions Lab

Purpose of Workflows
Workflow 1: Dependent Jobs

This workflow shows a simple CI/CD flow where tasks run one after another:
Build → Test → Deploy

Each step depends on the previous one, so nothing moves forward unless the earlier job is successful.

Workflow 2: Multi-Platform Testing

This workflow runs the same process on different operating systems at the same time:

Ubuntu
Windows
macOS

It helps make sure the application works across all platforms.

Key Concepts
needs → Used to control the order of jobs (Workflow 1 runs step by step)
runs-on → Chooses which operating system the job runs on
env → Used to store environment variables for workflows or jobs
Challenges & Fixes
The workflow didn’t run at first because the file wasn’t in the correct .github/workflows folder. Fixed by placing it correctly and pushing again.
Windows commands were slightly different, so PowerShell commands were used instead.
It was confusing at first to understand parallel vs sequential jobs, but testing helped clarify it.
Conclusion

This lab helped me understand how GitHub Actions works for automation. It showed how workflows can run step-by-step or in parallel depending on how they are configured.
