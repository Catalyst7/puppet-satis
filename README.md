puppet-satis
============

git clone https://github.com/cargomedia/puppet-packages
git filter-branch --tag-name-filter cat --prune-empty --subdirectory-filter modules/satis/ -- --all
