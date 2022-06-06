EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A3 16535 11693
encoding utf-8
Sheet 1 1
Title "automated rice cooker"
Date "2020-11-22"
Rev ""
Comp "batch19 UOM"
Comment1 "group 19"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Regulator_Linear:L7805 U7
U 1 1 5FB9D425
P 3450 800
F 0 "U7" H 3450 1042 50  0000 C CNN
F 1 "L7805" H 3450 951 50  0000 C CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 3475 650 50  0001 L CIN
F 3 "http://www.st.com/content/ccc/resource/technical/document/datasheet/41/4f/b3/b0/12/d4/47/88/CD00000444.pdf/files/CD00000444.pdf/jcr:content/translations/en.CD00000444.pdf" H 3450 750 50  0001 C CNN
	1    3450 800 
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x02_Male J1
U 1 1 5FB9DE4F
P 1000 950
F 0 "J1" H 1108 1131 50  0000 C CNN
F 1 "INPUT" H 1108 1040 50  0000 C CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 1000 950 50  0001 C CNN
F 3 "~" H 1000 950 50  0001 C CNN
	1    1000 950 
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C4
U 1 1 5FB9E792
P 2900 950
F 0 "C4" H 3018 996 50  0000 L CNN
F 1 "220uf" H 3018 905 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P5.00mm" H 2938 800 50  0001 C CNN
F 3 "~" H 2900 950 50  0001 C CNN
	1    2900 950 
	1    0    0    -1  
$EndComp
$Comp
L Device:C C3
U 1 1 5FB9F9E6
P 2450 950
F 0 "C3" H 2565 996 50  0000 L CNN
F 1 "104" H 2565 905 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 2488 800 50  0001 C CNN
F 3 "~" H 2450 950 50  0001 C CNN
	1    2450 950 
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C8
U 1 1 5FBA1B28
P 4450 950
F 0 "C8" H 4568 996 50  0000 L CNN
F 1 "220uf" H 4568 905 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P5.00mm" H 4488 800 50  0001 C CNN
F 3 "~" H 4450 950 50  0001 C CNN
	1    4450 950 
	1    0    0    -1  
$EndComp
$Comp
L Device:C C7
U 1 1 5FBA1B2E
P 4000 950
F 0 "C7" H 4115 996 50  0000 L CNN
F 1 "104" H 4115 905 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 4038 800 50  0001 C CNN
F 3 "~" H 4000 950 50  0001 C CNN
	1    4000 950 
	1    0    0    -1  
$EndComp
Wire Wire Line
	2450 800  2900 800 
Connection ~ 2900 800 
Wire Wire Line
	2900 800  3150 800 
Wire Wire Line
	3750 800  4000 800 
Connection ~ 4000 800 
Wire Wire Line
	4000 800  4450 800 
Wire Wire Line
	4450 1100 4000 1100
Connection ~ 2900 1100
Wire Wire Line
	2900 1100 2450 1100
Connection ~ 3450 1100
Wire Wire Line
	3450 1100 2900 1100
Connection ~ 4000 1100
Text GLabel 1200 950  2    50   Input ~ 0
12VCC
$Comp
L power:GND #PWR01
U 1 1 5FBA2EDF
P 1200 1050
F 0 "#PWR01" H 1200 800 50  0001 C CNN
F 1 "GND" H 1205 877 50  0000 C CNN
F 2 "" H 1200 1050 50  0001 C CNN
F 3 "" H 1200 1050 50  0001 C CNN
	1    1200 1050
	1    0    0    -1  
$EndComp
Text GLabel 2450 800  0    50   Input ~ 0
12VCC
Text GLabel 4450 800  2    50   Input ~ 0
5VCC
$Comp
L power:GND #PWR06
U 1 1 5FBA5DBE
P 2450 1100
F 0 "#PWR06" H 2450 850 50  0001 C CNN
F 1 "GND" H 2455 927 50  0000 C CNN
F 2 "" H 2450 1100 50  0001 C CNN
F 3 "" H 2450 1100 50  0001 C CNN
	1    2450 1100
	1    0    0    -1  
$EndComp
$Comp
L Device:R R22
U 1 1 5FBA663E
P 7250 4100
F 0 "R22" H 7180 4054 50  0000 R CNN
F 1 "1k" H 7180 4145 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7180 4100 50  0001 C CNN
F 3 "~" H 7250 4100 50  0001 C CNN
	1    7250 4100
	0    1    1    0   
$EndComp
Text GLabel 7100 4100 0    50   Input ~ 0
5VCC
Text GLabel 1300 2100 0    50   Input ~ 0
wash_motor_pin
Text GLabel 3150 1450 1    50   Input ~ 0
12VCC
Wire Wire Line
	4050 1350 4050 1450
$Comp
L Connector:Conn_01x02_Female J3
U 1 1 5FBD1C0A
P 4450 1350
F 0 "J3" H 4478 1326 50  0000 L CNN
F 1 "Conn_01x02_Female" H 4478 1235 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 4450 1350 50  0001 C CNN
F 3 "~" H 4450 1350 50  0001 C CNN
	1    4450 1350
	1    0    0    -1  
$EndComp
Wire Wire Line
	4250 1350 4050 1350
Wire Wire Line
	3650 1450 3650 1350
$Comp
L power:GND #PWR08
U 1 1 5FBDA053
P 2950 2600
F 0 "#PWR08" H 2950 2350 50  0001 C CNN
F 1 "GND" H 2955 2427 50  0000 C CNN
F 2 "" H 2950 2600 50  0001 C CNN
F 3 "" H 2950 2600 50  0001 C CNN
	1    2950 2600
	1    0    0    -1  
$EndComp
$Comp
L Device:R R3
U 1 1 5FC044A7
P 1550 3600
F 0 "R3" V 1343 3600 50  0000 C CNN
F 1 "1k" V 1434 3600 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1480 3600 50  0001 C CNN
F 3 "~" H 1550 3600 50  0001 C CNN
	1    1550 3600
	0    1    1    0   
$EndComp
Wire Wire Line
	2950 3800 2900 3800
Wire Wire Line
	3000 3600 2900 3600
Text GLabel 2150 4600 0    50   Input ~ 0
dc_motor1
Wire Wire Line
	2300 4100 2300 3900
Text GLabel 3400 3000 1    50   Input ~ 0
12VCC
$Comp
L Connector:Conn_01x02_Female J5
U 1 1 5FC044CF
P 4800 2800
F 0 "J5" H 4828 2776 50  0000 L CNN
F 1 "Conn_01x02_Female" H 4828 2685 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 4800 2800 50  0001 C CNN
F 3 "~" H 4800 2800 50  0001 C CNN
	1    4800 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	3400 3600 3250 3600
$Comp
L Device:R R19
U 1 1 5FC135EE
P 3550 4450
F 0 "R19" H 3480 4404 50  0000 R CNN
F 1 "100" H 3480 4495 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3480 4450 50  0001 C CNN
F 3 "~" H 3550 4450 50  0001 C CNN
	1    3550 4450
	-1   0    0    1   
$EndComp
$Comp
L Device:R R7
U 1 1 5FC135F4
P 2300 4600
F 0 "R7" V 2093 4600 50  0000 C CNN
F 1 "1k" V 2184 4600 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2230 4600 50  0001 C CNN
F 3 "~" H 2300 4600 50  0001 C CNN
	1    2300 4600
	0    1    1    0   
$EndComp
Wire Wire Line
	3550 4600 3450 4600
Wire Wire Line
	4250 1450 4250 2600
$Comp
L Transistor_BJT:BC548 Q3
U 1 1 5FC19F8E
P 3150 3800
F 0 "Q3" H 3341 3846 50  0000 L CNN
F 1 "BC548" H 3341 3755 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 3350 3725 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 3150 3800 50  0001 L CNN
	1    3150 3800
	1    0    0    -1  
$EndComp
Wire Wire Line
	4300 3000 4600 3000
Wire Wire Line
	4600 2900 4600 2950
Wire Wire Line
	4100 3000 4100 2900
Wire Wire Line
	4550 2900 4550 2800
Wire Wire Line
	4550 2800 4600 2800
Wire Wire Line
	4550 2800 3900 2800
Wire Wire Line
	3900 2800 3900 3000
Connection ~ 4550 2800
Wire Wire Line
	4600 2950 3700 2950
Connection ~ 4600 2950
Wire Wire Line
	4600 2950 4600 3000
Wire Wire Line
	4200 3550 4200 3600
Text GLabel 3550 2050 3    50   Input ~ 0
12VCC
Wire Wire Line
	3550 2050 3950 2050
Text GLabel 4200 3600 3    50   Input ~ 0
12VCC
$Comp
L power:GND #PWR05
U 1 1 5FC755B9
P 3250 4100
F 0 "#PWR05" H 3250 3850 50  0001 C CNN
F 1 "GND" H 3255 3927 50  0000 C CNN
F 2 "" H 3250 4100 50  0001 C CNN
F 3 "" H 3250 4100 50  0001 C CNN
	1    3250 4100
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 U2
U 1 1 5FCA0211
P 2350 6250
F 0 "U2" H 2350 6575 50  0000 C CNN
F 1 "PC817" H 2350 6484 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 2150 6050 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 2350 6250 50  0001 L CNN
	1    2350 6250
	1    0    0    -1  
$EndComp
$Comp
L Device:R R11
U 1 1 5FCA0217
P 2750 6000
F 0 "R11" H 2680 5954 50  0000 R CNN
F 1 "1k" H 2680 6045 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2680 6000 50  0001 C CNN
F 3 "~" H 2750 6000 50  0001 C CNN
	1    2750 6000
	-1   0    0    1   
$EndComp
$Comp
L Device:R R2
U 1 1 5FCA021D
P 1550 6150
F 0 "R2" V 1343 6150 50  0000 C CNN
F 1 "1k" V 1434 6150 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1480 6150 50  0001 C CNN
F 3 "~" H 1550 6150 50  0001 C CNN
	1    1550 6150
	0    1    1    0   
$EndComp
$Comp
L Device:R R9
U 1 1 5FCA0223
P 2700 6500
F 0 "R9" H 2770 6546 50  0000 L CNN
F 1 "10k" H 2770 6455 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2630 6500 50  0001 C CNN
F 3 "~" H 2700 6500 50  0001 C CNN
	1    2700 6500
	1    0    0    -1  
$EndComp
Wire Wire Line
	2750 6350 2700 6350
Connection ~ 2650 6350
Wire Wire Line
	2650 6350 2600 6350
Connection ~ 2700 6350
Wire Wire Line
	2700 6350 2650 6350
Wire Wire Line
	2750 6150 2650 6150
Text GLabel 1800 7150 0    50   Input ~ 0
dc_motor2
Wire Wire Line
	2700 6650 2050 6650
Wire Wire Line
	2050 6650 2050 6450
Text GLabel 3150 5550 1    50   Input ~ 0
12VCC
$Comp
L Connector:Conn_01x02_Female J4
U 1 1 5FCA0234
P 4550 5350
F 0 "J4" H 4578 5326 50  0000 L CNN
F 1 "Conn_01x02_Female" H 4578 5235 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 4550 5350 50  0001 C CNN
F 3 "~" H 4550 5350 50  0001 C CNN
	1    4550 5350
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR07
U 1 1 5FCA023A
P 3550 7650
F 0 "#PWR07" H 3550 7400 50  0001 C CNN
F 1 "GND" H 3555 7477 50  0000 C CNN
F 2 "" H 3550 7650 50  0001 C CNN
F 3 "" H 3550 7650 50  0001 C CNN
	1    3550 7650
	1    0    0    -1  
$EndComp
Wire Wire Line
	3150 6150 3000 6150
$Comp
L Isolator:PC817 U4
U 1 1 5FCA0241
P 2900 7250
F 0 "U4" H 2900 7575 50  0000 C CNN
F 1 "PC817" H 2900 7484 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 2700 7050 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 2900 7250 50  0001 L CNN
	1    2900 7250
	1    0    0    -1  
$EndComp
$Comp
L Device:R R16
U 1 1 5FCA0247
P 3300 7000
F 0 "R16" H 3230 6954 50  0000 R CNN
F 1 "100" H 3230 7045 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3230 7000 50  0001 C CNN
F 3 "~" H 3300 7000 50  0001 C CNN
	1    3300 7000
	-1   0    0    1   
$EndComp
$Comp
L Device:R R4
U 1 1 5FCA024D
P 1950 7150
F 0 "R4" V 1743 7150 50  0000 C CNN
F 1 "1k" V 1834 7150 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 7150 50  0001 C CNN
F 3 "~" H 1950 7150 50  0001 C CNN
	1    1950 7150
	0    1    1    0   
$EndComp
$Comp
L Device:R R15
U 1 1 5FCA0253
P 3250 7500
F 0 "R15" H 3320 7546 50  0000 L CNN
F 1 "10k" H 3320 7455 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3180 7500 50  0001 C CNN
F 3 "~" H 3250 7500 50  0001 C CNN
	1    3250 7500
	1    0    0    -1  
$EndComp
Wire Wire Line
	3300 7350 3250 7350
Connection ~ 3250 7350
Wire Wire Line
	3250 7350 3200 7350
Wire Wire Line
	3300 7150 3200 7150
Wire Wire Line
	3250 7650 2600 7650
Wire Wire Line
	2600 7650 2600 7450
$Comp
L Transistor_FET:IRF540N Q4
U 1 1 5FCA0262
P 3450 7350
F 0 "Q4" H 3654 7396 50  0000 L CNN
F 1 "IRF540N" H 3654 7305 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 3700 7275 50  0001 L CIN
F 3 "http://www.irf.com/product-info/datasheets/data/irf540n.pdf" H 3450 7350 50  0001 L CNN
	1    3450 7350
	1    0    0    -1  
$EndComp
$Comp
L Transistor_BJT:BC548 Q2
U 1 1 5FCA0268
P 2900 6350
F 0 "Q2" H 3091 6396 50  0000 L CNN
F 1 "BC548" H 3091 6305 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 3100 6275 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 2900 6350 50  0001 L CNN
	1    2900 6350
	1    0    0    -1  
$EndComp
Wire Wire Line
	4050 5550 4350 5550
Wire Wire Line
	3850 5550 3850 5450
Wire Wire Line
	3850 5450 4300 5450
Wire Wire Line
	4300 5450 4300 5350
Wire Wire Line
	4300 5350 4350 5350
Wire Wire Line
	4300 5350 3650 5350
Wire Wire Line
	3650 5350 3650 5550
Connection ~ 4300 5350
Wire Wire Line
	3950 6100 3950 6150
Text GLabel 3950 6150 3    50   Input ~ 0
12VCC
Wire Wire Line
	3550 6150 3550 7150
$Comp
L power:GND #PWR04
U 1 1 5FCA0288
P 3000 6650
F 0 "#PWR04" H 3000 6400 50  0001 C CNN
F 1 "GND" H 3005 6477 50  0000 C CNN
F 2 "" H 3000 6650 50  0001 C CNN
F 3 "" H 3000 6650 50  0001 C CNN
	1    3000 6650
	1    0    0    -1  
$EndComp
Text GLabel 3550 4300 1    50   Input ~ 0
5VCC
Text GLabel 2750 5850 1    50   Input ~ 0
5VCC
Text GLabel 3300 6850 1    50   Input ~ 0
5VCC
$Comp
L Device:R R24
U 1 1 5FBC33BC
P 11550 2050
F 0 "R24" V 11343 2050 50  0000 C CNN
F 1 "1k" V 11434 2050 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 11480 2050 50  0001 C CNN
F 3 "~" H 11550 2050 50  0001 C CNN
	1    11550 2050
	0    1    1    0   
$EndComp
Wire Wire Line
	12400 2550 12400 2350
$Comp
L Device:R R25
U 1 1 5FBCE21D
P 11500 3550
F 0 "R25" V 11293 3550 50  0000 C CNN
F 1 "1k" V 11384 3550 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 11430 3550 50  0001 C CNN
F 3 "~" H 11500 3550 50  0001 C CNN
	1    11500 3550
	0    1    1    0   
$EndComp
Wire Wire Line
	12400 4050 12400 3850
$Comp
L Device:R R26
U 1 1 5FBD986E
P 11900 5100
F 0 "R26" V 11693 5100 50  0000 C CNN
F 1 "1k" V 11784 5100 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 11830 5100 50  0001 C CNN
F 3 "~" H 11900 5100 50  0001 C CNN
	1    11900 5100
	0    1    1    0   
$EndComp
$Comp
L Device:R R31
U 1 1 5FBD987A
P 13100 5450
F 0 "R31" H 13170 5496 50  0000 L CNN
F 1 "10k" H 13170 5405 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 13030 5450 50  0001 C CNN
F 3 "~" H 13100 5450 50  0001 C CNN
	1    13100 5450
	1    0    0    -1  
$EndComp
Wire Wire Line
	13150 5300 13100 5300
Connection ~ 13100 5300
Wire Wire Line
	13100 5600 12450 5600
Wire Wire Line
	12450 5600 12450 5400
$Comp
L power:GND #PWR014
U 1 1 5FBD9898
P 13450 5600
F 0 "#PWR014" H 13450 5350 50  0001 C CNN
F 1 "GND" H 13455 5427 50  0000 C CNN
F 2 "" H 13450 5600 50  0001 C CNN
F 3 "" H 13450 5600 50  0001 C CNN
	1    13450 5600
	1    0    0    -1  
$EndComp
Wire Wire Line
	13450 5600 13100 5600
Wire Wire Line
	13450 5500 13450 5600
Connection ~ 13100 5600
Connection ~ 13450 5600
Text GLabel 11400 2050 0    50   Input ~ 0
solonid_in
Text GLabel 11350 3550 0    50   Input ~ 0
solonid_out
Text GLabel 9700 7500 2    50   Input ~ 0
solonid_out
Text GLabel 11750 5100 0    50   Input ~ 0
ricecooker_on
$Comp
L Isolator:PC817 U12
U 1 1 5FD2B427
P 13750 6550
F 0 "U12" H 13750 6875 50  0000 C CNN
F 1 "PC817" H 13750 6784 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 13550 6350 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 13750 6550 50  0001 L CNN
	1    13750 6550
	1    0    0    -1  
$EndComp
$Comp
L Device:R R35
U 1 1 5FD2B42D
P 14150 6300
F 0 "R35" H 14080 6254 50  0000 R CNN
F 1 "1k" H 14080 6345 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 14080 6300 50  0001 C CNN
F 3 "~" H 14150 6300 50  0001 C CNN
	1    14150 6300
	-1   0    0    1   
$EndComp
$Comp
L Device:R R33
U 1 1 5FD2B433
P 12900 6450
F 0 "R33" V 12693 6450 50  0000 C CNN
F 1 "1k" V 12784 6450 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 12830 6450 50  0001 C CNN
F 3 "~" H 12900 6450 50  0001 C CNN
	1    12900 6450
	0    1    1    0   
$EndComp
$Comp
L Transistor_BJT:BC548 Q9
U 1 1 5FD2B439
P 14350 6650
F 0 "Q9" H 14541 6696 50  0000 L CNN
F 1 "BC548" H 14541 6605 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 14550 6575 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 14350 6650 50  0001 L CNN
	1    14350 6650
	1    0    0    -1  
$EndComp
$Comp
L Device:R R34
U 1 1 5FD2B43F
P 14100 6800
F 0 "R34" H 14170 6846 50  0000 L CNN
F 1 "10k" H 14170 6755 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 14030 6800 50  0001 C CNN
F 3 "~" H 14100 6800 50  0001 C CNN
	1    14100 6800
	1    0    0    -1  
$EndComp
Wire Wire Line
	14150 6650 14100 6650
Connection ~ 14050 6650
Wire Wire Line
	14050 6650 14000 6650
Connection ~ 14100 6650
Wire Wire Line
	14100 6650 14050 6650
Wire Wire Line
	14150 6450 14050 6450
Wire Wire Line
	14100 6950 13450 6950
Wire Wire Line
	13450 6950 13450 6750
Text GLabel 14650 6300 1    50   Input ~ 0
12VCC
Wire Wire Line
	14650 6400 14450 6400
Wire Wire Line
	14450 6400 14450 6450
$Comp
L power:GND #PWR015
U 1 1 5FD2B451
P 14450 6950
F 0 "#PWR015" H 14450 6700 50  0001 C CNN
F 1 "GND" H 14455 6777 50  0000 C CNN
F 2 "" H 14450 6950 50  0001 C CNN
F 3 "" H 14450 6950 50  0001 C CNN
	1    14450 6950
	1    0    0    -1  
$EndComp
Wire Wire Line
	14450 6950 14100 6950
