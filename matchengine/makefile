TARGET  := matchengine.exe
INCS = -I ../network -I ../utils
LIBS = -L ../utils -lutils -L ../network -lnetwork -L ../depends/hiredis -Wl,-Bstatic -lev -ljansson -lmpdec -lrdkafka -lz -lssl -lcrypto -lhiredis -lcurl -Wl,-Bdynamic -lm -lpthread -ldl -llz4 -lssl -lldap -llber -lmysqlclient
include ../makefile.inc
