
BIN = producer_consumer

CFLAGS = -Wall -Wextra -g -pthread

SRC = main.c \
      queue.c \
      producer.c \
      consumer.c

all: $(BIN)

clean:
	$(RM) $(BIN)

$(BIN): $(SRC)
	$(CC) -o $@ $(CFLAGS) $^
