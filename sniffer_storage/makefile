CC = gcc

CFLAGS = -L/opt/homebrew/lib -I/opt/homebrew/include -DSNIFFER_STORAGE_COMPILE


LDFLAGS = -lusb-1.0

SRC = sniffer_storage.c
TARGET = sniffer_storage

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC) $(LDFLAGS)

clean:
	rm -f $(TARGET)
