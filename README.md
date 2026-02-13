





<h1 align="center">Hi 👋 I'm MishkatuL B. SiFaT</h1>

<!--<p align="left"> <img src="https://komarev.com/ghpvc/?username=sifat049&label=Profile%20views&color=0e75b6&style=flat" alt="sifat049" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=sifat049"  /></a> </p>    -->

- 🌱 I’m currently learning **C++ Java**

- 📫 How to reach me **mishkat049@gmail.com**

  
<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/mishkatul bary" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="mishkatul bary" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/skylark" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="skylark" height="30" width="40" /></a>
</p>
<a href="https://www.codechef.com/users/mishkat_669" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" alt="mishkat_669" height="30" width="40" /></a>
<a href="https://www.hackerrank.com/@mishkat49" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="@mishkat49" height="30" width="40" /></a>
<a href="https://codeforces.com/profile/mishkat049" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codeforces.svg" alt="mishkat049" height="30" width="40" /></a>
<a href="https://www.leetcode.com/mishkat049" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="mishkat049" height="30" width="40" /></a>
</p
</p>
<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> </p>
 </p>

<!--<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sifat049&show_icons=true&locale=en" alt="sifat049" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=sifat049&" alt="sifat049" /></p>-->

name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 0 * * *"   # daily
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: Sifat049
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

[
](https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg)
