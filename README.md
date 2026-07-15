# GitHub Profile README Guide

This guide explains how to create and customize a GitHub profile README.

---

# Step 1: Create the Special Repository

Create a new repository with **exactly the same name as your GitHub username**.

Example:

```
Username: johndoe
Repository: johndoe
```

Requirements:

- Public repository
- Initialize with a README.md

GitHub will automatically detect this repository and display its README on your profile.

---

# Step 2: Edit README.md

Open the repository and edit the `README.md` file.

GitHub Profile READMEs support:

- Markdown
- HTML
- Emojis
- Images
- SVG
- GIFs
- Links
- Tables

HTML can also be mixed with Markdown.

---

# Step 3: Add an Introduction

Example:

```md
# Hi 👋 I'm John Doe
```

You can also include:

- Current job
- What you're learning
- Contact email
- Pronouns
- Location

Example:

```md
- 🔭 Working on Front-End Development
- 🌱 Learning TypeScript
- 📫 Email: example@email.com
- 😄 Pronouns: He/Him
```

---

# Step 4: Preview Frequently

Use GitHub's **Preview** tab while editing to see how the profile looks before saving.

---

# Step 5: Add GitHub Stats

Use GitHub Readme Stats.

Features include:

- Total commits
- Stars
- Repositories
- Languages
- Rank

Important:

Replace the username parameter.

Example:

```
username=YOUR_USERNAME
```

Do NOT leave someone else's username.

Example:

```text
https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME
```

Options shown in the video:

- theme=
- show_icons=true
- height=
- username=

Themes can be changed.

Examples:

- Dracula
- Radical
- Dark
- Others

---

# Step 6: Customize GitHub Stats

The speaker demonstrates changing URL parameters such as:

```
show_icons=true
theme=dracula
theme=radical
username=YOUR_USERNAME
```

Different themes completely change the appearance.

---

# Step 7: Add Programming Language Icons

Add icons representing technologies you use.

Examples:

- HTML
- CSS
- JavaScript
- TypeScript
- React
- Node.js
- Java
- Python

The speaker recommends using Devicon icons.

---

# Step 8: Add Social Media Badges

Create clickable badges linking to your profiles.

Examples:

- YouTube
- Instagram
- Twitter/X
- LinkedIn
- Discord
- Gmail
- WhatsApp
- Telegram

Each badge consists of:

- Link
- Image
- Alt text

Example structure:

```html
<a href="YOUR_LINK">
    <img src="BADGE_IMAGE">
</a>
```

---

# Step 9: Add Personal GIF

The profile can include an animated GIF.

Process:

1. Create or download a GIF.
2. Upload it somewhere accessible.
3. Copy its direct URL.
4. Embed it using an image tag.

---

# Step 10: Add Contribution Snake Animation

The speaker also adds the animated snake.

Requirements:

- GitHub Actions
- Workflow
- SVG generation

This cannot be done by simply copying the image.

It requires:

- GitHub Actions
- Workflow configuration
- Automatic regeneration after every commit

---

# Step 11: Enable Private Contributions

GitHub Settings →

```
Contribution settings
```

Enable:

```
Include private contributions
```

This allows private repository commits to appear in contribution statistics.

---

# Step 12: Personalize Everything

The speaker repeatedly reminds viewers to replace copied values.

Always replace:

- Username
- Links
- Email
- Social profiles
- Images
- GIF
- Stats username

Never leave someone else's information.

---

# Step 13: Experiment

The README can contain almost anything.

Ideas include:

- Headers
- Images
- GIFs
- Tables
- HTML layouts
- Badges
- Shields
- Tech stack
- Statistics
- Contribution graph
- Social links
- Visitor counter
- Quotes
- Widgets

---

# Useful Resources Mentioned

- GitHub Readme Stats
- Devicon
- Shields.io
- Emoji picker
- GitHub Actions
- Markdown Guide

---

# Final Profile Structure

```text
README.md

├── Greeting
├── About Me
├── Current Work
├── Learning
├── Contact
├── GitHub Stats
├── Top Languages
├── Tech Stack Icons
├── Social Badges
├── GIF
├── Snake Contribution Animation
└── Additional Widgets
```

---

# Checklist

- [ ] Create username repository
- [ ] Initialize README
- [ ] Write introduction
- [ ] Add personal information
- [ ] Add GitHub stats
- [ ] Configure themes
- [ ] Add language icons
- [ ] Add social badges
- [ ] Add GIF
- [ ] Configure snake animation
- [ ] Enable private contributions
- [ ] Preview profile
- [ ] Commit changes
- [ ] Continue customizing
