CC = gcc
CFLAGS = -O2 -Wextra -Wall -lpthread

OUT = qsort-mt

TSAN = 1

ifeq ("$(TSAN)", "1")
    CFLAGS += -g -fsanitize=thread
endif

all: $(OUT)

clean:
	rm -rf $(OUT)

run:
	./$(OUT) -tv -f2 -h2 -n100