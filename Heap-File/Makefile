hp_compile:
	@echo " Compile hp_main ...";
	rm -f ./build/hp_main
	gcc -I ./include/ -L ./lib/ -Wl,-rpath,./lib/ ./examples/hp_main.c ./src/*.c -lbf -o ./build/hp_main -O2

hp_run: hp_compile
	@echo " Running hp_main ..."
	rm -f *.db
	./build/hp_main