Wire Wire Line
	14450 6850 14450 6950
Connection ~ 14100 6950
Connection ~ 14450 6950
Text GLabel 14150 6150 1    50   Input ~ 0
5VCC
$Comp
L Connector:Conn_01x02_Female J11
U 1 1 5FD332FC
P 14850 6300
F 0 "J11" H 14878 6276 50  0000 L CNN
F 1 "Conn_01x02_Female" H 14878 6185 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 14850 6300 50  0001 C CNN
F 3 "~" H 14850 6300 50  0001 C CNN
	1    14850 6300
	1    0    0    -1  
$EndComp
Text GLabel 12750 6450 0    50   Input ~ 0
buzzer_pin
Text GLabel 13500 7750 0    50   Input ~ 0
SDA
Text GLabel 13550 8000 0    50   Input ~ 0
SCL
$Comp
L Connector:Conn_01x02_Female J9
U 1 1 5FD60527
P 14150 7650
F 0 "J9" H 14178 7626 50  0000 L CNN
F 1 "Conn_01x02_Female" H 14178 7535 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 14150 7650 50  0001 C CNN
F 3 "~" H 14150 7650 50  0001 C CNN
	1    14150 7650
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x02_Female J10
U 1 1 5FD6187A
P 14150 8000
F 0 "J10" H 14178 7976 50  0000 L CNN
F 1 "Conn_01x02_Female" H 14178 7885 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 14150 8000 50  0001 C CNN
F 3 "~" H 14150 8000 50  0001 C CNN
	1    14150 8000
	1    0    0    -1  
$EndComp
Wire Wire Line
	13950 7750 13950 8000
Wire Wire Line
	13950 8000 13550 8000
Connection ~ 13950 8000
Wire Wire Line
	13950 8100 13850 8100
Wire Wire Line
	13850 8100 13850 7750
Wire Wire Line
	13850 7750 13500 7750
Wire Wire Line
	13850 7750 13850 7650
Wire Wire Line
	13850 7650 13950 7650
Connection ~ 13850 7750
Text GLabel 9700 6000 2    50   Input ~ 0
SDA
Text GLabel 1400 3600 0    50   Input ~ 0
dc_motor1_derec
Text GLabel 1400 6150 0    50   Input ~ 0
dc_motor2_derec
Text GLabel 9200 6300 2    50   Input ~ 0
dc_motor2_derec
Text GLabel 9700 7100 2    50   Input ~ 0
wash_motor_pin
Text GLabel 9700 6900 2    50   Input ~ 0
Tx
$Comp
L Device:R R14
U 1 1 5FC51762
P 3000 8200
F 0 "R14" H 3070 8246 50  0000 L CNN
F 1 "10k" H 3070 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2930 8200 50  0001 C CNN
F 3 "~" H 3000 8200 50  0001 C CNN
	1    3000 8200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R21
U 1 1 5FC527CF
P 3850 8200
F 0 "R21" H 3920 8246 50  0000 L CNN
F 1 "10k" H 3920 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3780 8200 50  0001 C CNN
F 3 "~" H 3850 8200 50  0001 C CNN
	1    3850 8200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R10
U 1 1 5FC5C0C6
P 2700 8200
F 0 "R10" H 2770 8246 50  0000 L CNN
F 1 "10k" H 2770 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2630 8200 50  0001 C CNN
F 3 "~" H 2700 8200 50  0001 C CNN
	1    2700 8200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R17
U 1 1 5FC64EB8
P 3300 8200
F 0 "R17" H 3370 8246 50  0000 L CNN
F 1 "10k" H 3370 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3230 8200 50  0001 C CNN
F 3 "~" H 3300 8200 50  0001 C CNN
	1    3300 8200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R20
U 1 1 5FC6DCAA
P 3550 8200
F 0 "R20" H 3620 8246 50  0000 L CNN
F 1 "10k" H 3620 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3480 8200 50  0001 C CNN
F 3 "~" H 3550 8200 50  0001 C CNN
	1    3550 8200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R5
U 1 1 5FC77E22
P 2400 8200
F 0 "R5" H 2470 8246 50  0000 L CNN
F 1 "10k" H 2470 8155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2330 8200 50  0001 C CNN
F 3 "~" H 2400 8200 50  0001 C CNN
	1    2400 8200
	1    0    0    -1  
$EndComp
Wire Wire Line
	3850 8050 3550 8050
Wire Wire Line
	3550 8050 3300 8050
Connection ~ 3550 8050
Wire Wire Line
	3300 8050 3000 8050
Connection ~ 3300 8050
Wire Wire Line
	3000 8050 2700 8050
Connection ~ 3000 8050
Wire Wire Line
	2700 8050 2400 8050
Connection ~ 2700 8050
Wire Wire Line
	2100 9100 3850 9100
Wire Wire Line
	3850 8350 3850 9100
Connection ~ 3850 9100
Wire Wire Line
	2100 9000 3550 9000
Wire Wire Line
	2100 8800 3000 8800
Wire Wire Line
	2100 8600 2400 8600
Wire Wire Line
	3550 8350 3550 9000
Connection ~ 3550 9000
Wire Wire Line
	3300 8350 3300 8900
Wire Wire Line
	3000 8350 3000 8800
Connection ~ 3000 8800
Wire Wire Line
	2400 8350 2400 8600
Connection ~ 2400 8600
Connection ~ 2400 8050
$Comp
L power:GND #PWR02
U 1 1 5FD996E9
P 2200 8050
F 0 "#PWR02" H 2200 7800 50  0001 C CNN
F 1 "GND" H 2205 7877 50  0000 C CNN
F 2 "" H 2200 8050 50  0001 C CNN
F 3 "" H 2200 8050 50  0001 C CNN
	1    2200 8050
	0    1    1    0   
$EndComp
Text GLabel 6300 7500 2    50   Input ~ 0
wash_lim_down
Text GLabel 9750 5000 2    50   Input ~ 0
wash_lim_down
Text GLabel 6400 8250 2    50   Input ~ 0
cooker_lim_down
Text GLabel 9800 5200 2    50   Input ~ 0
cooker_lim_down
Text GLabel 6450 8600 2    50   Input ~ 0
cooker_lim_up
Text GLabel 6550 8950 2    50   Input ~ 0
cooker_set_lim
Text GLabel 9800 5400 2    50   Input ~ 0
cooker_set_lim
Text GLabel 6350 9350 2    50   Input ~ 0
finished_pin
Text GLabel 9700 7300 2    50   Input ~ 0
PD_SCK_PIN
Wire Wire Line
	12600 8750 12250 8750
Wire Wire Line
	12600 8850 12000 8850
Wire Wire Line
	12600 8950 12000 8950
Wire Wire Line
	12600 9050 12250 9050
Text GLabel 12000 8850 0    50   Input ~ 0
Tx
Text GLabel 12250 8750 0    50   Input ~ 0
Rx
Text GLabel 4600 9950 0    50   Input ~ 0
servo_pin
Text GLabel 12250 9050 0    50   Input ~ 0
DOUT_PIN
Text GLabel 12000 8950 0    50   Input ~ 0
PD_SCK_PIN
Text GLabel 9750 4200 2    50   Input ~ 0
echo_pin
Text GLabel 9750 4400 2    50   Input ~ 0
joystick_ok
$Comp
L Device:R R23
U 1 1 6001F437
P 8600 10050
F 0 "R23" H 8670 10096 50  0000 L CNN
F 1 "10k" H 8670 10005 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 8530 10050 50  0001 C CNN
F 3 "~" H 8600 10050 50  0001 C CNN
	1    8600 10050
	-1   0    0    1   
$EndComp
$Comp
L Connector:Conn_01x04_Female J8
U 1 1 6014F849
P 12800 8850
F 0 "J8" H 12828 8826 50  0000 L CNN
F 1 "Conn_01x04_Female" H 12828 8735 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-4-5.08_1x04_P5.08mm_Horizontal" H 12800 8850 50  0001 C CNN
F 3 "~" H 12800 8850 50  0001 C CNN
	1    12800 8850
	1    0    0    -1  
$EndComp
$Comp
L Regulator_Linear:L7805 U5
U 1 1 60163A05
P 2900 9850
F 0 "U5" H 2900 10092 50  0000 C CNN
F 1 "L7805" H 2900 10001 50  0000 C CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 2925 9700 50  0001 L CIN
F 3 "http://www.st.com/content/ccc/resource/technical/document/datasheet/41/4f/b3/b0/12/d4/47/88/CD00000444.pdf/files/CD00000444.pdf/jcr:content/translations/en.CD00000444.pdf" H 2900 9800 50  0001 C CNN
	1    2900 9850
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C2
U 1 1 60163A0B
P 2350 10000
F 0 "C2" H 2468 10046 50  0000 L CNN
F 1 "220uf" H 2468 9955 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P5.00mm" H 2388 9850 50  0001 C CNN
F 3 "~" H 2350 10000 50  0001 C CNN
	1    2350 10000
	1    0    0    -1  
$EndComp
$Comp
L Device:C C1
U 1 1 60163A11
P 1900 10000
F 0 "C1" H 2015 10046 50  0000 L CNN
F 1 "104" H 2015 9955 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 1938 9850 50  0001 C CNN
F 3 "~" H 1900 10000 50  0001 C CNN
	1    1900 10000
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C6
U 1 1 60163A17
P 3900 10000
F 0 "C6" H 4018 10046 50  0000 L CNN
F 1 "220uf" H 4018 9955 50  0000 L CNN
F 2 "Capacitor_THT:CP_Radial_D10.0mm_P5.00mm" H 3938 9850 50  0001 C CNN
F 3 "~" H 3900 10000 50  0001 C CNN
	1    3900 10000
	1    0    0    -1  
$EndComp
$Comp
L Device:C C5
U 1 1 60163A1D
P 3450 10000
F 0 "C5" H 3565 10046 50  0000 L CNN
F 1 "104" H 3565 9955 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 3488 9850 50  0001 C CNN
F 3 "~" H 3450 10000 50  0001 C CNN
	1    3450 10000
	1    0    0    -1  
$EndComp
Wire Wire Line
	1900 9850 2350 9850
Wire Wire Line
	3200 9850 3450 9850
Connection ~ 3450 9850
Wire Wire Line
	3450 9850 3900 9850
Wire Wire Line
	3900 10150 3450 10150
Connection ~ 2350 10150
Wire Wire Line
	2350 10150 1900 10150
