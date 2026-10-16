# Flamengo Website

Site de notícias sobre o Flamengo, em PHP e MySQL. Foi meu primeiro projeto funcional completo: tem página pública de notícias e uma área de administração para criar, editar e apagar posts e administradores.

## Tecnologias

PHP, MySQL (mysqli), HTML, CSS e JavaScript.

## Como rodar

1. Instale o XAMPP (ou outro Apache + PHP + MySQL).
2. Copie a pasta do projeto para `htdocs`.
3. No phpMyAdmin, crie o banco `projtest` e importe `extra/bd/projtest.sql`.
4. Ajuste usuário e senha do banco em `factory/connect.php`, se precisar.
5. Abra `http://localhost/Flamengo-website/`.

## Pastas

- `paginas/`: páginas do site e do painel.
- `model/`: login e ações de criar, editar e apagar.
- `factory/connect.php`: conexão com o banco.
- `misc/fotos/`: imagens dos posts.
