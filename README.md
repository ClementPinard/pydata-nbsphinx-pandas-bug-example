# pydata-nbsphinx-pandas-bug-example


Small repository to show a bug in pydata + nbsphinx formatting

to reproduce the bug, make sure you have sphinx, pydata-sphinx-theme, nbsphinx and pandas installed.

If you have poetry you can create the adhoc virtualenv with this command :

```bash
poetry install
poetry shell
```

Next, build the docs with

```bash
make html
```

the faulty page should be in `_build/html/test.html`