Connection ~ 2900 10150
Connection ~ 3450 10150
Text GLabel 1900 9850 0    50   Input ~ 0
12VCC
$Comp
L power:GND #PWR03
U 1 1 60163A32
P 2900 10150
F 0 "#PWR03" H 2900 9900 50  0001 C CNN
F 1 "GND" H 2905 9977 50  0000 C CNN
F 2 "" H 2900 10150 50  0001 C CNN
F 3 "" H 2900 10150 50  0001 C CNN
	1    2900 10150
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x03_Female J6
U 1 1 60177808
P 4800 9950
F 0 "J6" H 4828 9976 50  0000 L CNN
F 1 "Conn_01x03_Female" H 4828 9885 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-3-5.08_1x03_P5.08mm_Horizontal" H 4800 9950 50  0001 C CNN
F 3 "~" H 4800 9950 50  0001 C CNN
	1    4800 9950
	1    0    0    -1  
$EndComp
Wire Wire Line
	3900 9850 4600 9850
Connection ~ 3900 9850
Wire Wire Line
	3900 10150 4600 10150
Wire Wire Line
	4600 10150 4600 10050
Connection ~ 3900 10150
$Comp
L Device:Crystal Y1
U 1 1 602A7D0D
P 8050 2300
F 0 "Y1" H 8050 2568 50  0000 C CNN
F 1 "16mhz" H 8050 2477 50  0000 C CNN
F 2 "Crystal:Crystal_HC49-4H_Vertical" H 8050 2300 50  0001 C CNN
F 3 "~" H 8050 2300 50  0001 C CNN
	1    8050 2300
	0    -1   -1   0   
$EndComp
$Comp
L pspice:CAP C9
U 1 1 602A8FAD
P 7300 1850
F 0 "C9" H 7478 1896 50  0000 L CNN
F 1 "22uf" H 7478 1805 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 7300 1850 50  0001 C CNN
F 3 "~" H 7300 1850 50  0001 C CNN
	1    7300 1850
	0    -1   -1   0   
$EndComp
$Comp
L pspice:CAP C10
U 1 1 602A9F4D
P 7300 2650
F 0 "C10" H 7478 2696 50  0000 L CNN
F 1 "22uf" H 7478 2605 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W2.0mm_P2.50mm" H 7300 2650 50  0001 C CNN
F 3 "~" H 7300 2650 50  0001 C CNN
	1    7300 2650
	0    -1   -1   0   
$EndComp
Wire Wire Line
	7050 1850 7050 2650
Wire Wire Line
	7550 1850 8050 1850
Wire Wire Line
	7550 2650 8050 2650
Wire Wire Line
	8050 1850 8050 2150
Connection ~ 8050 2150
Wire Wire Line
	8050 2150 8050 2200
Connection ~ 8050 1850
Wire Wire Line
	8050 1850 9150 1850
Wire Wire Line
	8050 2450 8050 2650
Connection ~ 8050 2650
Wire Wire Line
	8050 2650 9150 2650
Text GLabel 9150 1850 2    50   Input ~ 0
XTL1
Text GLabel 9150 2650 2    50   Input ~ 0
XTL2
$Comp
L power:GND #PWR010
U 1 1 603C1E35
P 7050 2650
F 0 "#PWR010" H 7050 2400 50  0001 C CNN
F 1 "GND" H 7055 2477 50  0000 C CNN
F 2 "" H 7050 2650 50  0001 C CNN
F 3 "" H 7050 2650 50  0001 C CNN
	1    7050 2650
	1    0    0    -1  
$EndComp
Connection ~ 7050 2650
Text GLabel 6400 7850 2    50   Input ~ 0
wash_lim_up
Wire Wire Line
	3250 4000 3250 4100
Wire Wire Line
	3000 6550 3000 6650
Wire Wire Line
	3000 6650 2700 6650
Connection ~ 2700 6650
Wire Wire Line
	3550 7550 3550 7650
Wire Wire Line
	3550 7650 3250 7650
Connection ~ 3250 7650
Connection ~ 3000 6650
Connection ~ 3550 7650
NoConn ~ 25900 -650
Wire Wire Line
	4100 2900 4550 2900
Wire Wire Line
	3650 1350 4050 1350
Connection ~ 1750 2100
Wire Wire Line
	1750 2100 1950 2100
Wire Wire Line
	1750 2100 1600 2100
$Comp
L Device:R R12
U 1 1 6059D4D2
P 1750 2250
F 0 "R12" H 1820 2296 50  0000 L CNN
F 1 "1k" H 1820 2205 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1680 2250 50  0001 C CNN
F 3 "~" H 1750 2250 50  0001 C CNN
	1    1750 2250
	1    0    0    -1  
$EndComp
Text GLabel 3000 3300 1    50   Input ~ 0
5VCC
Text GLabel 2650 1800 1    50   Input ~ 0
5VCC
Connection ~ 2950 2600
Connection ~ 2600 2600
Wire Wire Line
	2950 2500 2950 2600
Wire Wire Line
	2950 2600 2600 2600
$Comp
L Device:R R13
U 1 1 5FC044A1
P 3000 3450
F 0 "R13" H 2930 3404 50  0000 R CNN
F 1 "1k" H 2930 3495 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2930 3450 50  0001 C CNN
F 3 "~" H 3000 3450 50  0001 C CNN
	1    3000 3450
	-1   0    0    1   
$EndComp
Wire Wire Line
	2950 2050 2950 2100
Wire Wire Line
	3150 2050 2950 2050
Wire Wire Line
	2600 2600 1950 2600
Wire Wire Line
	2650 2100 2550 2100
Wire Wire Line
	2600 2300 2550 2300
Connection ~ 2600 2300
Wire Wire Line
	2650 2300 2600 2300
$Comp
L Device:R R6
U 1 1 5FBADA06
P 2600 2450
F 0 "R6" H 2670 2496 50  0000 L CNN
F 1 "10k" H 2670 2405 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2530 2450 50  0001 C CNN
F 3 "~" H 2600 2450 50  0001 C CNN
	1    2600 2450
	1    0    0    -1  
$EndComp
$Comp
L Transistor_BJT:BC548 Q1
U 1 1 5FBA8CF2
P 2850 2300
F 0 "Q1" H 3041 2346 50  0000 L CNN
F 1 "BC548" H 3041 2255 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 3050 2225 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 2850 2300 50  0001 L CNN
	1    2850 2300
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 5FBA5493
P 1450 2100
F 0 "R1" V 1243 2100 50  0000 C CNN
F 1 "1k" V 1334 2100 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1380 2100 50  0001 C CNN
F 3 "~" H 1450 2100 50  0001 C CNN
	1    1450 2100
	0    1    1    0   
$EndComp
$Comp
L Device:R R8
U 1 1 5FBA0AC6
P 2650 1950
F 0 "R8" H 2580 1904 50  0000 R CNN
F 1 "1k" H 2580 1995 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2580 1950 50  0001 C CNN
F 3 "~" H 2650 1950 50  0001 C CNN
	1    2650 1950
	-1   0    0    1   
$EndComp
$Comp
L Isolator:PC817 U1
U 1 1 5FB9D532
P 2250 2200
F 0 "U1" H 2250 2525 50  0000 C CNN
F 1 "PC817" H 2250 2434 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 2050 2000 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 2250 2200 50  0001 L CNN
	1    2250 2200
	1    0    0    -1  
$EndComp
Wire Wire Line
	1750 2400 1950 2400
Wire Wire Line
	1950 2300 1950 2400
Wire Wire Line
	1950 2400 1950 2600
Connection ~ 1950 2400
$Comp
L Device:R R36
U 1 1 60694CEA
P 1900 3750
F 0 "R36" H 1970 3796 50  0000 L CNN
F 1 "1k" H 1970 3705 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1830 3750 50  0001 C CNN
F 3 "~" H 1900 3750 50  0001 C CNN
	1    1900 3750
	1    0    0    -1  
$EndComp
Wire Wire Line
	1700 3600 1900 3600
Wire Wire Line
	1900 3600 2300 3600
Connection ~ 1900 3600
Wire Wire Line
	1900 3900 2300 3900
Connection ~ 2300 3900
Wire Wire Line
	2300 3900 2300 3800
$Comp
L Device:R R38
U 1 1 606EEE12
P 2650 4750
F 0 "R38" H 2720 4796 50  0000 L CNN
F 1 "1k" H 2720 4705 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2580 4750 50  0001 C CNN
F 3 "~" H 2650 4750 50  0001 C CNN
	1    2650 4750
	1    0    0    -1  
$EndComp
Wire Wire Line
	2450 4600 2650 4600
Wire Wire Line
	2650 4600 2850 4600
Connection ~ 2650 4600
Wire Wire Line
	2650 4900 2850 4900
Connection ~ 2850 4900
Wire Wire Line
	2850 4900 2850 4800
$Comp
L Device:R R18
U 1 1 607610AE
P 1850 6300
F 0 "R18" H 1920 6346 50  0000 L CNN
F 1 "R" H 1920 6255 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1780 6300 50  0001 C CNN
F 3 "~" H 1850 6300 50  0001 C CNN
	1    1850 6300
	1    0    0    -1  
$EndComp
Wire Wire Line
	1850 6150 1700 6150
Wire Wire Line
	1850 6150 2050 6150
Connection ~ 1850 6150
Wire Wire Line
	1850 6450 2050 6450
Connection ~ 2050 6450
Wire Wire Line
	2050 6450 2050 6350
$Comp
L Device:R R37
U 1 1 607D6348
P 2300 7300
F 0 "R37" H 2370 7346 50  0000 L CNN
F 1 "R" H 2370 7255 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2230 7300 50  0001 C CNN
F 3 "~" H 2300 7300 50  0001 C CNN
	1    2300 7300
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 7150 2300 7150
Wire Wire Line
	2300 7150 2600 7150
Connection ~ 2300 7150
Wire Wire Line
	2300 7450 2600 7450
Connection ~ 2600 7450
Wire Wire Line
	2600 7450 2600 7350
$Comp
L Relay:FINDER-40.52 K1
U 1 1 6086D300
P 3550 1750
F 0 "K1" H 4180 1796 50  0000 L CNN
F 1 "FINDER-40.52" H 4180 1705 50  0000 L CNN
F 2 "Relay_THT:Relay_DPDT_Finder_30.22" H 4900 1720 50  0001 C CNN
F 3 "http://gfinder.findernet.com/assets/Series/353/S40EN.pdf" H 3550 1750 50  0001 C CNN
	1    3550 1750
	1    0    0    -1  
