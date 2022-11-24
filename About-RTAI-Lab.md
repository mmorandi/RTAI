---
---

# About RTAI-Lab


The **RTAI-Lab** project provides a tool chain to develop block diagrams that can be compiled and executed on the [RTAI](http://www.rtai.org/) real-time Linux operating system. 
**RTAI-Lab** is included in the **RTAI** distribution.

Block diagrams can be developed using either [Scilab](http://www.scilab.org/)/[Scicos](http://www.scicos.org/) (Open Source) or [Matlab/Simulink](http://www.mathworks.com/products/simulink/)/[RTW](http://www.mathworks.com/products/rtw/) (commercial).

See also:

- RTAI-Lab tutorial for Scilab/Scicos and Linux
    [[PDF]](https://github.com/mmorandi/RTAI/blob/main/userfiles/downloads/RTAILAB/RTAI-Lab-tutorial.pdf), [[Tar archive with files]](https://github.com/mmorandi/RTAI/raw/main/userfiles/downloads/RTAILAB/RTAI-Lab-tutorial.tgz)
- Instructions to port Matlab/Simulink diagrams to RTAI:
    [RTAI-TARGET-HOWTO](https://github.com/mmorandi/RTAI/blob/main/userfiles/downloads/RTAILAB/RTAI-TARGET-HOWTO.txt)
    [RTAI-Lab repository](https://github.com/mmorandi/RTAI/tree/main/userfiles/downloads/RTAILAB)

![RTAI-Lab in action]({{ "userfiles/images/coverfigsmall4.gif" | relative_url }})

### RTAI-Lab main features

- Adds [RTAI-Lib palette](https://github.com/mmorandi/RTAI/blob/main/userfiles/downloads/RTAILAB/RTAILibPaletteKDE.gif) of **RTAI** blocks to [Scicos](http://www.scicos.org/) to develop real-time block diagrams
- Enables host and target systems to communicate via net_rpc
- xrtailab virtual oscilloscope and monitoring application lets you interact with the real-time executable
- Automatic real-time code generation from Scilab/Scicos
- Possibility to port Matlab/Simulink/Real-Time Workshop projects to **RTAI**
- Interfaces to signal acquisition hardware and other devices supported by [Comedi](http://www.comedi.org/)

### RTAI-Lab bug reports

To report bugs, ask questions, or submit improvements contact roberto.bucher at supsi.ch.For bug reports please provide Linux kernel version, **RTAI** version, **RTAI** patch number, CPU type, data acqusition hardware type, Scilab version, gcc/g++/cpp versions, the block diagram that may cause the bug (.cos file), outputs using verbose option "-v", and possibly kernel logs resulting from "tail -f /var/log/syslog".
**RTAI-Lab** project leaders

[Roberto Bucher](http://www.dti.supsi.ch/%7Ebucher), roberto.bucher at supsi.ch
[Lorenzo Dozio](https://www.aero.polimi.it/index.php?id=263&uid=60749&L=0), lorenzo.dozio at polimi.it
