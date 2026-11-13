# Host a Static Website Using GitHub Pages

## Project Overview
This project demonstrates how to create and deploy a static website using HTML, CSS, Git, GitHub, and GitHub Pages.

The website is hosted publicly using GitHub Pages and is accessible through a live URL.

## Objective
To create a simple static website using HTML and CSS and publish it online using GitHub Pages.

## Technologies Used
- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages
- AWS EC2 (Amazon Linux)

## Project Structure

```text
live-website-link/
│
├── index.html
├── style.css
└── README.md
```

## Website Features
- Simple and responsive website layout
- Welcome section
- About Me section
- Customized styling using CSS
- Public hosting through GitHub Pages

## Implementation Steps

1. Launched an AWS EC2 instance using Amazon Linux.
2. Updated the system and installed Git.
3. Created a project directory.
4. Initialized a Git repository using `git init`.
5. Created the `index.html` file.
6. Added website styling using `style.css`.
7. Added and committed project files using Git.
8. Created a GitHub repository named `live-website-link`.
9. Connected the local repository to GitHub.
10. Pushed the project files to GitHub.
11. Enabled GitHub Pages using the `main` branch and root folder.
12. Verified the published website using the live URL.

## Git Commands Used

```bash
git init
git add .
git commit -m "Add static website using HTML and CSS"
git branch -M main
git remote add origin https://github.com/Mithula7777/live-website-link.git
git push -u origin main
```

## Project Links

**GitHub Repository:**

https://github.com/Mithula7777/live-website-link

**Live Website:**

https://mithula7777.github.io/live-website-link/

## Expected Output

The website displays:
- Welcome to My Website!
- About Me section
- Introduction about learning DevOps and Cloud Computing.

## Learning Outcomes

- Learned how to create a static website using HTML and CSS.
- Practiced Git version control.
- Learned how to push project files to GitHub.
- Understood GitHub Pages configuration and deployment.
- Successfully hosted a static website publicly.

## Conclusion

Successfully created and deployed a static website using GitHub Pages. This project provided practical experience with HTML, CSS, Git, GitHub, and static website hosting.
