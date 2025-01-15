#
#
#
#
SRCS += demod_double.c
SRCS += filter_bits.c
SRCS += split_to_to_files.c
SRCS += uart.c
SRCS += uart_ganz_simpel.c
SRCS += uart_simpel.c

TARGETS = $(SRCS:.c=)

CC = gcc

CFLAGS = -std=gnu11
CFLAGS += -O2
CFLAGS += -Wall
CFLAGS += -g

LDFLAGS = -lm

all:	$(TARGETS)

clean:
	-rm *.o $(TARGETS)

