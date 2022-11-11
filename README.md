### Hi there 👋

<!--
**prince26ayush/prince26ayush** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on scanotics
- 🌱 I’m currently learning machine learning
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with guatam yadav
- 💬 Ask me about front end
- 📫 How to reach me: prince26ayush@gmail.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=prince26ayush&hide=stars,prs&show_icons=true&theme=merko)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=prince26ayush&layout=compact&theme=merko)](https://github.com/anuraghazra/github-readme-stats)
![Spotify recently played](https://spotify-recently-played-readme.vercel.app/api?user=xlaxzeff8iwo3zrvr4m89jo2u)
![Jokes Card](https://readme-jokes.vercel.app/api)
[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=prince26ayush&repo=scanotics)](https://github.com/prince26ayush/scanotics)

name: Waka Readme

on:
  workflow_dispatch: # for manual workflow trigger
  schedule:
    - cron: '0 0 * * *' # runs at every 12AM UTC

jobs:
  update-readme:
    name: WakaReadme DevMetrics
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{1bcc71bb-8682-4043-8eff-2036d47d6c96}}
          # following flags are required, only if this is not on
          # profile readme, remove the leading `#` to use them
          #GH_TOKEN: ${{ secrets.GH_TOKEN }}
          #REPOSITORY: <gh_username/gh_username>


