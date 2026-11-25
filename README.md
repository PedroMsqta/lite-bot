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
        <img alt="Version" src="https://img.shields.io/badge/Vers%C3%A3o-1.2.1-blue?style=flat-square">
    </a>
    <a href="https://github.com/PedroMsqta/lite-bot/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/Licen%C3%A7a-GPL--3.0-green?style=flat-square">
    </a>
    <img alt="Status" src="https://img.shields.io/badge/Status-Ativo-brightgreen?style=flat-square">
</div>

<br />

## Sobre o Projeto

O **Lite Bot ☕︎** é um bot de WhatsApp Open Source, desenvolvido em JavaScript com foco em simplicidade, praticidade e múltiplas funcionalidades.

Criado para oferecer recursos de automação, gerenciamento de grupos, ferramentas de produtividade e integração com inteligência artificial, o projeto possui uma estrutura organizada e permite personalizações diretamente em seus arquivos de configuração.

Desenvolvido por **Dev Pedro ☕︎**, o Lite Bot foi pensado para funcionar em ambientes como Termux e Linux, mantendo uma experiência simples de instalação e utilização.

### Características

- **Multifunções:** ferramentas para administração de grupos e utilização individual.
- **Inteligência artificial:** integração com Herc.ai para geração de imagens.
- **Automação:** respostas automáticas e gerenciamento de recursos.
- **Personalização:** prefixo, nome, emoji e números configuráveis.
- **Código aberto:** estrutura disponível para estudo, utilização e contribuição.
- **Integrações:** conexão com WhatsApp por meio da Baileys e serviços externos.

## Estrutura do Projeto

<div align="center">
  <img src="https://img.shields.io/badge/LITE%20BOT- PROJECT-A78BFA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PROJECT%20STRUCTURE-OVERVIEW-F9A8D4?style=for-the-badge" />
</div>

<br />

<div align="center">
  <svg width="100%" viewBox="0 0 720 760" xmlns="http://www.w3.org/2000/svg">
    <rect width="720" height="760" rx="12" fill="#242424"/>
    <text x="30" y="48" fill="#A78BFA" font-size="22" font-weight="bold" font-family="monospace">lite-bot/</text>
    <g font-family="monospace" font-size="15">
      <g fill="#F9A8D4">
        <text x="30" y="85">├── assets/</text>
        <text x="65" y="110">└── images/</text>
      </g>
      <g fill="#BAE6FD">
        <text x="100" y="135">├── default-user.png</text>
        <text x="100" y="160">├── erros-comuns-1.png</text>
        <text x="100" y="185">└── menu.png</text>
      </g>
      <text x="30" y="225" fill="#F9A8D4">├── baileys/</text>
      <text x="30" y="260" fill="#F9A8D4">├── database/</text>
      <g fill="#FEF08A">
        <text x="65" y="285">├── .gitignore</text>
        <text x="65" y="310">└── db.js</text>
      </g>
      <text x="30" y="350" fill="#F9A8D4">├── errors/</text>
      <g fill="#FEF08A">
        <text x="65" y="375">├── DangerError.js</text>
        <text x="65" y="400">├── InvalidParameterError.js</text>
        <text x="65" y="425">├── WarningError.js</text>
        <text x="65" y="450">└── index.js</text>
      </g>
      <text x="30" y="490" fill="#F9A8D4">├── services/</text>
      <g fill="#C4B5FD">
        <text x="65" y="515">├── hercai.js</text>
        <text x="65" y="540">└── poorplix-api.js</text>
      </g>
      <text x="30" y="580" fill="#F9A8D4">├── temp/</text>
      <text x="30" y="615" fill="#F9A8D4">├── utils/</text>
      <g fill="#FEF08A">
        <text x="65" y="640">├── functions.js</text>
        <text x="65" y="665">├── menu.js</text>
        <text x="65" y="690">└── terminal.js</text>
      </g>
    </g>
  </svg>
</div>

```text
lite-bot/
├── config.js
├── connection.js
├── index.js
├── welcome.js
├── test.js
├── package.json
├── README.md
├── LICENSE
└── .gitignore
```

## Linguagens e Tecnologias

<div align="center">
    <img src="https://skillicons.dev/icons?i=js,nodejs,git,bash,linux&theme=dark" alt="Linguagens e Ferramentas" />
    <br><br>
    <a href="#" title="Baileys"><img src="https://cdn.simpleicons.org/whatsapp/25D366" alt="Baileys" width="45" height="45" /></a>
    &nbsp;&nbsp;
    <a href="#" title="FFMPEG"><img src="https://cdn.simpleicons.org/ffmpeg/007808" alt="FFMPEG" width="45" height="45" /></a>
    &nbsp;&nbsp;
    <a href="#" title="Yarn"><img src="https://cdn.simpleicons.org/yarn/2188B6" alt="Yarn" width="45" height="45" /></a>
    &nbsp;&nbsp;
    <a href="#" title="Axios"><img src="https://cdn.simpleicons.org/axios/5A29E4" alt="Axios" width="45" height="45" /></a>
    &nbsp;&nbsp;
    <a href="https://github.com/Bes-js/herc.ai" title="Herc.ai">
  <img src="https://api.iconify.design/mdi/brain.svg?color=%23A78BFA" alt="Herc.ai" width="45" height="45" />
