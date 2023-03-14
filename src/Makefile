ALL = main

all: $(ALL)

%: %.c
	$(CC) -g -O3 $< -o $@

dump:
	objdump -dS ./bfc

clean:
	rm -rf $(ALL) *.o *.dSYM
