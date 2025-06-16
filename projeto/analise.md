# Análise orientada a objeto
> [!NOTE]
> A **análise** orientada a objeto consiste na descrição do problema a ser tratado, duas primeiras etapas da tabela abaixo, a definição de casos de uso e a definição do domínio do problema.

## Descrição Geral do domínio do problema
O projeto Hidden Code está inserido no domínio dos jogos de lógica baseados em tentativa e erro. Ele simula um desafio onde o jogador deve descobrir uma senha numérica oculta, utilizando raciocínio lógico e estratégias de dedução. A cada tentativa, o sistema fornece um feedback indicando quantos números foram acertados na posição correta, permitindo ao jogador ajustar suas próximas jogadas até encontrar a senha correta.

Trata-se de um problema que envolve validação de entradas, comparações posicionais, geração pseudoaleatória de dados e controle de fluxo de jogo, além de permitir a aplicação direta dos principais pilares da Programação Orientada a Objetos (POO).
## Diagrama de Casos de Uso
### 🎯 Hidden Code
<p align="center">
  <img src="https://github.com/user-attachments/assets/e128e979-b7e6-4f83-979e-a74fcdee19ee" alt="Imagem ilustrativa do projeto" />
</p>
| Caso de Uso                          | Descrição                                                                                  |
|--------------------------------------|---------------------------------------------------------------------------------------------|
| **Selecionar nível de dificuldade**  | Jogador escolhe entre fácil (3 dígitos), médio (4 dígitos) ou difícil (4 dígitos + troca). |
| **Iniciar jogo**                     | Sistema gera a senha aleatória e inicializa a partida.                                     |
| **Inserir palpite**                  | Jogador digita uma sequência numérica tentando adivinhar a senha.                          |
| **Receber feedback**                 | Sistema informa quantos números estão corretos e na posição correta.                       |
| **Trocar senha** *(somente no difícil)* | Após 15 tentativas, o sistema troca automaticamente a senha.                              |
| **Finalizar jogo**                   | O jogo termina quando o jogador acerta a senha.                                            |
| **Visualizar número de tentativas**  | O sistema mostra quantos palpites foram realizados.                                        |

 
## Diagrama de Domínio do problema

Elaborar um diagrama conceitual do domínio do problema.


<div align="center">

[Retroceder](README.md) | [Avançar](projeto.md)

</div>
