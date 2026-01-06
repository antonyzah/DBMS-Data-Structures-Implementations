sort_compile:
	@echo " Compile sort_main ...";
	gcc -g -I ./include/ -L ./lib/ -Wl,-rpath,./lib/ ./examples/sort_main.c ./src/record.c ./src/sort.c ./src/merge.c ./src/chunk.c -lbf -lhp_file -o ./build/sort_main -O2

sort_run: sort_compile
	@echo " Running sort_main ..."
	rm -f data.db out*.db
	./build/sort_main
