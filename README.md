<div align="center">
    <h1>Lite Bot ☕︎</h1>
    <p><strong>Bot de WhatsApp minimalista multifunções</strong></p>
</div>

<p align="center">
    O <strong>Lite Bot</strong> foi construído por <strong>Dev Pedro ☕︎</strong> com o objetivo de ser uma base leve, rápida e multifunções para WhatsApp.<br/>
    O foco do projeto é entregar simplicidade, automações práticas e código limpo, sendo ideal para rodar de forma acessível <strong>diretamente pelo celular via Termux</strong>, sem perder a performance.
</p>

<div align="center">
  <a href="https://github.com/PedroMsqta">
    <img src="https://img.shields.io/badge/GitHub-PEDROMSQTA-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.youtube.com/@DevPedro">
    <img src="https://img.shields.io/badge/YouTube-DEV%20PEDRO-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
</div>

<br />

<div align="center">
    <img src="./assets/images/menu.png" width="100%">
</div>

<br />

<div align="center">
    <a href="https://github.com/PedroMsqta/lite-bot">
        <img alt="Version" src="https://img.shields.io/badge/Vers%C3%A3o-1.2.1-blue?style=for-the-badge">
    </a>
</div>

<br />

## 🛠️ Tecnologias envolvidas

<p align="left">
    <img src="https://img.shields.io/badge/Node.js-20.18.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
    <img src="https://img.shields.io/badge/Baileys-Latest-8e44ad?style=for-the-badge" alt="Baileys">
    <img src="https://img.shields.io/badge/FFMPEG-Latest-E67E22?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFMPEG">
    <img src="https://img.shields.io/badge/Yarn-1.22.22-2188B6?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn">
    <img src="https://img.shields.io/badge/Axios-Latest-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios">
    <img src="https://img.shields.io/badge/Herc.ai-API-blueviolet?style=for-the-badge" alt="Herc.ai">
    <img src="https://img.shields.io/badge/Poorplix_API-Em_breve-lightgrey?style=for-the-badge" alt="Poorplix API">
</p>

<br />

## ⚠ Atenção

Este projeto é **desenvolvido e mantido por Dev Pedro ☕︎**.
Não há vínculo com terceiros. Para suporte, utilize o canal oficial do projeto.

## 🚀 Instalação no Termux <a id="termux-setup"></a>

Organizamos a instalação em etapas simples para facilitar o seu aprendizado. Siga o Guia abaixo na ordem correta.

<details>
<summary><b>Passo 1: Preparando o Termux e as Permissões</b></summary>
<br>

