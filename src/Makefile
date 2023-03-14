ALL = main

all: $(ALL)

%: %.c
	$(CC) -g -O3 $< -o $@ && mv main bfc

dump:
	objdump -dS ./bfc

clean:
	rm -rf $(ALL) *.o *.dSYM
