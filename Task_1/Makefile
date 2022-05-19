all: Lec_2 lec3 lec4

Lec_2: Programm2_1

lec3: Programm3_1 Programm3_2

lec4: Programm4_1 Programm4_2 Programm4_3

Programm2_1:
	gcc 'Lec_2/Programm2_1/Programm2_1.c' -o 'Lec_2/Programm2_1/Programm2_1.out'

Programm3_1:
	gcc 'lec3/Programm3_1/Programm3_1.c' -o 'lec3/Programm3_1/Programm3_1.out'

Programm3_2:
	gcc 'lec3/Programm3_2/Programm3_2.c' -o 'lec3/Programm3_2/Programm3_2.out'

Programm4_1:
	gcc 'lec4/Programm4_1/Programm4_1.c' -o 'lec4/Programm4_1/Programm4_1.out'

Programm4_2:
	gcc 'lec4/Programm4_2/Programm4_2.c' -o 'lec4/Programm4_2/Programm4_2.out'

Programm4_3:
	gcc 'lec4/Programm4_3/Programm4_3.c' -o 'lec4/Programm4_3/Programm4_3.out'

clear:
	rm -rf lec?/Programm*/*.out
