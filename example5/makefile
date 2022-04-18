CC = gcc
CFLAGS = -W -Wall
DTARGET = shop_debug
TARGET = shop
OBJECTS = main.c menu.o guest.o
all : $(TARGET)
$(TARGET) : $(OBJECTS)
	$(CC) $(CFLAGS) -o $@ $^

$(DTARGET) : $(OBJECTS)
	$(CC) $(CFLAGS) -DDEBUG -o $@ $^
clean :
	rm *.o shop
