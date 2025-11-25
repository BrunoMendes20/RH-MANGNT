# RH MANGNT

O **RH MANGNT** é uma aplicação simples de gestão de recursos humanos, desenvolvida com foco em estudos e prática dos recursos essenciais do Laravel.  
Não se trata de uma solução completa de RH, mas sim de um sistema funcional que demonstra domínio de rotas, controllers, views, autenticação, autorização, migrations e boas práticas da arquitetura do framework.

---

## 📘 Descrição Geral

O sistema possui dois tipos principais de usuários:

- **Administrador**  
  Gerencia os funcionários do setor de RH.

- **Funcionários de RH**  
  São responsáveis pela gestão dos demais recursos humanos da aplicação.

O objetivo do projeto é demonstrar habilidades práticas em Laravel trabalhando com autenticação, autorização, CRUD básico e camadas essenciais do framework.

---

## 🚀 Funcionalidades

- CRUD de colaboradores
- Controle de usuários do setor de RH
- Gestão simples de recursos humanos
- Autenticação com Laravel Fortify
- Autorização com Gates e Policies
- Criptografia de dados sensíveis
- Organização com Services e Componentes Blade

---

## 🛠️ Tecnologias Utilizadas

- **PHP 8.4**
- **Laravel 12**
- **MySQL**
- **Routes, Controllers e Views**
- **Blade & Blade Components**
- **Eloquent ORM**
- **Migrations**
- **Laravel Fortify (Autenticação)**
- **Gates & Policies (Autorização)**
- **Encryption (Criptografia)**
- **Services**

---

## 📦 Como Instalar

```bash
git clone https://github.com/seu-usuario/rh-mangnt.git
cd rh-mangnt
composer install
cp .env.example .env
php artisan key:generate
