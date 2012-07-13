hakta.com
=========

Setup
-----

sudo npm -g install less 


Run
---

cd app
python -M SimpleHTTPServer 


Deploy
-----

lessc -x app/static/less/style.less > app/static/css/style.css
dotcloud push site
