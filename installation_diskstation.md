# installation CUBA : 
===================

## initialisation
- http://cuba
- restauration conf

`ln -s /volume1/homes /home`

## installation de ipkg
- determiner le proc : `uname --machine`
- `cd /tmp`
- `wget http://ipkg.nslu2-linux.org/feeds/optware/syno-i686/cross/unstable/syno-i686-bootstrap_1.2-7_i686.xsh`
- `chmod +x syno-i686-bootstrap_1.2-7_i686.xsh`
- `./syno-i686-bootstrap_1.2-7_i686.xsh`
- `ipkg update`
- `ipkg upgrade`
- `ipkg install nano fdupes`

