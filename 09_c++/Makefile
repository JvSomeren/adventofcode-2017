.PHONY: all
SRC= 09a 09b
all: $(SRC)
CompileParms = -g -Wall -Wextra -std=c++11
RM = rm -f

09%: 09%.cpp
	g++ $(CompileParms) -o $@ $<

clean:
	$(RM) $(SRC)
