## To start

Go to folder:
cd ~/projects/design-portfolio

Run locally:
bundle exec jekyll serve --livereload

Run locally (4000):
bundle exec jekyll serve --livereload --host localhost
  
Shortcut:
cd ~/projects/design-portfolio && bundle exec jekyll serve --livereload --host localhost

Generate token (commit login):
git config --global user.name "hellolynn"
git config --global user.email "mail@hellolynn.com"
git config --global credential.helper osxkeychain
git remote -v
git push origin main