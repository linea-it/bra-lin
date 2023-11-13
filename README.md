# BRA-LIN Documentation Website 

This repository is a fork of LIneA's IT Documentation at [docs.linea.org.br](https://docs.linea.org.br). 

This repository contains information about the LIneA's in-kind contribution program to LSST called BRA-LIN, written in Markdown which is converted to html/css/js with the [mkdocs](http://www.mkdocs.org) static site generator. The theme is [mkdocs-material](https://github.com/squidfunk/mkdocs-material) with LIneA customizations such as the colors injected via selective overloading of templates and CSS. 

# Reporting Issues

To report a problem with our documentation please create an [issue](https://github.com/linea-it/bra-lin/issues/new/choose) and someone will work on your task. Before you create a ticket, please check if there is an existing issue for the same problem to avoid duplicate issues.

If you need any further assistance send an email to `helpdesk@linea.org.br`.

# How to build the documentation

```
git clone https://github.com/linea-it/bra-lin/
cd bra-lin

apt-get install python-pip python3.10-venv
python3 -m venv mkdocs
source mkdocs/bin/activate
pip install -r requirements.txt
```

To run a local server using mkdocs:

```
cd docs
source mkdocs/bin/activate
mkdocs serve
```


# License

This repository is licensed under the BSD 3-Clause. For more details, see [LICENSE](https://github.com/linea-it/docs/blob/main/LICENSE).