</a>
    &nbsp;&nbsp;
    <a href="#" title="Poorplix API"><img src="https://cdn.simpleicons.org/rocket/FF6600" alt="Poorplix API" width="45" height="45" /></a>
</div>

<br />

## Funcionalidades

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

### Aplicativos Necessários

Instale as ferramentas que você vai usar para editar os arquivos e rodar o bot:

<details>
  <summary>Aplicativos recomendados</summary>

  <p>Utilize um dos aplicativos abaixo para editar arquivos e executar o Lite Bot:</p>

  - **MT Manager:** <a href="https://mt2.cn/" target="_blank">Acessar site</a> — editor e gerenciador de arquivos.
  - **Acode:** <a href="https://acode.app/" target="_blank">Acessar site</a> — editor de código.
  - **Termux:** <a href="https://f-droid.org/packages/com.termux/" target="_blank">Acessar download</a> — terminal para executar o bot.

</details>

> **Atenção:** Evite instalar o Termux pela Google Play Store. A versão da loja está desatualizada e não recebe mais manutenção. Use os ícones do **F-Droid** ou do **GitHub** acima.

---

Abaixo está o Guia para instalação. Clique nas setinhas para expandir.

<details>
<summary><b>Passo 1: Preparando o Termux e Permissões</b></summary>
<br>

1. Abra o **Termux** no seu celular.
2. Para dar permissão de acesso aos arquivos, digite o comando abaixo e aperte Enter:
```sh
termux-setup-storage
```

Atenção: Aceite a permissão que aparecerá na tela do celular.

</details>

<details>
<summary><b>Passo 2: Instalando as Ferramentas</b></summary>
<br>

Copie e cole o código abaixo no Termux para instalar o Node.js, Git, FFMPEG e o Yarn de uma vez só:

```sh
pkg upgrade -y && pkg update -y && pkg install git -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && npm install -g yarn
```

Dica: Se o Termux fizer alguma pergunta no meio do processo (como [Y/n]), digite y e aperte Enter.

</details>

<details>
<summary><b>Passo 3: Baixando o Bot</b></summary>
<br>

Agora baixe os arquivos do projeto. Cole o comando:

```sh
cd /sdcard && git clone https://github.com/PedroMsqta/lite-bot.git && cd ./lite-bot
```

O que faz? Ele entra na memória do celular, baixa o projeto e entra na pasta lite-bot.

</details>

<details>
<summary><b>Passo 4: Configurando o Bot</b></summary>
<br>

1. Use o MT Manager ou o Acode para abrir a pasta /sdcard/lite-bot.
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
<summary><b>Passo 6: Iniciando o Bot</b></summary>
<br>

Agora que o WhatsApp já está conectado, você não precisa mais do código de pareamento. Para ligar o bot no dia a dia, basta entrar na pasta e rodar:

```sh
yarn start
```

ou

```sh
npm start
```

Pronto! O Lite Bot está online.

</details>

<br />

Comandos que necessitam de API

Alguns comandos precisam de uma chave de API para funcionar. Edite a linha 34 do arquivo config.js e cole seu token:

```js
exports.POORPLIX_API_TOKEN = "seu_token_aqui";
```

Para obter seu token, acesse a plataforma Poorplix API e crie sua conta gratuitamente em breve.

<br />

Erros comuns

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

Conecte-se com o Dev

<div align="center">
  <a href="https://www.youtube.com/@DevPedro?sub_confirmation=1" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="40" />
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/PedroMsqta" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="GitHub" height="40" />
  </a>
</div>

<br />

Como contribuir

Este é um projeto Open Source e sua contribuição é muito bem-vinda!

1. Faça um Fork do projeto.
2. Crie uma Branch para sua modificação (git checkout -b feature/MinhaNovaFuncao).
3. Faça o Commit de suas alterações (git commit -m 'Adicionando uma nova função').
4. Faça o Push para a branch (git push origin feature/MinhaNovaFuncao).
5. Abra um Pull Request.

<br />

Licença

GPL-3.0

Este projeto está licenciado sob a Licença Pública Geral GNU (GPL-3.0).

Isso significa que você pode usar, modificar e compartilhar o código, desde que:

· Mantenha os créditos ao autor original: Pedro Lucas - Dev Pedro ☕︎.
· Torne o código modificado disponível sob a mesma licença GPL-3.0.

<br />

Disclaimer

Neste projeto, precisei hospedar a node_modules, para auxiliar quem está rodando o bot pelo celular, pois muitos deles podem não rodar o npm install ou yarn pelo Termux corretamente.