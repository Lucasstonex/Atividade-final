# Atividade-final
Av. final Projeto aplicado multiplataforma 1
#  Vitrine Digital de Artesanato  

##  Objetivo do Projeto  
O projeto tem como objetivo criar uma vitrine digital para valorizar e divulgar o trabalho de artesãos locais.  
A plataforma permitirá que cada artesão apresente suas peças, enquanto os visitantes poderão visualizar os produtos e entrar em contato direto com o produtor, fortalecendo a economia criativa da comunidade.  

---

##  Descrição Funcional da Solução Planejada  
- Cadastro de artesãos com perfil individual  
- Exposição de produtos em formato de vitrine digital  
- Busca e filtro por categorias de artesanato  
- Página de contato direto entre comprador e artesão  
- Versão responsiva para web e dispositivos móveis  

---

##  Visão Geral da Arquitetura  

A solução será desenvolvida em arquitetura **cliente-servidor** com integração de APIs.  

```mermaid
flowchart LR
    U[Usuário Web/Mobile] --> F[Frontend (React ou Next.js)]
    F -->|API REST| B[Backend (Node.js/Express)]
    B --> D[(Banco de Dados PostgreSQL)]
    B --> S[Serviços externos (ex: autenticação, envio de e-mail)]



    
