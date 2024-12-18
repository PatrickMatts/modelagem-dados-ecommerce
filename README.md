# Modelagem de Dados para E-commerce

**Descrição do Projeto**

Este projeto apresenta a modelagem de dados para um sistema de e-commerce, desenvolvida com base em boas práticas de banco de dados relacionais. O modelo foi estruturado para atender às principais operações de um comércio eletrônico, como gestão de clientes, pedidos, produtos, pagamentos, entregas e estoque.

### Objetivos

O principal objetivo deste projeto é demonstrar uma estrutura de dados eficiente e bem organizada para um sistema de e-commerce, aplicando conceitos de:
- Modelagem relacional (entidades, atributos e relacionamentos)
- Generalização e especialização de dados (clientes PF e PJ)
- Normalização para evitar redundâncias
- Relacionamentos complexos (1:1, 1:N, N:N)

### Entidades Principais

1. **Cliente**
- Armazena os dados dos clientes, com especialização para Pessoa Física (PF) e Pessoa Jurídica (PJ).

2. **Pedido**
- Representa os pedidos realizados pelos clientes.
- Relacionamento: Cada pedido está vinculado a um cliente e possui uma entrega.

3. **Produto**
- Contém as informações dos produtos disponíveis no e-commerce.

4. **Pagamento** 
- Gerencia os tipos de pagamento e os detalhes relacionados aos pedidos.

5. **Entrega**
- Registra o status e o código de rastreamento das entregas.

6. **Estoque**
- Monitora a disponibilidade dos produtos em locais específicos.

### Tecnologia Utilizada
- **Ferramenta de Modelagem:** MySQL Workbench
  

Projeto desenvolvido como parte do meu aprendizado em modelagem de dados e banco de dados relacionais.
