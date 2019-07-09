TARGET  := accessws.exe
INCS = -I ../network -I ../utils -I ../depends
LIBS = -L ../utils -lutils -L ../network -lnetwork -L ../depends/hiredis -Wl,-Bstatic -ljansson -lmpdec -lrdkafka -lz -lssl -lcrypto -lhiredis  -Wl,-Bdynamic -lm -lpthread -ldl -lssl -lldap -llber -lgss -lgnutls -lidn -lnettle -lrtmp -lsasl2 -lmysqlclient -lev -lcurl
include ../makefile.inc
