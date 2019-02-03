# Eustis-Bash-Commands
Simple shell scripts for UCF's Eustis server:
- VPN auto login
- Eustis auto login
- file upload (add -r for folder upload)

![gif](https://github.com/dlam96/GIFS/blob/master/script.gif)
# How to use
* Expect scripts: expect <script name>.exp
> ex: expect vpn.exp

Note:

Remove **#** on spawn bash ... line to combine VPN and Eustis auto login!

**VPN + Eustis scripts must be in _same_ directory**

* Shell scripts: bash <script name>.sh
> ex: bash auto-login.sh

# To disconnect from VPN
> /opt/cisco/anyconnect/bin/vpn disconnect

# IMPORTANT
* Replace username and password to use scripts properly
* Must have VPN (Cisco AnyConnect VPN cilent) already installed if using vpn.exp
