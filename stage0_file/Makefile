
clean:
	rm -f *.o *.elf *.self *.484 *.bin *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o

all:
	rm -f *.o *.elf *.self *.484 *.bin *.484C *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_484C --no-print-directory

	rm -f *.o *.elf *.self *.485 *.bin *.485 *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	make -f Makefile_485C --no-print-directory 
	rm -f *.o *.bin *.elf *.485 *.485 *.map ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
	#rm -f *.o *.elf *.self ../lv1/src/*.o ../debug/src/*.o ../lv2/src/*.o
