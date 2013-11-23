LVDS-7-to-1-Serializer
======================

An Verilog implementation of 7-to-1 LVDS Serializer. Which can be used for comunicating FPGAs with LVDS TFT Screens.
Tested on Spartan 3A Evaluation Kit

*   Target Device: `xa3s400a-4ftg256`
*   Flip-flops used: 114
*   4 Input LUTs used: 140
*   Slices used: 127
*   DCMs used: 2
*   ODDR2 used: 4

The Serializer core is composed by `lvds_clockgen.v` and `serializer.v`. But I provided an example of how to use it with `maincore.v`, `video_lvds.v` that is both files for a Video Signal Generator to common notebook LVDS TFT Panels.
