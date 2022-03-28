<p align="center">
  <img width="10%" align="center" src="src/icon.ico">
</p>
<h1 align="center">
  SoftAdminer
</h1>

<p align="center">
    A Python GUI for uninstalling the default Windows 10 apps.
</p>

<p align="center">
  <a style="text-decoration:none" href="https://github.com/kinseyy/SoftAdminer/releases">
    <img src="https://img.shields.io/github/v/release/kinseyy/SoftAdminer?label=Version&style=flat-square&color=00B16A" alt="Releases" />
  </a>
  <a style="text-decoration:none" href="https://www.python.org/downloads/release/python-379/">
    <img src="https://img.shields.io/badge/python-3.7+-blue.svg?color=00B16A&style=flat-square" alt="Python Version" />
  </a>
  <a style="text-decoration:none" href="https://www.codefactor.io/repository/github/kinseyy/SoftAdminer">
    <img src="https://www.codefactor.io/repository/github/kinseyy/SoftAdminer/badge?style=flat-square" alt="CodeFactor" />
  </a>
  <a style="text-decoration:none" href="https://github.com/kinseyy/SoftAdminer/releases">
    <img src="https://img.shields.io/github/downloads/kinseyy/SoftAdminer/total?color=00B16A&style=flat-square" alt="Downloads" />
  </a>
  <a style="text-decoration:none">
    <img src="https://img.shields.io/badge/OS-Windows%2010-blue?style=flat-square&color=00B16A" alt="OS" />
  </a>
</p>


<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#installing">Installing</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#building">Building</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## Installing
Pre-built binaries are available from the [releases](https://github.com/kinseyy/










releases) page.

## Shortcuts

* <kbd>CTRL</kbd> <kbd>R</kbd> - refresh the list of installed apps.
* <kbd>CTRL</kbd> <kbd>S</kbd> - view links to apps in Microsoft Store.
* <kbd>CTRL</kbd> <kbd>G</kbd> - visit the GitHub page.
* <kbd>CTRL</kbd> <kbd>A</kbd> - view the "About" window.
* <kbd>CTRL</kbd> <kbd>Q</kbd> - quit the app.

## Features

* Intuitive design allows to easily navigate through the GUI and uninstall apps with a few clicks.
* It is not possible to break the OS using this tool. All listed apps can be reinstalled with Microsoft Store using the "Store" sidebar tab. Apps like Edge or Cortana are deeply integrated with Windows 10, so they cannot be easily uninstalled without creating any issues.
* The GUI does not require elevated administrator privileges to run. It also does not save registry entries.

## Dependencies

* [PySide6](https://pypi.org/project/PySide6/)
* [requests](https://pypi.org/project/requests/)
* [packaging](https://pypi.org/project/packaging/)

## Usage

```batch
git clone https://github.com/kinseyy/SoftAdminer

cd SoftAdminer

pip install -r requirements.txt

cd SoftAdminer

python app.py
```

## Building

Build with the `Auto-Py-To-Exe`, it's better.



## License

This software is available under the following licenses:

  * **GNU GPL - v3.0**
