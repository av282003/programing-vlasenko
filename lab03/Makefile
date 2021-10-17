all:mkdir build debug clean
almost:mkdir build debug
clean:
	rm -r src/bin
compile:
	clang -g src/main.c -o src/bin/lab03
prep:
	mkdir -p src/bin
debug:
	lldb ./src/bin/lab03
check:
	clang-format --verbose -dry-run --Werror src/*
	cppcheck src/main.c
