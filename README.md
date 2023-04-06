### Hi there 👋

# Languages & Tools

| Mobile app | <img alt="Mobile app Languages & Tools" src="https://skillicons.dev/icons?theme=dark&perline=8&i=flutter,dart" /> |
| :---: | :---: |
| Cloud | <img alt="Cloud Languages & Tools" src="https://skillicons.dev/icons?theme=dark&perline=8&i=firebase,gcp" /> |

# Status

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=yamatku415&theme=onedark&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)



[![trophy](https://github-profile-trophy.vercel.app/?username=yamatku415&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)



on:
  workflow_dispatch:
  schedule:
    - cron: '10 14 * * *'
    
name: Git commit
  run: |
    git config user.name github-actions[bot]
    git config user.email 41898282+github-actions[bot]@users.noreply.github.com
    if [ -n "$(git status --porcelain)" ]
    then git commit -am 'Generate README.md' && git push origin
    else echo 'nothing to commit, working tree clean'
    fi
