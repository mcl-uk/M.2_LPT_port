# M.2_LPT_port
This is a hardware design for a an M.2 22x42 B-keyed LPT: parallel port based on the CH382L chip.
Although USB-to-LPT printer adapters are widely available they do not provide an actual Windows LPTx: port.
If, for example, you need support for a legacy parallel port security dongle (eg Sentinal for Mentor PADS) then you need a real, Windows LPTx: port.
Most modern PCs / motherboards no longer provide a hardware parallel port and while PCIe LPT add-in cards are widely available, compact form-factor PCs (like the NUC) do not include a PCIe slot.
One solution would be an external PCIe slot (usually targetted for graphics cards) connected via USB4 / Thunderbolt but these are bulky, expensive and in my experience unreliable.
A better solution would be an M.2 LPT card, but currently (2024) there are no commercially available options - hence this project.
The board has been tried and tested on a 12th gen Intel Core i5 NUC PC where it provides a reliable, fully functional LPT3: parallel port.
For those wanting to source one of these boards I can recommend JLCPCB who made and assembled my prototypes at modest cost.
All design files are provided here, including schematics, Gerber files for the 4-layer board, XY pick-and-place file, and BOM.
Note that the board must be 0.8mm thick and should have gold plating on the edge connector, also the crystal X1 is not required and RC1 should be omitted.
![M2BLPT](https://github.com/user-attachments/assets/cc2c6f83-16b1-47c6-a712-7730c051d392)
