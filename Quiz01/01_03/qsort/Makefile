FLAGS=-O2 -Wall -Wextra -lpthread

OUT = qsort-mt

all: $(OUT)
clean:
	rm -rf $(OUT)

%.out: %.c
	@$(CC) -o $@ $^ $(FLAGS)