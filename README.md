
### 👾 I use
![RUST](https://img.shields.io/badge/-Rust-141414?style=flat&logo=rust)
![Typescript](https://img.shields.io/badge/-Typescript-141414?style=flat&logo=typescript)
![Python](https://img.shields.io/badge/-Python-141414?style=flat&logo=python)
![React](https://img.shields.io/badge/-React-141414?style=flat&logo=react)

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=k4zam1&theme=dracula&hide=html,css,dockerfile,shell,ejs,stylus,javascript&count_private=true&show_icons=true&hide_border=true&layout=compact"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=k4zam1&count_private=true&show_icons=true&theme=dracula&include_all_commits=true&hide_border=true"/>
</p>
<p align="center">
<img src="https://activity-graph.herokuapp.com/graph?username=k4zam1&theme=dracula"/>
</p>

[![trophy](https://github-profile-trophy.vercel.app/?username=k4zam1)](https://github.com/ryo-ma/github-profile-trophy)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ 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 }}
          GH_TOKEN: ${{ 3c7db5f7-f264-422f-bb67-0d2ff88248c4 }}
<!--END_SECTION:waka-->
