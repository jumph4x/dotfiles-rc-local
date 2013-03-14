dotfiles-rc-local
=================

/etc/rc.local for the Ubuntu installation on my s7-391

## Steps

1. `sudo rm /etc/rc.local`
2. `cd`
3. `git clone git@github.com:jumph4x/dotfiles-rc-local.git .rc-local`
4. `sudo ln -s ~/.rc-local/rc-local /etc/rc.local`
5. `sudo chmod o+w /etc/rc.local`
6. `sudo update-rc.d -f ondemand remove`

## Note

Remember to install and configure laptop-mode-tools
