# 🎮 Paulo and Alycia's Arcade  

Este é um projeto avaliativo para os alunos de Engenharia de Computaçõa no CESUPA 2025 em que se deve desenvolver um jogo simples em C, que contenha três minijogos interativos:  

![image](https://github.com/user-attachments/assets/285c39ad-6b99-4e42-a9ed-ede7d11491c8)

- Perguntas e Respostas
- Cobra na Caixa
- Gousma's War

# 🎮 Explicação dos Jogos  

## 🧠 Perguntas e Respostas (Quiz)  

Um jogo de raciocínio lógico com perguntas de múltipla escolha. O jogador deve responder corretamente para acumular pontos. Ao final das cinco perguntas, a pontuação é exibida, e o jogador pode optar por tentar novamente ou voltar ao menu principal.  

![image](https://github.com/user-attachments/assets/6441b500-e262-40f0-a03e-a3b11b660b05)

- Cada pergunta tem quatro alternativas (1 a 4).  
- O jogo informa se a resposta está certa ou errada.
- Se a resposta for errada, o jogo exibe a resposta correta

![Screenshot 2025-03-20 04 24 12](https://github.com/user-attachments/assets/776da09f-617d-4064-8c94-9f27f5bd194c)

- Pontuação final exibida ao término do quiz.

![image](https://github.com/user-attachments/assets/c3c34aa0-5a2d-4ca9-bd17-11b3644b8a4a)


## 🐍 Cobra na Caixa  

Um jogo de sorte onde dois exploradores (ou um explorador contra o computador) tentam encontrar o botão escondido ou uma cobra dentro de uma das cinco caixas na tumba egipcia.  

![image](https://github.com/user-attachments/assets/d70286b8-daec-4fff-adda-e8e61fd33c9e)

- Primeiramente, o jogador escolhe o seu explorador

![image](https://github.com/user-attachments/assets/4588fdad-de74-4e93-99b7-ac25b4fb1077)

- Cada rodada, as posições do botão e da cobra mudam aleatoriamente.
- Se o jogador escolher a caixa com o botão, vence o jogo.

![image](https://github.com/user-attachments/assets/28277f8a-51f6-41a1-9bc8-cb840e2a6307)

- Se escolher a caixa com a cobra, perde imediatamente.

![image](https://github.com/user-attachments/assets/883f726b-ef62-44d7-8161-169140ba4fd0)

- O jogo alterna entre os jogadores a cada tentativa.  


## ⚔️ Gousma’s War 
um jogo de estrategia onde voce controla criaturas chamadas gousmas, que podem se dividir e acumular furias ao serem atacadas

![Image](https://github.com/user-attachments/assets/96e07772-cc26-4926-8a63-374955faf6f0)

- Cada jogador inicia com duas Gousmas, cada uma com nível de fúria 1
- Quando uma Gousma ataca outra, transfere todo o seu nível de fúria
para a Gousma atacada
- Se uma Gousma atingir um nível de fúria maior que 5, ela se desintegra
- O jogador pode optar por dividir uma Gousma, transferindo uma parte da
fúria para uma nova Gousma (respeitando o limite de duas Gousmas por
jogador)
- Se o jogador perder todas as gousmas será derrotado

 ![Image](https://github.com/user-attachments/assets/17d49b35-09e2-490d-8423-89ad8954773a)


# 🛠️ Tecnologias Utilizadas  

- Linguagem C  
- Biblioteca padrão do C (`stdio.h`, `stdlib.h`, `locale.h`, `time.h`, `stdbool.h`)
- Laços de repetição (`do-while`, `while`, `if-else`)
- Switch-case
- Funções
- Variáveis e Tipos de Dados (int, char, float, etc.)
- Vetores (Arrays)
- Sistema de Pontuação
