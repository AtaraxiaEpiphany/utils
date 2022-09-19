# Install Node Version Manage(NVM)
> Use the following command alternatively.
- [nvm](https://tecadmin.net/how-to-install-nvm-on-ubuntu-22-04/)
```
sudo apt install curl
curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash 

```
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```

## If getting 443 ERROR
- Get the ip of `raw.githubusercontent.com` on the link [ipaddress](http://ipaddress.com)
- Type the command `sudo vi /etc/hosts` to modify the hosts file.
- Add the real ip to the hosts file.
- `(real ip) raw.githubusercontent.com`
- `source ~/.bashrc`
- Verify
- `command -v nvm` will output `nvm`

## Usage of NVM
- List available node.js version for the installation.
- `nvm ls`
- Switch to another version
- `nvm use 10.24`(gitbook)

## Install Gitbook
- `npm install -g gitbook-cli`
- `gitbook -V`

## If `gitbook -V` command not found
- sudo ln -s /node/path  /usr/local/bin/gitbook 