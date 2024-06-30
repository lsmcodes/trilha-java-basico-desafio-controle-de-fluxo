# DIO - Trilha Java Básico
<div style="display:inline-block">
        <picture  title="Java">
                <source height="40" width="40" media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/openjdk/000000">
                <img height="40" width="40" src="https://cdn.simpleicons.org/openjdk/FFFFFF" />
        </picture>
        <picture  title="Apache Maven">
                <source height="40" width="40" media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/apachemaven/000000">
                <img height="40" width="40" src="https://cdn.simpleicons.org/apachemaven/FFFFFF" />
        </picture>
        <picture  title="Spring Boot">
                <source height="40" width="40" media="(prefers-color-scheme: light)" srcset="https://cdn.simpleicons.org/springboot/000000">
                <img height="40" width="40" src="https://cdn.simpleicons.org/springboot/FFFFFF" />
        </picture>
</div>

## Autor do Desafio e Repositório Original
- [Gleyson Sampaio](https://github.com/glysns)
- [Desafio Controle de Fluxo](https://github.com/digitalinnovationone/trilha-java-basico/blob/main/desafios/controle-fluxo)

## Desafio de projeto
O desafio é desenvolver um contador seguindo os seguintes passos:

- Criar uma classe `Contador` para codificar o desafio nela;
- Criar uma classe `ParametrosInvalidosException` para que seja uma exceção customizada;
- O sistema deverá receber dois parâmetros no terminal, ambos inteiros representando o o início do contador e o fim respectivamente;
- Se o primeiro parâmetro for maior que o segundo, o sistema deve lançar a exceção ParametrosInvalidosException com a mensagem descrevendo qual foi o erro cometido;
- Se os parâmetros forem válidos, o sistema imprime a contagem no terminal.

## Código Base
Abaixo temos o código que servirá de base para a resolução do desafio:

```java
public class Contador {
    	public static void main(String[] args) {
		Scanner terminal = new Scanner(System.in);

		System.out.println("Digite o primeiro parâmetro");
		int parametroUm = // Atribuir input do usuário

		System.out.println("Digite o segundo parâmetro");
		int parametroDois = // Atribuir input do usuário
		
		try {
			// Chamando o método contendo a lógica de contagem
			contar(parametroUm, parametroDois);
		
		} catch (ParametrosInvalidosException exception) {
			// Imprimir a mensagem de erro
		}
	}

        static void contar(int parametroUm, int parametroDois) throws ParametrosInvalidosException {
                // Validar se os parâmetros são válidos

                // Realizar o for para imprimir os números com base nos parâmetros
        }
}
```