# EthMining
ETH Mining tutorial For Windows 10 NVIDIA GTX 1070

Mining instructions.
 
1)Go to bios> advanced >chipset config and configure the PC to turn on when power is feed. (this will make it turn on when it’s plugged in meaning that there is no need to turn it back on when there is a power outage)<br>
2)Install windows<br>
3)Set windows to not sleep<br>
4)Run with one video card
<br>5)Install the Nvidia Drivers
<br>6)Install visual studio community 2017
<br>7)Install cuda 8
<br>8)Install MSI afterburner<br>
9)Restart with all the video cards
<br>10)In afterburner set the cpu clock speed for -100 and up the memory speed until your cards allow. Mine went up by 600. (this will make your mining more efficient mine got to an avg of 30 MH/s per card)
<br>11)Install geth following this tutorial (Part 1): https://www.cryptocompare.com/mining/guides/how-to-mine-ethereum/
<br>12)Get Genoil miner from here: https://github.com/Genoil/cpp-ethereum/tree/master/releases Or get it from my drive with the start file ready from here: https://drive.google.com/open?id=0B9aQDGbOvTD0V0FNN0ZJMmh6Rmc
<br>13)Change the start file to where your address is the address that Geth created for you, miner name is how you want to name this pc (it is for when you have many):
<br>setx GPU_FORCE_64BIT_PTR 0
<br>setx GPU_MAX_HEAP_SIZE 100
<br>setx GPU_USE_SYNC_OBJECTS 1
<br>setx GPU_SINGLE_ALLOC_PERCENT 100
<br>setx GPU_MAX_ALLOC_PERCENT 100
<br>ethminer.exe -F http://eth-eu1.nanopool.org:8888/YOUR_ADDRESS/MINER_NAME/YOUR_EMAIL -U
<br>14) And start mining :)
<br>15)You can check your progress in eth,nanopool.org (there is a bit of a delay)
<br>16)To make your miner even more badass you can make it start mining as soon as you sign in by making your start file run on startup by following this tutorial: https://www.computerhope.com/issues/ch000322.htm
<br>17) I just saved you 4 hours of googling stuff ;)
 <br><br><br>
Happy mining feel free to donate ;)<br>
ETH: 0x2fc7723d8623eb414abb4fa6d81395d81b87a8f9

