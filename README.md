# Calculadora MEC Java com Padrões de Projeto Singleton e Observer


![image](https://github.com/joaohenriDev/calculadora/assets/118625621/035d4915-f117-4fd9-8a8b-0274fcc869f7)


Este é um projeto de uma calculadora inspirada na calculadora do MEC (Ministério da Educação) implementada em Java, que utiliza os padrões de projeto Singleton e Observer para garantir a criação de uma única instância da calculadora e permitir que outros objetos se inscrevam para receber notificações de alterações nos resultados dos cálculos.

# Sobre o Projeto


Este projeto implementa uma calculadora simples que possui uma interface gráfica semelhante à calculadora do MEC. A calculadora permite a realização de operações matemáticas básicas, como adição, subtração, multiplicação e divisão, e possui um display que exibe o resultado das operações.


# Requisitos do Sistema

Antes de utilizar o projeto, certifique-se de que sua máquina atende aos seguintes requisitos:

- JDK (Java Development Kit) 8 ou superior instalado na máquina.
- IDE de desenvolvimento Java (recomendamos o uso do Eclipse, IntelliJ IDEA ou NetBeans).


# Como Usar

1. Você pode simplesmente baixar o executavel do jogo click no link para ser redirecionado: https://github.com/joaohenriDev/calculadora/tree/main/out/artifacts/calculadora_jar


2. Você pode clonar este repositório em sua máquina local:

![image](https://github.com/joaohenriDev/calculadora/assets/118625621/d63803db-5b69-4841-825c-6ce59d5c3446)

1. Importe o projeto em sua IDE preferida, como um projeto Java existente.

2. Execute a classe Calculadora.java para abrir a interface da calculadora.

# Funcionalidades

- Realizar operações matemáticas básicas, como adição, subtração, multiplicação e divisão.
- Manter o histórico das operações realizadas.
- Exibir o resultado das operações no display da calculadora.


# Padrões de Projeto Utilizados

- Singleton
  
O padrão Singleton é aplicado na classe Memoria, garantindo que a calculadora tenha apenas uma única instância em toda a execução do programa. Isso é especialmente importante para evitar problemas de concorrência e compartilhar o mesmo estado entre diferentes partes do código.



- Observer
  
O padrão Observer é empregado na classe Display, onde a calculadora se registra como observadora da classe Memoria. Sempre que o resultado das operações é alterado, a classe Memoria notifica os observadores, e o Display é atualizado automaticamente com o novo valor.


# Estrutura do Projeto

O projeto está estruturado da seguinte forma:

- Calculadora.java: Classe que representa a janela da calculadora e organiza os componentes gráficos.
  
- Display.java: Classe que exibe o resultado das operações no display da calculadora e implementa a interface MemoriaObservador.
  
- Teclado.java: Classe que representa o teclado da calculadora, com os botões para números e operações.

- Botao.java: Classe customizada para os botões da calculadora, definindo aparência e comportamento.

- Memoria.java: Classe que implementa o padrão Singleton e representa a memória da calculadora, onde são armazenados os valores e operações realizadas.


# Contribuição


Se você encontrar algum problema, tiver alguma sugestão de melhoria ou quiser contribuir com novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Esperamos que esta calculadora inspirada na calculadora do MEC, com os padrões de projeto Singleton e Observer, seja útil para seus projetos e estudos em Java. Sinta-se à vontade para explorar o código e entender como os padrões são implementados na prática. Se tiver dúvidas, consulte a documentação do código ou entre em contato com a equipe de desenvolvimento. Confira também os outros projetos feito por mim Happy coding! 😊

# Autor

João Henrique de Oliveira

https://www.linkedin.com/in/jo%C3%A3o-henrique-8625341b9/
