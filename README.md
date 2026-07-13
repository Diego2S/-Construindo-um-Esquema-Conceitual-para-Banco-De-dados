# 🔧 Sistema de Gerenciamento de Oficina Mecânica

## 📖 Sobre o Projeto

Este projeto apresenta a modelagem conceitual e lógica de um banco de dados para um sistema de gerenciamento de uma oficina mecânica.

O modelo foi desenvolvido utilizando **MySQL Workbench**, aplicando conceitos de modelagem relacional, normalização e integridade referencial.

---

## 📊 Diagrama do Banco de Dados

<img width="884" height="1002" alt="Oficina" src="https://github.com/user-attachments/assets/4fad1e3d-10fe-4763-a756-7cdac8ae4737" />


---

## 📌 Regras de Negócio

- Um cliente pode possuir vários veículos.
- Cada veículo pertence a apenas um cliente.
- Um veículo pode possuir diversas Ordens de Serviço.
- Cada Ordem de Serviço é atribuída a uma equipe de mecânicos.
- Uma equipe pode atender várias Ordens de Serviço.
- Uma equipe é composta por um ou mais mecânicos.
- Cada Ordem de Serviço pode conter diversos serviços e peças.
- O valor da Ordem de Serviço é composto pelos serviços executados e pelas peças utilizadas.

---

## 🗂 Principais Entidades

- Cliente
- Veículo
- Ordem de Serviço
- Equipe de Mecânicos
- Mecânico
- Serviço
- Peça

Além das tabelas associativas:

- Serviços
- Itens
- Equipe_has_Mecanico

---

## 🛠 Tecnologias Utilizadas

- MySQL Workbench
- Modelo Entidade-Relacionamento (MER)
- Banco de Dados Relacional

---

## 📚 Conceitos Aplicados

- Modelagem de Banco de Dados
- Normalização
- Chaves Primárias (PK)
- Chaves Estrangeiras (FK)
- Relacionamentos 1:N
- Relacionamentos N:N
- Integridade Referencial

---

## 👨‍💻 Autor

**Diego Santos**

Estudante de Análise e Desenvolvimento de Sistemas, desenvolvendo projetos práticos para aprimorar conhecimentos em Banco de Dados, Back-end e Engenharia de Dados.
