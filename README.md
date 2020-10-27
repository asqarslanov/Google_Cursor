<p align="center">
    <img src="https://i.imgur.com/nooUY96.png" width="120" alt="GoogleDot" />
</p>

<p align="center">
    🍭 Cursor theme inspired on Google
</p>

<!-- Badges -->
<p align="center">
  <!-- First Row -->
  <a href="https://github.com/ful1e5/Google_Cursor/actions?query=workflow%3Abuild">
    <img alt="GitHub Action Build" src="https://github.com/ful1e5/Google_Cursor/workflows/build/badge.svg" width="102" />
  </a>
  
  <a href="https://www.codefactor.io/repository/github/ful1e5/google_cursor">
    <img src="https://www.codefactor.io/repository/github/ful1e5/google_cursor/badge" alt="CodeFactor" />
  </a>

  <!-- Second Row -->
  </br >
  <a href="https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html">
    <img alt="npm type definitions" src="https://img.shields.io/npm/types/typescript">
  </a>

  <a href="https://github.com/puppeteer/puppeteer/">
    <img alt="Puppeteer version" src="https://img.shields.io/github/package-json/dependency-version/ful1e5/Google_Cursor/puppeteer">
  </a>

  <a href="https://github.com/ful1e5/clickgen">
    <img alt="Clickgen" src="https://img.shields.io/badge/theme%20builder-clickgen-FD0542" />
  </a>
  
  <!-- Second Row -->
  <br />
  <a href="https://github.com/ful1e5/Google_Cursor/releases">
    <img alt="Google Cursor release (latest by date including pre-releases)" src="https://img.shields.io/github/v/release/ful1e5/Google_Cursor?include_prer">
  </a>

  <a href="https://github.com/ful1e5/Google_CursorICENSE">
    <img alt="License" src="https://img.shields.io/github/license/ful1e5/Google_Cursor?color=0081FB" />
  </a>

  <!-- Third Row -->
  <br />
  <a href="www.pling.com/p/1215613#files-panel">
    <img alt="License" src="https://img.shields.io/badge/-Linux-grey?logo=linux" />
  </a>

  <a href="www.pling.com/p/1215613#files-panel">
    <img alt="License" src="https://img.shields.io/badge/-Windows-blue?logo=windows" />
  </a>

  <a href="https://www.python.org/">
    <img alt="License" src="https://img.shields.io/badge/-Python-yellow?logo=python" />
  </a>

 <!-- Fourth Row -->
  <br />
  <a href="https://github.com/ful1e5">
    <img alt="Made By Kaiz"  src="https://kaiz.vercel.app/api/badge" width="133" />
  </a>
</p>

---

<!-- Intro -->

# GoogleDot Cursor

Cursor theme inspired on **google material design** for `Windows` and `Linux` with _HiDPi Support_ 🎉.

#### Cursor Sizes

<kbd>22</kbd>
<kbd>24</kbd>
<kbd>28</kbd>
<kbd>32</kbd>
<kbd>40</kbd>
<kbd>48</kbd>
<kbd>56</kbd>
<kbd>64</kbd>
<kbd>72</kbd>
<kbd>80</kbd>
<kbd>88</kbd>
<kbd>96</kbd>

#### Colors

