# Requisitos Funcionais
## Cadastro e Login
- [RF01] O usuário deve ser capaz de se cadastrar como produtor ou consumidor.
- [RF02] O sistema deve efetuar login de usuários de forma simples com e-mail e senha.
- [RF03] O sistema deve ter um usuário com permissões de admin para a cooperativa.
 
## Divulgação de Produtos e Serviços
- [RF04] O usuário de tipo produtor pode cadastrar produtos (com nome, descrição, preço, data de validade e foto).
- [RF05] O usuário de tipo produtor pode categorizar produtos (ex.: alimentos, artesanato, serviços).
- [RF06] O usuário de tipo produtor pode categorizar o "impacto ambiental" no cadastro de produtos (ex.: baixo, médio, alto).
- [RF07] O sistema deve permitir que produtores editem ou removam produtos cadastrados.

## Busca e Navegação
- [RF08] O usuário pode buscar produtos por nome, categoria ou preço.
- [RF09] O sistema deve conter uma página inicial com lista de produtos em destaque.
- [RF10] O sistema deve possuir filtro por "impacto ambiental" na busca de produtos.
- [RF11] O sistema deve incluir uma seção de "produtos mais vendidos" ou "destaques da semana" na página inicial.

## Gestão de Pedidos

- [RF12] O sistema deve ter um carrinho de compras para usuários consumidores poderem adicionar produtos.
- [RF13] O sistema deve enviar a finalização de pedido para o produtor preparar.
- [RF14] O sistema deve ser capaz de receber o prazo para disponibilidade do usuário produtor e reencaminhar para o usuário consumidor
- [RF15] O sistema deve conter informações dos pedidos (id, valor, produtos, nome do usuário) para retirada
- [RF16] O usuário consumidor pode escolher se a retirada será no endereço do produtor ou direto na cooperativa
- [RF17] O sistema deve conter status de pedido para consulta e edição (ex.: "em preparação", "pronto para retirada", "entregue").
- [RF18] O sistema deve permitir que o consumidor cancele o pedido antes da confirmação do produtor.
- [RF29] O usuário consumidor pode adicionar avaliação do pedido para cada produtor (ex.: notas de 1 a 5).

## Seção de Excedentes

- [RF20] O sistema deve conter uma área especial para, produtos excedentes ou com prazo de validade próximo, com preços reduzidos.

# Requisitos Não Funcionais 
- [RNF01] O sistema deve carregar rapidamente, mesmo com muitos produtos cadastrados.
- [RNF02] Os dados dos usuários devem ser protegidos (senhas criptografadas).
- [RNF03] O sistema deve ser compatível com dispositivos móveis.
- [RNF04] A interface simples e fácil de usar, mesmo para pessoas com pouca experiência tecnológica.
- [RNF05] O sistema deve funcionar nos principais navegadores (Chrome, Firefox, Edge).
- [RNF06] O sistema deve estar sempre disponível, com pouquíssimo tempo de inatividade.

