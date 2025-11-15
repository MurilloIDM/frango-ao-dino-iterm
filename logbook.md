- [] Estruturar tabelas do banco
- [] Criar as entidades de domínio
- [] Criar fluxo completo do cadastro/autenticação
- [] Criar menu principal:

1. Nova ficha de treino
2. Gerenciar fichas anteriores
   2.1 Deletar ficha (seletor de fichas)
   2.2 Visualizar completo (seletor de fichas)
   2.3 Gerar PDF (seletor de fichas)
   2.4 Voltar (Menu principal)
3. Configurações
   3.1 Editar idioma
4. Encerrar
   4.1 Sair e encerrar todos e qualquer operação que estiver executando

- [] Criar fluxo completo da gestão do perfil do usuário (mudar idioma)
- [] Criar fluxo completo de cadastro para nova ficha
- [] Criar fluxos relacionados as fichas anteriores

## Tabelas

### Account

- id
- name
- email
- password
- language
- created_at
- updated_at

### AnamnesisAsk

- id
- label
- type (normal, single, multiple)
- options (OPTION_1,OPTION_2,OPTION_3)

## AnamnesisAnswer

- account_id
- anmnesis_ask_id
- training_sheet_id
- response

## TrainingSheet

- id
- account_id
- data
