# Leetcode Download Script

This repo records my pratice of leetcode questions. The script will download leetcode problem to local for using you prefer code editor in writing or debugging your code.



![leetcodedownload_final](README.assets/leetcodedownload_final.gif)



## Getting Started

This project contains a make file script written in python that helps to download and create local file directly from leetcode.com

### Prerequisites

The python script requires is run on python3, and require pypi and selenium chrome driver used for automatically download question and description from the website.

```
python3 --version
pip3 --version
```

### Installing

Pip

for Mac OS

```
brew install python3
pip3 --version
```

Or Ubuntu 18.04

```
sudo apt update
sudo apt install python3-pip
pip3 --version
```



beatifulSoup

```
sudo apt-get install python3-bs4
```

or 

```
pip3 install bs4
```



Selenium

```
pip3 install selenium
```

Web Drivers

Selenium requires a driver to interface with the chosen browser. Firefox, for example, requires geckodriver, which needs to be installed before the below examples can be run. Make sure it’s in your PATH, e. g., place it in /usr/bin or /usr/local/bin.

https://sites.google.com/a/chromium.org/chromedriver/downloads



### Usage

```
python3 make.py [Seach keyword]
```



note: search keyword could be question id or question title.



