```md
<div align="center">
    <img src="./assets/images/menu.png" width="100%" alt="Lite Bot Banner">
</div>

<br />

<div align="center">
    <h1>Lite Bot ☕︎</h1>
    <p><strong>O bot de WhatsApp minimalista, rápido e multifunções.</strong></p>
    <p>Desenvolvido por <b>Dev Pedro ☕︎</b></p>
</div>

<div align="center">
    <a href="https://github.com/PedroMsqta/lite-bot">
        <img alt="Version" src="https://img.shields.io/badge/Vers%C3%A3o-1.2.1-blue?style=for-the-badge">
    </a>
    <a href="https://github.com/PedroMsqta/lite-bot/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/Licen%C3%A7a-GPL--3.0-green?style=for-the-badge">
    </a>
    <img alt="Status" src="https://img.shields.io/badge/Status-Ativo-brightgreen?style=for-the-badge">
</div>

<br />

## 📖 Sobre o Projeto

O **Lite Bot** é um projeto **100% Open Source** construído com o objetivo de ser uma base leve, rápida e altamente multifunções para WhatsApp. O foco principal é entregar **simplicidade, automações práticas e código limpo**, sendo ideal para rodar de forma acessível (diretamente pelo celular via Termux) sem perder a performance.

<br />

## 🛠️ Linguagens e Tecnologias

<div align="center">
    <p>As principais linguagens e ferramentas que movem o bot:</p>
    <img src="https://skillicons.dev/icons?i=js,nodejs,git,bash,linux&theme=dark" alt="Minhas Habilidades" />
    <br><br>
    <p><i>Bibliotecas e APIs específicas do projeto:</i></p>
    <img src="https://img.shields.io/badge/Baileys-Latest-8e44ad?style=for-the-badge" alt="Baileys">
    <img src="https://img.shields.io/badge/FFMPEG-Latest-E67E22?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFMPEG">
    <img src="https://img.shields.io/badge/Yarn-1.22.22-2188B6?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn">
    <img src="https://img.shields.io/badge/Axios-Latest-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios">
    <img src="https://img.shields.io/badge/Herc.ai-API-blueviolet?style=for-the-badge" alt="Herc.ai">
    <img src="https://img.shields.io/badge/Poorplix_API-Em_breve-lightgrey?style=for-the-badge" alt="Poorplix API">
</div>

<br />

## ✨ Funcionalidades

<table align="center">
  <thead>
    <tr>
      <th align="left">Função</th>
      <th align="center">Online?</th>
      <th align="center">Contexto</th>
      <th align="center">Requer API?</th>
    </tr>
  </thead>
  <tbody>
    <tr><td align="left">Desligar o bot no grupo</td><td align="center">✅</td><td align="center">Dono</td><td align="center">❌</td></tr>
    <tr><td align="left">Ligar o bot no grupo</td><td align="center">✅</td><td align="center">Dono</td><td align="center">❌</td></tr>
    <tr><td align="left">Anti link</td><td align="center">✅</td><td align="center">Admin</td><td align="center">❌</td></tr>
    <tr><td align="left">Banir membros</td><td align="center">✅</td><td align="center">Admin</td><td align="center">❌</td></tr>
    <tr><td align="left">Ligar/desligar boas vindas</td><td align="center">✅</td><td align="center">Admin</td><td align="center">❌</td></tr>
    <tr><td align="left">Marcar todos</td><td align="center">✅</td><td align="center">Admin</td><td align="center">❌</td></tr>
    <tr><td align="left">Busca CEP</td><td align="center">✅</td><td align="center">Membro</td><td align="center">❌</td></tr>
    <tr><td align="left">Figurinha de texto animada</td><td align="center">✅</td><td align="center">Membro</td><td align="center">✅</td></tr>
    <tr><td align="left">Figurinha de texto</td><td align="center">✅</td><td align="center">Membro</td><td align="center">✅</td></tr>
    <tr><td align="left">Geração de imagens com IA</td><td align="center">✅</td><td align="center">Membro</td><td align="center">❌</td></tr>
    <tr><td align="left">GPT 4</td><td align="center">✅</td><td align="center">Membro</td><td align="center">✅</td></tr>
    <tr><td align="left">Ping</td><td align="center">✅</td><td align="center">Membro</td><td align="center">❌</td></tr>
    <tr><td align="left">Play áudio</td><td align="center">✅</td><td align="center">Membro</td><td align="center">✅</td></tr>
    <tr><td align="left">Play vídeo</td><td align="center">✅</td><td align="center">Membro</td><td align="center">✅</td></tr>
    <tr><td align="left">Sticker</td><td align="center">✅</td><td align="center">Membro</td><td align="center">❌</td></tr>
  </tbody>
</table>

<br />

## Guia de Instalação [Termux]

Clique nas setinhas abaixo para expandir e ver o passo a passo de cada etapa.

<details>
<summary><b>Passo 1: Preparando o Termux e Permissões</b></summary>
<br>

1. Abra o **Termux** no seu celular. 
   *(Não tem o Termux? [Clique aqui e baixe a última versão](https://www.mediafire.com/file/082otphidepx7aq/Termux_0.119.1_aldebaran_dev.apk).)*

2. Para dar permissão de acesso aos arquivos, digite o comando abaixo e aperte Enter:
```sh
termux-setup-storage
```

⚠️ Atenção: Aceite a permissão que aparecerá na tela do celular.

</details>

<details>
<summary><b>Passo 2: Instalando as Ferramentas</b></summary>
<br>

Copie e cole o código abaixo no Termux para instalar o Node.js, Git, FFMPEG e o Yarn de uma vez só:

```sh
pkg upgrade -y && pkg update -y && pkg install git -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && npm install -g yarn
```

💡 Dica: Se o Termux fizer alguma pergunta no meio do processo (como [Y/n]), digite y e aperte Enter.

</details>

<details>
<summary><b>Passo 3: Baixando o Bot</b></summary>
<br>

Agora baixe os arquivos do projeto. Cole o comando:

```sh
cd /sdcard && git clone https://github.com/PedroMsqta/lite-bot.git && cd ./lite-bot
```

💡 O que faz? Ele entra na memória do celular, baixa o projeto e entra na pasta lite-bot.

</details>

<details>
<summary><b>Passo 4: Configurando o Bot</b></summary>
<br>

1. Use um gerenciador de arquivos (recomendamos o MT Manager) e abra a pasta /sdcard/lite-bot.
2. Abra o arquivo config.js e edite as informações com os seus dados:

```js
// Prefixo dos comandos
exports.PREFIX = "/";

