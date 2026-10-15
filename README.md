<div align="center">

<a href="https://github.com/vitaliy887/vitaliy887">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1200&color=4FC3F7&center=true&vCenter=true&width=650&height=70&bg=0d1b2a,1b263b,0a192f&gradient=true&lines=%D0%9A%D0%BE%D0%BB%D1%8C%D1%86%D0%BE%D0%B2%20%D0%92.;%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%20%D0%A1%D0%9A%D0%A4%D0%A3;Future%20Developer" alt="Кольцов В. — студент СКФУ" />
</a>

<!-- Тёмно-синий баннер-фон -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a192f,50:1b263b,100:13315c&height=120&section=header" width="100%" />

# 🐍 Привет, я **Кольцов В.**

**Студент СКФУ** • учусь, кодю и кормлю змейку точками

![GitHub followers](https://img.shields.io/github/followers/vitaliy887?style=for-the-badge&color=1b263b)
![Repo stars](https://img.shields.io/badge/СКФУ-%20студент-13315c?style=for-the-badge)
![Snake](https://img.shields.io/badge/игра-Змейка-4FC3F7?style=for-the-badge)

</div>

---

## 🕹️ Змейка

> **https://vitaliy887.github.io/IT-Cod_VKoltsov/** 🎮

---

## 🐍 Змейка ест мой график контрибуций

Анимация генерируется автоматически GitHub Actions и обновляется сама после каждого коммита.

<picture>
  <source media="prefers-color-scheme: dark" srcset="https://raw.githubusercontent.com/vitaliy887/vitaliy887/output/github-contribution-grid-snake-dark.svg" />
  <source media="prefers-color-scheme: light" srcset="https://raw.githubusercontent.com/vitaliy887/vitaliy887/output/github-contribution-grid-snake.svg" />
  <img alt="Змейка ест контрибуции" src="https://raw.githubusercontent.com/vitaliy887/vitaliy887/output/github-contribution-grid-snake.svg" />
</picture>

<details>
<summary>⚙️ Как включить (workflow-файл)</summary>

Сохрани как `.github/workflows/snake.yml`:

```yaml
name: 🐍 Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [main]
jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>

---

## 📊 Статистика

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vitaliy887&show_icons=true&theme=blue-navy&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?vitaliy887=vitaliy887&layout=compact&theme=blue-navy&hide_border=true" height="150" />
</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:13315c,100:0a192f&height=100&section=footer" width="100%" />

**Кольцов В.** ✦ Студент СКФУ ✦ 2026

![snake ascii](https://img.shields.io/badge/🐸-eat-code-sleep-repeat-0a192f?style=flat-square)

</div>
