<div align="center">

<img src="./assets/banner.svg" alt="SrTecc, automação, integrações e dados" width="100%">

<br>

**Construo sistemas que continuam trabalhando depois que eu fecho o editor.**

Automação de processos, integrações entre plataformas e pipelines de dados.
Do coletor até a entrega, com o mínimo de intervenção manual no meio.

<br>

</div>

---

## Stack

<div align="center">

**Back-end e dados**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Front-end**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Automação e infra**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

</div>

---

## Em destaque

<div align="center">
<a href="https://github.com/SrTecc/qr-forge">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SrTecc&repo=qr-forge&theme=tokyonight&bg_color=0b1220&title_color=38bdf8&text_color=8fb3d9&icon_color=22d3ee&hide_border=true" alt="qr-forge">
</a>
</div>

**[qr-forge](https://github.com/SrTecc/qr-forge)** gera QR Code para PIX,
WhatsApp, WiFi e contato. O trabalho não está em desenhar o código, e sim em
montar o payload: o BR Code do PIX usa estrutura EMV com CRC16, senha de WiFi
com ponto e vírgula corta o payload no meio, e número de WhatsApp com parêntese
gera link quebrado.

A biblioteca não tem dependência de runtime, e a geração acontece inteiramente
no navegador, então chave PIX e senha de rede não saem da máquina de quem usa.

`TypeScript` `Next.js` `51 testes`

---

## No que eu trabalho

<table>
<tr>
<td width="50%" valign="top">

### 🔁 Pipelines de automação

Fluxos que rodam sozinhos em cima de **n8n**, Node e Python: coleta de dados,
regras de filtragem, geração de conteúdo com IA e distribuição multicanal.

Cada etapa é idempotente e testada isoladamente. Rodar duas vezes não duplica
nada, e falha de um item não derruba o lote.

</td>
<td width="50%" valign="top">

### 🔌 Integrações de plataforma

Consumo e orquestração de APIs de terceiros: mensageria, marketplaces, CRMs e
serviços de IA.

Onde não existe API oficial, entra automação de navegador com **Playwright**,
com a ressalva honesta de onde isso é frágil.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Dados e curadoria

Modelagem em **PostgreSQL** e **MongoDB**, migrations versionadas, e histórico
para detectar o que os dados brutos escondem.

Regra que eu sigo: o número que chega ao usuário final nunca é escrito por IA.
Vem do banco.

</td>
<td width="50%" valign="top">

### 🤖 Aplicações com IA

Uso de LLM onde ele agrega de verdade, para escrever texto, classificar e
extrair, sempre com validação da resposta e caminho de fallback.

Modelo que falha não pode virar erro na cara do usuário.

</td>
</tr>
</table>

---

## Como eu gosto de trabalhar

- **Idempotência antes de agendamento.** Se rodar duas vezes quebra, não está pronto para automatizar.
- **Configuração no ambiente, não no código.** Nenhum valor mágico espalhado pelo repositório.
- **Registrar a decisão, não só o código.** O *porquê* é o que se perde primeiro.
- **Ser honesto sobre o que não foi testado.** "Escrito" e "validado" são coisas diferentes.

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SrTecc&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=tokyonight&bg_color=0b1220&title_color=38bdf8&icon_color=22d3ee&text_color=8fb3d9" height="165" alt="Estatísticas">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SrTecc&layout=compact&hide_border=true&langs_count=8&theme=tokyonight&bg_color=0b1220&title_color=38bdf8&text_color=8fb3d9" height="165" alt="Linguagens">

</div>