$EndComp
$Comp
L Relay:FINDER-40.52 K3
U 1 1 60885D94
P 3800 3300
F 0 "K3" H 4430 3346 50  0000 L CNN
F 1 "FINDER-40.52" H 4430 3255 50  0000 L CNN
F 2 "Relay_THT:Relay_DPDT_Finder_30.22" H 5150 3270 50  0001 C CNN
F 3 "http://gfinder.findernet.com/assets/Series/353/S40EN.pdf" H 3800 3300 50  0001 C CNN
	1    3800 3300
	1    0    0    -1  
$EndComp
Wire Wire Line
	3700 2950 3700 3000
Connection ~ 3700 3000
Wire Wire Line
	3700 3000 3700 3050
$Comp
L Relay:FINDER-40.52 K2
U 1 1 608EC841
P 3550 5850
F 0 "K2" H 4180 5896 50  0000 L CNN
F 1 "FINDER-40.52" H 4180 5805 50  0000 L CNN
F 2 "Relay_THT:Relay_DPDT_Finder_30.22" H 4900 5820 50  0001 C CNN
F 3 "http://gfinder.findernet.com/assets/Series/353/S40EN.pdf" H 3550 5850 50  0001 C CNN
	1    3550 5850
	1    0    0    -1  
$EndComp
Text GLabel 13950 5300 3    50   Input ~ 0
230live
Wire Wire Line
	14150 5300 14150 5400
Wire Wire Line
	14150 5400 14600 5400
Wire Wire Line
	13100 5300 13050 5300
Wire Wire Line
	14600 4350 14750 4350
Connection ~ 14600 4350
Wire Wire Line
	14600 5400 14600 4350
Wire Wire Line
	14150 4350 14600 4350
Wire Wire Line
	14150 4500 14150 4350
Text GLabel 14800 4150 1    50   Input ~ 0
230live
$Comp
L OMRON_MY2N:OMRON_MY2N K5
U 1 1 6059BE75
P 14050 4900
F 0 "K5" H 14050 5365 50  0000 C CNN
F 1 "OMRON_MY2N" H 14050 5274 50  0000 C CNN
F 2 "My_Footprint:OMRON_MY2N" H 13650 5250 50  0001 L BNN
F 3 "" H 14050 4900 50  0001 L BNN
	1    14050 4900
	0    1    1    0   
$EndComp
Wire Wire Line
	13400 4050 14700 4050
Wire Wire Line
	13400 2550 14700 2550
Wire Wire Line
	14700 2900 14700 4050
Wire Wire Line
	14500 2800 14500 2900
Connection ~ 14500 2800
Wire Wire Line
	14100 2800 14100 2900
Text GLabel 13150 4800 1    50   Input ~ 0
5VCC
Wire Wire Line
	13150 5100 13050 5100
$Comp
L Transistor_BJT:BC548 Q8
U 1 1 5FBD9874
P 13350 5300
F 0 "Q8" H 13541 5346 50  0000 L CNN
F 1 "BC548" H 13541 5255 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 13550 5225 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 13350 5300 50  0001 L CNN
	1    13350 5300
	1    0    0    -1  
$EndComp
$Comp
L Device:R R32
U 1 1 5FBD9868
P 13150 4950
F 0 "R32" H 13080 4904 50  0000 R CNN
F 1 "1k" H 13080 4995 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 13080 4950 50  0001 C CNN
F 3 "~" H 13150 4950 50  0001 C CNN
	1    13150 4950
	-1   0    0    1   
$EndComp
$Comp
L Isolator:PC817 U11
U 1 1 5FBD9862
P 12750 5200
F 0 "U11" H 12750 5525 50  0000 C CNN
F 1 "PC817" H 12750 5434 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 12550 5000 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 12750 5200 50  0001 L CNN
	1    12750 5200
	1    0    0    -1  
$EndComp
Text GLabel 13100 3250 1    50   Input ~ 0
5VCC
Wire Wire Line
	14000 3500 14400 3500
Text GLabel 14000 3500 3    50   Input ~ 0
12VCC
$Comp
L Relay:FINDER-40.52 RL5
U 1 1 5FBCE256
P 14000 3200
F 0 "RL5" H 14630 3246 50  0000 L CNN
F 1 "G2RL-2-ASI-DC12" H 14630 3155 50  0000 L CNN
F 2 "Relay_THT:Relay_DPDT_Finder_30.22" H 14650 3150 50  0001 L CNN
F 3 "https://omronfs.omron.com/en_US/ecb/products/pdf/en-g2rl.pdf" H 14000 3200 50  0001 C CNN
	1    14000 3200
	1    0    0    -1  
$EndComp
Connection ~ 13400 4050
Connection ~ 13050 4050
Wire Wire Line
	13400 3950 13400 4050
$Comp
L power:GND #PWR013
U 1 1 5FBCE247
P 13400 4050
F 0 "#PWR013" H 13400 3800 50  0001 C CNN
F 1 "GND" H 13405 3877 50  0000 C CNN
F 2 "" H 13400 4050 50  0001 C CNN
F 3 "" H 13400 4050 50  0001 C CNN
	1    13400 4050
	1    0    0    -1  
$EndComp
Wire Wire Line
	14100 2800 14500 2800
Wire Wire Line
	14700 2800 14500 2800
$Comp
L Connector:Conn_01x02_Female J13
U 1 1 5FBCE23D
P 14900 2800
F 0 "J13" H 14928 2776 50  0000 L CNN
F 1 "Conn_01x02_Female" H 14928 2685 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 14900 2800 50  0001 C CNN
F 3 "~" H 14900 2800 50  0001 C CNN
	1    14900 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	13400 3500 13400 3550
Wire Wire Line
	13600 3500 13400 3500
Text GLabel 13600 2900 1    50   Input ~ 0
12VCC
Wire Wire Line
	13050 4050 12400 4050
Wire Wire Line
	13100 3550 13000 3550
Wire Wire Line
	13050 3750 13000 3750
Connection ~ 13050 3750
Wire Wire Line
	13100 3750 13050 3750
$Comp
L Device:R R28
U 1 1 5FBCE229
P 13050 3900
F 0 "R28" H 13120 3946 50  0000 L CNN
F 1 "10k" H 13120 3855 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 12980 3900 50  0001 C CNN
F 3 "~" H 13050 3900 50  0001 C CNN
	1    13050 3900
	1    0    0    -1  
$EndComp
$Comp
L Transistor_BJT:BC548 Q7
U 1 1 5FBCE223
P 13300 3750
F 0 "Q7" H 13491 3796 50  0000 L CNN
F 1 "BC548" H 13491 3705 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 13500 3675 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 13300 3750 50  0001 L CNN
	1    13300 3750
	1    0    0    -1  
$EndComp
$Comp
L Device:R R30
U 1 1 5FBCE217
P 13100 3400
F 0 "R30" H 13030 3354 50  0000 R CNN
F 1 "1k" H 13030 3445 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 13030 3400 50  0001 C CNN
F 3 "~" H 13100 3400 50  0001 C CNN
	1    13100 3400
	-1   0    0    1   
$EndComp
Text GLabel 13100 1750 1    50   Input ~ 0
5VCC
Text GLabel 14000 2000 3    50   Input ~ 0
12VCC
Connection ~ 13400 2550
Wire Wire Line
	14700 1400 14700 2550
Connection ~ 13050 2550
Wire Wire Line
	13400 2450 13400 2550
Wire Wire Line
	13400 2550 13050 2550
$Comp
L power:GND #PWR012
U 1 1 5FBC33E6
P 13400 2550
F 0 "#PWR012" H 13400 2300 50  0001 C CNN
F 1 "GND" H 13405 2377 50  0000 C CNN
F 2 "" H 13400 2550 50  0001 C CNN
F 3 "" H 13400 2550 50  0001 C CNN
	1    13400 2550
	1    0    0    -1  
$EndComp
Connection ~ 14500 1300
Wire Wire Line
	14100 1300 14500 1300
Wire Wire Line
	14100 1400 14100 1300
Wire Wire Line
	14700 1300 14500 1300
$Comp
L Connector:Conn_01x02_Female J12
U 1 1 5FBC33DC
P 14900 1300
F 0 "J12" H 14928 1276 50  0000 L CNN
F 1 "Conn_01x02_Female" H 14928 1185 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 14900 1300 50  0001 C CNN
F 3 "~" H 14900 1300 50  0001 C CNN
	1    14900 1300
	1    0    0    -1  
$EndComp
Wire Wire Line
	13400 2000 13400 2050
Wire Wire Line
	13600 2000 13400 2000
Wire Wire Line
	14500 1300 14500 1400
Text GLabel 13600 1400 1    50   Input ~ 0
12VCC
Wire Wire Line
	13050 2550 12400 2550
Wire Wire Line
	13100 2050 13000 2050
Wire Wire Line
	13050 2250 13000 2250
Connection ~ 13050 2250
Wire Wire Line
	13000 2250 12950 2250
Connection ~ 13000 2250
Wire Wire Line
	13100 2250 13050 2250
$Comp
L Device:R R27
U 1 1 5FBC33C8
P 13050 2400
F 0 "R27" H 13120 2446 50  0000 L CNN
F 1 "10k" H 13120 2355 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 12980 2400 50  0001 C CNN
F 3 "~" H 13050 2400 50  0001 C CNN
	1    13050 2400
	1    0    0    -1  
$EndComp
$Comp
L Transistor_BJT:BC548 Q6
U 1 1 5FBC33C2
P 13300 2250
F 0 "Q6" H 13491 2296 50  0000 L CNN
F 1 "BC548" H 13491 2205 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92_Inline" H 13500 2175 50  0001 L CIN
F 3 "http://www.fairchildsemi.com/ds/BC/BC547.pdf" H 13300 2250 50  0001 L CNN
	1    13300 2250
	1    0    0    -1  
$EndComp
$Comp
L Device:R R29
U 1 1 5FBC33B6
P 13100 1900
F 0 "R29" H 13030 1854 50  0000 R CNN
F 1 "1k" H 13030 1945 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 13030 1900 50  0001 C CNN
F 3 "~" H 13100 1900 50  0001 C CNN
	1    13100 1900
	-1   0    0    1   
$EndComp
$Comp
L Isolator:PC817 U9
U 1 1 5FBC33B0
P 12700 2150
F 0 "U9" H 12700 2475 50  0000 C CNN
F 1 "PC817" H 12700 2384 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 12500 1950 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 12700 2150 50  0001 L CNN
	1    12700 2150
	1    0    0    -1  
