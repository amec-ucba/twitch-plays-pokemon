# 💻 Twitch Plays Pokémon

Starter files for an HTML coding exercise. You will turn plain text about **Twitch Plays
Pokémon**, the 2014 stream where more than a million people played one game of Pokémon Red
together through chat, into a well-structured HTML web page and publish it with GitHub Pages.

This page is going to look plain in the browser, and that is fine. There is no CSS in this
exercise. The point is to practice using HTML to give content structure and meaning.
Styling comes later in the course.

> [!NOTE]
> `.editorconfig`, `.gitattributes`, `.gitignore`, `.noai`, and the `.github` and `.idea`
> folders are setup files that keep assignments consistent. Leave them alone. `content.txt`
> and the four images are your starter content. Keep them in the repo.

## 📋 Assignment Requirements

> [!IMPORTANT]
> **Start here: [read ASSIGNMENT.md →](.github/ASSIGNMENT.md)**

It has the overview, the requirements, the grading criteria, and a final checklist. Read it before you start, and check it again before you submit.

## ✅ At a Glance

Every assignment follows the same steps. Each guide has screenshots for every step.

| Step | What you do                                                                | Guide                                         |
|------|----------------------------------------------------------------------------|-----------------------------------------------|
| 0    | **First assignment only:** install and set up WebStorm                     | [WebStorm Setup](.github/WEBSTORM_SETUP.md)   |
| 1    | Create your repo from this template, clone it, and make a `develop` branch | [Getting Started](.github/GETTING_STARTED.md) |
| 2    | Build your page in the root folder                                         | [Where Your Files Go](#-where-your-files-go)  |
| 3    | Commit and push often, then turn on GitHub Pages                           | [Publishing](.github/PUBLISHING.md)           |
| 4    | Open a pull request into `main` and submit its URL in Canvas               | [Submitting](.github/SUBMITTING.md)           |

## 📂 Where Your Files Go

Your page goes in the **root folder** of this repo, the same folder as this README.
GitHub Pages publishes from the root, so `index.html` has to live there or your site will 404.

You can get started in either of two ways. Pick **one**:

- **Rename the starter file.** Rename `content.txt` to `index.html`, then add your markup
  around the text that is already there.
- **Create a new file.** Create a new `index.html` in the root folder, then copy the text
  from `content.txt` into it as you mark it up. You can leave `content.txt` in the repo.

Either way, when you are finished your root folder should contain:

```
index.html
anarchy-vs-democracy.jpg
party.webp
twitch-plays-pokemon-logo.png
twitch-plays-pokemon.gif
```

Keep everything in the root folder. The images are already there, so
`<img src="party.webp">` just works. Don't move or rename them.

> [!WARNING]
> The file must be named exactly `index.html`, all lowercase. On Windows, turn on file
> extensions first so you don't end up with `index.html.txt` by mistake.

## 🤖 AI Policy

Work on this assignment must be your own. Do not use AI coding assistants — including
GitHub Copilot, Cursor, ChatGPT, Claude, or JetBrains AI Assistant — to generate,
complete, or rewrite your code.

You should be able to explain any line of your submission. You may be asked to do so.

This repo includes a `.noai` file, which disables JetBrains AI Assistant for the project
in IDEs like WebStorm. Leave it in place. It is a reminder of the policy above, not a
substitute for it — following the policy is still your responsibility.

> [!NOTE]
> The `.noai` file does **not** turn off WebStorm's local Full Line code completion. Turn that
> off yourself as part of the [one-time setup](.github/WEBSTORM_SETUP.md) (step 5).

> [!CAUTION]
> Late or missing submissions are graded on what is in the pull request at the deadline, so push your final commits
> before you submit.
