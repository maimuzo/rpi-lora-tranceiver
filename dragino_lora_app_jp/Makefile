# dragino lora testing
# Single lora testing app

CC=g++
CFLAGS=-c -Wall
LIBS=-lwiringPi

all: dragino_lora_app_jp

dragino_lora_app_jp: main_jp.o
	$(CC) main_jp.o  $(LIBS) -o dragino_lora_app_jp

main_jp.o: main_jp.c
	$(CC) $(CFLAGS) main_jp.c

clean:
	rm *.o dragino_lora_app_jp
