FLAGS=-O2 -Wextra -Wall -g -fsanitize=thread -lpthread

OUT = qsort-mt

# TSAN = 1

# ifeq ("$(TSAN)", "1")
#     FLAGS += -g -fsanitize=thread
# endif

all: $(OUT)

%.out: %.c
	@$(CC) -o $@ $^ $(FLAGS)

clean:
	rm -rf $(OUT)

run:
	./$(OUT) -tv -f2 -h2 -n100