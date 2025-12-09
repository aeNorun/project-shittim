# HP Mini PC issues
For me, the HP 800 G3 Mini has a major issue that is very weird. In the 35w variant of the HP 800 G3 Mini there is no fan under the sata ssd/hdd housing. 

<img width="300" src="https://github.com/user-attachments/assets/46e2cb7e-1b73-4395-ad59-2f9e676a9b2e" />
<img width="527" height="291" alt="Screenshot 2025-09-18 141023" src="https://github.com/user-attachments/assets/bd9efb9e-3165-4430-bd5d-299dd43950b0" />

In spite of not having a hdd fan from the factory, weirdly everytime I boot this mini PC this message shows up at every boot.




### Solution
THe solution is simply short the 2 pins to trick the bios firmware into thinking that theres a fan connected in the hddfan slot. Make sure the shorting solution to not touch the other cables. It will not work. 
