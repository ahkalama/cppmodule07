NAME = array
FILES = main.cpp
HEADERS = Array.hpp
FLAGS = c++ -std=c++98 -Wall -Wextra -Werror

all: $(NAME)

$(NAME):	$(FILES) $(HEADERS)
	$(FLAGS) $(FILES) -o $(NAME)
	@echo "\033[0;32mDone\033[m"

clean:
	@rm -rf $(NAME)
	@echo "\033[0;34mclean\033[m"

re: clean all

.PHONY: all clean re
