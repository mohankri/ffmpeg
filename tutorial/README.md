make install --> Install fmpeg library

gcc -o tutorial01 tutorial01.c -lavutil -lavformat -lavcodec -lswresample -lswscale -lz -lavutil -lm -lpthread  -Wl,--no-as-needed -ldl

