# Event Planner

<hr>
The Event Planner is a web application that allows users to organize and manage events, including creating, editing, and RSVPing to events. Users can securely authenticate using OAuth with popular providers.

# 💻 RF
 - [ ] Autenticação de Usuário: Os usuários podem autenticar de forma segura usando OAuth com provedores populares, como Google, Facebook ou GitHub.

 - [ ] Criação de Eventos: Usuários autenticados podem criar novos eventos, especificando detalhes como nome do evento, data, localização e descrição.

 - [ ] Gerenciamento de Eventos: Os usuários podem visualizar uma lista de eventos que criaram e gerenciá-los, editando ou excluindo eventos.

 - [ ] Funcionalidade de RSVP: Usuários autenticados podem RSVP para eventos, indicando se planejam comparecer, talvez comparecer ou recusar o convite.

# 💻 RFN:
  - [ ] Implementar a funcionalidade de autenticação usando OAuth com um provedor de redes sociais, como o Facebook.
  - [ ] Integrar o fluxo de autorização OAuth para obter um token de acesso válido.
  - [ ] Implementar a lógica para recuperar os dados do usuário usando o token de acesso e exibir o nome e a foto do perfil do usuário na interface do aplicativo.
  - [ ] Garantir que a integração OAuth seja segura, protegendo os tokens de acesso e implementando as melhores práticas de segurança recomendadas pelos provedores de redes sociais. 
  - [ ] Renovação de Token: Implemente a lógica para renovar automaticamente os tokens de acesso antes de expirarem, utilizando o fluxo de atualização de token do OAuth 2.0.
  - [ ] Revogação de Token: Adicione a capacidade de revogar manualmente os tokens de acesso de um usuário, por exemplo, através de uma página de configurações de conta.
  - [ ] Escopo de Autorização Personalizado: Explore a definição e o uso de escopos de autorização personalizados para limitar o acesso do cliente apenas a recursos específicos do usuário.
  - [ ] Autorização de Dois Fatores (2FA): Implemente um fluxo de autorização que inclua um segundo fator de autenticação, como um código SMS ou de autenticação de dois fatores, para aumentar a segurança do processo de autenticação.
  - [ ] Autenticação Multifator (MFA): Explore a integração do OAuth com sistemas de autenticação multifator para adicionar camadas adicionais de segurança ao processo de autenticação.
  - [ ] Armazenamento Seguro de Tokens: Aprofunde-se nas melhores práticas para o armazenamento seguro de tokens de acesso e atualização, incluindo técnicas como criptografia, hashing e proteção contra ataques de injeção de código.
  - [ ] Implementação de Webhooks: Explore a implementação de webhooks OAuth para receber notificações sobre eventos relacionados à autorização, como a expiração de tokens ou alterações nas permissões de acesso.
  - [ ] Monitoramento e Auditoria: Desenvolva recursos de monitoramento e auditoria para rastrear e registrar atividades relacionadas à autenticação e autorização, incluindo tentativas de login, concessões de permissões de acesso e alterações nos tokens.
  - [ ] Testes de Segurança: Realize testes de segurança abrangentes, incluindo testes de penetração e análise de vulnerabilidades, para garantir que sua implementação OAuth esteja protegida contra ameaças de segurança conhecidas.
        
# Installation and Configuration
1.Clone the repository to your local machine:
```#!/bin/bash
 git clone https://github.com/LucasBiazon/Event-Planner_OAuth.git
```
2. Install project dependencies:
```
cd social-media-aggregator
npm install
```

3. Configure OAuth credentials for authentication providers in the `config.js` file.

4. Install Fastify, Prism

- **Fastify:** Install Fastify using npm:

  ```
  npm install fastify
  ```

- **Prisma:** Install Prisma CLI globally using npm:

  ```
  npm install prisma --save-dev
  ```




  ```
  npx prisma init
  ```

- Update the `schema.prisma` file with your MongoDB connection details.

6. Start the server:
```
npm start
```

## Technologies Used

- Fastify
- OAuth 2.0
- Prisma
- MongoDB




