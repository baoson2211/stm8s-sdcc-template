# stm8s-sdcc-template
STM8s template using Small Device C Complier (SDCC) and STM8S_StdPeriph_Driver libraries.<br />
Porting StdPeriph Driver to SDCC, see more [here](https://gist.github.com/baoson2211/f8b96f521b1f0c7d50959c24de129791)

**NOTE:** Several common libraries (e.g.:stdio.h, ctype.h, math.h, string.h, etc.), which are provided by SDCC,
have been modified and no longer resemble the traditional gcc compiler. You should refer to
[this document](http://sdcc.sourceforge.net/mediawiki/index.php/List_of_the_SDCC_library) before using them
