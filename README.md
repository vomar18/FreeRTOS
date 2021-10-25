# FreeRTOS
from book Beginning STM32 by warren gay

st-flash read ./saved.img 0x8000000 0x1000 : read from device memory starting from 0x8000000 abd save 0x1000 (4K) of data
st-flash write ./saved.img 0x8000000 : write the image starting from 0x8000000
st-flash erase : cacella completamente la memoria (per regalarla ad un amico...)
/usr/bin/st-flash  write miniblink.bin 0x8000000
