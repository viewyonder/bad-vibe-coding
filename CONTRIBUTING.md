# Contributing to Bad Vibe Coding

Thank you for contributing to Bad Vibe Coding! This repo collects stories about when vibe coding goes wrong. Share your coding disasters, bugs, and lessons learned.

### Quick Overview

* **Contributors** Fork the repo, create a branch in your fork, add your story, push to your fork, and submit a PR to this repo.
* **Story Format** Use stories/story-XXX.md (e.g., story-001.md) with the provided template. Place images in images/ with names like story-XXX-image1.png.
* **Review** Maintainers review your PR, may request changes, and merge it into the main repo.

## How to create your story

We use markdown for our stories. Each story is a standalone markdown file with its images in a central /images directory with all other images.

You need a tool like VScode or Dillinger (many others).

Before submitting your story, preview it to ensure formatting and images look correct.

### Option 1: Visual Studio Code (Local Editor)

* Download and install Visual Studio Code.
* Open the bad-vibe-coding folder in VS Code.
* Create or open your stories/story-XXX.md file.
* Click the “Preview” button (magnifying glass) or press Ctrl+Shift+V (Windows/Linux) or Cmd+Shift+V (macOS) to see a live preview.
* Add images to the images/ folder and use relative paths (e.g., ![Alt text](images/story-XXX-image1.png)). They’ll show in the preview if paths are correct.

### Option 2: Pick a Markdown editor from this list

[Awesome Markdown Editors & (Pre)viewers](https://github.com/mundimark/awesome-markdown-editors)

## How to Contribute

For contributors without write access to the main repo.

### 1. Fork the repository

Click the "Fork" button on the bad-vibe-coding GitHub page to create a copy under your GitHub account.

### 2. Clone your fork

Clone your fork to your local machine:


```
git clone https://github.com/your-username/bad-vibe-coding.git
cd bad-vibe-coding
```

### 3. Create a Branch and add your story

Create a new branch for your story. Use a descriptive name, like add-story-yourname or story-001:


```
git checkout -b add-story-yourname
```

### 4. Add your own story.

Create a new Markdown file in the stories/ directory, named story-XXX.md (replace XXX with the next sequential number, e.g., story-001.md).

Follow the Story Format below.

If including images, place them in the images/ directory with names like story-XXX-image1.png. Reference images in your Markdown file using relative paths (e.g., ![Alt text](images/story-XXX-image1.png)).

### 5. Commit your changes

Stage and commit your files.

```
git add stories/story-XXX.md images/story-XXX-*.*
git commit -m "Add story-XXX: Short description of your story"
```

### 6. Push to your branch to your fork:


```
git push origin add-story-yourname
```

### 7. Create a Pull Request (PR)  

* Go to the bad-vibe-coding GitHub page.
* You’ll see a prompt to “Compare & pull request” for your branch.
* Provide a clear title (e.g., Add story-XXX: My Vibe Coding Disaster) and describe your story briefly.
* Submit the PR. Maintainers will review and may request changes.

### 8. Respond to Feedback

If changes are requested, update your branch locally, commit, and push to your fork. The PR updates automatically.

## Story Format

Each story should be a Markdown file in the stories/ directory, named story-XXX.md (e.g., story-001.md). Use this template:

```
# Story XXX: [Short Title]

**Author**: [Your Name or Handle]  
**Date**: [YYYY-MM-DD]

## The Story

[Write your story here. Describe the context, what went wrong, and any lessons learned. Keep it engaging and concise.]

## Images (Optional)

[Include images using Markdown syntax, e.g., `![Description](images/story-XXX-image1.png)`. Place images in the `images/` directory.]

## Lessons Learned

[Summarize 1-3 key takeaways from the experience.]
```

* Keep stories concise (500-1000 words recommended).  
* Use clear, descriptive file names for images (e.g., story-XXX-image1.png).  
* Ensure images are relevant and appropriately licensed (e.g., your own or public domain).

## Repo Structure

```
bad-vibe-coding/
├── stories/
│   ├── story-001.md
│   ├── story-002.md
│   └── ...
├── images/
│   ├── story-001-image1.png
│   ├── story-001-image2.png
│   └── ...
├── CONTRIBUTING.md
├── README.md
└── LICENSE
```

## Why We Use Forks, Branches, and Pull Requests
For external contributors (those without write access), we use a forking workflow to keep the process secure and organized:

### Forking 

You work in a copy of the repo (your fork) under your GitHub account. This lets you make changes without affecting the main repo, as you don’t have direct write access.

### Branches

Creating a branch (e.g., add-story-yourname) keeps your story separate from other changes. It prevents conflicts and makes it easier to manage multiple contributions.

### Pull Requests (PRs)

A PR proposes your changes from your fork’s branch to the main repo’s main branch. Maintainers review your story for quality and fit. If changes are needed, you update your fork’s branch, and the PR reflects those updates. Once approved, your story is merged into the main repo.

This process ensures the main repo stays clean, contributions are reviewed, and everyone can contribute safely. Trusted contributors skip forking because they have write access to push branches directly to this repo.

## Code of Conduct

Be respectful and constructive. Offensive or inappropriate content will not be accepted.
Getting Collaborator Access
To become a trusted contributor with direct write access, submit a story via forking and contact the repo owner via [insert contact method, e.g., GitHub Issues or email]. Access is granted at the owner’s discretion.

## Questions?

Open an issue on the repo or reach out via [insert contact method]. For help with PRs, see GitHub’s guide.
