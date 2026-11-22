# Controle de Compras

Aplicativo web de controle de compras com categorias, níveis de importância, filtros, busca e backup em JSON.

Os dados são sincronizados em tempo real entre todos os dispositivos que acessarem o link, usando Firebase Firestore.

## Como usar

Abra o site publicado pelo GitHub Pages. Adicione itens, altere o status, filtre por categoria/importância/status e use **Configurações** para gerenciar categorias, níveis de importância e baixar um backup.

## Publicação

O site é publicado automaticamente pelo GitHub Actions sempre que houver um push na branch `main`.

## Configuração do Firebase

O arquivo `index.html` já contém a configuração do projeto Firebase `controle-de-compras-1c1ec`. Para que a sincronização funcione, o Firestore deve estar criado nesse projeto.
