# 🦖 **Dino Game no Scratch** 

Vamos criar um jogo incrível no Scratch com um céu azul, um gato aventureiro e obstáculos divertidos! 

---

## **Etapa 1: Cenário Bonito**
Adicione o cenário **"Blue Sky"** para que o jogo comece com um céu brilhante e ensolarado! 🌤️  
![Blue Sky](https://github.com/user-attachments/assets/ef68fe29-b2ef-4735-8f29-afc2da58dc0f)

---

## **Etapa 2: Gato Aventureiro**
- Adicione o ator **"Cat"** (gato fofinho) que será o protagonista do seu jogo.  
- **Dica:** Você pode mudar o nome do ator para **"gato"** e ajustar o tamanho para **70%** (menorzinho e ágil). 🐾  
![Cat](https://github.com/user-attachments/assets/49211e06-34c3-4125-812a-b4b52147ef61)

---

## **Etapa 3: Obstáculo Desafiador**
- Adicione a **"Tree"** (árvore) como o obstáculo que o gato precisará desviar. 🌲  
- Renomeie o ator para **"Arvore"** e ajuste o tamanho para **20%**.  

![Tree](https://github.com/user-attachments/assets/55c53f63-81f6-47a0-9578-54d1e9ac2bcb)

---

## **Etapa 4: Tela de Fim de Jogo**
1. Duplique o cenário **"Blue Sky"**.  
2. Renomeie o novo cenário para **"Fim de Jogo"**.  
3. Adicione um texto no centro: **"FIM DE JOGO"** em letras grandes e coloridas! 🎮  

![Fim de Jogo](https://github.com/user-attachments/assets/f803cdf8-671b-4347-8b59-d5112327ef80)

---

## **Etapa 5: Variável de Pontuação**
- Crie uma variável chamada **"pontos"** para acompanhar o desempenho no jogo. Cada vez que o obstáculo passa, o jogador ganha 1 ponto! 🏆  

---

## **Código para o Gato 🐱**

1. **Quando a bandeira verde for clicada:**  
   - **Posição inicial:** Vá para **x: -155, y: -125**.  
   - Troque para o cenário **"Blue Sky"**.  
   - Espere até que esteja tocando na **"Arvore"**.  
   - Troque para o cenário **"Fim de Jogo"**.  

2. **Quando a tecla "espaço" for pressionada:**  
   - Faça o gato **pular**!  
     - Deslize por 0.3 segundos até **x: -155, y: -50** (voando!).  
     - Volte ao chão com um deslizar de 0.4 segundos para **x: -155, y: -125**.

---

## **Código para a Árvore 🌲**

1. **Quando a bandeira verde for clicada:**  
   - Defina a variável **"pontos"** como **zero**.  
   - Sempre execute:  
     - Comece em **x: 241, y: -144** (fora da tela à direita).  
     - Deslize por **1 segundo** até **x: -239, y: -144** (atravesse a tela!).  
     - Adicione **1 ponto** à variável **"pontos"**.

---

## 🌟 **Agora é com você!**
Você pode adicionar sons divertidos, como um **"plim"** a cada ponto ganho ou um **"bum!"** quando o gato bate na árvore. 🥳 Solte sua imaginação e divirta-se!
