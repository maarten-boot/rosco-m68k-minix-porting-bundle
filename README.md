# rosco-m68k-minix-porting-bundle
several repos/branches combined are needed to test and develop the minix port

create a dir 68k somewhere
checkout:
- Minix-st-2: https://github.com/maarten-boot/minix-st-2.0.4/tree/rosco-m68k
- ack: https://github.com/maarten-boot/ack/tree/rosco-minix68k
- emulator (mame): https://github.com/maarten-boot/rosco-emulator/tree/rosco-m68k-ram-bios
- r68k:  https://github.com/maarten-boot/r68k/tree/rosco-minix-duart

i let Claude work in the minix branch and tell it:
- where ack is to adapt it to minix.
- where r68k is for quick tests. 
- where mame (emulator) is for the more hw accurate tests.

when all is well i create a image and boot on hw
then i cut and paste relevant facts back to the Thing (claude) for further discussion.
