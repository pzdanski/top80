
# Projeto TODO List - Desafio Softpar

Este projeto é uma aplicação completa de gerenciamento de tarefas.

## Tecnologias
- Frontend: Vue.js + Quasar
- Backend: Laravel 9 + Postgres
- Extras: JWT, Exportação CSV, Lembretes por e-mail

## Como executar
### Backend
1. Navegue até a pasta backend
2. Instale as dependências com `composer install`
3. Configure o `.env` e rode as migrations com `php artisan migrate`
4. Inicie o servidor com `php artisan serve`

### Frontend
1. Navegue até a pasta frontend
2. Instale as dependências com `npm install`
3. Inicie o servidor com `quasar dev`

## Documentação
A documentação completa da API está em `docs/swagger.json`.

## Funcionalidades Extras
- JWT Authentication
- Lembrete automático por e-mail
- Exportação CSV

## MER
Veja em `docs/mer.pdf`.
