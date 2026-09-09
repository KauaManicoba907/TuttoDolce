# Documentação de Decisões

## DEC001 — Utilização de MySQL

### Decisão

Utilizar MySQL como banco de dados relacional.

### Motivo

O sistema possui diversos relacionamentos entre
usuários, produtos, pedidos, pagamentos e outras entidades.

---

## DEC002 — Utilização de Docker

### Decisão

Executar o MySQL através de Docker.

### Motivo

Permitir configurar o ambiente do banco de dados
sem depender de uma instalação local do MySQL.

---

## DEC003 — Uma única fonte de produção

### Decisão

O sistema não possuirá múltiplos vendedores ou lojas.

### Motivo

O projeto representa uma única produção de doces.

---

## DEC004 — Produtos podem ser desativados

### Decisão

Utilizar um campo de ativo/inativo para produtos.

### Motivo

Preservar o histórico de pedidos e evitar a remoção
desnecessária de registros.