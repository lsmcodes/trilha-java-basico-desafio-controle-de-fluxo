# DIO - Trilha Java Básico
www.dio.me

## Autor do desafio e repositório com a proposta original
- [Gleyson Sampaio](https://github.com/glysns)
- [Desafio Controle de Fluxo](https://github.com/digitalinnovationone/trilha-java-basico/blob/main/desafios/controle-fluxo)

## Desafio de projeto
Para realizar o desafio, os conhecimentos adquiridos durante o módulo de Controle de Fluxo e Exceções serão necessários, sobretudo exceções customizadas, blocos if/else e for.

## Contexto
O desafio é desenvolver um contador seguindo os seguintes requisitos:

- Criar uma classe **Contador** para codificar o desafio nela;

- Criar uma classe **ParametrosInvalidosException** para que seja uma exceção customizada;

- O sistema deverá receber dois parâmetros no terminal, ambos inteiros representando o o início do contador e o fim respectivamente;

- Se o primeiro parâmetro for maior que o segundo, o sistema deve lançar a exceção ParametrosInvalidosException com a mensagem "O segundo parâmetro deve ser maior que o primeiro";

- Se os parâmetros forem válidos, o sistema imprime a contagem no terminal.

## Código base
Abaixo temos o código que servirá de base para a resolução do desafio:

```java
public class Contador {
	public static void main(String[] args) {
		Scanner terminal = new Scanner(System.in);

		System.out.println("Digite o primeiro parâmetro");
		int parametroUm = //atribuir input do usário

		System.out.println("Digite o segundo parâmetro");
		int parametroDois =  //atribuir input do usário
		
		try {
			//chamando o método contendo a lógica de contagem
			contar(parametroUm, parametroDois);
		
		}catch (ParametrosInvalidosException exception) {
			//imprimir a mensagem de erro
		}
		
	}
	static void contar(int parametroUm, int parametroDois ) throws ParametrosInvalidosException {
		//validar se os parâmetros são válidos
		
		int contagem = parametroDois - parametroUm;
		//realizar o for para imprimir os números com base na variável contagem
	}
}
```