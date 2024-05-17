# Introdução à sintaxe Java

## Anatomia das classes:

### Estruturação inicial

> Uma classe bem estruturada não quer guerra com ninguém

A escrita de códigos é feita através da composição de palavras já definidas pela linguagem com as expressões que utilizamos para determinar o nome dos arquivos, classes, atributos e métodos.

Essa é a sintaxe geral para uma nova classe em Java:

```
public class MinhaClasse {
	//Seu código vem aqui!
}
```

Este, para todos os fins, é meu primeiro trecho de código:

```
public class MinhaClasse {

	public static void main (String [] args){
		System.out.println("Olá, mundo!")
	}

}
```

### Convenções estruturais do Java:
- Arquivo .java: todo arquivo .java deve ter a primeira letra maiúscula; se for palavra composta, a segunda também inicia com letra maiúscula.
- Nome da classe no arquivo: o nome da classe deve ser o mesmo nome do arquivo .java.
- Nome de váriavel: toda variável deve ser escrita com letra minúscula; se for palavra composta, a segunda letra iniciára com letra maiúscula; em caso de variáveis que não devem ser alteradas, ela deve ser escrita inteira em letras maiúsculas (ou, também, deve se usar o parâmetro `final` antes da declaração).

### Declaração de váriaveis no Java:
