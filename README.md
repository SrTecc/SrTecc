<div align="center">

<img src="./assets/banner.svg" alt="SrTecc, programo por hobby e construo por curiosidade" width="100%">

</div>

<br>

Programo por hobby. Meus projetos quase sempre começam do mesmo jeito: alguma
coisa me irritou, ou fiquei curioso para saber se dava para automatizar.

A maior parte do que eu construo é para uso próprio e fica em repositório
privado. Aqui em cima ficam os que fazem sentido para outra pessoa usar.

<br>

## Projetos públicos

<a href="https://github.com/SrTecc/qr-forge">
  <img src="./assets/qr-forge.svg" alt="qr-forge" width="460" align="right">
</a>

### [qr-forge](https://github.com/SrTecc/qr-forge)

Começou com uma pergunta: por que gerar um QR Code de PIX é mais chato do que
deveria ser?

A resposta é que desenhar o código já é problema resolvido há anos. A parte
difícil é montar o texto que vai dentro dele. O BR Code do PIX usa estrutura
EMV com CRC16, senha de WiFi com ponto e vírgula corta o payload no meio, e
número de WhatsApp com parêntese gera link quebrado.

Virou uma biblioteca sem nenhuma dependência, mais um site que roda inteiro no
navegador.

<br clear="right">

<br>

## Como eu gosto de resolver as coisas

Não tenho área de especialidade, tenho um tipo de problema que me prende: o que
dá para automatizar e ninguém automatizou ainda.

Na prática isso costuma virar três coisas.

**Fazer sistemas que não se conhecem conversarem.** Ligar plataformas que nunca
foram feitas para trabalhar juntas, geralmente por API, às vezes por caminhos
mais frágeis quando API não existe.

**Transformar processo repetitivo em algo que roda sozinho.** A graça aqui não
é fazer funcionar uma vez, é fazer aguentar rodar todo dia sem alguém olhando.

**Construir a ferramenta pequena que resolve um problema específico.** Quase
sempre nasce de algo que me atrapalhou duas vezes seguidas.

<br>

## Ferramentas

<div align="center">

<!-- Cada grupo fica numa unica linha de propriedade: quebra de linha no fonte
     faz o GitHub empilhar um badge por linha. -->

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

</div>

<br>

## Coisas que eu aprendi quebrando

**Se rodar duas vezes quebra, ainda não está pronto.** Vale para qualquer coisa
que vá rodar sem alguém olhando.

**O porquê é o que se perde primeiro.** Daqui a três meses o código continua
lá, a decisão que levou até ele não.

**"Funciona aqui" e "está testado" são coisas diferentes.** Descobri isso do
jeito difícil, mais de uma vez.

**Um número errado na tela custa mais caro que uma tela feia.** Por isso valor
e link nunca saem de um modelo de IA nos meus projetos. Saem do banco.
