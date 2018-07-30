#### For BIOS Modification purposes

* TSEnvironment.mod
  MMTool Offset : CC
  GUID : B1DA0ADF-4F77-4070-A88E-BFFE1C60529A

* Setup.mod
  MMTool Offset : 037
  GUID : 899407D7-99FE-43D8-9A21-79EC328CAC2

- VBios.bin
  Option ROM GUID : ED1F5A63-3B4B-4E8A-B8DF-880C03E46836

#### Important Offsets

* TSEnvironment.mod
  Goto 0x222c : Tabs order
  or 
  Search by hex : 00 4A 10 59 7B 0D C0 58 41 87 FF F0 4D 63 96 A9 15 11 27 00

* Setup.mod
  0x103ac : Chipset tab unsupression
  or
  Search by hex : 0A 82 46 02 (Better using Universal IFR Extractor insteads)
