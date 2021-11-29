
  283  git init
  284  gh repo create
  285  git add .
  286  git commit -m "Primer commit"
  287  git branch -M main
  288  gh repo create
  289  git push -u origin main
  290  git config --global init.defaultBranch main
  291  git branch ramas_githud
  292  git branch testing
  293  HEAD
  294  git checkout testing
  295  git log
  296  git add .
  297  git commit -m"segundo commit"
  298  git ush
  299  git push
  300  git log
  301  git checkout testing
  302  git log
  303  git log --oneline --decorate --graph --all
  304  git checkout main
  305  git merge testing
  306  git log --oneline --decorate --graph --all
  307  git branch -d testing
  308  git log --oneline --decorate --graph --all
  309  history > history.md