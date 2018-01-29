# Builds of EOS

## Download and install

```
wget https://github.com/ghoti143/eosio-builds/raw/master/3.0.x/eos-DAWN-2018-01-25-Linux.deb
sudo dpkg -i eos-DAWN-2018-01-25-Linux.deb
```

## Notes

It puts all the contract skeleton files into /usr/share/skeleton for you, so eoscpp can find them, and it puts eosc, eosd, eoscpp, launcher, and eos-walletd in /usr/bin for you, so they're in the path.

It does include header and library files, unlike most Debian packages that don't have -dev in the name.

## Uninstall
```apt remove eos``` works to remove it from your system if you need to.