// Emoji do bot (mude se preferir).
exports.BOT_EMOJI = "☕";

// Nome do bot (mude se preferir).
exports.BOT_NAME = "Lite Bot";

// Número do bot. (Apenas números)
exports.BOT_NUMBER = "5511920202020";

// Número do dono do bot. (Apenas números)
exports.OWNER_NUMBER = "5511999999999";
```

3. Salve o arquivo.

</details>

<details>
<summary><b>Passo 5: Conectando ao WhatsApp</b></summary>
<br>

1. No Termux, digite:

```sh
/sdcard/lite-bot
```

2. Inicie o bot com o comando:

```sh
yarn start
```

3. Digite o seu número de telefone (com DDD) quando o Termux pedir.
4. Ele vai gerar um Código de Pareamento de 8 dígitos.
5. Abra o WhatsApp no celular > Dispositivos Conectados > Conectar um Dispositivo > Conectar com número de telefone.
6. Insira o código gerado no Termux.
7. Aguarde 10 segundos, aperte CTRL + C duas vezes no Termux para parar o bot.

</details>

<details>
<summary><b>✅ Passo 6: Iniciando o Bot</b></summary>
<br>

Agora que o WhatsApp já está conectado, você não precisa mais do código de pareamento. Para ligar o bot no dia a dia, basta entrar na pasta e rodar:

```sh
yarn start
```

ou

```sh
npm start
```

🎉 Pronto! O Lite Bot está online.

</details>

<br />

⚙️ Comandos que necessitam de API

Alguns comandos precisam de uma chave de API para funcionar. Edite a linha 34 do arquivo config.js e cole seu token:

```js
exports.POORPLIX_API_TOKEN = "seu_token_aqui";
```

(Para obter seu token, acesse a plataforma Poorplix API e crie sua conta gratuitamente em breve).

<br />

🐛 Erros comuns

<details>
<summary><b>Erro: "Permission denied" ao acessar /sdcard</b></summary>
<br>

Causa: Falta de permissão do Termux para acessar os arquivos do celular.



<div align="center">
    <img src="./assets/images/erros-comuns-1.png" width="500">
</div>

Solução: Abra o Termux, digite termux-setup-storage e aceite as permissões na tela.

</details>

<br />

🌐 Conecte-se com o Dev

<div align="center">
  <a href="https://www.youtube.com/@DevPedro?sub_confirmation=1" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-Se_Inscreva-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
  </a>
  <a href="https://github.com/PedroMsqta" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-Siga_o_Dev-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

<br />

🤝 Como contribuir

Este é um projeto Open Source e sua contribuição é muito bem-vinda!

1. Faça um Fork do projeto.
2. Crie uma Branch para sua modificação (git checkout -b feature/MinhaNovaFuncao).
3. Faça o Commit de suas alterações (git commit -m 'Adicionando uma nova função').
4. Faça o Push para a branch (git push origin feature/MinhaNovaFuncao).
5. Abra um Pull Request.

<br />

📄 Licença

GPL-3.0

Este projeto está licenciado sob a Licença Pública Geral GNU (GPL-3.0).

Isso significa que você pode usar, modificar e compartilhar o código, desde que:

· Mantenha os créditos ao autor original: Pedro Lucas - Dev Pedro ☕︎.
· Torne o código modificado disponível sob a mesma licença GPL-3.0.

<br />

⚠ Disclaimer

Neste projeto, precisei hospedar a node_modules, para auxiliar quem está rodando o bot pelo celular, pois muitos deles podem não rodar o npm install ou yarn pelo Termux corretamente.

```