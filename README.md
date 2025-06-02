# Artsfest 2025 PoC PCBs

audio-test-board consist of an I2S DAC, connected to a headphone and speaker amp.

* DAC: Texas Instruments PCM5100A I2S DAC. This feeds both the headphone and the speaker amp
* Headphone amp: TI TPA6139A2RGTR, Speaker amp: TI TPA6211A1DGN
* Headphone jack: generic 3.5mm TRRS jack with normally-closed contacts on Tip and R1

touch-test-board breaks out an Infineon CY8CMBR3116 16-way capacitive touch sensing controller into a I2C interface, and 16 touch pads. Manufacture with ENIG for best results =)