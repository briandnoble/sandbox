CXX=g++
CFLAGS+=-Wall -Werror -g
CXXFLAGS+=${CFLAGS}

SOURCES=race.cc
OBJS=${SOURCES:.cc=.o}

all: race

race: race.cc
	${CXX} ${CXXFLAGS} -o $@ $^ -pthread

