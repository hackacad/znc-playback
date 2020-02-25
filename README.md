An advanced playback module for ZNC
===================================

The advanced playback module for ZNC makes it possible for IRC clients
to avoid undesired repetitive buffer playback. IRC clients may request
the module to send a partial buffer playback starting from and ending
to a certain point of time. The detailed instructions are available at
http://wiki.znc.in/Playback.

Installation:
```
git clone https://github.com/jpnurmi/znc-playback
cd znc-playback
make
cp playback.so /path/to/znc/modules/
```

Got questions? Contact jpnurmi@gmail.com, or *jpnurmi* @ *#znc* on Freenode.
