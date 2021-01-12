## STRONTIC

This project is the source code (markdown) for https://strontic.github.io. The markdown pages are built locally and pushed to the `gh-pages` branch as HTML.

### Jekyll Local Build Instructions

1. Open *Git Bash*
2. `cd ~/Documents/GitHub/strontic.github.io` (cloned project directory)
3. `bundle update github-pages`
4. (OPTIONAL) `export JEKYLL_GITHUB_TOKEN=<your token>`
5. `export JEKYLL_ENV=production`
6. `bundle exec jekyll build --incremental`
    * (OPTIONAL) Incremental build: `--incremental` *([Experimental!](https://jekyllrb.com/docs/configuration/incremental-regeneration/))*
    * (OPTIONAL) Listen for changes: `--watch` *([Info](https://jekyllrb.com/docs/installation/windows/#auto-regeneration))*
7. (OPTIONAL) for testing what it looks like in a browser: `bundle exec jekyll serve`
8. `cd Docs`
9. `git init`
10. `git add .`
11. (OPTIONAL) `touch .nojekyll`
12. `git commit -m "Add Lastest GH-PAGES Files"`
13. (OPTIONAL) `git remote add origin git@github.com:strontic/strontic.github.io.git` (**required** for first run. change value to your project destination)
14. `git push --force origin master:gh-pages`

#### Helpful Resources:
- https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll
- https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll
- https://blog.bloomca.me/2017/12/15/how-to-push-folder-to-github-pages.html

### Prerequisites

#### Ruby

If Ruby is not already installed... https://www.ruby-lang.org/en/documentation/installation/

#### Bundler

1. Git Bash: `gem install bundler`
2. Git Bash (At project root): `bundle install`

#### Git SSH Keys

1. If SSH keys were not already configured
2. Generate SSH Keys `ssh-keygen -t ed25519 -C "your_github_email@example.com"`
3. Ensure `ssh-agent` is running: `eval $(ssh-agent -s)`
4. From the Git Bash terminal: `ssh-add ~/.ssh/id_ed25519`, then `clip < ~/.ssh/id_ed25519.pub`
5. Paste into Github Account. [Instructions](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
6. Done. [Additional Resources](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#platform-windows)

> Note: For legacy systems, generate SSH Keys using `ssh-keygen -t rsa -b 4096 -C "your_github_email@example.com"` and, `ssh-add ~/.ssh/id_rsa`, then `clip < ~/.ssh/id_rsa`