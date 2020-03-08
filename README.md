# hello-world
This is the first git project of mine. Just Learn how to use it.
# sovle the problem of pip :ValueError: Unable to determine SOCKS version from socks://127.0.0.1:1080/
I use v2ray as my proxy, however when i try to use pip or conda after i install anaconda in ubuntu18.04, it proposes that error.
add 
export http_proxy="socks5://127.0.0.1:1080" 
export https_proxy="socks5://127.0.0.1:1080"
in bashrc sloves it.
