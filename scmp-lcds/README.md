
National Semiconductor SC/MP (Simple Low-Cost Microprocess) resources. Also resources for the Low Cost Development System for the SC/MP.

The following are ROM dumps from the LCDS. I used an Arduino to run through the addresses. They are named per the LCDS schematic.

The format is just ROM address then contents. If you need these in a different format please let me know and I may be able to write a little script to translate them as needed.

The ROM dumps are:

ROM-8E-ISP-8F-001B.raw
ROM-8F-ISP-8F-001A.raw
ROM_8G-ISP-8F-000B.raw
ROM_8H_ISP-8F-000A.raw

Example:
```
> head ROM-8E-ISP-8F-001B.raw
0 1C
1 C2
2 0
3 FC
4 0
5 94
6 A
7 C2
8 1
9 90
```
