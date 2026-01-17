# 👋 Hi, I'm Rushikesh Pawar

### 🚀 B.Tech E&TC Student | App & Web Developer | Tech Innovator from India 🇮🇳

**💌 Email Me 👉** [rushikeshrpawar77@gmail.com](mailto:rushikeshrpawar77@gmail.com)
For Collaboration / Projects / Startups / Ideas 😎

---

## 💡 About Me

* 🔭 **I’m currently working on:** Campus Cash App, College Result Portal, Smart Campus Systems
* 🌱 **I’m currently learning:** Flutter, Firebase, AI Tools, Ethical Hacking, Cloud Basics
* 👯 **I’m looking to collaborate on:** App Development, College Projects, Startup Ideas
* 🤝 **I’m looking for help with:** Scaling apps, Deployment, Security
* 💬 **Ask me about:** Flutter, Firebase, Web Apps, Student Startups, Tech Ideas
* 📫 **How to reach me:** [rushikeshrpawar77@gmail.com](mailto:rushikeshrpawar77@gmail.com)
* 😄 **Pronouns:** He / Him
* ⚡ **Fun fact:** I turn ideas into apps before they turn into dreams 🚀

---

## 🧑‍💻 Tech Stack

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge\&logo=flutter\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge\&logo=firebase\&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

---

## 🌐 Connect With Me

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:rushikeshrpawar77@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/07plusdeveloper)

---
# snker BHAI 

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image. Colors can [be](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-ocean.svg) [customized](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-grey.svg).

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

### **github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

### **svg**

If you are only interested in generating a svg (not a gif), consider using this faster action: `uses: Platane/snk/svg-only@v3`

### **dark mode**

![dark mode](https://github.com/user-attachments/assets/6b900b64-0cdc-43f0-a234-e11dba8e786e)

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

[solver algorithm](./packages/solver/README.md)

## Contribution Policy

This project does not accept pull request.

Reporting or fixing issues is appreciated, but change in the API or implementation should be discussed in issue first and is likely not going be greenlighted.


---

## 🔥 Quote

> "Build in silence, let your success make the noise." 🔥🚀

---

⭐ From [07plusdeveloper](https://github.com/07plusdeveloper)
