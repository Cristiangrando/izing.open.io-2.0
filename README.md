[![Grupo do WhatsApp](https://img.shields.io/badge/WhatsApp-Grupo%20IZING-brightgreen.svg)](https://chat.whatsapp.com/IIReEheixAx27ZbneHpskP)

# Izing

Um sistema para gestão de atendimento multicanais centralizado.


**IMPORTANTE**: não garantimos que a utilização desta ferramenta não irá gerar bloqueio nas contas utilizadas. São bots que em sua maioria utilizam APIs secundarias para comunicação com os fornecedores dos serviços. Use com responsabilidade!

<br/>

## Screenshots

![Doação](screenshots/Bot.gif)
<br/>

![Doação](screenshots/dashboard.gif)
<br/>

![Doação](screenshots/izing.gif)
___

<br/>

## Principais funcionalidades

- Multíplos canais de atendimento ✅
- Multíplos usuários simultâneos por canais de atendimento ✅
- Iniciar conversa com contatos existentes (whatsapp) ✅
- Construção de Chatbot interativo ✅
- Enviar e receber mensagens ✅
- Enviar e receber mídias diversas (imagens/áudio/documentos) ✅
- Multiempresas (abordagem de base compartilhada)

<br/>

## Instalando
Seguem links sugerimos:
-  [Como Instalar o IZING - Método 2024 Video](https://youtu.be/bZ-jXRtcGyc?si=B8oQxv0V0V36fgrF)
-  [Como Instalar o IZING - Método 2023 Video](https://www.youtube.com/watch?v=0j1v6m4Nk74&t=379s)

-  [Como Instalar o IZING VPS - Método 2024 - UBUNTU 20, 22](docs/INSTALL_VPS_UBUNTU_20_22.md)
-  [Como Instalar o IZING WINDOWS LOCALHOST - Método 2024](docs/INSTALL_LOCALHOST_WINDOWS.md)

-  [Instalador automatico](https://github.com/cleitonme/izing.instalador)
<br/>

## Diferenças dessa versão repositorio ldurans

Bugs:
*Correção encaminhar mensagens
*Correção envio arquivos
*Correção bug montar fluxo (perdia etapa 2 cliques)
*Correção bug envio video
*Correção bug apagar mensagem
*Correção bug apagar mensagem agendada
*Correção arquivos sumir do chatbot

Melhorias:
*Arquivo server.js frontend para facilitar instalacao
*Atualizacao versao whaapp.js^1.23.1-alpha.6 para melhorar a conexao whatsapp
*Abas aberto, pedente, fechado e grupos no painel atendimento 
*Tickets fechados ja vir selecionado atendimento(como coloquei abas para separar atendimentos achei melhor fechados já aparecer)
*Fundo dark whatsapp para modo escuro 
*Botao espiar ticket e adaptacao layout
*Mudanca cache local melhora na conexão(depois varios testes veriquei que com essa mudança a conexão fica mais rapida e da menos erros leitura QRCODE)
*Update libs instagram para melhor conexão com instagram
*Botao modelo planilha para importar contatos 
*Botao modelo POSTMAN api
*Emoji na mensagem de despedida
*Variáveis nas campanhas
*Aceitar audios gravados no whatsapp-formato .ogg


## Atualizando

Izing é um trabalho em progresso e estamos frequentemente adicionando novas funcionalidades e correções de bugs.

<br/>

**IMPORTANTE**: verifique sempre o .env.example e ajuste o seu .env antes de atualizar, uma vez que algumas novas variáveis podem ser adicionadas.


<br/>

## FIQUE ATENTO

A utilização desta ferramenta é feita por sua conta e risco. O código é aberto e todos podem contribuir.

Este projeto não é afiliado, associado, autorizado, endossado por, ou de qualquer forma oficialmente ligado à WhatsApp, ou a qualquer uma das suas filiais ou afiliadas. O website oficial da WhatsApp pode ser encontrado em <https://whatsapp.com>. "WhatsApp", bem como nomes, marcas, emblemas e imagens relacionadas são marcas registadas dos seus respectivos proprietários.

--------------------------
<br/>


#### Curtiu? Apoie o projeto!! Com sua doação, será possível continuar com as atualizações. Segue QR code (PIX)  

[<img src="donate.jpeg" height="150" width="200"/>](donate.jpeg)

--------------------------
<br/>

## **Licença e seus requerimentos**

Izing é open-source, licenciado com base na licença GNU Affero General Public License Version 3 [(AGPLv3)](https://www.gnu.org/licenses/agpl-3.0.pt-br.html). O objetivo da licença AGPL é maximizar a liberdade do usuário e incentivar as empresas a contribuir com o código aberto.

Você pode usar o izing em sua própria estrutura, desde que não seja para fins de comercialização.
Você pode fazer um fork do projeto para realizar suas alterações, implementar os recursos desejados, mas deverá abrir o código para a comunidade, conforme previsto pela licença. 

Uma vez que você deseje utilizar o izing para fins comerciais, todas as suas alterações, seu código fonte, precisa ser aberto (open source) para acesso pela comunidade, conforme licença. Bem como, deverá de forma clara, evidenciar aos seus usuários/clientes em menção de destaque ao projeto oficial (https://izing.io). Também é requerido a menção que você fornece uma versão alterada do izing e, em algum lugar do seu site, deverá fornecer o link para o repositório do seu projeto, permitindo que todos possam verificar as mudanças realizadas.

