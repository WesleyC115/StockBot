# 📦 StockBot - Gerenciamento de Estoque e Fluxo de Aprovações

<div align="center">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="Render" src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white">
  <img alt="Aiven" src="https://img.shields.io/badge/Aiven-FF3554?style=for-the-badge&logo=aiven&logoColor=white">
</div>

<br>

## 🎯 Sobre o Projeto
O **StockBot** é um sistema Full-Stack robusto desenvolvido para resolver o desafio de rastreabilidade de inventário. A aplicação oferece controle em tempo real de entradas, saídas, níveis críticos de estoque e gestão de pedidos de compra, garantindo que o fluxo de materiais de uma empresa seja monitorado de ponta a ponta.

**🔗 Acesso em Produção:** [https://stockbot-web.onrender.com](https://stockbot-web.onrender.com)

---

## 🚀 Arquitetura e Tecnologias

A aplicação foi desenhada com uma arquitetura de microsserviços para separar as responsabilidades e facilitar o deploy em nuvem.

### Frontend
* **Core:** React.js com Vite para uma build ultrarrápida.
* **Estilização e UX:** Interface moderna, responsiva e com suporte a *Dark Mode*.
* **Integração:** Axios para consumo da API REST e React Router para navegação segura.

### Backend
* **Core:** Java 21 com Spring Boot 3.
* **Persistência:** Spring Data JPA com migração automática de esquemas (Hibernate).
* **Segurança:** Spring Security com autenticação via **Tokens JWT**. O sistema protege rotas específicas garantindo que apenas usuários autorizados realizem movimentações críticas.

### Infraestrutura (Cloud)
* **Hospedagem Front & Back:** Deployed no **Render**, utilizando comandos de build personalizados para compatibilidade de pacotes Linux/Windows.
* **Banco de Dados:** MySQL gerenciado na nuvem através do **Aiven**, garantindo alta disponibilidade e segurança dos dados.

---

## ⚙️ Principais Funcionalidades
- **Gestão de Componentes:** Cadastro completo com patrimônio, categoria e localização física.
- **Alertas de Threshold:** Monitoramento inteligente de "Nível Mínimo" que alerta quando um componente precisa de reposição.
- **Fluxo de Compras:** Sistema de "Pedidos de Compra" integrado à tabela de requisições.
- **Auditoria de Histórico:** Log imutável de quem retirou ou adicionou peças, incluindo data, hora e justificativa.

---

## 📸 Demonstração do Sistema

<p align="center">
  <img src="https://github.com/user-attachments/assets/51440d4c-8f6f-4e51-b472-cebda95ed288" width="48%" style="margin-right: 1%">
  <img src="https://github.com/user-attachments/assets/3b3ac126-f854-489e-b833-f5a8e7d56667" width="48%">
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/55717faa-768a-453c-a9c5-763e242a5af4" width="48%" style="margin-right: 1%">
  <img src="https://github.com/user-attachments/assets/cc17bff8-91fd-4ec5-bc9c-6cefe11e8c5d" width="48%">
</p>

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0e5bd3af-be6d-464f-9644-7e749d7380ee" width="70%">
</p>
