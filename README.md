# GitHub Organization Access Request - Pihow Services

Welcome to the **Pihow Services** GitHub access repository. This repository allows new and existing employees to request access to the organization's GitHub resources.

🔗 **Pihow Services GitHub Organization:** [https://github.com/Pihow-Services](https://github.com/Pihow-Services)

## How to Request Access

To get added to the organization, please follow these steps carefully:

1.  **Fork this repository** to your personal GitHub account.
2.  **Clone your fork** locally:
    ```bash
    git clone https://github.com/YOUR_USERNAME/giyhub-access.git
    ```
3.  **Create a new branch** for your request (e.g., `feature/john-doe-access`):
    ```bash
    git checkout -b feature/your-name-access
    ```
4.  **Create your request file**:
    - Navigate to the `requests/` directory.
    - Copy the `requests/TEMPLATE.md` file.
    - Rename it to `YOUR_GITHUB_USERNAME.md` (e.g., `octocat.md`).
    - Fill in the required details inside the file.
5.  **Commit and Push**:
    ```bash
    git add requests/YOUR_GITHUB_USERNAME.md
    git commit -m "Request access for @YOUR_GITHUB_USERNAME"
    git push origin feature/your-name-access
    ```
6.  **Open a Pull Request (PR)** against the `main` branch of this repository.

## What Happens Next?

- An administrator will review your PR.
- Once approved, you will receive an invitation to join the Pihow Services GitHub organization via email.
- After you accept the invitation, your PR will be merged/closed.

## Troubleshooting

If you have any issues, please contact the IT support team or reach out on the internal communication channel.
