# chat_socketio_node
# 💬 Chat em Tempo Real com Node.js e Socket.io

Um **chat simples** em tempo real utilizando **Node.js, Express e Socket.io**, projetado para estudos e como um dos **108 projetos de prática**.

---

## 🚀 Funcionalidades

✅ Enviar e receber mensagens em tempo real  
✅ Vários usuários na mesma sala de chat  
✅ Interface HTML/CSS simples  
✅ Possibilidade de acessar via **LAN ou internet (ngrok/localtunnel)** para conversar com outras pessoas

---


---

## 🛠️ Instalação

1️⃣ Clone o repositório:

git clone https://github.com/seu-usuario/chat_socketio_node
cd chat_socketio_node

2️⃣ Instale as dependências:

bash
Copiar
Editar
npm install
▶️ Como rodar localmente
Execute o servidor:

bash
Copiar
Editar
node cod/server.js
Abra o navegador em:

arduino
Copiar
Editar
http://localhost:3000
Abra em outra aba ou outro dispositivo na mesma rede para conversar em tempo real.

🌐 Acessar de outro dispositivo / Internet
Usando Ngrok:
1️⃣ Instale/configure o Ngrok:

bash
Copiar
Editar
npx ngrok config add-authtoken SEU_TOKEN
2️⃣ Rode:

bash
Copiar
Editar
npx ngrok http 3000
3️⃣ Envie o link gerado para outra pessoa acessar o chat.

Usando LocalTunnel (alternativa gratuita):
bash
Copiar
Editar
npx localtunnel --port 3000
Envie o link gerado para quem desejar acessar.

🧩 Tecnologias utilizadas
Node.js

Express

Socket.io

HTML / CSS

🪪 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

✏️ Autor
Richard Souza
GitHub
