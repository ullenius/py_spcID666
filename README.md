# py_spcID666

Python script to read and modify the ID666 tag, base and extended (xid6), from a SNES SPC file.

Contributions welcome!

###Usage
From command line:
```sh
$ python spcid666.py snesmusic.spc
```

As a module:

```Python
import spcid666
tag = spcid666.parse('snesmusic.spc')
tag.base.game = 'Ramoutz'
spcid666.save(tag) #warning: saving xid6 not supported yet! xid6 will be lost!
```


###More info

http://wiki.superfamicom.org/snes/show/SPC+and+RSN+File+Format#extended-id666
http://www.johnloomis.org/cpe102/asgn/asgn1/riff.html

License
----
Free as in free beer! Any contribution is welcome.
