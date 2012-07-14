hakta.com
=========

Setup
-----

Install depencies::

    sudo apt-get install npm

Install less compiler::

    sudo npm -g install less 


Run
---

Run a simple python static server::

  cd app
  python -M SimpleHTTPServer 


Compile
-------

Compile using lessc::

    lessc -x app/static/less/style.less > app/static/css/style.css


Deploy
-----

Deploy to dotlcloud::

    dotcloud push site
