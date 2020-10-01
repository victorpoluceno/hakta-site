hakta.com
=========
# Made using Ruby.

Setup
-----

Install depencies::

    sudo apt-get install npm

Install less compiler::

    sudo npm install less -g


Run
---

Run a simple python static server::

  cd app
  python -m SimpleHTTPServer 


Compile
-------

Compile using lessc::

    lessc -x app/static/less/style.less > app/static/css/style.css


Deploy
-----

Deploy to dotlcloud sandbox::

    dotcloud push site


Deploy to dotcloud live WARNING::

    dotcloud push sitelive
    
    