$EndComp
$Comp
L Device:R R41
U 1 1 60B6D677
P 12000 2200
F 0 "R41" H 12070 2246 50  0000 L CNN
F 1 "R" H 12070 2155 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 11930 2200 50  0001 C CNN
F 3 "~" H 12000 2200 50  0001 C CNN
	1    12000 2200
	1    0    0    -1  
$EndComp
$Comp
L Device:R R42
U 1 1 60B6D836
P 12000 3700
F 0 "R42" H 12070 3746 50  0000 L CNN
F 1 "R" H 12070 3655 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 11930 3700 50  0001 C CNN
F 3 "~" H 12000 3700 50  0001 C CNN
	1    12000 3700
	1    0    0    -1  
$EndComp
Wire Wire Line
	11700 2050 12000 2050
Wire Wire Line
	12000 2050 12400 2050
Connection ~ 12000 2050
Wire Wire Line
	12000 2350 12400 2350
Connection ~ 12400 2350
Wire Wire Line
	12400 2350 12400 2250
Wire Wire Line
	11650 3550 12000 3550
Wire Wire Line
	12000 3550 12400 3550
Connection ~ 12000 3550
Wire Wire Line
	12000 3850 12400 3850
Connection ~ 12400 3850
Wire Wire Line
	12400 3850 12400 3750
$Comp
L Device:R R43
U 1 1 60C23572
P 12250 5250
F 0 "R43" H 12320 5296 50  0000 L CNN
F 1 "R" H 12320 5205 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 12180 5250 50  0001 C CNN
F 3 "~" H 12250 5250 50  0001 C CNN
	1    12250 5250
	1    0    0    -1  
$EndComp
$Comp
L Device:R R44
U 1 1 60C247F7
P 13200 6600
F 0 "R44" H 13270 6646 50  0000 L CNN
F 1 "R" H 13270 6555 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 13130 6600 50  0001 C CNN
F 3 "~" H 13200 6600 50  0001 C CNN
	1    13200 6600
	1    0    0    -1  
$EndComp
Wire Wire Line
	12050 5100 12250 5100
Wire Wire Line
	12250 5100 12450 5100
Connection ~ 12250 5100
Wire Wire Line
	12250 5400 12450 5400
Connection ~ 12450 5400
Wire Wire Line
	12450 5400 12450 5300
Wire Wire Line
	13050 6450 13200 6450
Wire Wire Line
	13200 6450 13450 6450
Connection ~ 13200 6450
Wire Wire Line
	13200 6750 13450 6750
Connection ~ 13450 6750
Wire Wire Line
	13450 6750 13450 6650
NoConn ~ 3450 1450
NoConn ~ 3850 1450
NoConn ~ 13900 1400
NoConn ~ 14300 1400
NoConn ~ 13900 2900
NoConn ~ 14300 2900
NoConn ~ 14250 4500
NoConn ~ 14250 5300
Wire Wire Line
	2300 4100 2950 4100
$Comp
L Device:R R39
U 1 1 60DDA273
P 2950 3950
F 0 "R39" H 3020 3996 50  0000 L CNN
F 1 "10k" H 3020 3905 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 2880 3950 50  0001 C CNN
F 3 "~" H 2950 3950 50  0001 C CNN
	1    2950 3950
	1    0    0    -1  
$EndComp
Connection ~ 2950 3800
Connection ~ 2950 4100
Wire Wire Line
	2950 4100 3250 4100
Wire Wire Line
	2850 5100 2850 4900
$Comp
L power:GND #PWR09
U 1 1 5FC044DC
P 3800 5100
F 0 "#PWR09" H 3800 4850 50  0001 C CNN
F 1 "GND" H 3805 4927 50  0000 C CNN
F 2 "" H 3800 5100 50  0001 C CNN
F 3 "" H 3800 5100 50  0001 C CNN
	1    3800 5100
	1    0    0    -1  
$EndComp
Connection ~ 3800 5100
$Comp
L Device:R R40
U 1 1 60E0B08C
P 3450 4950
F 0 "R40" H 3520 4996 50  0000 L CNN
F 1 "10k" H 3520 4905 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 3380 4950 50  0001 C CNN
F 3 "~" H 3450 4950 50  0001 C CNN
	1    3450 4950
	1    0    0    -1  
$EndComp
Wire Wire Line
	3800 3600 3800 4600
Wire Wire Line
	3800 5000 3800 5100
$Comp
L Transistor_FET:IRF540N Q5
U 1 1 5FC1360A
P 3700 4800
F 0 "Q5" H 3904 4846 50  0000 L CNN
F 1 "IRF540N" H 3904 4755 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-220-3_Vertical" H 3950 4725 50  0001 L CIN
F 3 "http://www.irf.com/product-info/datasheets/data/irf540n.pdf" H 3700 4800 50  0001 L CNN
	1    3700 4800
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 U6
U 1 1 5FC135E8
P 3150 4700
F 0 "U6" H 3150 5025 50  0000 C CNN
F 1 "PC817" H 3150 4934 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 2950 4500 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 3150 4700 50  0001 L CNN
	1    3150 4700
	1    0    0    -1  
$EndComp
Wire Wire Line
	2850 5100 3450 5100
Connection ~ 3450 5100
Wire Wire Line
	3450 5100 3800 5100
Wire Wire Line
	3500 4800 3450 4800
Connection ~ 3450 4800
$Comp
L Connector:Conn_01x03_Female J14
U 1 1 605BCF89
P 14950 4350
F 0 "J14" H 14978 4376 50  0000 L CNN
F 1 "Conn_01x03_Female" H 14978 4285 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-3-5.08_1x03_P5.08mm_Horizontal" H 14950 4350 50  0001 C CNN
F 3 "~" H 14950 4350 50  0001 C CNN
	1    14950 4350
	1    0    0    -1  
$EndComp
Wire Wire Line
	14800 4150 14750 4150
Wire Wire Line
	14750 4150 14750 4250
Wire Wire Line
	14750 4250 13950 4250
Wire Wire Line
	13950 4250 13950 4500
Connection ~ 14750 4250
NoConn ~ 14750 4450
Wire Wire Line
	13050 4050 13400 4050
Wire Wire Line
	4350 5450 4350 5500
Wire Wire Line
	4350 5500 3450 5500
Wire Wire Line
	3450 5500 3450 5550
Connection ~ 4350 5500
Wire Wire Line
	4350 5500 4350 5550
Wire Wire Line
	2200 8050 2400 8050
$Comp
L Connector:Conn_01x06_Female J2
U 1 1 5FCE32CA
P 1600 8800
F 0 "J2" H 1492 8275 50  0000 C CNN
F 1 "Conn_01x06_Female" H 1492 8366 50  0000 C CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-6-5.08_1x06_P5.08mm_Horizontal" H 1600 8800 50  0001 C CNN
F 3 "~" H 1600 8800 50  0001 C CNN
	1    1600 8800
	-1   0    0    -1  
$EndComp
$Comp
L power:GND #PWR016
U 1 1 60CF5B19
P 8250 7800
F 0 "#PWR016" H 8250 7550 50  0001 C CNN
F 1 "GND" H 8255 7627 50  0000 C CNN
F 2 "" H 8250 7800 50  0001 C CNN
F 3 "" H 8250 7800 50  0001 C CNN
	1    8250 7800
	1    0    0    -1  
$EndComp
NoConn ~ 8850 5700
NoConn ~ 8850 5600
$Comp
L MCU_Microchip_ATmega:ATmega32-16PU U8
U 1 1 5FB9C1F9
P 8250 5800
F 0 "U8" H 8250 3711 50  0000 C CNN
F 1 "ATmega32-16PU" H 8250 3620 50  0000 C CNN
F 2 "Package_DIP:DIP-40_W15.24mm" H 8250 5800 50  0001 C CIN
F 3 "http://ww1.microchip.com/downloads/en/DeviceDoc/doc2503.pdf" H 8250 5800 50  0001 C CNN
	1    8250 5800
	1    0    0    -1  
$EndComp
NoConn ~ 8850 4800
NoConn ~ 8850 4700
NoConn ~ 8850 4600
NoConn ~ 8850 4500
Text GLabel 9400 5100 2    50   Input ~ 0
wash_lim_up
Text GLabel 7650 4500 0    50   Input ~ 0
XTL2
Text GLabel 7650 4300 0    50   Input ~ 0
XTL1
Text GLabel 9500 4300 2    50   Input ~ 0
joystick_Y
Text GLabel 9500 4100 2    50   Input ~ 0
trigger_pin
Wire Wire Line
	8850 4400 9750 4400
Wire Wire Line
	8850 4300 9500 4300
Wire Wire Line
	8850 4200 9750 4200
Wire Wire Line
	8850 4100 9500 4100
Wire Wire Line
	8850 7400 9150 7400
Wire Wire Line
	8850 7300 9700 7300
Text GLabel 9150 7400 2    50   Input ~ 0
DOUT_PIN
Text GLabel 9400 5500 2    50   Input ~ 0
finished_pin
Wire Wire Line
	8850 5500 9400 5500
Wire Wire Line
	8850 5400 9800 5400
Wire Wire Line
	8850 5300 9400 5300
Text GLabel 9400 5300 2    50   Input ~ 0
cooker_lim_up
Wire Wire Line
	8850 5200 9800 5200
Wire Wire Line
	8850 5100 9400 5100
Wire Wire Line
	8850 5000 9750 5000
Wire Wire Line
	8850 6800 9300 6800
Wire Wire Line
	8850 6900 9700 6900
Wire Wire Line
	8850 7000 9250 7000
Text GLabel 9300 6800 2    50   Input ~ 0
Rx
Text GLabel 9250 7000 2    50   Input ~ 0
servo_pin
Wire Wire Line
	8850 7100 9700 7100
Wire Wire Line
	8850 5900 9200 5900
Wire Wire Line
	8850 6000 9700 6000
Text GLabel 9650 6200 2    50   Input ~ 0
dc_motor1
Wire Wire Line
	8850 6100 9200 6100
Wire Wire Line
	8850 6200 9650 6200
Wire Wire Line
	8850 6400 9700 6400
Wire Wire Line
	8850 6300 9200 6300
