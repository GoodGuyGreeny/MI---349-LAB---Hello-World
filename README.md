# Ms. Direction Website

This project is a semantic, HTML-only landing page for **Ms. Direction**, a student
first-person 3D puzzle game set inside the unsettling corporate offices of FOLLOW INC.
The page introduces the game’s premise, departments, gameplay features, and development
process in the voice of a slightly untrustworthy corporate welcome message.

## Technologies

- HTML5 semantic elements
- Unity and C# for the game
- Blender for low-poly 3D assets
- Photoshop for textures and visual assets
- GitHub for version control and collaboration

The landing page intentionally uses no CSS, JavaScript, frameworks, or external dependencies.
Its organization comes from headings, paragraphs, lists, links, horizontal rules, and semantic
HTML structure.

## Features

- Game title and tagline
- Satirical welcome message from FOLLOW INC.
- Overview of the game premise and puzzle-solving approach
- Key gameplay features
- Introductions to Human Resources, Accounting, Marketing, Operations, and the Executive Floor
- Development process and technology list
- Link to the actual Ms. Direction game repository
- Responsive viewport metadata and descriptive page metadata

## View Locally

1. Clone or download this repository.
2. Open `index.html` in a web browser.

No build tools or local server are required for this static page. In VS Code, you can also
right-click `index.html` and choose **Reveal in File Explorer**, then open the file in your browser.

## Game Repository

The game project is maintained separately at:

https://github.com/GoodGuyGreeny/Ms-Direction-

## Publish to GitHub

Create an empty GitHub repository, then run these commands from this project folder:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the placeholder repository URL with the URL for the website repository. The existing
commit history can be pushed as-is.

## Deploy with Netlify

1. Sign in at [Netlify](https://www.netlify.com/).
2. Choose **Add new site** and **Import an existing project**.
3. Connect the GitHub repository containing this website.
4. Leave the build command empty because the site is plain HTML.
5. Set the publish directory to the repository root (`.`).
6. Choose **Deploy site**.

Netlify will publish `index.html` as the site’s homepage and can automatically redeploy when
new commits are pushed.