1 - Abra o **Termux** no seu celular. 
_Não tem o Termux? [Clique aqui e baixe a última versão](https://www.mediafire.com/file/082otphidepx7aq/Termux_0.119.1_aldebaran_dev.apk)._

2 - Para que o bot consiga ler e salvar arquivos no seu celular, digite o comando abaixo e aperte Enter:

```sh
termux-setup-storage
```

⚠️ Atenção: Assim que rodar o comando, o celular vai pedir permissão de acesso aos arquivos. Clique em "Permitir".

</details>

<details>
<summary><b>Passo 2: Instalando as Ferramentas Necessárias</b></summary>
<br>

O bot precisa de algumas ferramentas para funcionar como o Node.js e o FFMPEG. Para instalar tudo de uma vez, copie e cole o código abaixo no Termux e aperte Enter:

```sh
pkg upgrade -y && pkg update -y && pkg install git -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && npm install -g yarn
```

💡 Dica: Esse processo pode demorar alguns minutos. Se o Termux fizer alguma pergunta durante a instalação como [Y/n], basta digitar y e apertar Enter.

</details>

<details>
<summary><b>Passo 3: Baixando o Bot</b></summary>
<br>

Agora vamos baixar os arquivos do bot direto do GitHub para a memória do seu celular. Quando o passo anterior terminar, cole o código abaixo:

```sh
cd /sdcard && git clone https://github.com/PedroMsqta/lite-bot.git && cd ./lite-bot
```

💡 O que isso faz? Ele entra na pasta do seu celular /sdcard, baixa o projeto git clone e já entra na pasta do bot /lite-bot. O bot ficará salvo em /sdcard/lite-bot.

</details>

<details>
<summary><b>Passo 4: Configurando o Bot</b></summary>
<br>

1 - Use um gerenciador de arquivos no celular para encontrar a pasta /sdcard/lite-bot e abra o arquivo chamado config.js.

Recomendamos o MT Manager v2.26.11 ou o ZArchiver para fazer isso.

2 - Altere as informações do arquivo com os seus dados:

```js
// Prefixo dos comandos
exports.PREFIX = "/";

// Emoji do bot (mude se preferir).
exports.BOT_EMOJI = "🤖";

// Nome do bot (mude se preferir).
exports.BOT_NAME = "Lite Bot";

// Número do bot. Coloque o número do bot (apenas números).
exports.BOT_NUMBER = "5511920202020";

// Número do dono do bot. Coloque o número do dono do bot (apenas números).
exports.OWNER_NUMBER = "5511999999999";
```

3 - Não esqueça de salvar o arquivo depois de editar.

</details>

<details>
<summary><b>Passo 5: Conectando ao WhatsApp</b></summary>
<br>

1 - Volte para o Termux e digite o caminho da pasta do bot:

```sh
/sdcard/lite-bot
```

2 - Inicie o bot rodando o comando:

```sh
yarn start
```

ou

```sh
npm start
```

3 - O Termux vai pedir o seu número de telefone. Digite o número com o DDD e aperte Enter.

4 - Em seguida, ele vai gerar um Código de Pareamento de 8 dígitos.

5 - Abra o WhatsApp no seu celular, vá em Dispositivos Conectados > Conectar um Dispositivo > Conectar com número de telefone.

6 - Insira o código de 8 dígitos que apareceu no Termux.

7 - Aguarde 10 segundos e, no Termux, aperte CTRL + C duas vezes para parar o bot.

</details>

<details>
<summary><b>Passo 6: Iniciando o Bot para uso</b></summary>
<br>

Agora que o WhatsApp já está conectado, o bot não vai mais pedir o número nem o código. Para ligar o bot no dia a dia, basta entrar na pasta e rodar:

```sh
yarn start
```

ou

```sh
npm start
```

🎉 Pronto! Seu bot está online e funcionando no WhatsApp.

</details>

<br>

Alguns comandos necessitam de API

Edite a linha 34 do arquivo config.js e cole sua api key da plataforma Poorplix API.

Para obter seu token, acesse: [em breve] e crie sua conta gratuitamente!

```js
exports.POORPLIX_API_TOKEN = "seu_token_aqui";
```

Funcionalidades

Função Online? Contexto Requer API?
Desligar o bot no grupo ✅ Dono ❌
Ligar o bot no grupo ✅ Dono ❌
Anti link ✅ Admin ❌
Banir membros ✅ Admin ❌
Ligar/desligar boas vindas ✅ Admin ❌
Marcar todos ✅ Admin ❌
Busca CEP ✅ Membro ❌
Figurinha de texto animada ✅ Membro ✅
Figurinha de texto ✅ Membro ✅
Geração de imagens com IA ✅ Membro ❌
GPT 4 ✅ Membro ✅
Ping ✅ Membro ❌
Play áudio ✅ Membro ✅
Play vídeo ✅ Membro ✅
Sticker ✅ Membro ❌

Erros comuns

Causa: Permission denied - permissão negada ao acessar cd /sdcard

<br/>

<div align="center">
    <img src="./assets/images/erros-comuns-1.png" width="500">
</div>

Solução: abra o termux, digite termux-setup-storage e depois, aceite as permissões

Inscreva-se no canal!

<div align="center">
  <a href="https://www.youtube.com/@DevPedro?sub_confirmation=1" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Inscreva-se no canal">
  </a>
</div>

Licença

GPL-3.0

Este projeto está licenciado sob a Licença Pública Geral GNU (GPL-3.0).


Isso significa que:

· Você pode usar este código como quiser, seja para projetos pessoais ou comerciais.
· Você pode modificar o código para adaptá-lo às suas necessidades.
· Você pode compartilhar ou vender o código, mesmo modificado, mas precisa:
  · Manter os créditos ao autor original: Pedro Lucas - Dev Pedro ☕︎.
  · Tornar o código modificado disponível sob a mesma licença GPL-3.0.

O que você não pode fazer:

· Não pode transformar este código em algo proprietário ou fechado e impedir outras pessoas de acessá-lo ou usá-lo.
  Esta licença garante que todos tenham acesso ao código-fonte e podem colaborar livremente, promovendo o compartilhamento e o aprimoramento do projeto.

⚠ Disclaimer

Neste projeto, precisei hospedar a node_modules, para auxiliar quem está rodando o bot pelo celular, pois muitos deles podem não rodar o npm install ou yarn pelo termux corretamente.