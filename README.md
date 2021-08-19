### Segundo Semestre
# Desafio Tech UAUBox
Bem vindo(a) ao Desafio Tech UAUBox, nesse desafio todos podem participar!
Após o envio da sua resolução iremos retornar em alguns dias para darmos o resultado e te mostrar
o caminho no qual você melhor se encaixa no mercado de trabalho,lembrando que também
vamos guardar o seu contato para vagas disponíveis aqui na UAU!

# Especificações

## Iniciar
Acesse o documento [clicando aqui](https://s3.amazonaws.com/static.uaubox.com.br/pspublico/Desafio+Tech+UAU+-+2021_2.pdf) para participar do nosso desafio.

## Serviços
*Você deverá escolher o método correto para cada endpoint seguindo as rotas especificadas*<br />
*Você poderá adicionar mais dados nas tabelas se achar necessário*

***Todas as tabelas devem possuir os timestamps (created_at, updated_at, deleted_at)***

### Autenticação
- Endpoints
  - [/signup]   Cadastro
  - [/signin]   Login
  - [/validate] Validar
  - [/me]       Dados Pessoais
  - [/me]       Remover
- Dados Necessários
  - user
    - name
    - email
    - password
  - user_info
    - cpf
    - birthdate
    - phone
    - address

### Assinatura
- Endpoints
  - [/]     Nova
  - [/]     Listar Todas
  - [/:id]  Detalhar Uma
  - [/:id]  Cancelar
- Dados Necessários
  - subscription
    - edition (ex.: 202101 | ano+mês)
    - status (ex.: ACTIVE)
    - type (utilizar o enum SUBSCRIPTION_TYPES)
    - cancel_reason (nullable | utilizar o enum CANCEL_TYPES)

## ENUMs
### CANCEL_TYPES
- financial_problems
- not_interested
- not_matching_profile
- other

### SUBSCRIPTION_STATUS
- ACTIVE
- CANCELED

### SUBSCRIPTION_TYPES
- montlhy
- quarterly
- biannual
- annual

# Envio
Ah, lembre de utilizar somente **1 repositório** para o envio do desafio, pode separar os serviços em pastas.

Acesse o formulário [clicando aqui](https://forms.gle/C2RueSNjnoMthCTX8)

# FAQ

### Quem Pode Participar?
Todos podem participar, ao contrário de outros processos seletivos neste buscamos um talento, independente de seu currículo.

### Data Limite
O fim do desafio ocorrerá no dia 01/12/2021, mas quanto antes enviar melhor!

### Posso ser selecionado para uma vaga na UAUBox?
Sim, enviando o seu desafio iremos analisar o seu perfil e caso faça sentido iremos entrar em contato.

### Qual a idade mínima para participar?
Você deve ter no mínimo 16 anos para participar.

### Qual a senioridade necessária?
No envio do formulário você poderá selecionar a senioridade desejada para ser avaliado.

### Tenho uma dúvida não técnica
Pode enviar qualquer dúvida que não influencie no seu desafio para o email [mateus.tozoni@uaubox.com.br](mailto:mateus.tozoni@uaubox.com.br)
<br /><br /><br />
<small>
**Com Amor,**<br />
Time Tech **UAUBox**
</small>
