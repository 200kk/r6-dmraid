The Quick and Easy Way
---

    sudo -s
    cd /usr/src/linux
    wget https://raw.github.com/calebgray/r6-dmraid/master/linux-3.4.5-gentoo-r6-dmraid.patch
    patch -p1 -F10 < linux-3.4.5-gentoo-r6-dmraid.patch
