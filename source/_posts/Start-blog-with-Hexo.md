---
title: Start blog with Hexo
date: 2020-11-05 19:29:09
tags:
- Hexo
- blog
- setup
---
Beginning...
===============

I finally decided to start blog to save memories from my IT journey. Don't get me wrong 
i tried to start own blog many times(too many :-D) but this time I'm really doing this!
After some research i decided to go with Hexo because of Node.js and simplicity.

I will shortly guide you how to setup Hexo on Github. It is very easy and quick so..
Let's begin:

## Install npm 
First of all you will need to install npm if you dont have it already.(npm is distributed with Node.js)

*  **Mac**

 `curl`
{% codeblock %}
curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg</a>.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg" -target "/"
{% endcodeblock %}
`Homebrew`
{% codeblock %}brew install node{% endcodeblock %}
`Mac pkg`
Just download and install package from [nodejs.org](https://nodejs.org/en/download/current)


*  **Windows**
`Scoop`
{% codeblock %}scoop install nodejs{% endcodeblock %}
`Chocolatey`
{% codeblock %}choco install nodejs{% endcodeblock %}
`msi installer`
Download and install Windows Installer (.msi) from [nodejs.org](https://nodejs.org/en/download/current)

## Install Hexo
After we got Node.js the installation of Hexo is straightforward:
{% codeblock %}npm install hexo-cli -g{% endcodeblock %}

## Setup


