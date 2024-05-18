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

Como, por exemplo, esse trecho inicial:

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

### Declaração de variáveis e métodos no Java:
- Declarar uma variável segue a seguinte estrutura:

```
// Estrutura da variável
Tipo nomeBemDefinido = Atribuição/Valor // <- opcional em alguns casos
```

- Para declarar um método, será seguida a seguinte estrutura:

```
// Estrutura do método
TipoDoRetorno NomeObjetivoNoInfinitivo Parametro(s){}
```

### Identação:
- É uma forma de organização/escrita do código de forma hierárquica, facilitando a visualização e compreensão do programa.

### Organização de arquivos:
- À medida que nosso sistema vai evoluindo, surgem novos arquivos em nosso projeto. Isso exige a realização de organizações padronizadas em pacotes.
- São divididos em alguns prefixos:
	- com -> comercial
	- org -> organizacional
	- opensource -> open-source
	- edu -> educacional

```
// Exemplo do nome do pacote
com.Gusmas.JogoQualquer
```

### Java Beans:
- Java Beans são as convenções da comunidade Java que regem questões escritas no código, diferente da identação.
- É como uma forma de escrita universal para nossas classes, atributos, métodos e pacotes.
- Variáveis:
	- Seu nome deve ser claro, sem abreviações ou definições nada haver
	- É sempre no singular, exceto com arrays e coleções
	- Defina um idioma único
- Métodos:
	- Deverão ser nomeados como verbos no infinitivo
	- Mistura de maiúsculas e minúsculas (camelCase)