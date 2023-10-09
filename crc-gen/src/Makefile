clean_exe:
	rm -rf crc_gen
gen-exe:clean_exe
	gcc crc-gen.cpp -o crc_gen
crc32:gen-exe
	crc_gen verilog 8 5 05
