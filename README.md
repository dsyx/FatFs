# FatFs

[FatFs](http://elm-chan.org/fsw/ff/00index_e.html) is a generic FAT/exFAT filesystem module for small embedded systems. The FatFs module is written in compliance with ANSI C (C89) and completely separated from the disk I/O layer. Therefore it is independent of the platform. It can be incorporated into small microcontrollers with limited resource, such as 8051, PIC, AVR, ARM, Z80, RX and etc. 

> Note:
> 
> This is not an official repository, but a repository I created based on official archives.
> 
> The official website is: [http://elm-chan.org/fsw/ff/00index_e.html](http://elm-chan.org/fsw/ff/00index_e.html).

## About FatFs License

FatFs has being developped as a personal project of the author, ChaN. It is free from the code anyone else wrote at current release. Following code block shows a copy of the FatFs license document that included in the source files.

```c
/*----------------------------------------------------------------------------/
/  FatFs - Generic FAT Filesystem Module  Rx.xx                               /
/-----------------------------------------------------------------------------/
/
/ Copyright (C) 20xx, ChaN, all right reserved.
/
/ FatFs module is an open source software. Redistribution and use of FatFs in
/ source and binary forms, with or without modification, are permitted provided
/ that the following condition is met:
/
/ 1. Redistributions of source code must retain the above copyright notice,
/    this condition and the following disclaimer.
/
/ This software is provided by the copyright holder and contributors "AS IS"
/ and any warranties related to this software are DISCLAIMED.
/ The copyright owner or contributors be NOT LIABLE for any damages caused
/ by use of this software.
/----------------------------------------------------------------------------*/
```

Therefore FatFs license is one of the BSD-style licenses but there is a significant feature. FatFs is mainly intended for embedded systems. In order to extend the usability for commercial products, the redistributions of FatFs in binary form, such as embedded code, binary library and any forms without source code, does not need to include about FatFs in the documentations. This is equivalent to the 1-clause BSD license. Of course FatFs is compatible with the most of open source software licenses includes GNU GPL. When you redistribute the FatFs source code with any changes or create a fork, the license can also be changed to GNU GPL, BSD-style license or any open source software license that compatible with FatFs license.
