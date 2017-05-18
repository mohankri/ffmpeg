make install --> Install fmpeg library

gcc -o tutorial01 tutorial01.c -lavutil -lavformat -lavcodec -lswresample -lswscale -lz -lavutil -lm -lpthread  -Wl,--no-as-needed -ldl


gcc -o tutorial02 tutorial02.c -lavutil -lavformat -lavcodec -lswscale -lz -lm  -I/home/corp.roku/kmohan/ffmpeg/SDL2-2.0.5/include -lswresample -lswscale -lz -lavutil -lm -lpthread -Wl,--no-as-needed -ldl -lSDL2

http://lazyfoo.net/tutorials/SDL/01_hello_SDL/linux/

yum install SDL2-devel

gcc test.c -o test `sdl2-config --cflags --libs`
