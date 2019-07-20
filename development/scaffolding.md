title: Scaffolding Project Using PyScaffold
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  {{title}}
]

---

class: impact

{{title}}
=========

---

Installation
------------

PyScaffold helps you setup a new Python project. Just install it with:

> pip install pyscaffold

This will give you a new putup command and you can just type:

> putup --pre-commit --travis my_project

This will create a new folder called my_project containing a perfect project template with everything you need for some serious coding and Github integration. 

---

Setup
------

After the usual,

> cd my_project
>
> pip install pre-commit
>
> pre-commit install
>
> python setup.py develop

you are all set and ready to go.

---

Benefit of Using PyScaffold
---------------------------

After the project was setup, you can:

-   Configuration & Packaging
-   Versioning and Git Integration
-   Sphinx Documentation
-   Unittest & Coverage

---

Configuration & Packaging
-------------------------

-   All configuration can be done in `setup.cfg`.
-   Edit `setup.cfg` to serve your purpose.
-   In order to build a source, binary or wheel distribution, just run:

> python setup.py bdist_wheel

---

Versioning and Git Integration
------------------------------

> git clone ssh://git@github.com/Loksu/ellpy.py
>
> pre-commit run --all-files

---

Sphinx Documentation
--------------------

> python setup.py docs
> firefox build/sphinx/html/index.html

---

Unittest & Coverage
----------------------------

> source tests/travis_install.sh
>
> python setup.py test

---

Further reading
----------------------

-   <https://pypi.org/project/PyScaffold/>
-   [Pro Python Best Practices (2017)](https://rd.springer.com/book/10.1007/978-1-4842-2241-6)

---

class: impact

Questions?
==========
