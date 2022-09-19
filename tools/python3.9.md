#install python3.9
- [python3.9](https://linuxize.com/post/how-to-install-python-3-9-on-ubuntu-20-04/)


```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.9


```

#install pip3.9 for python3.9
- [pip3.9](https://stackoverflow.com/questions/65644782/how-to-install-pip-for-python-3-9-on-ubuntu-20-04)

You can install pip for python 3.9 the following way:

`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`
`python3.9 get-pip.py`

It is important you use python3.9 instead of just python3, to ensure pip is installed for python 3.9.

If you see any permissions errors, you may need to use 

`python3.9 get-pip.py --user`

If you get an error like No module named 'distutils.util' when you run python3.9 get-pip.py, and you are on a Debian-based Linux distribution, run

`sudo apt install python3.9-distutils`
