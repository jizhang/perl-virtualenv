perl-virtualenv
===============

Virtual Environment for Perl

Usage
-----

### Activate & deactivate

```bash
$ cd /path/to/project
$ /path/to/perl/bin/virtualenv.pl venv
$ source venv/bin/activate
(venv) $ perl -v
(venv) $ cpanm -v
(venv) $ deactivate
$ perl -v
```

### Use it directly

```bash
$ /path/to/project/venv/bin/perl -v
```
