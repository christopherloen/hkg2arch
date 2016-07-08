# hkg2arch - 0.5
A simple script to generate PKGBUILDs for haskell packages. Language: Bash

usage: hkg2arch [HKGNAME] [HKGVER]
    
    examples:
    
    - hkg2arch curl 1.3.8 [create PKGBUILD for curl-1.3.8]

#Installation

git clone https://github.com/christopherloen/hkg2arch.git

cd hkg2arch && chmod +x hkg2arch

sudo cp hkg2arch /usr/bin && sudo mkdir /usr/share/hkg2arch && sudo cp deps.txt /usr/share/hkg2arch

But you can find hkg2arch on AUR, so I suggest to get it from there.
