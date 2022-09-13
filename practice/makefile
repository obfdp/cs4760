CC = gcc
CFLAGS = -g
TARGET = sumapp
OBJS = driver.o addnum.o

$(TARGET): $(OBJS)
	$(CC) -o $(TARGET) $(OBJS)

addnum.o: addnum.c
	$(CC) $(CFLAGS) -c addnum.c

driver.o: driver.c
	$(CC) $(CFLAGS) -c driver.c

clean:
	rm driver.o
	rm addnum.o
