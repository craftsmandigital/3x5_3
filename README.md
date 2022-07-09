# 3x5_3

the keyboard .../qmk_firmware/keyboards/handwired/dactyl_manuform/3x5_3 does not work, because there is different versions of the keyboard. This version of the keyboard is the most simple one with differs from the version maintained in qmk:
- This keyboard has the simplest comunication between the halfes --> Serial comunication and not I2C.
- This keyboard does not have anny LED matrix..

The only file changed from original config is the file config.h

### Here is how to use this:
- Delete .../qmk_firmware/keyboards/handwired/dactyl_manuform/3x5_3/config.h
- Copy the file config.h to destination .../qmk_firmware/keyboards/handwired/dactyl_manuform/3x5_3
