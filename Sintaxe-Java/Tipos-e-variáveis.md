# Tipos e variáveis

## Tipos de dados:
- No Java, existem palavras reservadas para representação de dados básicos, também conhecidos como os tipos primitivos de dados. São eles:
	- byte -> 1 byte de memória (-128 até 127)
	- short -> 2 bytes de memória (-32.768 até 32.767)
	- int -> 4 bytes de memória (-2.147.483.648 até 2.147.483.647) - mais comum para inteiros
	- long -> 8 bytes de memória (-9.223.372.036.854.775.808 até -9.223.372.036.854.775.807)
	- float -> 4 bytes de memória 
	- double ->  8 bytes de memória - mais comuns para números com vírgula
	- boolean -> armazena um valor lógico, verdadeiro ou falso
	- char -> armazena um caractere
- Esses tipos não são considerados objetos, e, portanto, representam valores brutos. Eles são armazenados diretamente na pilha de memória (memory stack).
- Toda constante em Java deve, por convenção, ter seu nome inteiramente maiúsculo e deve, por sintaxe, possuir a palavra `final` antes de declarar.