# Matrix-and-filter
full description at readme file
work on FPGA DE10 lite ,The project mainly work on verilog and the rest is in C. We got Matrix 4X4 ,each value is 8 bit . Filter that is 3X3 and each value is 8 bit also. What say 4 iteration that the filter run on the matrix. at first we should need to multiply each value in matrix by the suitable place in the Filter. This result in comment ,cause we have to do more things . More feuture that in comment is ,when multiply get overflow ,we print in that 8 bits FF(Hexadecimal). To what is printed in the 7 segment first time -the multiply after we minus the average.More feuture is if the minus is getting negative numbers so present 0. so the display work like that , cause we have 8 digits to present in HEXA ,so the last 6 digits presented and then the first one. After that , what is present is the variance of the matrix .