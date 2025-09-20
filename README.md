backup firmware



Fuse setting:

Govibe rivo - fuse low: 0xE2, fuse high: 0xD9, extended fuse: 0xFD, lock bit: 0xFF

usbaspbootloader328p : -U lfuse:w:0xd7:m -U hfuse:w:0xd0:m -U efuse:w:0xfc:m -U lock:w:0x3f:m

usbaspbootloader32 : -U lfuse:w:0x1f:m -U hfuse:w:0xc0:m -U lock:w:0x3f:m
