# Aplicação Laravel Sail

Este é um projeto base para uma aplicação Laravel usando o Laravel Sail e as dependências que você pode precisar. O Laravel Sail é uma ferramenta para facilitar o desenvolvimento local de aplicativos Laravel usando Docker. Como SGBD, escolhi Postgres.

## Requisitos

Certifique-se de ter os seguintes requisitos instalados na sua máquina:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Tutorial Laravel Sail](https://laravel.com/docs/10.x/sail)
- [Composer](https://getcomposer.org)

## Configuração

1. Clone este repositório para sua máquina local:

```
   git clone <URL_DO_SEU_REPOSITÓRIO>
```

Navegue até o diretório da aplicação:

```
cd NOME_DA_SUA_APLICACAO
```

Crie um arquivo `.env` baseado no arquivo .env.example e defina as variáveis de ambiente necessárias para a sua aplicação.

Inicie os serviços com o Laravel Sail:

```
./vendor/bin/sail up
```

Sua aplicação Laravel estará disponível em http://localhost. Acesse o aplicativo no seu navegador.

## Serviços e Dependências

Este projeto base inclui os seguintes serviços e dependências:

Laravel Sail: Ambiente Docker pré-configurado para o desenvolvimento Laravel.

PostgreSQL: Banco de dados PostgreSQL para sua aplicação.

você pode criar um `.env` a partir do `.env.example`
