# 🐾 Sistema de Gerenciamento para PetShop

Este projeto apresenta a modelagem conceitual de um banco de dados para um PetShop, desenvolvido com o objetivo de organizar informações sobre clientes, animais, serviços, produtos e atendimentos realizados.

---

## 🎯 Objetivo

O sistema tem como finalidade facilitar o gerenciamento das atividades de um PetShop, permitindo o controle de clientes, pets, agendamentos e serviços prestados.

---

## 🏗️ Entidades Principais

### 👤 Cliente
Responsável pelos animais cadastrados.

#### Atributos:
- Id_Cliente
- Nome
- CPF
- Telefone
- Email
- Endereço

---

### 🐶 Pet

Armazena informações dos animais.

#### Atributos:
- Id_Pet
- Nome
- Espécie
- Raça
- Idade
- Sexo
- Peso

---

### 🩺 Serviço

Representa os serviços oferecidos pelo PetShop.

#### Atributos:
- Id_Servico
- Nome
- Descrição
- Valor

Exemplos:
- Banho
- Tosa
- Consulta Veterinária
- Vacinação

---

### 📅 Agendamento

Controla os atendimentos realizados.

#### Atributos:
- Id_Agendamento
- Data
- Horário
- Status

---

## 🔗 Relacionamentos

### Possui
- Um cliente pode possuir vários pets.
- Um pet pertence a apenas um cliente.

### Agenda
- Um cliente pode realizar vários agendamentos.

### Recebe
- Um pet pode receber diversos serviços.

### Realiza
- Um agendamento pode conter um ou mais serviços.

---

## 📊 Benefícios

- Organização dos clientes e animais.
- Controle dos serviços prestados.
- Gerenciamento de atendimentos.
- Histórico completo dos pets.

---

## 📚 Conceitos Aplicados

- Banco de Dados Relacional
- Modelo Entidade-Relacionamento (MER)
- Cardinalidade
- Chaves Primárias
- Relacionamentos

---

## 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e aprendizado em modelagem de banco de dados.
