# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: anaji-el <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2021/11/14 07:50:13 by anaji-el          #+#    #+#              #
#    Updated: 2021/12/18 03:51:32 by anaji-el         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libftprintf.a
CC = cc
CFLAGS = -Wall -Wextra -Werror
RM = rm -f
SRC = ft_printf.c \
		ft_putchar.c \
		ft_putstr.c \
		ft_unsdeci.c \
		ft_xdecimal.c \
		ft_xldecimal.c \
		ft_putptr.c \
		ft_putnm.c \
		ft_checker.c

OBJ = $(SRC:.c=.o)
	
$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)
	
all : $(NAME)

clean :
	$(RM) $(OBJ)

fclean : clean
	$(RM) $(NAME)

re: fclean $(NAME)

.PHONY: all clean fclean re