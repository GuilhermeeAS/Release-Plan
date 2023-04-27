# Release Plan 
## Funcionalidade de Login para Agendamentos de Consultas Médicas On-line
\
**Guilherme Alves Soares - RA: 22.01540-0**

\
**User Story:**\
Como usuário do site de agendamentos de consultas médicas on-line, quero poder realizar login em minha conta para agendar, reagendar ou cancelar consultas de forma segura e prática.

**Tarefas Técnicas e Story Points:**
\
**Implementar o formulário de login (3 story points):**

Criar a estrutura do formulário de login com campos para e-mail/username e senha.
Adicionar validações de entrada nos campos do formulário.
Implementar a lógica de autenticação do usuário.

**Integrar com o sistema de autenticação (5 story points):**
\
Configurar o sistema de gerenciamento de usuários e autenticação existente ou escolher uma solução de terceiros confiável.
Realizar a integração entre o formulário de login e o sistema de autenticação.
Implementar a lógica de verificação de credenciais e geração de tokens de autenticação.

**Personalização do perfil do usuário (2 story points):**

Criar uma página de perfil do usuário onde ele possa visualizar e atualizar suas informações pessoais, como nome, endereço, telefone, etc.
Implementar a funcionalidade de edição de perfil, permitindo que o usuário atualize suas informações.

**Recuperação de Senha (Story Points: 3)**

Adicionar a funcionalidade de recuperação de senha.
Implementar um fluxo de redefinição de senha seguro, com envio de e-mail de redefinição.
Criar a página de redefinição de senha com campos de entrada e verificação.

**Medição de Prioridade Rice:**

Reach (Abrangência): Alta
A funcionalidade de login é essencial para que os usuários acessem o sistema e façam agendamentos de consultas médicas.
Todos os usuários registrados precisam passar pelo processo de login para utilizar a plataforma.



Impact (Impacto): Alta
O login personalizado permite que os usuários acessem suas informações, histórico de consultas e perfil.
Permite que o sistema personalize a experiência do usuário com base em suas preferências e histórico.

Confidence (Confiança): Média
A equipe de desenvolvimento possui experiência em implementar funcionalidades de login em projetos anteriores.
Os recursos necessários para implementação estão disponíveis e bem documentados.

Effort (Esforço): Médio
As tarefas técnicas envolvem a implementação do formulário de login, integração com sistema de autenticação existente e personalização do perfil do usuário.
Não há dependências externas significativas além do sistema de autenticação.

**Conclusão:**
Com base na medição de prioridade Rice, a funcionalidade de login recebe alta prioridade para ser incluída no próximo release, dada a sua abrangência e impacto, com um esforço e confiança médios.

**Observações:**
\
Para a implementação do login, é necessário considerar questões de segurança, como proteção contra ataques de força bruta e armazenamento seguro de senhas.
Recomenda-se realizar testes rigorosos para garantir que o sistema de log in funcione corretamente e seja fácil de usar.
É importante fornecer feedback adequado ao usuário durante o processo de login, informando-o sobre erros de entrada ou falhas de autenticação.

**Revisão e Entrega:**
\
Após a conclusão das tarefas técnicas, a funcionalidade de login deverá ser revisada internamente pela equipe de desenvolvimento para garantir sua eficácia e segurança. Após a revisão, a funcionalidade poderá ser implantada em um ambiente de produção e disponibilizada para os usuários finais. É recomendável monitorar a funcionalidade em produção para garantir sua estabilidade e corrigir eventuais problemas identificados pelos usuários.






