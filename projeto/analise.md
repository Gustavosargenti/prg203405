# Análise orientada a objeto
> [!NOTE]
> A **análise** orientada a objeto consiste na descrição do problema a ser tratado, duas primeiras etapas da tabela abaixo, a definição de casos de uso e a definição do domínio do problema.

## Descrição Geral do domínio do problema
O projeto Hidden Password está inserido no domínio dos jogos de lógica baseados em tentativa e erro. Ele simula um desafio onde o jogador deve descobrir uma senha numérica oculta, utilizando raciocínio lógico e estratégias de dedução. A cada tentativa, o sistema fornece um feedback indicando quantos números foram acertados na posição correta, permitindo ao jogador ajustar suas próximas jogadas até encontrar a senha correta. Trata-se de um problema que envolve validação de entradas, comparações posicionais, geração pseudoaleatória de dados e controle de fluxo de jogo.
## Diagrama de Casos de Uso
### 🎯 Hidden Password
<p align="center">
  <img src="https://github.com/user-attachments/assets/e2359bf7-1fe9-4ac5-9e47-0282fad062c6" alt="Imagem ilustrativa do projeto" />
</p>

| Caso de Uso                          | Descrição                                                                                  |
|--------------------------------------|---------------------------------------------------------------------------------------------|
| **Selecionar nível de dificuldade**  | Jogador escolhe entre fácil (3 dígitos), médio (4 dígitos) ou difícil (4 dígitos + troca). |
| **Iniciar jogo**                     | Sistema gera a senha aleatória e inicializa a partida.                                     |
| **Inserir palpite**                  | Jogador digita uma sequência numérica tentando adivinhar a senha.                          |
| **Receber feedback**                 | Sistema informa quantos números estão corretos e na posição correta.                       |
| **Embaralhar senha** *(somente no difícil)* | Após 15 tentativas, o sistema embaralha automaticamente a senha.                              |
| **Finalizar jogo**                   | O jogo termina quando o jogador acerta a senha.                                            |
| **Visualizar número de tentativas**  | O sistema mostra quantos palpites foram realizados.                                        |

 
## Diagrama de Domínio do problema

<p align="center">
  <img src="https://github.com/user-attachments/assets/ca7ea4f4-c42b-463a-afec-62770cbf9a63" alt="Imagem ilustrativa do projeto" />
</p>


<div align="center">

[Retroceder](README.md) | [Avançar](projeto.md)

</div>