Text GLabel 9200 6100 2    50   Input ~ 0
dc_motor1_derec
Text GLabel 9700 6400 2    50   Input ~ 0
dc_motor2
Text GLabel 9200 5900 2    50   Input ~ 0
SCL
Wire Wire Line
	9150 6500 8850 6500
Text GLabel 9150 6500 2    50   Input ~ 0
buzzer_pin
Wire Wire Line
	9650 6600 8850 6600
Text GLabel 9650 6600 2    50   Input ~ 0
ricecooker_on
Wire Wire Line
	9700 7500 8850 7500
Wire Wire Line
	9150 7200 8850 7200
Text GLabel 9150 7200 2    50   Input ~ 0
solonid_in
Wire Wire Line
	7650 4100 7400 4100
Wire Wire Line
	8350 3800 8250 3800
Text GLabel 8250 3800 1    50   Input ~ 0
5VCC
Wire Wire Line
	13450 5100 13450 4500
Wire Wire Line
	13450 4500 13850 4500
Text GLabel 13850 5300 3    50   Input ~ 0
12VCC
Wire Wire Line
	2600 9850 2350 9850
Connection ~ 2350 9850
Wire Wire Line
	2350 10150 2900 10150
Wire Wire Line
	2900 10150 3450 10150
Wire Wire Line
	3450 1100 4000 1100
Connection ~ 4050 1350
Connection ~ 3250 4100
Wire Wire Line
	2950 2600 4250 2600
Wire Wire Line
	8600 10200 8600 10250
Text GLabel 7650 4700 0    50   Input ~ 0
5VCC
Wire Wire Line
	8350 9800 8700 9800
Wire Wire Line
	8700 9700 8200 9700
Connection ~ 2450 1100
Text GLabel 8350 9600 0    50   Input ~ 0
trigger_pin
Text GLabel 8200 9700 0    50   Input ~ 0
echo_pin
Text GLabel 8350 9800 0    50   Input ~ 0
joystick_Y
Text GLabel 8200 9900 0    50   Input ~ 0
joystick_ok
Wire Wire Line
	8200 9900 8600 9900
Connection ~ 8600 9900
Wire Wire Line
	8600 9900 8700 9900
Wire Wire Line
	8350 9600 8700 9600
$Comp
L Connector:Conn_01x04_Female J7
U 1 1 6001D2E4
P 8900 9800
F 0 "J7" H 8928 9776 50  0000 L CNN
F 1 "Conn_01x04_Female" H 8928 9685 50  0000 L CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-4-5.08_1x04_P5.08mm_Horizontal" H 8900 9800 50  0001 C CNN
F 3 "~" H 8900 9800 50  0001 C CNN
	1    8900 9800
	1    0    0    1   
$EndComp
Wire Wire Line
	14000 2000 14400 2000
$Comp
L Relay:FINDER-40.52 K4
U 1 1 609516E7
P 14000 1700
F 0 "K4" H 14630 1746 50  0000 L CNN
F 1 "FINDER-40.52" H 14630 1655 50  0000 L CNN
F 2 "Relay_THT:Relay_DPDT_Finder_30.22" H 15350 1670 50  0001 C CNN
F 3 "http://gfinder.findernet.com/assets/Series/353/S40EN.pdf" H 14000 1700 50  0001 C CNN
	1    14000 1700
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 U3
U 1 1 5FC0449B
P 2600 3700
F 0 "U3" H 2600 4025 50  0000 C CNN
F 1 "PC817" H 2600 3934 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 2400 3500 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 2600 3700 50  0001 L CNN
	1    2600 3700
	1    0    0    -1  
$EndComp
$Comp
L Device:R re1
U 1 1 606F8195
P 1950 8600
F 0 "re1" V 1743 8600 50  0000 C CNN
F 1 "1k" V 1834 8600 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 8600 50  0001 C CNN
F 3 "~" H 1950 8600 50  0001 C CNN
	1    1950 8600
	0    1    1    0   
$EndComp
$Comp
L Device:R re2
U 1 1 606F9BF6
P 1950 8700
F 0 "re2" V 1743 8700 50  0000 C CNN
F 1 "1k" V 1834 8700 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 8700 50  0001 C CNN
F 3 "~" H 1950 8700 50  0001 C CNN
	1    1950 8700
	0    1    1    0   
$EndComp
$Comp
L Device:R re3
U 1 1 606FBA2E
P 1950 8800
F 0 "re3" V 1743 8800 50  0000 C CNN
F 1 "1k" V 1834 8800 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 8800 50  0001 C CNN
F 3 "~" H 1950 8800 50  0001 C CNN
	1    1950 8800
	0    1    1    0   
$EndComp
$Comp
L Device:R re4
U 1 1 606FC563
P 1950 8900
F 0 "re4" V 1743 8900 50  0000 C CNN
F 1 "1k" V 1834 8900 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 8900 50  0001 C CNN
F 3 "~" H 1950 8900 50  0001 C CNN
	1    1950 8900
	0    1    1    0   
$EndComp
$Comp
L Device:R re5
U 1 1 606FE805
P 1950 9000
F 0 "re5" V 1743 9000 50  0000 C CNN
F 1 "1k" V 1834 9000 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 9000 50  0001 C CNN
F 3 "~" H 1950 9000 50  0001 C CNN
	1    1950 9000
	0    1    1    0   
$EndComp
$Comp
L Device:R re6
U 1 1 606FED43
P 1950 9100
F 0 "re6" V 1743 9100 50  0000 C CNN
F 1 "1k" V 1834 9100 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 1880 9100 50  0001 C CNN
F 3 "~" H 1950 9100 50  0001 C CNN
	1    1950 9100
	0    1    1    0   
$EndComp
$Comp
L Isolator:PC817 U10
U 1 1 5FBCE211
P 12700 3650
F 0 "U10" H 12700 3975 50  0000 C CNN
F 1 "PC817" H 12700 3884 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 12500 3450 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 12700 3650 50  0001 L CNN
	1    12700 3650
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op2
U 1 1 607205EF
P 5650 7750
F 0 "op2" H 5650 8075 50  0000 C CNN
F 1 "PC817" H 5650 7984 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 7550 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 7750 50  0001 L CNN
	1    5650 7750
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op3
U 1 1 60737BD7
P 5650 8150
F 0 "op3" H 5650 8475 50  0000 C CNN
F 1 "PC817" H 5650 8384 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 7950 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 8150 50  0001 L CNN
	1    5650 8150
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op4
U 1 1 6074DF6A
P 5650 8500
F 0 "op4" H 5650 8825 50  0000 C CNN
F 1 "PC817" H 5650 8734 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 8300 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 8500 50  0001 L CNN
	1    5650 8500
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op1
U 1 1 607911F0
P 5650 7400
F 0 "op1" H 5650 7725 50  0000 C CNN
F 1 "PC817" H 5650 7634 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 7200 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 7400 50  0001 L CNN
	1    5650 7400
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op5
U 1 1 607A767F
P 5650 8850
F 0 "op5" H 5650 9175 50  0000 C CNN
F 1 "PC817" H 5650 9084 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 8650 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 8850 50  0001 L CNN
	1    5650 8850
	1    0    0    -1  
$EndComp
$Comp
L Isolator:PC817 op6
U 1 1 607BDEF6
P 5650 9250
F 0 "op6" H 5650 9575 50  0000 C CNN
F 1 "PC817" H 5650 9484 50  0000 C CNN
F 2 "Package_DIP:DIP-4_W7.62mm" H 5450 9050 50  0001 L CIN
F 3 "http://www.soselectronic.cz/a_info/resource/d/pc817.pdf" H 5650 9250 50  0001 L CNN
	1    5650 9250
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 8700 2700 8700
Wire Wire Line
	2100 8900 3300 8900
Wire Wire Line
	5350 7300 4500 7300
Wire Wire Line
	4500 7300 4500 8600
Wire Wire Line
	2400 8600 4500 8600
Wire Wire Line
	2700 8350 2700 8700
Wire Wire Line
	2700 8700 4600 8700
Wire Wire Line
	4600 8700 4600 7650
Wire Wire Line
	4600 7650 5350 7650
Connection ~ 2700 8700
Wire Wire Line
	4750 8800 4750 8050
Wire Wire Line
	4750 8050 5350 8050
Wire Wire Line
	3000 8800 4750 8800
Wire Wire Line
	3300 8900 4800 8900
Wire Wire Line
	4800 8900 4800 8400
Wire Wire Line
	4800 8400 5350 8400
Connection ~ 3300 8900
Wire Wire Line
	4900 9000 4900 8750
Wire Wire Line
	4900 8750 5350 8750
Wire Wire Line
	3550 9000 4900 9000
Wire Wire Line
	5350 9100 5350 9150
Wire Wire Line
	3850 9100 5350 9100
$Comp
L power:GND #PWR0101
U 1 1 60A4A275
P 5350 7500
F 0 "#PWR0101" H 5350 7250 50  0001 C CNN
F 1 "GND" H 5355 7327 50  0000 C CNN
F 2 "" H 5350 7500 50  0001 C CNN
F 3 "" H 5350 7500 50  0001 C CNN
	1    5350 7500
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR0102
U 1 1 60A7B994
P 5350 7850
F 0 "#PWR0102" H 5350 7600 50  0001 C CNN
F 1 "GND" H 5355 7677 50  0000 C CNN
F 2 "" H 5350 7850 50  0001 C CNN
F 3 "" H 5350 7850 50  0001 C CNN
	1    5350 7850
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR0103
U 1 1 60A93C2E
P 5350 8250
F 0 "#PWR0103" H 5350 8000 50  0001 C CNN
F 1 "GND" H 5355 8077 50  0000 C CNN
F 2 "" H 5350 8250 50  0001 C CNN
F 3 "" H 5350 8250 50  0001 C CNN
	1    5350 8250
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR0104
U 1 1 60AAC0DE
P 5350 8600
F 0 "#PWR0104" H 5350 8350 50  0001 C CNN
F 1 "GND" H 5355 8427 50  0000 C CNN
F 2 "" H 5350 8600 50  0001 C CNN
F 3 "" H 5350 8600 50  0001 C CNN
	1    5350 8600
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR0105
U 1 1 60AC4336
P 5350 8950
F 0 "#PWR0105" H 5350 8700 50  0001 C CNN
F 1 "GND" H 5355 8777 50  0000 C CNN
F 2 "" H 5350 8950 50  0001 C CNN
F 3 "" H 5350 8950 50  0001 C CNN
	1    5350 8950
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR0106
U 1 1 60ADC619
P 5350 9350
F 0 "#PWR0106" H 5350 9100 50  0001 C CNN
F 1 "GND" H 5355 9177 50  0000 C CNN
F 2 "" H 5350 9350 50  0001 C CNN
F 3 "" H 5350 9350 50  0001 C CNN
	1    5350 9350
	0    1    1    0   
