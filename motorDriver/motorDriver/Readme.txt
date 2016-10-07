-------- PROJECT GENERATOR --------
PROJECT NAME :	motorDriver
PROJECT DIRECTORY :	C:\WorkSpace\motorDriver\motorDriver
CPU SERIES :	RX200
CPU TYPE :	RX210
TOOLCHAIN NAME :	Renesas RX Standard Toolchain
TOOLCHAIN VERSION :	1.2.1.0
GENERATION FILES :
    C:\WorkSpace\motorDriver\motorDriver\dbsct.c
        Setting of B,R Section
    C:\WorkSpace\motorDriver\motorDriver\typedefine.h
        Aliases of Integer Type
    C:\WorkSpace\motorDriver\motorDriver\sbrk.c
        Program of sbrk
    C:\WorkSpace\motorDriver\motorDriver\iodefine.h
        Definition of I/O Register
    C:\WorkSpace\motorDriver\motorDriver\intprg.c
        Interrupt Program
    C:\WorkSpace\motorDriver\motorDriver\vecttbl.c
        Initialize of Vector Table
    C:\WorkSpace\motorDriver\motorDriver\vect.h
        Definition of Vector
    C:\WorkSpace\motorDriver\motorDriver\resetprg.c
        Reset Program
    C:\WorkSpace\motorDriver\motorDriver\motorDriver.c
        Main Program
    C:\WorkSpace\motorDriver\motorDriver\sbrk.h
        Header file of sbrk file
    C:\WorkSpace\motorDriver\motorDriver\stacksct.h
        Setting of Stack area
START ADDRESS OF SECTION :
 H'1000	B_1,R_1,B_2,R_2,B,R,SU,SI
 H'FFFF8000	PResetPRG
 H'FFFF8100	C_1,C_2,C,C$*,D_1,D_2,D,P,PIntPRG,W*,L
 H'FFFFFFD0	FIXEDVECT

* When the user program is executed,
* the interrupt mask has been masked.
* 
* Program start 0xFFFF8000.
* RAM start 0x1000.

SELECT TARGET :
    RX E1/E20 SYSTEM
DATE & TIME : 2016/10/07 20:00:27
