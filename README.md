# Python Django Environment

A Python with Django development environment

## Prerequisite

### Python3

```
pip3 install virtualenv

pip3 install virtualenvwrapper
```

### Install dependencies

```
pip3 install virtualenv
```

### virtualenv

#### Usage

Creation of virtualenv:

```bash
$ virtualenv -p python3 <path/to/the/project>
```

Activate the virtualenv:

```bash
$ source <path/to/the/project>/bin/activate
```

Deactivate the virtualenv:

```bash
$ deactivate
```

#### virtualenvwrapper

Copy this in your '.bash_profile' or '.zshrc'

```bash
# virtualenv & virtualenvwrapper (Python)
alias v='workon'
alias v.deactivate='deactivate'
alias v.mk='mkvirtualenv'
alias v.rm='rmvirtualenv'
alias v.switch='workon'
alias v.add2virtualenv='add2virtualenv'
alias v.cdsitepackages='cdsitepackages'
alias v.cd='cdvirtualenv'
alias v.lssitepackages='lssitepackages'

export WORKON_HOME=$HOME/.virtualenvs
export PROJECT_HOME=$HOME/Devel
```

## Information & Documentation

### virtualenv

[virtualenv](https://virtualenv.pypa.io/en/latest/)

### virtualenvwrapper

[virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)