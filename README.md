<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:8b5cf6&height=200&section=header&text=Sanjay%20Kumar%20Thakur&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full%20Stack%20JavaScript%20Developer&descSize=20&descAlignY=55"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Building+scalable+web+applications;MERN+Stack+%7C+Next.js+%7C+TypeScript;Turning+ideas+into+reality+with+code)](https://git.io/typing-svg)

<br/>
</div>

---

<table>
<tr>
<td width="50%" valign="top">

<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="25"/> **About Me**

```typescript
interface Developer {
  name: string;
  role: string;
  location: string;
  workingOn: string;
  learning: string[];
  askMeAbout: string[];
}

const sanjay: Developer = {
  name: "Sanjay Kumar Thakur",
  role: "Full Stack JavaScript Developer",
  location: "India",
  workingOn: "Production-grade MERN apps",
  learning: [
    "System Design",
    "Cloud Architecture", 
    "DevOps"
  ],
  askMeAbout: [
    "React", "Node.js", "MongoDB",
    "Next.js", "TypeScript", "REST APIs"
  ]
};
```

</td>
<td width="50%" valign="top">

<picture>

<img align="center" alt="Coding" width="100%" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"/>

</picture>

<br/>

<img align="center" alt="Coding" width="100%" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif"/>

<br/><br/>

<div align="center">

| | |
|:---:|:---|
| 🔭 | **Currently:** Building production-ready web apps |
| 🌱 | **Learning:** System Design & DevOps |
| 💬 | **Ask Me:** React, Node.js, MongoDB |
| ⚡ | **Fun Fact:** I debug with console.log |

</div>

</td>
</tr>
</table>

---

## 💭 Developer's Wisdom

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote"/>


</div>

---

## 🛠️ Tech Stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,redux,tailwind,materialui,html,css,sass&theme=dark" alt="Frontend Skills"/>

### Backend

<img src="https://skillicons.dev/icons?i=nodejs,express,graphql,nestjs&theme=dark" alt="Backend Skills"/>

### Database & ORM

<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,prisma,mysql&theme=dark" alt="Database Skills"/>

### Tools & DevOps

<img src="https://skillicons.dev/icons?i=git,github,docker,vscode,postman,figma,linux,vercel,aws&theme=dark" alt="Tools"/>

</div>

<div align="center">

## 🌐 Let's Connect 

  <a href="https://linkedin.com/in/sanjay-kumar-thakur">
    <img src="https://skillicons.dev/icons?i=linkedin" />
  </a>
  <a href="https://twitter.com/sanjay_kumar80">
    <img src="https://skillicons.dev/icons?i=twitter" />
  </a>
  <a href="mailto:sanjay17126@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" />
  </a>
  <a href="https://github.com/snjy-kumar">
    <img src="https://skillicons.dev/icons?i=github" />
  </a>
  <a href="https://www.sanjaykumarthakur.me/">
    <img src="https://skillicons.dev/icons?i=htmx" />
  </a>

</div>

---

<div align="center">

## 💭 Developer's Philosophy

<table>
<tr>
<td align="center" width="50%">

```javascript
while (alive) {
    eat();
    sleep();
    code();
    repeat();
}
```

</td>
<td align="center" width="50%">

> *"The best error message is the one that never shows up."*
> 
> — Thomas Fuchs

</td>
</tr>
</table>

<br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random Dev Quote"/>

</div>

---

<div align="center">

### 💜 Thanks for visiting!

<sub>If you like my work, consider giving a ⭐ to my repositories!</sub>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:8b5cf6&height=120&section=footer"/>

</div>

---

<details>
<summary>🐍 <b>Setup Snake Animation</b> (Click to expand)</summary>

<br/>

Create `.github/workflows/snake.yml` in your repository:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: snjy-kumar
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then run the workflow manually from Actions tab.

</details>
