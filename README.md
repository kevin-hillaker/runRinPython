# runRinPython

## Description

Example of running R code within Python using VS Code.

## Notes

## References

* Setup
  * [Use .env Files for Environment Variables in Python Applications](https://dev.to/jakewitcher/using-env-files-for-environment-variables-in-python-applications-55a1)
  * [venv - Creation of virtual environments](https://docs.python.org/3/library/venv.html)
  * [How to use virtual env in make file](https://stackoverflow.com/posts/46188210/edit)
  * [Creating a Python makefile](https://earthly.dev/blog/python-makefile/#the-sample-source-code)

## Process

### Installation

* Windows Terminal
* Python
* R
* Visual Studio Code
* GitHub for Windows

#### make

``` ps1
winget install GnuWin32.Make
```

* Environment Variable > Path > Path-to-Make

### Create Python Virtual Environment (venv)

* Note: See .env file for editable path and env_path information.

``` ps1
python -m venv 'S:\Version_Control\RinPython\venv'
```
