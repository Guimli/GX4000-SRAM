# GX4000-SRAM

![Photo-01](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/Photo-01.jpg)

RAM replacement mod for GX4000 based on modern RAM. This mod can be used to replace the original RAM of the GX4000. And it is also possible to expand the GX4000's RAM to 128K.

![Top](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/GX4000-SRAM-128K-v2.1-Top.jpg)
![Bottom](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/GX4000-SRAM-128K-v2.1-Bottom.jpg)

This mod is inspired by the SRAM for C64 on https://github.com/jamarju/c64-sram

Video of the installation of this mod on the Twitch of RetroRedrum :
[![RetroRedrum - Amstrad GX4000 - 128k S-Ram mod](http://img.youtube.com/vi/3vgKoG_qG3Q/0.jpg)](https://www.youtube.com/watch?v=3vgKoG_qG3Q "RetroRedrum - Amstrad GX4000 - 128k S-Ram mod")

Approximate cost for one RAM mod (costs can be considerably reduced if you build several modules) :

- IS61C1024AL-12TLI : 3.28 €
- SN74HCT573PWR : 0.58 €
- SN74LVC1G08DBVR : 0.36 €
- SN74LVC1G32DBVR : 0.38 €
- R1 & R2 : 0.10 €
- C1 & C2 : 0.84 €
- PCB (minimum 5 + Shipping) : 14.95€
- IC10 & IC11 (Headers 20 pin) : 2.49€
- Round Pinheader (10x 1x40) : 8.19€

Total : 31,32€

I can sell you modules already assembled. But the shipping costs from France are prohibitive...

To enable the 128K mod, add a 10 kΩ resistor between pins 8 and 11 of IC8 (74HC4051).
![Photo-04](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/Photo-04.jpg)
And connect pin 91 of the ASIC to the dedicated CAS1 slot on the mod.
![Photo-02](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/Photo-02.jpg)
![Photo-03](https://github.com/Guimli/GX4000-SRAM/raw/main/Images/Photo-03.jpg)
(See https://www.cpcwiki.eu/index.php/128k_on_GX-4000 for more information)