# Requisitos Funcionais
## Cadastro e Login
- [RF01] O usuário se cadastra na plataforma.
- [RF02] O usuário pode solicitar a habilitação como produtor
- [RF03] O usuário efetua login de forma simples com e-mail e senha.
- [RF04] O sistema deve ter um usuário com permissões de admin para a cooperativa.
- [RF05] O usuário admin - cooperativa pode aprovar ou negar habilitação de usuário como produtor.
 
## Divulgação de Produtos
- [RF06] O usuário com perfil de produtor não ativo não deve ser capaz de adicionar produtos
- [RF07] O usuário com perfil de produtor ativo pode cadastrar produtos (com nome, descrição, preço, data de validade e foto).
- [RF08] O usuário com perfil de produtor ativo pode categorizar produtos (ex.: alimentos, artesanato).
- [RF09] O usuário com perfil de produtor ativo pode categorizar o "impacto ambiental" no cadastro de produtos (ex.: baixo, médio, alto).
- [RF10] O usuário com perfil de produtor ativo pode editar ou remover produtos cadastrados.

## Busca e Navegação
- [RF11] O usuário pode buscar produtos por nome, categoria ou preço.
- [RF12] O sistema deve conter uma página inicial com lista de produtos em destaque.
- [RF13] O sistema deve possuir filtro por "impacto ambiental" na busca de produtos.
- [RF14] O sistema deve incluir uma seção de "produtos mais vendidos" ou "destaques da semana" na página inicial.

## Gestão de Pedidos
- [RF15] O sistema deve ter um carrinho de compras para usuários consumidores poderem adicionar produtos.
- [RF16] O sistema deve enviar a criação de pedido para o produtor preparar.
- [RF17] O sistema deve ser capaz de receber o prazo para disponibilidade do usuário produtor e reencaminhar para o usuário consumidor
- [RF18] O sistema deve conter informações dos pedidos (id, valor, produtos, nome do usuário) para retirada
- [RF19] O usuário consumidor pode escolher se a retirada será no endereço do produtor ou direto na cooperativa
- [RF20] O sistema deve conter status de pedido para consulta e edição (ex.: "em preparação", "pronto para retirada", "entregue").
- [RF21] O sistema deve permitir que o consumidor cancele o pedido antes da confirmação do produtor.

## Seção de Excedentes

- [RF22] O sistema deve conter uma área especial para, produtos excedentes ou com prazo de validade próximo a expirar, com preços reduzidos.

# Requisitos Não Funcionais 
- [RNF01] O sistema deve carregar rapidamente, mesmo com muitos produtos cadastrados.
- [RNF02] O sistema deve implementar as regras básicas de segurança e proteção de dados.
- [RNF03] O sistema deve ser compatível com dispositivos móveis.
- [RNF04] A ‘interface’ simples e fácil de usar, mesmo para pessoas com pouca experiência tecnológica.
- [RNF05] O sistema deve funcionar nos principais navegadores (Chrome, Firefox, Edge).
- [RNF06] O sistema deve estar sempre disponível, com pouquíssimo tempo de inatividade.
- [RNF07] O sistema deve conter uma base de dados SQL (**PostgreSQL**)
- [RNF08] O sistema deve usar a linguagem **C#** com _**Asp.net**_ core para a construção da API
- [RNF09] O sistema deve usar a biblioteca **ReactJS** para construção do frontend

