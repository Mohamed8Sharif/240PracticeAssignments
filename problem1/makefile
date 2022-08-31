#
# PROGRAM: Lab training Exercise
# AUTHOR: Mohamed Sharif
#

CXXFLAGS = -Wall -Werror -std=c++11

assignment0: assignment0.o
	g++ $(CXXFLAGS) -o assignment0 assignment0.o

assignment0.o: assignment0.cpp
	g++ $(CXXFLAGS) -c assignment0.cpp

clean:
	rm -f *.o assignment0