![#4285F4](https://imgur.com/NXEup6E.png)
![#FFFFFF](https://imgur.com/cvFxSBb.png)

#### Quick install

<p align="center">
  <a href="https://www.pling.com/p/1215613/" >
    <img title="GoogleDot Pling Store" width="40%" src="https://imgur.com/VxSgrWw.png">
  </a>
</p>

#### Preview:

> Detailed Cursors Informations inside [src/svgs/README.md](https://github.com/ful1e5/Google_Cursor/blob/main/src/svg/README.md)

<!-- Preview -->

<p align="center">
  <img title="GoogleDot" src="https://imgur.com/osnWiED.png">
  </br>
  <sub>GoogleDot Cursors 🍭</sub>
</p>


### Manual Install

#### Linux/X11

```bash
# extract `GoogleDot.tar.gz`
tar -xvf GoogleDot.tar.gz

# For local users
mv GoogleDot ~/.icons/

# For all users
sudo mv GoogleDot /usr/share/icons/
```


#### Windows

1. unzip `GoogleDot_Windows.zip` file
2. Open `GoogleDot_Windows/` in Explorer, and **right click** on `install.inf`.
3. Click 'Install' from the context menu, and authorize the modifications to your system.
4. Open _Control Panel > Personalization and Appearance > Change mouse pointers_, and select **GoogleDot Cursors**.
5. Click '**Apply**'.

<!-- Build Dependencies -->

# Dependencies

## Runtime Dependencies

- libxcursor-dev
- libx11-dev
- libpng-dev (<=1.6)

#### Install Runtime Dependencies

##### macOS

```bash
brew cask install xquartz libpng
```

##### Debain/ubuntu

```bash
sudo apt install libx11-dev libxcursor-dev libpng-dev
```

##### ArchLinux/Manjaro

```bash
sudo pacman -S libx11 libxcursor libpng
```

##### Fedora/Fedora Silverblue/CentOS/RHEL

```bash
sudo dnf install libx11-devel libxcursor-devel libpng-devel
```

## Build Dependencies

- [nodejs](https://nodejs.org/en/) (<=12.x.x)
- [yarn](https://classic.yarnpkg.com/en/docs/install/)
- [python](https://www.python.org/downloads/) (<=3.6)
- [pip3](https://pip.pypa.io/en/stable/installing/)

### Node Packages

- [puppeteer](https://www.npmjs.com/package/puppeteer)
- [pngjs](https://www.npmjs.com/package/pngjs)
- [pixelmatch](https://www.npmjs.com/package/pixelmatch)

### PyPi Packages

- [clickgen](https://pypi.org/project/clickgen/s)
- [Pillow](https://pypi.org/project/Pillow/)

## Build From Scratch

### ⚡ Auto Build (using GitHub Actions)

GitHub Actions is automatically runs on every `push`(on **main** and **dev** branches) and `pull request`(on **main** branch), You found theme resources in `artifact` section of **build**.GitHub **Actions** available inside [.github/workflows](https://github.com/ful1e5/Google_Cursor/tree/main/.github/workflows) directory.

### Manual Build

#### Setup python environment

```bash
python3 -m pip install --upgrade pip                 # Update pip to latest
python3 -m pip3 install virtualenv                   # Install python virtual environment
virtualenv venv                                      # Create new virtualenv named `venv`
source venv/bin/activate                             # Activate virtualenv

# For Deactivate virtualenv
deactivate
```

#### Compile From Source

> Make sure your [python environment](#setup-python-environment) setup and `virtualenv` is **active**.

```bash
yarn install                                         # Install all Node Packages
yarn py_install                                      # Install all PyPi Packages
yarn compile                                         # Compile the cursor theme
```

After build `bitmaps` and `themes` directory are generated at project **root**.

### Install Build Theme

All builded cursor themes are available inside `themes` directory.

#### Linux

```bash
cd ./themes
rm -rf ~/.icons/GoogleDot && cp GoogleDot ~/.icons/   # installing Theme to local user(recommend)
```

#### Windows

1. unzip `GoogleDot_Windows.zip` file
2. Open the `settings` app.
3. **Goto** `Devices` -> `Mouse` -> `Additional Mouse Options`.
4. **Goto** the `pointers` tab.
5. Replace each cursor in the currently applied cursor set with the corresponding cursor in the `GoogleDot_Windows` folder.
6. Click "**save as**" and type in the desired name.
7. Click "**apply**" and "**ok**".

<!-- Bug Report -->

# Bugs

Bugs 🐛 should be reported [here](https://github.com/ful1e5/Google_Cursor/issues) on the Github issues page.

<!-- Help -->

# Getting Help

You can create a **issue**, I will help you. 🙂

<!-- Contributions and Suggestion -->

# Contributing

Check [CONTRIBUTING.md](CONTRIBUTING.md), any suggestions for features and contributions to the continuing code masterelopment can be made via the issue tracker or code contributions via a `Fork` & `Pull requests`.

<!-- Support -->

## Support

Give a **★** or Follow on [GitHub](https://github.com/ful1e5),That's work as **Steroid 💉** for me. 😉

> For extra support

<a href="https://www.buymeacoffee.com/Nt7Wg4V" target="_blank">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" >
</a>

<!-- Ninja  -->

<h1 align="center">
  ( `ω´ )۶▬ι═══════ﺤ
</h1>
<p align="center">
  <sub>I'm Using Katana </sub>
</p>