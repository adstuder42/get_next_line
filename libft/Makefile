# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: adstuder <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/04/24 18:51:28 by adstuder          #+#    #+#              #
#    Updated: 2018/05/02 19:01:40 by adstuder         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a

SRC = ft_strdup.c ft_strlen.c
SRCO = ft_strdup.o ft_strlen.o
HEADER = -I libft.h

all: $(NAME)

$(NAME):
	gcc -c -Werror -Wall -Wextra $(SRC) $(HEADER)
	ar rc libft.a $(SRCO)

clean:
	/bin/rm -rf $(SRCO)

fclean: clean
	/bin/rm -rf $(NAME)

re: fclean all
