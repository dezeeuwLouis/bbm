CC =	gcc -pthread
NAME =	server
SRC =	server.c \
			arg.c\
			map.c\
			delliste.c\
			client.c\
			initdata.c\
			move.c\
			bombe.c\
			other.c\
			other2.c\
			liste.c


OBJ = $(SRC:%.c=%.o)
RM = rm -f
CFLAGS = -Wall -Werror -Wextra -ansi -pedantic

all :		$(NAME)
$(NAME) :	$(OBJ)
		$(CC) $(OBJ) -o $(NAME) $(CFLAGS) -L ../parse/ -lParse
clean :
		$(RM) $(OBJ)
fclean :		clean
		$(RM) $(NAME)
re : 		fclean all
