## STRONTIC

This project is the source code (markdown) for https://strontic.github.io. The markdown pages are built locally and pushed to the `gh-pages` branch as HTML.

### Jekyll Local Build Instructions

1) Open *Git Bash*
2) `cd ~/Documents/GitHub/strontic.github.io`
3) `bundle update github-pages`
4) `bundle exec jekyll build`
5) (OPTIONAL) for testing what it looks like in a browser: `bundle exec jekyll serve`
6) `cd Docs`
7) `git init`
8) `git add .`
9) `touch .nojekyll`
10) `git commit -m "Add Lastest GH-PAGES Files"`
11) (OPTIONAL?) `git remote add origin git@github.com:strontic/strontic.github.io.git`
12) `git push --force origin master:gh-pages`

#### Helpful Sources:
- https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll
- https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll
- https://blog.bloomca.me/2017/12/15/how-to-push-folder-to-github-pages.html

#### Git SSH Keys

If SSH keys were not already configured... `ssh-add ~/.ssh/id_rsa`, then `clip < ~/.ssh/id_rsa`. Paste into Github Account (More info: https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#platform-windows)
