# jackchuka Hugo

Source for [jackchuka.github.io](https://github.com/jackchuka/jackchuka.github.io)

## Initial setup
```bash
# clone this repo
git clone git@github.com:jackchuka/jackchuka-hugo.git

# clone public
git clone git@github.com:jackchuka/jackchuka.github.io.git public
```

## To update
```bash
hugo server
hugo new blog/title.md
# write content
git add .
git commit -m '<commit message>' # commit to this repository
./deploy.sh '<commit message>' # commits to github.io
```
