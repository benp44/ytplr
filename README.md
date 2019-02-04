# ytplr

**Play audio from a YouTube video in the terminal.**

Inspired by and largely based on [ytmdl](https://github.com/deepjyoti30/ytmdl) which instead of playing audio directly from a video on YouTube, downloads it as an mp3

**ytplr** runs vlc in the background via it's `cvlc` cli in order to play the audio.

### Demo

![Screenshot](/screencast.gif?raw=true)

### Dependencies/Requirements

Built on [youtube-dl](https://github.com/rg3/youtube-dl) and [vlc](https://github.com/videolan/vlc)

### Installation

Install the dependencies using your package manager and pip:

    sudo apt install vlc
    sudo -H pip3 install youtube-dl beautifulsoup

Clone the repo and alias the script in .bashrc, .zshrc, etc. For example:
  
    alias ytplr='~/dev/ytplr/ytplr'

### Usage

Search for a song:

    ytplr "one more time" 
    
Stop any currently playing song:

    ytplr
