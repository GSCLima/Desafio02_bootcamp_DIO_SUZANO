# Modelo de Entidade-Relacionamento para Oficina Mecânica

Este repositório contém um modelo conceitual projetado para organizar os dados de uma oficina mecânica. O MER pode ser usado como base para implementar um banco de dados em sistemas de gerenciamento de oficinas.

## Objetivo
O objetivo deste modelo é fornecer uma estrutura clara e eficiente para gerenciar informações como:
- Dados dos clientes e seus veículos;
- Serviços realizados na oficina;
- Mecânicos responsáveis;
- Ordens de serviço;
- Orçamentos e tabelas de valores.

## Descrição das Tabelas
### 1. Cliente
Armazena informações dos clientes, como nome, CPF e histórico.

### 2. Veículos
Relaciona os veículos aos seus respectivos proprietários (clientes) e registra o tipo de serviço e uma descrição adicional.

### 3. Ordem de Serviço
Centraliza as informações sobre os serviços realizados, incluindo número da ordem, datas de emissão e conclusão, e o valor.

### 4. Equipe
Gerencia os mecânicos responsáveis por cada serviço.

### 5. Mecânicos
Detalha os dados dos mecânicos, como nome, endereço e especialidade.

### 6. Orçamento
Relaciona os orçamentos com as ordens de serviço, incluindo peças e mão de obra.

### 7. Tabela de Valores
Define os valores de serviços, mão de obra e produtos.

## Tecnologias e Ferramentas
- Ferramenta de modelagem: MySQL Workbench
- Diagrama salvo no formato de imagem para consulta.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para ajudar.

---
