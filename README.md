🧩 Quiz de Ciência da Computação (Python)

Um quiz interativo em Python, com perguntas de Verdadeiro ou Falso sobre temas de Ciência da Computação.
O jogador responde uma sequência de perguntas e, ao final, recebe sua pontuação.


🚀 Funcionalidades

Apresenta perguntas de forma sequencial.

Recebe respostas do usuário via terminal (True / False).

Informa se a resposta está correta.

Atualiza e exibe a pontuação em tempo real.

Mostra o resultado final ao término do quiz.

  
  🧠 Estrutura do Projeto

  day17/
│
├── data.py              # Base de dados com as perguntas
├── question_model.py    # Classe que representa cada pergunta
├── quiz_brain.py        # Lógica do quiz (perguntas, pontuação, controle)
├── main.py              # Arquivo principal para rodar o jogo
└── __pycache__/         # Cache gerado automaticamente pelo Python (ignorado)


⚙️ Como executar

1 - Clone o repositório:

https://github.com/MarceloDavid76/projeto_quiz

2 - Entre na pasta do projeto:

cd day17


3 - Execute o script principal:

python main.py



📦 Requisitos

Python 3.8 ou superior
(nenhuma biblioteca externa é necessária — apenas o Python puro).



🧩 Estrutura de Classes
Question (em question_model.py)

Representa uma pergunta do quiz.
Atributos:

text: texto da pergunta

answer: resposta correta (True ou False)

QuizBrain (em quiz_brain.py)

Gerencia o funcionamento do quiz.
Principais métodos:

still_has_questions(): verifica se ainda há perguntas.

next_question(): exibe a próxima pergunta e recebe a resposta do usuário.

check_answer(): compara a resposta do usuário com a correta e atualiza a pontuação.




🧑‍💻 Exemplo de execução

Q1: The HTML5 standard was published in 2014. (True/False)? true
You got it right!
Your current score is: 1/1

Q2: The first computer bug was formed by faulty wires. (True/False)? false
You got it right!
Your current score is: 2/2
...
You've completed the quiz
Your final score was: 8/10


💡 Possíveis melhorias futuras

Adicionar perguntas de múltipla escolha.

Criar interface gráfica com Tkinter.

Integrar com a API Open Trivia DB para buscar perguntas dinâmicas.

Armazenar pontuação em arquivo ou banco de dados.
