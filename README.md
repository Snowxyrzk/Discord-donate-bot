<a href="#"><img width="100%" src="https://capsule-render.vercel.app/api?type=cylinder&height=250&color=gradient&text=Donate%20BOT"/></a>


## 📋 Sobre o Projeto
Este é um sistema completo de doações para Discord que utiliza a API do **PIX GG** para processar pagamentos. Inclui um bot Discord e uma API de verificação de doações.

> Sistema ideal para servidores que querem automatizar recompensas por doações!

<details>
  <summary>🛠️ Componentes do Sistema</summary>

### 1. 🤖 Bot Discord
- Interface interativa para doações
- Cargos automáticos conforme valor doado
- Verificação automática de pagamentos
- QR Code e código PIX gerado automaticamente
- Logs detalhados de cada doação

### 2. 🌐 API de Verificação
- Verificação de doações em tempo real
- Conexão direta com o PIX GG
- Autenticação segura com tokens
- Logs com data, valor, usuário e status
</details>

<details>
  <summary>📦 Instalação</summary>

### Pré-requisitos
- Node.js (v14+)
- npm ou yarn
- Conta no PIX GG
- Bot Discord configurado

### 📁 Configuração do Bot
```bash
cd "donate bot completo"
npm install
```
Crie o arquivo `.env` com:
```
DISCORD_TOKEN=seu_token_do_bot
PIXGG_URL=sua_url_do_pixgg
STREAMER_ID=seu_id_do_streamer
LOGS_CHANNEL_ID=id_do_canal_de_logs
API_URL=url_da_api
BASIC_ROLE_ID=id_do_cargo_basic
PLUS_ROLE_ID=id_do_cargo_plus
PRO_ROLE_ID=id_do_cargo_pro
TEST_ROLE_ID=id_do_cargo_teste
```

### 📁 Configuração da API
```bash
cd "api pix gg"
npm install
```
Crie o arquivo `.env` com:
```
LOGIN_URL=sua_url_de_login
DONATIONS_URL=sua_url_de_doacoes
EMAIL=seu_email
PASSWORD=sua_senha
```
</details>

<details>
  <summary>🚀 Como Usar</summary>

### Comando `/donate`
1. Inicie com o comando `/donate`
2. Escolha um valor
3. Escaneie o QR Code ou copie o código PIX
4. O sistema detecta o pagamento e aplica o cargo automaticamente

### Verificação manual
Use:
```
!verificar [token]
```
O sistema verifica doações a cada **10 segundos** automaticamente.
</details>

<details>
  <summary>⚙️ Funcionalidades</summary>

### 🎖️ Sistema de Cargos (editável)
- **Basic**: R$5 (30 dias)
- **Plus**: R$10 (30 dias)
- **Pro**: R$15 (30 dias)

> 📝 *Atualize os IDs e o tempo e o preço conforme sua preferência!*

### 💰 Sistema de aprovação de pagamento automático 
- aprova pagamentos e seta o cargo sozinho de acordo com o valor
- envia embed no privado dizendo que o pagamento foi aprovado
- log de doações
- tudo 100% automático e fácil 

  <summary>🔒 Segurança</summary>

- Variáveis sensíveis protegidas em `.env`
- Autenticação com tokens
- Verificação automática e segura dos pagamentos
- Backup automático dos logs
</details>

<details>
  <summary>📝 Logs</summary>

- Doações registradas em arquivos `.json`
- Incluem data, valor, usuário, status
- Sistema de backup automático incluso
</details>

<details>
  <summary>⚠️ Importante</summary>

  
- Proteja seu `.env`
- Nunca compartilhe tokens ou senhas
- Faça backup frequente
- Monitore doações com frequência
</details>

## 📄 Licença
Projeto **privado**. Proibida a redistribuição sem permissão.

# NOSSO DISCORD!
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gamesdest)

👤 Desenvolvido por:  
- [Snow](https://e-z.bio/im_snow)  
- [iUnknowbr](https://e-z.bio/iUnknownBr)
