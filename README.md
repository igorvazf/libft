# Libft
Minha biblioteca de funções em C, primeiro projeto como cadete na 42 São Paulo.

### Como compilar?
Utilizando o Makefile você pode criar o arquivo libft.a
```
make
make clean
```

### Breve descrição de cada função:

#### Mandatory

| Função        | Descrição                                                                             |
| ------------- | --------------------------------------------------------------------------------------|
| ft_atoi       | converte uma string ASCII em um integer |
| ft_bzero      | preenche uma string com zeros |
| ft_calloc     | aloca espaço na memória e preenche os valores com NULL |
| ft_isalnum    | verifica se o caractere é alfanumérico |
| ft_isalpha    | verifica se o caractere é uma letra |
| ft_isascii    | verifica se o caractere é ASCII |
| ft_isdigit    | verifica se o caractere é um número |
| ft_isprint    | verifica se o caractere é imprimível |
| ft_itoa       | converte um integer em uma string ASCII |
| ft_memchr     | procura a primeira ocorrência de um caractere c nos primeiros n bytes de uma string e retorna a partir do encontro |
| ft_memcmp     | compara os primeiros n bytes de duas strings |
| ft_memcpy     | copia os primeiros n bytes de uma string para outra |
| ft_memmove    | copia os primeiros n bytes de uma string para outra, sendo uma opção mais segura em casos de sobreposição de memória do que o memcpy |
| ft_memset     | copia um caractere c para os primeiros n bytes de uma string |
| ft_putchar_fd | retorna um caractere para o file descriptor fd |
| ft_putendl_fd | retorna uma string com uma quebra de linha no final para o file descriptor fd |
| ft_putnbr_fd  | retorna um número inteiro para o file descriptor fd |
| ft_putstr_fd  | retorna uma string para o file descriptor fd |
| ft_split      | divide uma string em várias substrings baseada em um separador c |
| ft_strchr     | localiza a primeira ocorrência de um caractere c em uma string e retorna a partir do encontro |
| ft_strdup     | faz uma cópia da string passada como parâmetro |
| ft_striteri   | aplica uma função f em cada caractere de uma string |
| ft_strjoin    | retorna uma string resultante da concatenação de duas strings passadas como parâmetro |
| ft_strlcat    | concatena duas strings com um tamanho limitado |
| ft_strlcpy    | copia uma quantidade definida de bytes de uma string para outra |
| ft_strlen     | retorna o tamanho de uma string |
| ft_strmapi    | aplica uma função f em cada caractere de uma cópia da string passada como parâmetro |
| ft_strncmp    | compara os primeiros n caracteres de duas strings |
| ft_strnstr    | localiza a primeira ocorrência da string s2 na string s1 |
| ft_strrchr    | localiza a última ocorrência de um caractere c em uma string |
| ft_strtrim    | retorna uma cópia da string passada como parâmetro, removendo do início e do final os caracteres que fizerem parte do conjunto set |
| ft_substr     | retorna uma nova string baseada na string passada como parâmetro, começando do index start e com um tamanho máximo len |
| ft_tolower    | transforma letras maiúsculas em minúsculas |
| ft_toupper    | transforma letras minúsculas em maiúsculas |

#### Bonus

| Função          | Descrição                                                                             |
| --------------- | --------------------------------------------------------------------------------------|
| ft_lstadd_back  | adiciona um novo elemento no final de uma lista |
| ft_lstadd_front | adiciona um novo elemento no início de uma lista |
| ft_lstclear     | remove o elemento atual e todos depois dele de uma lista |
| ft_lstdelone    | remove um único elemento de uma lista utilizando uma função del |
| ft_lstiter      | aplica uma função f no conteúdo de cada elemento de uma lista |
| ft_lstlast      | retorna o último elemento de uma lista |
| ft_lstmap       | aplica uma função f no conteúdo de cada elemento de uma cópia de uma lista |
| ft_lstnew       | cria um novo elemento de uma lista |
| ft_lstsize      | retorna o tamanho da lista |


#### Mais informações sobre a Escola 42 (inglês): https://en.wikipedia.org/wiki/42_(school)
