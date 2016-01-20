#This documents describes in which way _aGamepad_ application sends data to PC

All data is send using UDP protocol on port 5000.

All data is in _Big Endian First_ format

`|4bytes|4bytes|4bytes|4bytes |`

`|z axis|x axis|y axis|buttons|`

### axis ###
Each axis has values from 0 to 150
### buttons ###
Protocol supports up to 32 buttons.

1 means button is down

0 means button is up