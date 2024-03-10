CC = gcc
CFLAGS = -Wall -pedantic -I/home/millan/Dev/Learn/Raylib/raylib/include
LDFLAGS = -L/home/millan/Dev/Learn/Raylib/raylib/lib -lraylib -lm -lpthread -ldl -lrt -lX11

SRC = arkanoid.c
TARGET = my_game

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(SRC) -o $(TARGET) $(LDFLAGS)

clean:
	rm -f $(TARGET)