$EndComp
$Comp
L Device:R opr1
U 1 1 60BFF0AE
P 6100 7300
F 0 "opr1" H 6030 7254 50  0000 R CNN
F 1 "100" H 6030 7345 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 7300 50  0001 C CNN
F 3 "~" H 6100 7300 50  0001 C CNN
	1    6100 7300
	0    -1   -1   0   
$EndComp
Text GLabel 6250 7300 2    50   Input ~ 0
5VCC
$Comp
L Device:R opr2
U 1 1 60C17A08
P 6100 7650
F 0 "opr2" H 6030 7604 50  0000 R CNN
F 1 "100" H 6030 7695 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 7650 50  0001 C CNN
F 3 "~" H 6100 7650 50  0001 C CNN
	1    6100 7650
	0    -1   -1   0   
$EndComp
Text GLabel 6250 7650 2    50   Input ~ 0
5VCC
$Comp
L Device:R opr3
U 1 1 60C4B9D8
P 6100 8050
F 0 "opr3" H 6030 8004 50  0000 R CNN
F 1 "100" H 6030 8095 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8050 50  0001 C CNN
F 3 "~" H 6100 8050 50  0001 C CNN
	1    6100 8050
	0    -1   -1   0   
$EndComp
Text GLabel 6250 8050 2    50   Input ~ 0
5VCC
$Comp
L Device:R opr5
U 1 1 60C63F86
P 6100 8750
F 0 "opr5" H 6030 8704 50  0000 R CNN
F 1 "100" H 6030 8795 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8750 50  0001 C CNN
F 3 "~" H 6100 8750 50  0001 C CNN
	1    6100 8750
	0    -1   -1   0   
$EndComp
Text GLabel 6250 8750 2    50   Input ~ 0
5VCC
$Comp
L Device:R opr6
U 1 1 60C94F0C
P 6100 9150
F 0 "opr6" H 6030 9104 50  0000 R CNN
F 1 "100" H 6030 9195 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 9150 50  0001 C CNN
F 3 "~" H 6100 9150 50  0001 C CNN
	1    6100 9150
	0    -1   -1   0   
$EndComp
Text GLabel 6250 9150 2    50   Input ~ 0
5VCC
$Comp
L Device:R opr4
U 1 1 60CC5A51
P 6100 8400
F 0 "opr4" H 6030 8354 50  0000 R CNN
F 1 "100" H 6030 8445 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8400 50  0001 C CNN
F 3 "~" H 6100 8400 50  0001 C CNN
	1    6100 8400
	0    -1   -1   0   
$EndComp
Text GLabel 6250 8400 2    50   Input ~ 0
5VCC
$Comp
L Connector:Conn_01x02_Male out5v1
U 1 1 60DF011A
P 6500 1000
F 0 "out5v1" H 6608 1181 50  0000 C CNN
F 1 "OUTPUT 5v" H 6608 1090 50  0000 C CNN
F 2 "TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2-5.08_1x02_P5.08mm_Horizontal" H 6500 1000 50  0001 C CNN
F 3 "~" H 6500 1000 50  0001 C CNN
	1    6500 1000
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0107
U 1 1 60E09E68
P 6700 1100
F 0 "#PWR0107" H 6700 850 50  0001 C CNN
F 1 "GND" H 6705 927 50  0000 C CNN
F 2 "" H 6700 1100 50  0001 C CNN
F 3 "" H 6700 1100 50  0001 C CNN
	1    6700 1100
	1    0    0    -1  
$EndComp
Text GLabel 7300 1100 2    50   Input ~ 0
5VCC
$Comp
L Device:R led_r1
U 1 1 60E3A070
P 7150 1100
F 0 "led_r1" V 6943 1100 50  0000 C CNN
F 1 "470" V 7034 1100 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 7080 1100 50  0001 C CNN
F 3 "~" H 7150 1100 50  0001 C CNN
	1    7150 1100
	0    1    1    0   
$EndComp
$Comp
L Device:LED led1
U 1 1 60E3CF46
P 6850 1100
F 0 "led1" H 6843 1317 50  0000 C CNN
F 1 "LED" H 6843 1226 50  0000 C CNN
F 2 "LED_THT:LED_D5.0mm" H 6850 1100 50  0001 C CNN
F 3 "~" H 6850 1100 50  0001 C CNN
	1    6850 1100
	1    0    0    -1  
$EndComp
Connection ~ 6700 1100
Wire Wire Line
	7300 1100 7300 1000
Wire Wire Line
	7300 1000 6700 1000
$Comp
L Device:R pinr1
U 1 1 61115691
P 6150 7400
F 0 "pinr1" H 6080 7354 50  0000 R CNN
F 1 "10k" H 6080 7445 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6080 7400 50  0001 C CNN
F 3 "~" H 6150 7400 50  0001 C CNN
	1    6150 7400
	0    -1   -1   0   
$EndComp
$Comp
L Device:R pinr2
U 1 1 6112EB59
P 6100 8500
F 0 "pinr2" H 6030 8454 50  0000 R CNN
F 1 "10k" H 6030 8545 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8500 50  0001 C CNN
F 3 "~" H 6100 8500 50  0001 C CNN
	1    6100 8500
	0    -1   -1   0   
$EndComp
$Comp
L Device:R pinr3
U 1 1 6115F052
P 6100 9250
F 0 "pinr3" H 6030 9204 50  0000 R CNN
F 1 "10k" H 6030 9295 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 9250 50  0001 C CNN
F 3 "~" H 6100 9250 50  0001 C CNN
	1    6100 9250
	0    -1   -1   0   
$EndComp
$Comp
L Device:R pinr4
U 1 1 611772BD
P 6150 7750
F 0 "pinr4" H 6080 7704 50  0000 R CNN
F 1 "10k" H 6080 7795 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6080 7750 50  0001 C CNN
F 3 "~" H 6150 7750 50  0001 C CNN
	1    6150 7750
	0    -1   -1   0   
$EndComp
$Comp
L Device:R pinr5
U 1 1 6118F546
P 6100 8850
F 0 "pinr5" H 6030 8804 50  0000 R CNN
F 1 "10k" H 6030 8895 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8850 50  0001 C CNN
F 3 "~" H 6100 8850 50  0001 C CNN
	1    6100 8850
	0    -1   -1   0   
$EndComp
$Comp
L Device:R pinr6
U 1 1 611F5A13
P 6100 8150
F 0 "pinr6" H 6030 8104 50  0000 R CNN
F 1 "10k" H 6030 8195 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal" V 6030 8150 50  0001 C CNN
F 3 "~" H 6100 8150 50  0001 C CNN
	1    6100 8150
	0    -1   -1   0   
$EndComp
Wire Wire Line
	5950 7850 6000 7850
Wire Wire Line
	5950 8250 6400 8250
Wire Wire Line
	5950 8600 6450 8600
Wire Wire Line
	5950 8950 6550 8950
Wire Wire Line
	5950 9350 6350 9350
Wire Wire Line
	5950 9250 5950 9350
Connection ~ 5950 9350
Wire Wire Line
	5950 8850 5950 8950
Connection ~ 5950 8950
Wire Wire Line
	5950 8500 5950 8600
Connection ~ 5950 8600
Wire Wire Line
	5950 8150 5950 8250
Connection ~ 5950 8250
Wire Wire Line
	6000 7750 6000 7850
Connection ~ 6000 7850
Wire Wire Line
	6000 7850 6400 7850
Wire Wire Line
	6300 7500 6000 7500
Wire Wire Line
	6000 7400 6000 7500
Connection ~ 6000 7500
Wire Wire Line
	6000 7500 5950 7500
$Comp
L power:GND #PWR0108
U 1 1 615212A2
P 6650 7400
F 0 "#PWR0108" H 6650 7150 50  0001 C CNN
F 1 "GND" H 6655 7227 50  0000 C CNN
F 2 "" H 6650 7400 50  0001 C CNN
F 3 "" H 6650 7400 50  0001 C CNN
	1    6650 7400
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0109
U 1 1 6158BFA5
P 6550 7750
F 0 "#PWR0109" H 6550 7500 50  0001 C CNN
F 1 "GND" H 6555 7577 50  0000 C CNN
F 2 "" H 6550 7750 50  0001 C CNN
F 3 "" H 6550 7750 50  0001 C CNN
	1    6550 7750
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0110
U 1 1 615A6568
P 6550 8150
F 0 "#PWR0110" H 6550 7900 50  0001 C CNN
F 1 "GND" H 6555 7977 50  0000 C CNN
F 2 "" H 6550 8150 50  0001 C CNN
F 3 "" H 6550 8150 50  0001 C CNN
	1    6550 8150
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0111
U 1 1 615C0CE9
P 6600 8500
F 0 "#PWR0111" H 6600 8250 50  0001 C CNN
F 1 "GND" H 6605 8327 50  0000 C CNN
F 2 "" H 6600 8500 50  0001 C CNN
F 3 "" H 6600 8500 50  0001 C CNN
	1    6600 8500
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0112
U 1 1 615DB2AC
P 6550 8850
F 0 "#PWR0112" H 6550 8600 50  0001 C CNN
F 1 "GND" H 6555 8677 50  0000 C CNN
F 2 "" H 6550 8850 50  0001 C CNN
F 3 "" H 6550 8850 50  0001 C CNN
	1    6550 8850
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR0113
U 1 1 615F58A2
P 6500 9250
F 0 "#PWR0113" H 6500 9000 50  0001 C CNN
F 1 "GND" H 6505 9077 50  0000 C CNN
F 2 "" H 6500 9250 50  0001 C CNN
F 3 "" H 6500 9250 50  0001 C CNN
	1    6500 9250
	0    -1   -1   0   
$EndComp
Wire Wire Line
	6600 8500 6250 8500
Wire Wire Line
	6550 8150 6250 8150
Wire Wire Line
	6550 7750 6300 7750
Wire Wire Line
	6650 7400 6300 7400
Wire Wire Line
	6550 8850 6250 8850
Wire Wire Line
	6500 9250 6250 9250
Text GLabel 8600 10250 3    50   Input ~ 0
5VCC
$EndSCHEMATC
