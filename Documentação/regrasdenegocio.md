# Regras de Negócio

## RN001 — Produto inativo

Produtos inativos não podem ser adquiridos pelo cliente.

O produto pode permanecer registrado no banco de dados,
mas não deve ser disponibilizado para novas compras.

## RN002 — Quantidade do produto

A quantidade de um produto adicionada ao carrinho
não pode ser igual a zero.

## RN003 — Preço do produto

O preço de um produto não pode ser igual a zero.

## RN004 — Pedido personalizado

Pedidos personalizados precisam passar por análise
e aprovação antes de serem considerados confirmados.

## RN005 — Histórico de produtos

Produtos não devem ser necessariamente excluídos
fisicamente do banco de dados.

A utilização de um estado ativo/inativo permite
preservar referências históricas.

## RN006 — Fonte de produção

O sistema representa uma única fonte de produção.

Não existe gerenciamento de múltiplas lojas ou vendedores.