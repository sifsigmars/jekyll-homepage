Source for the home page is in a separate repo.

Source for the site itself is in _site which is ignored in the main repo and has its own repo.

To update the homepage itself:
 - jekyll build --config _config.yml,_config_production.yml
 - cd _site
 - git commit and push

To develop and view local changes run the local server
 - jekyll serve
