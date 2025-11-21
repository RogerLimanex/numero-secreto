# 🎮 Jogo do Número Secreto  
Um simples e divertido jogo desenvolvido em **HTML, CSS e JavaScript**, onde o usuário tenta adivinhar um número secreto entre 1 e 50. O jogo fornece dicas de “maior” ou “menor” e conta o número de tentativas até o acerto.

---

## 🚀 Funcionalidades

- 🎯 Geração automática de um número secreto entre **1 e 50**  
- 🔁 Evita repetição de números sorteados até completar o limite da lista  
- 💬 Feedback visual + **leitura por voz** usando Web Speech API  
- 👀 Interface estilizada com responsividade  
- 🔄 Botão de “Novo Jogo” habilitado somente após acerto  
- 🧹 Campo de entrada limpo automaticamente a cada tentativa  

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Web Speech API** (para narração)

---

## 📁 Estrutura do Projeto

📂 Game em JavaScript 2
├── .vscode
│ └── launch.json
├── js-curso-2-aula1
│ ├── index.html
│ ├── style.css
│ ├── app.js
│ └── img/
│ ├── ia.png
│ ├── code.png
│ └── Ruido.png

---

## ▶️ Como Executar o Projeto

1. Instale a extensão **Live Server** no VS Code  
2. Clique com o botão direito no `index.html` → **Open with Live Server**  
3. O navegador abrirá automaticamente em algo como:

http://localhost:5500/js-curso-2-aula1/

O arquivo `launch.json` já está configurado para abrir o Chrome apontando para esse endereço.

---

## 📜 Regras do Jogo

1. O sistema escolhe um número aleatório entre **1 e 50**  
2. O jogador digita um número e clica em **Chutar**  
3. O jogo informa se o número secreto é *maior* ou *menor*  
4. Ao acertar, o jogo mostra quantas tentativas foram necessárias  
5. O botão **Novo Jogo** é ativado para reiniciar a partida  

---

## 🔊 Web Speech API

O texto exibido na tela também é **falado**, caso o navegador suporte:

- Idioma: `pt-BR`  
- Velocidade: `1.2x`  

Isso torna o jogo mais acessível e interativo.

---

## 📸 Interface

A interface foi construída com foco em:

- Visual moderno  
- Elementos destacados  
- Fundo com gradiente  
- Imagem decorativa  
- Estilo responsivo para telas menores  

---

## 🧩 Lógica Principal

### Sorteio sem repetição
O jogo mantém uma lista de números já sorteados (`listaDeNumerosSorteados`).  
Quando todos os números já foram usados, a lista é zerada automaticamente.

### Comparação e dicas
Ao tentar adivinhar:
- Se o chute for maior → “O número secreto é menor”
- Se o chute for menor → “O número secreto é maior”

### Reinício
O botão **Novo Jogo**:
- Reseta tentativas  
- Gera novo número  
- Limpa entrada  

---

## 📌 Melhorias Futuras (Sugestões)

- 🔊 Ativar/desativar narração  
- 🎨 Temas claro/escuro  
- 📊 Adicionar placar com histórico  
- 📱 Versão mobile aprimorada  

---

## 📄 Licença

Este projeto é livre para estudos e modificações.

---

✉️ **Criado para fins de aprendizado em JavaScript.**
