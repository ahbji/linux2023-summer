FLAGS=-O2 -Wall -Wextra

OUT = main

all: $(OUT)

clean:
	rm -rf $(OUT)
	rm -rf build

%.out: %.c
	@$(CC) -o $@ $^ $(FLAGS)