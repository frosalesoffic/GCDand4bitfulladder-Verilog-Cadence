﻿<a name="br1"></a> 

**Fernando Rosales**

**862086644**

**Session 021**

**Frosales**

**Frosa009**



<a name="br2"></a> 

**Summary: For Lab 4 we use Design compiler and IC compiler to simulate Verilog code.**

**WE learn how to setup each environment to accept the files and how to convert them into**

**visual representations of the code. In this lab we create a 4bit full adder and a GCD circuit**

**using this method of simulation.**



<a name="br3"></a> 



<a name="br4"></a> 



<a name="br5"></a> 

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Report : timing

-path full

-delay max

-nets

-max\_paths 1

-transition\_time

Design : gcdGCDUnit\_rtl

Version: T-2022.03-SP3

Date : Wed Mar 15 00:14:57 2023

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Operating Conditions: TYPICAL Library: saed90nm\_typ

Wire Load Model Mode: top

Startpoint: GCDdpath0/A\_reg\_reg[9]

(rising edge-triggered flip-flop clocked by ideal\_clock1)

Endpoint: GCDdpath0/A\_reg\_reg[14]

(rising edge-triggered flip-flop clocked by ideal\_clock1)

Path Group: ideal\_clock1

Path Type: max

Attributes:

d - dont\_touch

u - dont\_use

mo - map\_only

so - size\_only

i - ideal\_net or ideal\_network

inf - infeasible path

Point

Fanout Trans

Incr

Path

Attributes

\---------------------------------------------------------------------------------------------------------

clock ideal\_clock1 (rise edge)

clock network delay (ideal)

0\.00

0\.00

0\.00

0\.00

GCDdpath0/A\_reg\_reg[9]/CLK (DFFARX1)

GCDdpath0/A\_reg\_reg[9]/Q (DFFARX1)

0\.00

0\.04

0\.24 f

0\.00

0\.24

0\.00 r

0\.24 f

result\_bits\_data[9] (net)

4

0\.00



<a name="br6"></a> 

U228/QN (NOR2X0)

n312 (net)

U139/QN (NOR2X0)

n142 (net)

U133/QN (NOR2X0)

n321 (net)

U157/QN (INVX0)

n157 (net)

U128/QN (NAND2X1)

n163 (net)

U248/QN (NAND2X1)

n206 (net)

U304/QN (INVX0)

n345 (net)

U314/Q (OA21X1)

n218 (net)

U315/Q (OA21X1)

n220 (net)

U317/Q (XNOR2X1)

n221 (net)

U318/QN (NAND2X0)

n225 (net)

U322/QN (NAND4X0)

n100 (net)

0\.08

0\.00

0\.05

0\.00

0\.07

0\.00

0\.03

0\.00

0\.05

0\.29 r

0\.05

0\.33 f

0\.04

0\.38 r

0\.03

0\.41 f

0\.03

0\.43 r

0\.03

0\.46 f

0\.04

0\.50 r

0\.09

0\.59 r

0\.09

0\.29 r

0\.33 f

0\.38 r

0\.41 f

0\.43 r

0\.46 f

0\.50 r

0\.59 r

0\.68 r

0\.80 r

0\.84 f

0\.88 r

0\.00

3

1

3

1

1

2

4

1

1

1

1

1

0\.04

0\.00

0\.04

0\.00

0\.05

0\.00

0\.04

0\.00

0\.04

0\.00

0\.04

0\.00

0\.06

0\.00

0\.07

0\.00

0\.68 r

0\.12

0\.80 r

0\.04

0\.84 f

0\.04

0\.88 r

0\.07

GCDdpath0/A\_reg\_reg[14]/D (DFFARX1)

data arrival time

0\.88 r

1\.00 r

0\.88

clock ideal\_clock1 (rise edge)

clock network delay (ideal)

GCDdpath0/A\_reg\_reg[14]/CLK (DFFARX1)

library setup time

1\.00

0\.00

1\.00

1\.00

0\.00

-0.12

0\.88

0\.88

data required time

\---------------------------------------------------------------------------------------------------------

data required time

data arrival time

0\.88

-0.88

\---------------------------------------------------------------------------------------------------------

slack (MET) 0.00

1



<a name="br7"></a> 



<a name="br8"></a> 



<a name="br9"></a> 



<a name="br10"></a> 



<a name="br11"></a> 



<a name="br12"></a> 

ISSUES: Overall there were no major issues this lab. Most of the simulations

and commands went smoothly. The only issues occurred during 2 commands. Both

times when using the insert\_stdcell\_filler this command would make a small

error appear but overall I do not believe it affected the lab majorly. Other

than that no other errors occurred during the lab assignment.



<a name="br13"></a> 


